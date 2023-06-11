# GenAIhackathon2023
GenAI Hackathon at Bangalore 10-11 June 2023 


2. The application should allow the user to enter a YouTube URL and a language code for translation.
3. Use an hour long audio clip and convert it into 8 second mono channel wav files for training a voice cloning model
3. When a 'Translate Video' button is clicked, the application should:
    - Download the video and audio from the YouTube video.
    - Trim the video and audio to the desired interbval.
    - Ask the user to enter the desired langugae to translate.
    - convert the video into transcripts
    - Translate the transcripts text per each interval into the chosen language.
    - Convert the translated transcript text into speech.
    - Convert the resulting speech to the desired voice of the person cloning 
    - Display the final video in the application.



Note:
- The translation should be done using the Googletrans library in Python.
- The text-to-speech should be done using the gTTS library in Python.
- The video editing should be done using the Moviepy library in Python.
- The downloading of YouTube videos should be done using the Pytube library in Python.


## Resources and code

Pipeline Notebook https://colab.research.google.com/drive/1lu3lfkmT_EcrnTMGJGPQj0_zhUlJg78f?usp=sharing 
data perparation for clonning https://colab.research.google.com/drive/11a--eE8FCZVKHwKcTWPZJCcpkmFIyigw?usp=sharing 
Clonning training and inference notebook https://colab.research.google.com/drive/1OTB4dqZYi0yvYmshkiwTsYhm6aQJ-Fv5?usp=sharing 
Cloning UI Demo  https://6af3d23d8791be791d.gradio.live/

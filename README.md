# Milkbuns
Our submission for BrainHack 2023 XRExperience utilised Large Language Models to create a smart virtual avatar that can be interacted with through speech.

## Architecture
We first used a speech to text service (Whisper), before inputting the user prompt into a large language model (GPT-3.5), and finally we used a text to speech model (ElevenLabs) for the avatar to give an auditory response to the user.

We made use of specific prompts to ensure that the response generated by the large language model stayed in character.

You may view our presentation slides at https://docs.google.com/presentation/d/1vWLeFUOVZR6s7jBK8XJala5OPH5_kZGK4-X_2w_Aq4w/edit#slide=id.g2540c13af14_1_15

# Multilingual-Audio-Speech-to-Speech-LLM-Chatbot
This multilingual speech-based conversational AI bot is capable of interacting with humans via spoken audio in multiple languages and responding via speech in the speaker's native language. The solution integrates 3 AI models to conduct multilingual conversations via speech interactions with humans in their native tongue. This research is an outcome of a research internship by the author at CMU's AI Biometrics lab conducted under the supervision and mentorship of Professor Marios Savvides.

## Tools Used
This tool involves the integration of 3 AI models- Whisper, Llama 3.1 8B, and GoogleTTS.
Whisper was used for speech-to-text; it is a multilingual model, and it can transcribe input audio even through minor background noise and mediocre audio resolution.
This transcribed text was fed into Llama 3.1 8B, which is an LLM model with 8 billion parameters, which is used to generate a response to the user's questions. 
Lastly, the response from Llama 3.1 8B was fed into GoogleTTS, which does text-to-speech and was used to convert the Llama LLM output into a spoken response.

## Usage Guide
The mp3 files found contain the multilingual audio files used to evaluate the models. The input speech files with the user questions in Arabic and Spanish are in the .mp3 files *question*.mp3, and the output responses from the Multilingual-Audio-Speech-to-Speech-LLM-Chatbot in Arabic and Spanish (in response to the spoken questions) are in the llmspokenresponse*.mp3 files.
The ipynb file is a Python notebook containing the necessary code. Run for results.

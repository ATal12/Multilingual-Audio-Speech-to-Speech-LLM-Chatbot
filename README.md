# Multilingual-Audio-Speech-to-Speech-LLM-Chatbot
This LLM tool uses 3 AI models to listen to an audio clip in any language and respond in that same language. This was made under the supervision and mentorship of Marios Savvides as a research intern at CMU's AI Biometrics lab.

## Tools used
This tool was made using Whisper, Llama 3.1 8B, and GoogleTTS.
Whisper was used for speech-to-text; it is a multilingual model, and it can transcribe input audio even through minor background noise and mediocre audio resolution.
This transcription was fed into Llama 3.1 8B, which is an LLM model with 8 billion parameters was used to generate a response. 
Lastly, the response from Llama 3.1 8B was fed into GoogleTTS, which does text-to-speech and was used to convert Llama's response into a spoken response.

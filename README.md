# CHAT-BOT-Experimental-Pipeline----Using-whisper-lmsys-fastchat-t5-3b-v1.0-edge_tts
CHAT-BOT(Experimental Pipeline) -- Using whisper,lmsys/fastchat-t5-3b-v1.0[small],edge_tts

Experimental Pipeline Overview :

This experimental pipeline is designed to convert audio input into text, use that text as a prompt for a large language model (LLM), and then generate an audio output. The primary focus of this project is to demonstrate that the pipeline remains fully functional and efficient, regardless of the specific LLM's performance, even when utilizing a 3B sequence-to-sequence model like lmsys/fastchat-t5-3b-v1.0.

The pipeline begins with an audio input, which is either captured live or uploaded. This audio is then transcribed into text using a speech-to-text model. The transcribed text serves as a prompt for the LLM, which generates a response based on the input. This generated text may undergo further processing to refine the content before being converted back into an audio format through a text-to-speech model. The final product is an audio output that mirrors the original input prompt, completing the loop.

Even when using a model like the 3B sequence-to-sequence lmsys/fastchat-t5-3b-v1.0, which may have certain limitations in terms of processing speed or computational requirements or low effeciency of genrating outputs [As it is a coparitively smnaller network and has less trainabel parameters],the overall functionality and flow of the pipeline remain smooth and uninterrupted.

In the demonstration, each component of the pipeline is explained in detail, showcasing how they interact to form a cohesive system. The process is then brought together in a final demonstration, highlighting the seamless operation from audio input to audio output. The focus on maintaining uninterrupted operations , irrespective of the LLM used, underlines the robustness and flexibility of the pipeline, making it a reliable tool for various applications.


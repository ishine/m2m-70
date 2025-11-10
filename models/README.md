
## Download Model 
Encoder | Adapter | LLM 
|---|---|---
[whisper-large-v3](https://huggingface.co/openai/whisper-large-v3) | [q-former+pool+mlp](https://huggingface.co/yxdu/llm-srt) | [Gemma-3-27b-it](https://huggingface.co/google/gemma-3-27b-it) 
```
cd models/
git lfs clone https://huggingface.co/openai/whisper-large-v3
git lfs clone https://huggingface.co/Qwen/Qwen2.5-3B
# for 27B model (support 70 languages)
git lfs clone https://huggingface.co/google/gemma-3-27b-it
```

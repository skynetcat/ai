# Setup
## Models
The following models are used as GGUFs
1. [Qwen3-1.7B-UD-Q4_0](https://huggingface.co/unsloth/Qwen3-1.7B-GGUF/blob/main/Qwen3-1.7B-Q4_0.gguf) from Unsloth
2. [SmolVLM2-500M-Video-Instruct-f16](https://huggingface.co/ggml-org/SmolVLM2-500M-Video-Instruct-GGUF/blob/main/SmolVLM2-500M-Video-Instruct-f16.gguf) and the corresponding [mmproj-f16](https://huggingface.co/ggml-org/SmolVLM2-500M-Video-Instruct-GGUF/blob/main/mmproj-SmolVLM2-500M-Video-Instruct-f16.gguf) from ggml-org
## Android
App: [ChatterUI](https://github.com/Vali-98/ChatterUI)
### Steps
1. Create a new character.
2. Add prompt to "Description".
3. Add a friendly pfp.
4. Save character.
### Themes
Available in [themes directory](themes/)

# Images
Friendly images I use for each prompt: [Available here](images/)

# Samplers
Settings I use for LLMs: [Available here](samplers/)

# Prompts
## Learning
[Summarizer](prompts/summarizer): Summarizes long text and extracts useful information and ideas in a structured manner.

## Life
[Strategic Advisor](prompts/advisor): Helps greatly in self-development, planning and generating a clear vision.

## Content Creation
1. [Social Posts (X)](prompts/twitter)
2. [Thread or IG Carousel](prompts/thread)
3. [Fast YouTube Scripts, Newsletters, or Articles](content/newsletter)

## Misc.
1. [General Purpose Info Bot](prompts/infobot): Answers questions in detail and gives structured output.
2. [Meta Prompt Creator](prompts/prompter): A prompt to create more prompts!

# Special Thanks:
1. [Dan Koe](https://thedankoe.com/) : for [Prompt & Template Library](https://stan.store/thedankoe/p/prompt-library)
2. Images are made by ChatGPT or grabbed from stock photos.
3. Some prompts are improved using ChatGPT.

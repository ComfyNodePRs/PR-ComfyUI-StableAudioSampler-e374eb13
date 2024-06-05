# ComfyUI-StableAudioSampler
The New Stable Diffusion Audio Sampler 1.0 In a ComfyUI Node. Make some beats!
![Screenshot from 2024-06-05 23-09-52](https://github.com/lks-ai/ComfyUI-StableAudioSampler/assets/163685473/037a23a7-0183-45b0-ae07-935664ba6dc7)

## Requirements
- At least 7GB VRAM
- ComfyUI

## Installation
1. Make sure you have your `HF_TOKEN` environment variable for hugging face because model loading doesn't work just yet directly from a saved file
2. Go ahead and download model from here for when we fix that: https://huggingface.co/stabilityai/stable-audio-open-1.0/blob/main/model.safetensors
3. It should just run if you've got your environment variable set up

There will definitely be issues because this is so new and it was coded quickly so we could test it out.

This is not an official StableAudioOpen repository

## Current Features
- Uses HuggingFace
- 

## Roadmap and Requested Features
Keeping track of requests and ideas as they come in:
- Model loading from the `models/audio_checkpoints` folder
- Nodes
  - A Mixer Node (mix your audio outputs with some sort of mastering)
  - A Tiling Sampler (concatenate the audios)
  - A Model Loader Node (to load audio models separately and pipe to wherever)
- Making the Audio format compatible with other Audio Node packs
- A bit of Refactoring cause this was a quick release

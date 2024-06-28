#### Example of different Instant LoRA Workflows

##### Instant LoRA #1
![Workflow Example of Instant LoRA #1](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/Instant_LoRA_1.png)

Instant LoRA 1
Inspired by AloeVera (almost identical).
Really simple, no training, "LoRA" like functionality.
SD 1.5. IP Adapter models:
1. https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus_sd15.bin -> custom_nodes/IPAdapter-ComfyUI/models.
2. https://huggingface.co/h94/IP-Adapter/blob/main/models/image_encoder/model.safetensors -> models/clip_vision.
NB (2024). As IPAdapter-ComfyUI from 2023 is now deprecated, you should replace it with a currently supported version before use
Video guide - https://youtu.be/HtmIC6fqsMQ

##### Instant LoRA #2
![Workflow Example of Instant LoRA #2](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/Instant_LoRA_2.png)

Instant LoRA 2
As above, but with ControlNet to guide the shape

##### Instant LoRA #3
![Workflow Example of Instant LoRA #3](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/Instant_LoRA_3.png)

Instant LoRA 3
As above, but with QR Code Monster ControlNet too :)

##### Instant LoRA #4
![Workflow Example of Instant LoRA #4](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/Instant_LoRA_4.png)

Instant LoRA 4
As above, but with basic upscaling

##### Instant LoRA #5
![Workflow Example of Instant LoRA #5](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/Instant_LoRA_5.png)

Instant LoRA 5
As above, but with more upscaling to 16k+

##### Instant LoRA #6
![Workflow Example of Instant LoRA #6](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/Instant_LoRA_6.png)

Instant LoRA 6
As above, but different upscaling to 16k+

##### SDXL Instant LoRA #1
![Workflow Example of Instant LoRA #1](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/SDXL_Instant_LoRA_1.png)

SDXL "Instant LoRA" - basic.
Really simple, no training, "LoRA" like functionality.
Uses SDXL IP Adapter - https://huggingface.co/h94/IP-Adapter
Video - https://youtu.be/dGL02W4QatI

##### SDXL Instant LoRA #2
![Workflow Example of Instant LoRA #2](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/SDXL_Instant_LoRA_2.png)

SDXL "Instant LoRA" - with CLIP Vision
Uses SDXL IP Adapter - https://huggingface.co/h94/IP-Adapter
Also use "Revisions" CLIP vision - https://huggingface.co/stabilityai/control-lora

##### SDXL Instant LoRA #3
![Workflow Example of Instant LoRA #3](https://github.com/readycade/ComfyUI/blob/master/workflows/Reposer/Pics/SDXL_Instant_LoRA_3.png)

SDXL "Instant LoRA" - with CLIP Vision & ControlNet
Uses SDXL IP Adapter - https://huggingface.co/h94/IP-Adapter
Also use "Revisions" CLIP vision - https://huggingface.co/stabilityai/control-lora
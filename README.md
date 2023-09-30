# AVeryComfyNerd
A variety of ComfyUI related stuff.

ComfyUI - https://github.com/comfyanonymous/ComfyUI

Install any missing nodes using ComfyUI Manager - https://github.com/ltdrdata/ComfyUI-Manager

Many ControlNet Models - https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors/tree/main

AnimateDiff - https://github.com/guoyww/AnimateDiff

Text-to-Image models - https://huggingface.co/models?pipeline_tag=text-to-image&sort=trending

Upscale Wiki - https://upscale.wiki/wiki/Main_Page

# Things available
Workflow | Description
| :---:   | :---: |
<img src="SDXL_Depth_Badger.png" width="256px"></img> | Very basic ControlNet attached to the example SDXL workflow. Canny & Depth preprocessor examples (requires extension). See https://youtu.be/reqamcrPYiM for more information.
nr_sd15_QR_Monster.json | Basic QR Code Monster SD 1.5 controlnet - make spiral art!
nr_sd15_QR_Monster_AnimateDiff_LatentUpscale | QR Code Monster SD 1.5 controlnet - make animated spiral art!
<img src="AnimateDIff_FreeU.png" width="256px"></img> | Updated QR Code Monster SD 1.5 controlnet with AnimateDiff and FreeU  
<img src="AnimateDiff_MotionLoRA.png" width="256px"></img> | AnimateDiff_MotionLoRA.png - Montion LoRA example. Pan up, down, left right, etc.
<img src="Instant_LoRA_1.png" width="256px"></img>|Instant Lora 1 - Inspired by <a href="https://civitai.com/articles/2345/aloeveras-instant-lora-no-training-15-sdxl">AloeVeras</a> (almost identical). Needs 2 extra models: https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus_sd15.bin -> "custom_nodes/IPAdapter-ComfyUI/models". https://huggingface.co/h94/IP-Adapter/blob/main/models/image_encoder/model.safetensors -> "models/clipvision". Video guide - https://youtu.be/HtmIC6fqsMQ
<img src="Instant_LoRA_2.png" width="256px"></img>|Instant Lora 2 - As above, but with ControlNet to guide the shape
<img src="Instant_LoRA_3.png" width="256px"></img>|Instant Lora 3 - As above, but with QR Code Monster ControlNet too :)
<img src="Instant_LoRA_4.png" width="256px"></img>|Instant Lora 4 - As above, but with upscaling
<img src="Instant_LoRA_5.png" width="256px"></img>|Instant Lora 5 - As above, but with more upscaling
<img src="Instant_LoRA_6.png" width="256px"></img>|Instant Lora 6 - As above, but different upscaling

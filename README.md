# Resources
A variety of ComfyUI related stuff. You'll need different models and custom nodes for each different workflow.
<br>By default, models are saved in subdirectories under ``ComfyUI/models``, though some custom nodes have their own models directory.
<br>Use **ComfyUI Manager** to install missing custom nodes. Be sure to keep ComfyUI updated regularly - including all custom nodes.

[Playlist with loads of ComfyUI guides](https://www.youtube.com/playlist?list=PLjC8P1vEncQDahWnl_WKYsjF_tmIDXWEa)

Item | Description | Link
| --- | --- | --- | 
ComfyUI | The main thing you'll need! | https://github.com/comfyanonymous/ComfyUI<br>See https://youtu.be/2r3uM_b3zA8 for an install guide
ComfyUI Manager | Install any missing nodes using this | https://github.com/ltdrdata/ComfyUI-Manager
Stability AI | Models & VAEs | https://huggingface.co/stabilityai
Text-to-Image models | Text-2-image models | https://huggingface.co/models?pipeline_tag=text-to-image&sort=trending
ControlNet Models | ControlNet Models | https://huggingface.co/lllyasviel/sd_control_collection/tree/main<br>https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors/tree/main
QR Code Monster Control Net | ControlNet Model | https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster
TIAdapter | Control Models | https://github.com/TencentARC/T2I-Adapter
Control LoRA | Control Models | https://huggingface.co/stabilityai/control-lora
AnimateDiff | Original repo, many links and more info | https://github.com/guoyww/AnimateDiff
IPAdapter Extension | Custom Nodes for ComfyUI | https://github.com/laksjdjf/IPAdapter-ComfyUI
IPAdapter models | Models | https://huggingface.co/h94/IP-Adapter
Upscale Wiki | Many models & info | https://upscale.wiki/wiki/Main_Page
Artist Style Studies | SDXL Prompt output examples for inspiration | https://sdxl.parrotzone.art/

# Workflows available
In ComfyUI the image IS the workflow. Simply drag or load a workflow image into ComfyUI!

Workflow | Description
| --- | --- |
<img src="SDXL_Depth_Badger.png" width="256px"></img> | Simple SDXL ControlNet workflow.<br>Introductory SDXL Canny & Depth ControlNet example.<br>See https://youtu.be/reqamcrPYiM for more information.
nr_sd15_QR_Monster.json | Basic QR Code Monster SD 1.5 ControlNet - make spiral art!<br>See also - https://youtu.be/D4oJz0w36ps
nr_sd15_QR_Monster_AnimateDiff_LatentUpscale | QR Code Monster SD 1.5 ControlNet - make animated spiral art!<br>See also: https://youtu.be/D4oJz0w36ps
<img src="AnimateDIff_FreeU.png" width="256px"></img> | Updated QR Code Monster SD 1.5 ControlNet with AnimateDiff and FreeU<br>Works best with the v1 QR Code Monster - https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster
<img src="AnimateDiff_MotionLoRA.png" width="256px"></img> | AnimateDiff with Montion LoRA example. Pan up, down, left right, etc. SD 1.5
<img src="Instant_LoRA_1.png" width="256px"></img>|Instant LoRA 1<br>Inspired by <a href="https://civitai.com/articles/2345/aloeveras-instant-lora-no-training-15-sdxl">AloeVera</a> (almost identical).<br>Really simple, no training, "LoRA" like functionality.<br>SD 1.5. IP Adapter models:<br>**1.** https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus_sd15.bin -> "custom_nodes/IPAdapter-ComfyUI/models".<br>**2.** https://huggingface.co/h94/IP-Adapter/blob/main/models/image_encoder/model.safetensors -> "models/clip_vision".<br>**Video guide** - https://youtu.be/HtmIC6fqsMQ
<img src="Instant_LoRA_2.png" width="256px"></img>|Instant LoRA 2<br>As above, but with ControlNet to guide the shape
<img src="Instant_LoRA_3.png" width="256px"></img>|Instant LoRA 3<br>As above, but with QR Code Monster ControlNet too :)
<img src="Instant_LoRA_4.png" width="256px"></img>|Instant LoRA 4<br>As above, but with basic upscaling
<img src="Instant_LoRA_5.png" width="256px"></img>|Instant LoRA 5<br>As above, but with more upscaling to 16k+
<img src="Instant_LoRA_6.png" width="256px"></img>|Instant LoRA 6<br>As above, but different upscaling to 16k+
<img src="PromptTravel_AnimateDiff_IPAdapter.png" width="256px"></img>|Morphing AI videos of any length using AnimateDiff. SD 1.5. Includes IPAdapter & Upscaling. IP Adapter models:<br>**1.** https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus_sd15.bin -> "custom_nodes/IPAdapter-ComfyUI/models".<br>**2.** https://huggingface.co/h94/IP-Adapter/blob/main/models/image_encoder/model.safetensors -> "models/clip_vision".<br>**Video guide** - https://youtu.be/6A3a0QNPhIs
<img src="PromptTravel_AnimateDiff.png" width="256px"></img>|Morphing AI videos of any length using AnimateDiff. SD 1.5. Includes Upscaling. Like above, but without IPAdapter controls.
<img src="SDXL_Instant_LoRA_1.png" width="256px"></img>|SDXL "Instant LoRA" - basic.<br>Really simple, no training, "LoRA" like functionality.<br>Uses SDXL IP Adapter - https://huggingface.co/h94/IP-Adapter
<img src="SDXL_Instant_LoRA_2.png" width="256px"></img>|SDXL "Instant LoRA" - with CLIP Vision<br>Uses SDXL IP Adapter - https://huggingface.co/h94/IP-Adapter<br>Also use "Revisions" CLIP vision - https://huggingface.co/stabilityai/control-lora
<img src="SDXL_Instant_LoRA_3.png" width="256px"></img>|SDXL "Instant LoRA" - with CLIP Vision & ControlNet<br>Uses SDXL IP Adapter - https://huggingface.co/h94/IP-Adapter<br>Also use "Revisions" CLIP vision - https://huggingface.co/stabilityai/control-lora
<img src="AnimateDiff_QRCode_Video.png" width="256px"></img>|AnimateDiff + QRCode (Vid2Vid)<br>Use any high-contrast input video to create guided animations! Spirals away...
<img src="Reposer.png" width="256px"></img>|SD 1.5 Reposer - single face image to any pose. Get consistent faces!<br>**No** "roop" or similar face-swapping nodes required = easy install!<br>SD 1.5 ControlNet models:<br>https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors/tree/main<br>IP Adapter models:<br>**1.** https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus-face_sd15.bin -> "custom_nodes/IPAdapter-ComfyUI/models".<br>**2.** https://huggingface.co/h94/IP-Adapter/blob/main/models/image_encoder/model.safetensors -> "models/clip_vision".<br>IPAdapter Extension - https://github.com/laksjdjf/IPAdapter-ComfyUI<br>**Video guide** - https://youtu.be/SacK9tMVNUA
<img src="Reposer_plus.png" width="256px"></img>|SD 1.5 Reposer Plus - single face image to any pose. Get consistent faces!<br>Now also includes a supporting image for addings things like outfits<br>**No** "roop" or similar face-swapping nodes required = easy install!<br>SD 1.5 ControlNet models:<br>https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors/tree/main<br>IP Adapter models:<br>**1.** https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus-face_sd15.bin -> "custom_nodes/IPAdapter-ComfyUI/models".<br>**2.** https://huggingface.co/h94/IP-Adapter/blob/main/models/image_encoder/model.safetensors -> "models/clip_vision".<br>**3.** https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus_sd15.bin -> "custom_nodes/IPAdapter-ComfyUI/models".<br>IPAdapter Extension - https://github.com/laksjdjf/IPAdapter-ComfyUI<br>**Video guide** - https://youtu.be/SacK9tMVNUA

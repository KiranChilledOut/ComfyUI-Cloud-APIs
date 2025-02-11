# ComfyUI-Cloud-APIs
I have modified the existing ComfyUI-Cloud-APIs to support superior and faster generations with cost-effective offerings from Nebius AI, allowing you to use larger models in your local ComfyUI workflows despite GPU limitations. Currently, model support is limited, but we will add more models as time permits.
# Supported Models:
We recommend using the **Nebius** models for their superior performance and efficiency:
- **NebiusFluxDevAPI**
- **NebiusFluxSchnellAPI**
- **NebiusSdxlAPI**

Additionally, the following models are supported:
- Flux t2i (fal, replicate, runware)
- Flux i2i (fal)
- Flux w/loras and i2i (fal)
- Auraflow t2i (fal)
- SoteDiffusion t2i (fal)
- StableCascade t2i (fal)
- LLaVA 1.5 13B i2t (fal)
- LLaVA 1.6 34B i2t (fal)
- SDv1 t2i w/loras (runware)
- SDXL t2i w/loras (runware)
# Quick Setup
1. Install extension and dependencies (preferably with comfy manager)
2. Place your api key/token in a text file in ComfyUI-Cloud-APIs/keys

# Nebius Quick Setup
1. Install the extension with the "Install via Git URL" option in comfyUI manager
2. Create an account at [Nebius AI Studio](https://studio.nebius.ai/)
3. Follow th instructions at [API Keys](https://docs.nebius.com/studio/inference/api#images-generations)
4. Copy the API key in your ComfyUI folder `/Users/kiran/Desktop/ComfyUI/custom_nodes/ComfyUI-Cloud-APIs/keys` into a text file. (there is a placeholder nokey.txt file which you can delete or use the same file)
5. Consult the [models](https://studio.nebius.ai/models/text2image) page to get an idea of how much each generation will cost, you do get 1$ worth of free credit when you sign up which is enough for multiple test generations.
   
# Step by step setup (Fal)
1. Install the extension with the "Install via Git URL" option in comfyUI manager
2. Create an account at [fal.ai](https://fal.ai/)
3. Go to https://fal.ai/dashboard/keys and click "Add key"
4. Name the key then copy it into a text file in the ComfyUI-Cloud-APIs/keys folder. (there is a placeholder nokey.txt file which you can delete)
5. Consult the [models](https://fal.ai/models) page to get an idea of how much each generation will cost
6. Go to https://fal.ai/dashboard/billing and top up your account. For your financial well-being I recommend against automated topups, but I can't stop you.
# Step by step setup (Replicate)
1. Install the extension with the "Install via Git URL" option in comfyUI manager
2. Create an account at https://replicate.com/
3. Go to https://replicate.com/account/api-tokens and copy your token (or create a new one)
4. Copy the token into a text file in the ComfyUI-Cloud-APIs/keys folder. (there is a placeholder nokey.txt file which you can delete)
5. Consult https://replicate.com/explore to get an idea of how much each generation will cost
6. Go to https://replicate.com/account/billing to setup billing when you run out of free usage.
# Previews
![preview](https://github.com/BetaDoggo/ComfyUI-fal-api/blob/main/preview.png)
![i2ipreview](https://github.com/BetaDoggo/ComfyUI-Cloud-APIs/blob/main/fali2iwloraworkflow.png)

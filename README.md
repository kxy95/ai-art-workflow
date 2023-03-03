# ai-art-workflow

## Disclaimer
This is a document describing my workflow to generate AI art.
I am certain it is not perfect but since I got asked a few times to describe how I do it, here is how I do it.

## Tools
A list of tools I use to create my works with source and a description what it does.

### Stable Diffusion WebUI 
Source: https://github.com/AUTOMATIC1111/stable-diffusion-webui
- Absolut great program and to top it all it's free.
- Easy to use all in one UI in Browser to use Stable Diffusion Models on your local GPU.

### Stable Diffusion WebUI Extensions
Source: See the "Extensions" tab in Stable Diffusion WebUI.
- ultimate-upscale-for-automatic1111 -> Script to upscale images to higher resolutions through Stable Diffusion
- sd-webui-controlnet -> Integration to use ControlNet
- sd-webui-additional-networks -> Integration to use LoRAs
- openOutpaint-webUI-extension -> Image Editor with direct access to the Stable Diffusion Model via API

### Models 
Source: https://civitai.com/
- Already an excessive amount of Models, Textual Inversions (TI), LORAs and Hypernetworks.
- Quality pretty mixed.

Source: https://huggingface.co/models?library=diffusers
- You need a diffuser model.
- Many really good and well documented models.

### GPU
I use a GTX1070. 
It is somewhat limited in the initial size of an image you can generate with Stable Diffusion but I would say you can work with it very well.
Depending on the Model my maximum size is about 704x704 pixel.
At the moment only Nvidia Cards are supported but on a AMD support is worked on.

### Graphic Tablet
Not a hard requirement but absolutly necessary if you want to speed things up.
Often it is easier to actually - I know, crazy stuff - draw something than hitting a generate button till the model decides to give you what you are looking for. 
Especially with custom models that sometimes work in mysterious ways.

## Workflow

### Idea / Inspiration
Either start with a certain idea or somewhat of an idea and generate a few images till you got something you actually want to make.

### Choose a model
There is not a single perfect model that can do everything. 
Each model has a certain purpose. 
Finding one that can do what you want to do is key.

### Generating / Prompting
Different models work with different tags and settings for the samplers.
You will have to find out which settings work for what you want to create.
Typically a goo starting point is the page you download the model from, the author most likely will have some example prompts.
Additonally if you can find images made with this model you can check with the "Stable Diffusion Webui" feature "PNG Info" with what settings these images are created.
Add this step we want to create something pretty close to what we envision.

### Fine-tuning




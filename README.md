:octocat: Slides for [universe-22.vercel.app](https://universe-22.vercel.app/)

## Links

Stuff mentioned in the slides:

🙏🏼 [Request access to GPU Codespaces](https://github.surveymonkey.com/r/Y75GX9T) - GPU access in Codespaces is not yet generally available (as of November 9, 2022) so you'll need to request access using this form.

👩‍🚀 [replicate.com/stability-ai/stable-diffusion](https://replicate.com/stability-ai/stable-diffusion): The beloved open-source text-to-image model, running on Replicate. You can run it on Replicate using the web UI, or the [API](https://replicate.com/stability-ai/stable-diffusion/api).

🀄️ [Material Stable Diffusion](https://replicate.com/tommoore515/material_stable_diffusion): A fork of SD that generates tiling images

🎨 [Inpainter]https://github.com/replicate/inpainter): An open-source Next.js app that uses Replicate's API and Stable Diffusion to inpaint images. Check out the [source code](https://github.com/replicate/inpainter) or try it out at https://inpainter.vercel.app.

🍿 [Stable Diffusion animation](https://replicate.com/andreasjansson/stable-diffusion-animation): A model on Replicate that can animate Stable Diffusion by interpolating between two prompts

🧺 [Replicate Collections](https://replicate.com/explore#collections) - Curated sets of Replicate models that serve different purposes: Text to image, Image to text, Style transfer, Image restoration, etc.

📡 [Stable Diffusion Textual Inversion](https://github.com/zeke/replicate-sd-textual-inversion): A demo repo illustrating how to run GitHub Codespaces to fine-tune Stable Diffusion with your own concept using textual inversion, and deploy it to Replicate as a cloud API.

⚙️ [github.com/replicate/codespaces](https://github.com/replicate/codespaces): A convenience script that installs Cog and nvidia-docker on GitHub's GPU Codespaces, so you can build run and push Cog models to Replicate.


## Folks to watch

These people are creating some really interesting models on Replicate:

- https://replicate.com/andreasjansson
- https://replicate.com/cjwbw
- https://replicate.com/afiaka87

## Run Locally

To run this app on your own machine, you'll need to download and install Node.js, then:

```
npm install
npm run dev
```
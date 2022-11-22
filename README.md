# Emoji Diffusion Cog model

[![Replicate](https://replicate.com/m1guelpf/emoji-diffusion/badge)](https://replicate.com/m1guelpf/emoji-diffusion)

This is an implementation of the Valhalla's [Emoji Diffusion](https://huggingface.co/valhalla/emoji-diffusion) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights [with your Hugging Face auth token](https://huggingface.co/settings/tokens):

    cog run script/download-weights <your-hugging-face-auth-token>

Then, you can run predictions:

    cog predict -i prompt="monkey scuba diving"

# Sketch-to-Image Generation with ControlNet

This project uses Stable Diffusion v1.5 and ControlNet Scribble to transform three original hand-drawn sketches into realistic images.

## Files

- `Generative_AI.ipynb` — Python implementation in Google Colab
- `Images/` — Original hand-drawn sketches
- `Results/` — Generated images and experimental comparisons

## How to Run

1. Open the notebook in Google Colab and enable a GPU.
2. Install the dependencies using the first code cell.
3. Configure the input image paths.
4. Run the remaining cells in order.

## Models

- [Stable Diffusion v1.5](https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5)
- [ControlNet Scribble](https://huggingface.co/lllyasviel/control_v11p_sd15_scribble)

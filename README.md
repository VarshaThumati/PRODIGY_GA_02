
# PRODIGY TASK 02 - Image Generation with Pre-trained Models

## Project Overview

This project demonstrates text-to-image generation using a pre-trained Stable Diffusion model.

The system accepts a natural language text prompt and generates a corresponding image using a diffusion-based generative AI model.

## Objective

The objective of this project is to explore how pre-trained generative AI models can transform textual descriptions into visually meaningful images.

## Model Used

- Model: Stable Diffusion v1.5
- Framework: Hugging Face Diffusers
- Programming Language: Python
- Environment: Google Colab
- Hardware: NVIDIA Tesla T4 GPU

## Technologies Used

- Python
- PyTorch
- Hugging Face Diffusers
- Transformers
- Accelerate
- Safetensors
- Pillow
- Google Colab

---

## 🧠 How It Works

The overall generation pipeline can be represented as:

```text
              User Text Prompt
                     │
                     ▼
             Text Processing
                     │
                     ▼
          Stable Diffusion Model
                     │
                     ▼
             Random Noise
                     │
                     ▼
          Iterative Denoising
                     │
                     ▼
            Latent Representation
                     │
                     ▼
               Image Decoder
                     │
                     ▼
             Generated Image
```
## Features

- Text-to-image generation
- Negative prompt support
- Adjustable guidance scale
- Adjustable inference steps
- Configurable image resolution
- Reproducible generation using random seeds
- Multiple prompt experiments
- Generated image saving

## Example Prompts

1. A futuristic smart city at night with glowing skyscrapers.
2. A magnificent magical castle floating above the clouds.
3. A peaceful mountain lake surrounded by autumn forests.
4. A cute intelligent robot exploring an ancient library.

## Experimental Parameters

The project experiments with:

- Guidance Scale: 5.0, 7.5, 10.0
- Inference Steps: 30-40
- Resolution: 512 × 512
- Random Seed: 42 and 123

## Output

The generated images are stored in the `outputs` directory.

## Conclusion

This project demonstrates the practical use of a pre-trained diffusion model for text-to-image generation. The experiments show how different prompts and generation parameters can influence the resulting images.

## Author

Lakshmi Varsha Thumati

B.Tech - Computer Science and Engineering (Data Science)

## Internship

Prodigy Infotech - Generative AI Internship

Task 02: Image Generation with Pre-trained Models

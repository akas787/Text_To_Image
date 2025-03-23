# Stable Diffusion Image Generator  

This is a simple AI-powered image generator using **Stable Diffusion**. It allows users to enter a text prompt and generate an AI-generated image based on that prompt.  

## Features  
✅ Uses **Stable Diffusion v2** for high-quality image generation  
✅ Supports **CUDA (GPU)** for faster processing  
✅ Simple **Gradio UI** for easy interaction  
✅ **Reproducible results** with a fixed random seed  

## Installation  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/stable-diffusion-image-generator.git
   cd stable-diffusion-image-generator
   ```
2. Install dependencies:  
   ```bash
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
   pip install diffusers gradio
   ```
3. Run the application:  
   ```bash
   python app.py
   ```
   
## Usage  
- Enter a text prompt in the Gradio UI  
- Click the **Generate** button  
- Wait a few seconds for the AI to create your image  
- View or save the generated image  

## Example  
Prompt: **"A futuristic city with flying cars at sunset"**  
![Example Image](example.png)  

## Notes  
- The script uses **Stable Diffusion v2** from Hugging Face's `diffusers` library.  
- It requires a **GPU** for best performance. Running on **CPU** will be slow.  

## License  
This project is open-source under the MIT License.  


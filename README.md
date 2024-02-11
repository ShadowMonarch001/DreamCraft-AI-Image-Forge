# DreamCraft-AI-Image-Forge
Description:
DreamCraft:AI Image Forge is an exciting project that leverages the power of machine learning to generate images based on user-provided descriptions. With this fun project, you can watch your descriptions come to life as unique and captivating images. The project is built using Flask, a lightweight web framework in Python, and integrates with the Stable Diffusion model for image generation.
Steps to Run:

1. Upload IPYNB File to Colab and Connect to T4 GPU:
Start by uploading the IPYNB file from the GitHub repository to Google Colab.\
Once uploaded, ensure that the Colab notebook is connected to a T4 GPU for optimal performance.
Alternatively, you can open the Colab link directly from the GitHub repository and copy it to your Google Drive for easy access.

Installation:

1.Ensure you have Python installed on your system.
  Use pip to install the required Python packages: diffusers, transformers, scipy, ftfy, accelerate, pyngrok, and flask_ngrok.
  Get ngrok Authtoken:

2.Visit the ngrok website and sign up for an account if you haven't already.
  After logging in, you will receive an authentication token. Copy this token.
  In your terminal or command prompt, run !ngrok authtoken <your_auth_token> and replace <your_auth_token> with the token you copied. This will authenticate your ngrok account.

3.Run the Application:
  Execute the Python script to start the Flask web server: python <filename>.py.
  Once the server is running, it will provide you with a public URL generated by ngrok.

4.Accessing the Application:
  Open a web browser and navigate to the provided ngrok URL.
  You will see the AI Image Generator interface, where you can enter a description and click "Generate" to create an image based on your input.

5.Enjoy Generating Images:
  Have fun experimenting with different descriptions and watch as the AI Image Forge brings your ideas to life with unique and intriguing images!

Note: Remember to keep your ngrok authentication token secure and avoid sharing it publicly.




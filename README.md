# image_captioning
This project demonstrates how to generate captions for images using a pre-trained Transformer model. The entire workflow — from uploading images to generating captions — is implemented in Google Colab, making it easy to run without local setup.

 Features: 
Upload and process images directly in Google Colab
Generate captions using pre-trained models like nlpconnect/vit-gpt2-image-captioning
Visualization of image along with the generated caption
Easy-to-use notebook format for rapid experimentation

Technologies Used:
Python 
Google Colab
Hugging Face Transformers
PyTorch

Open Google Colab
Go to Google Colab

Click on "Upload" and upload the Image_Captioning_Transformer.ipynb notebook from this repository.

OR

Run the notebook directly from GitHub:

bash
Copy
Edit
https://colab.research.google.com/github/your-username/your-repo-name/blob/main/Image_Captioning_Transformer.ipynb

Install Requirements (in Colab)


!pip install transformers
!pip install torch torchvision
!pip install pillow

Run the Notebook
Upload your image in the provided upload cell

Generate the caption in one click

Visualize image + generated caption

Notebook Structure

Section	Description
Setup	Install and import required libraries
Load Pre-trained Model	Load image captioning model and processor
Image Upload	Upload your own images to Colab
Caption Generation	Generate captions with the model
Visualization	Display image with generated caption


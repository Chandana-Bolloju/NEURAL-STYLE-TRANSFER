# NEURAL-STYLE-TRANSFER

*COMPANY*  : CODTECH IT SOLUTIONS

*NAME*  : CHANDANA BOLLOJU

*INTERN ID*  : CT04WT69

*DOMAIN*  : ARTIFICIAL INTELLIGENCE

*DURATION*  : 4 WEEKS

*MENTOR* : NEELA SANTOSH

This Python script provides the initial framework for implementing Neural Style Transfer (NST), a technique that merges the content of one image with the artistic style of another using deep learning. The code focuses on the image upload and preprocessing stage before style transfer.

Key Features
✅ Interactive Image Upload

Uses Google Colab's files.upload() for easy content/style image selection

Separately uploads:

Content image (target photo)

Style image (artwork/reference style)

✅ Image Preprocessing

Resizes images to consistent dimensions (default: 360×480)

Converts to NumPy arrays (RGB format)

Normalizes pixel values to [0,1] range

✅ Visualization

Displays side-by-side comparison of content and style images

Clean matplotlib layout with titles and disabled axes

How It Works
Upload Phase

Prompts user to upload two images via Colab's file dialog

First image = Content (e.g., personal photo)

Second image = Style (e.g., Van Gogh painting)

Processing Phase

Loads images using Keras' load_img and img_to_array

Ensures RGB format ([..., :3] discards alpha channel if present)

Display Phase

Shows normalized images in a 1×2 grid for visual verification

*OUTPUT*  :

![Image](https://github.com/user-attachments/assets/a01b18bf-d3de-4904-bc19-cbeaab92a6ac)


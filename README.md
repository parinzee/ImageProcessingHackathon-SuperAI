# ImageProcessingHackathon-SuperAI
## By: Parinthapat Pengpun
This repo holds **winning 1st Place Notebook** in the **SuperAI Season 3 Image Processing Hackathon**! 

![](https://raw.githubusercontent.com/parinzee/ImageProcessingHackathon-SuperAI/main/Leaderboard.png)

# What is the competition?
This Image Processing Hackathon is one of the 6 hackathons for **qualifying entry** into the **Super AI Season 3 Program**. This hackathon is **open to the public** meaning that **people of all ages and all levels of education all over the nation are participating**. 

The goal of this hackathon is to **classify digits (0-9)** from images which could be written, printed, or from anywhere in the real world. The dataset is very diverse with the digits varying in size, color, and contrast. 

# Composition of Project
- **Image Processing Techniques**
- Usage of **State-of-The-Art Vision Transformer Model**

# Rationale behind Image Processing Steps
Therefore, I tackled this by making all the images as similar as possible.
1. Resize every image to fit 224x224 pixels (keeping aspect ratio) and pad the remaining spaces.
2. Apply auto contrast to increase the contrast between the digits and the background
3. Change the image to grayscale in order to emphasize the contrast and reduce classification based on digit color
4. Save the image. 
5. Invert the grayscale image and save it as another image (effectively augmenting the dataset) to handle for black and white text.

# Choosing a Model
The final aspect of this was also to choose a SOTA model. After reading a few papers, I settled on using Vision Transformers due to the nature of their architecture. 

# Code
You can access the code under the [Image_Processing_Hackathon.ipynb](https://github.com/parinzee/ImageProcessingHackathon-SuperAI/blob/main/Image_Processing_Hackathon.ipynb) file.

# Special Thanks
All in all, this was a very informative experience and I have to thank [**AI Builders**](https://github.com/ai-builders) for providing me with the knowledge to do all of these things!

![](https://raw.githubusercontent.com/ai-builders/.github/main/profile/logo-image.png)

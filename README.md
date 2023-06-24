# 🚀 Project 2: Colorizing Black and White Images using Deep Learning Neural Networks

[![Day 1 Thumbnail](https://img.youtube.com/vi/KVTszH6hk38/0.jpg)](https://youtu.be/KVTszH6hk38) [![Day 2 Thumbnail](https://img.youtube.com/vi/aiKEwLzLf1w/0.jpg)](https://youtu.be/aiKEwLzLf1w)

## Overview

Welcome to my Project 2: Colorizing Black and White Images using Deep Learning Neural Networks. This project is part of my series of 25 Projects in 100 days challenge, where I aim to enhance my coding skills and explore various technologies. In this project, I dive into the fascinating field of image colorization using deep learning techniques.

### Day 1 Update (Actually Day 5 of my series of 25 Projects in 100 days)

Today, I delved into colorizing black and white images using deep learning neural networks. Inspired by Zhang et al.'s ECCV paper on "Colorful Image Colorization," I explored their approach of dividing RGB images into lightness, A, and B channels. This division allows for the recreation of the original colored image. #ImageColorization #DeepLearning

I obtained a massive dataset consisting of 1.8 million unique images, totaling a staggering 23.5 GB. This dataset provided a rich resource for training and experimentation. However, its size posed significant challenges for my PC's resources. To address this, I reduced the number of classes to 25 and selected 100 images per class. #BigData #ResourceChallenge

Despite the reduction, memory and CPU usage remained high. To mitigate this, I resized the images to 32x32 pixels, significantly reducing the memory footprint. I then trained a model with encoder and decoder layers, a powerful architecture for image colorization. However, the initial results lacked the desired vibrancy and accuracy. #ModelTraining #EncoderDecoderArchitecture

To enhance the colorization process, I considered two options. First, I explored using a pretrained model developed by Zhang, fine-tuned on extensive datasets, to improve the accuracy and realism of the colorization. Alternatively, I contemplated training an autoencoder model with a focused dataset of 1000 images from a single class, aiming for refined colorization outcomes. #PretrainedModel #Autoencoder

Additionally, I experimented with various filters from the CV2 library to test alternative colormaps, seeking to enhance the visual impact of the colorized images. Moving forward, I will continue exploring the pretrained model by Zhang for improved results and conduct further experiments with larger datasets and different training approaches. #NextSteps #Optimism

### Day 2 Update (Actually Day 6 of my series of 25 Projects in 100 days)

Today, I focused on refining the colorization process for black and white images. To do this, I decided to use a smaller dataset consisting of 1000 images of airplanes. This focused dataset allowed me to explore the capabilities of autoencoders, specifically the U-Net architecture commonly used for image segmentation. #Colorization #Autoencoders #U-NetArchitecture

I began by creating an autoencoder model with the U-Net architecture. The model comprised of upscaling and downscaling layers, enabling it to learn the intricate details of the images. The training process was time-consuming, taking over 1.5 hours, but the results were promising. #ModelCreation #TrainingProcess

During the model creation, I used the blue channel as an input and predicted the actual colored images. This approach yielded an impressive accuracy of over 83 percent. #ColorizationAccuracy #BlueChannel

Encouraged by this outcome, I trained another model using different images, this time focusing on boxing rings. The training accuracy for this model reached 69 percent, and during evaluation, it achieved an accuracy of 62 percent. #ModelTraining #Evaluation #BoxingRings

To evaluate the performance of both models, I compared the colorized images produced by each. The results were satisfying, and I felt confident in the progress made during this project. #PerformanceEvaluation #Comparison

With the completion of this project, I have decided to move on to my next challenge. After my exams, I plan to explore colorizing videos from the black and white era. This new endeavor will allow me to apply the techniques I have learned and expand my knowledge further. The start date for this next project is set for June 3rd. #NextChallenge #VideoColorization
#project #ai #deeplearning

## Project Details

- Project: Colorizing Black and White Images
- Challenge: #100days25projectchallenge
- Repository: [GitHub](https://github.com/ChildEater69/Project2-Colorization-of-blackandwhite-images)

---

This project is part of the #100days25projectchallenge, where I take on the challenge of building 25 projects in 100 days. The goal is to enhance my coding skills, explore new technologies, and develop a portfolio of diverse projects.

Stay tuned for more updates as I continue my coding journey! Let's learn, build, and grow together! 💻🚀

---

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/avdhesh-kumar-sharma-751a49225/) for further discussions and collaborations. Let's connect and inspire each other! 🤝🌟

## Videos

### Day 1 Video: [YouTube](https://youtu.be/KVTszH6hk38)

[![Day 1 Thumbnail](https://img.youtube.com/vi/KVTszH6hk38/0.jpg)](https://youtu.be/KVTszH6hk38)


### Day 2 Video: [YouTube](https://youtu.be/aiKEwLzLf1w)

[![Day 2 Thumbnail](https://img.youtube.com/vi/aiKEwLzLf1w/0.jpg)](https://youtu.be/aiKEwLzLf1w)


## Download Models and Prediction Folder

For accessing the models and prediction folder used in this project, you can download them from the following Google Drive link:
[Download Models and Prediction Folder](https://drive.google.com/drive/folders/1aX-FWrJtnupONJW5YEUlbV81D3eH4jzN?usp=sharing)

Make sure to download the folder and place it in the appropriate location within your project directory.

---

**Note:** Replace `yourusername` and `yourname` with your actual GitHub username and name, respectively. Also, update the project details and links according to your project.

If you have any questions or need further assistance, feel free to reach out. Happy coding! 🎨🖼️🤖

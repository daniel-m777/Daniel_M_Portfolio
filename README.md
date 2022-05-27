## About Me
My name is Daniel and I am a recent college graduate who just finished a Master's in Artificial Intelligence. Here, you can find a portfolio of projects that I've worked on relating to data science and machine learning. Some of the skills I've developed include data visualization, data mining, machine learning, deep learning, deployment, and use of cloud services (GCP and AWS). Although I am well-versed in general machine/deep learning methods, one of my favorite topics is natural language processing. 

# Main Projects
## [Video Game Review Summarization](https://github.com/loriylo/video_game__review_NLP)
In this project, we combine the tasks of text classification, text summarization, and text-to-speech into one final implementation for users to quickly understand videogame reviews. Our focus was on IGN videogame reviews, such as this one. Our work involved heavy text cleaning, such as normalization via lowercasing, stopword removal, punctuation removal, and POS tagging.

## [Image Colorization](https://github.com/daniel-m777/image_colorization)
For this project, we decided to tackle the challenge of training a model to colorize black and white photos. For our dataset, we used this landscape dataset from Kaggle. For the architecture of the model, we based it on the CNN model from this paper. We will go through the code and describe the process in detail. To start, the following code demonstrates how we will be working with the LAB colorspace. The input for our model is the L channel, which is the luminance and ranges from 0-100 values. The output for our model are the ab channels, which represent different spectrum ranges (a is red-green, b is yellow-blue) with values ranging from -128-127.

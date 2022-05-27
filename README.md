## About Me
My name is Daniel and I am a recent college graduate who just finished a Master's in Artificial Intelligence. Here, you can find a portfolio of projects that I've worked on relating to data science and machine learning. Some of the skills I've developed include data visualization, data mining, machine learning, deep learning, deployment, and use of cloud services (GCP and AWS). Although I am well-versed in general machine/deep learning methods, one of my favorite topics is natural language processing. 

# Main Projects
## [Video Game Review Summarization](https://github.com/loriylo/video_game__review_NLP)
In this project, we combine the tasks of text classification, text summarization, and text-to-speech into one final implementation for users to quickly understand videogame reviews. Our focus was on IGN videogame reviews, such as this one. Our work involved heavy text cleaning, such as normalization via lowercasing, stopword removal, punctuation removal, and POS tagging.

![recommended wordcloud](https://github.com/loriylo/video_game__review_NLP/blob/main/images/recommended.png)
![not recommended wordcloud](https://github.com/loriylo/video_game__review_NLP/blob/main/images/not%20recommended.png)

Here is an example of the text classification component. First, we have a sample review, copied directly from the steam platform.

![steam game review](https://github.com/loriylo/video_game__review_NLP/blob/main/images/steam%20review%20ground%20truth.png)

Now we have our predicted recommendation label from our selected logistic regression model.

![predicted label](https://github.com/loriylo/video_game__review_NLP/blob/main/images/game%20review%20prediction.png)

## [Image Colorization](https://github.com/daniel-m777/image_colorization)
For this project, we decided to tackle the challenge of training a model to colorize black and white photos. For our dataset, we used this landscape dataset from Kaggle. For the architecture of the model, we based it on the CNN model from this [paper](https://arxiv.org/pdf/1603.08511.pdf). We will go through the code and describe the process in detail. To start, the following code demonstrates how we will be working with the LAB colorspace. The input for our model is the L channel, which is the luminance and ranges from 0-100 values. The output for our model are the ab channels, which represent different spectrum ranges (a is red-green, b is yellow-blue) with values ranging from -128-127.

![Lab colorspace](https://github.com/daniel-m777/image_colorization/blob/main/images/lab%20colorspace.png)

Below, we have an example of one of the final predictions made from our deep learning model. Ground truth images that already mostly consisted of grayish-blue, desaturated colors were the best predicted.

![Image prediction](https://github.com/daniel-m777/image_colorization/blob/main/images/prediction.png)

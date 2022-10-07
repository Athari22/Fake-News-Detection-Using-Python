# Fake News Detection Using Python
## Introduction
[Fake news](https://en.wikipedia.org/wiki/Fake_news) is the intentional broadcasting of false or misleading claims as news, where the statements are purposely deceitful.

Newspapers, tabloids, and magazines have been supplanted by digital news platforms, blogs, social media feeds, and a plethora of mobile news applications. News organizations benefitted from the increased use of social media and mobile platforms by providing subscribers with up-to-the-minute information.

Consumers now have instant access to the latest news. These digital media platforms have increased in prominence due to their easy connectedness to the rest of the world and allow users to discuss and share ideas and debate topics such as democracy, education, health, research, and history. Fake news items on digital platforms are getting more popular and are used for profit, such as political and financial gain.

## The main goal for this tutorial is:

To build a model to accurately classify a piece of news as REAL or FAKE.

## Dataset
This [dataset](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view) has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. The dataset takes up 29.2MB of space.

## Part One:
- Using TfidfVectorizer to convert a collection of raw documents into a matrix of TF-IDF features.
- Using Passive Aggressive algorithms (online learning algorithms) for the purpose is to make updates that correct the loss.
- Build confusion matrix.
![image](https://github.com/Athari22/Fake-News-Detection-Using-Python/blob/main/can_m.png)

## Part Two:
Using Natural language processing for display the reveal structure and meaning of text.
![image]()


## Ref:
1. https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/
2. https://www.thepythoncode.com/article/fake-news-classification-in-python   

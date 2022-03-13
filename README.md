# Arabic_Dialect_Sentiment_Analysis
A ML/DL based system, able to analyze Arabic Tweets and Classifies it to different types of Arabic accents.

![Arabic_Dialect_Classification](https://user-images.githubusercontent.com/24530726/158072356-7e5d3100-1ca8-4e98-9919-22c0e141c799.png)


Additional describtion about the project below.

## Tools, Libs used

• HTML

•CSS

•GIT

•Word2Vec

•Colab

•Python

•Gensim

•Flask

•ngrok

•keras

•TensorFlow

## Data Preprocessing

• Arabert pre-Trained Model
https://github.com/aub-mind/arabert

```
git clone https://github.com/aub-mind/arabert.git
!pip install farasapy
!pip install pyarabic

from arabert.preprocess import ArabertPreprocessor
```
• Word2vec word embeddings from gensim library

```
!pip3 install --upgrade gensim
```

```
from gensim.models import word2vec
```


## Modeling

• Machine Learning Modeling

```
from sklearn.svm import SVC
```

• Deep Learning Modeling

```
from tensorflow.keras import Sequential
from tensorflow.keras.layers import Bidirectional
```

## Deployment on Flask, ngrok service

### install important dependecies for Flask

```
!pip install flask-ngrok
!pip install pyngrok
```

### Linux command on colab to install Flask dependencies

```
!curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok
```

### install flask libraries
```
from flask import Flask, request, render_template
from flask_ngrok import run_with_ngrok
```


# Author

👤 Remon Atef Boshra

• Github @Remon128

• LinkedIn https://www.linkedin.com/in/remon-boshra/

• Twitter @remonaboshra

# Show your Support

Give a ⭐️ if you like the project !

Contributions, issues, and feature requests are welcome!

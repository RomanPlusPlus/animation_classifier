# animation_classifier
A fastai/Voila web-app to classify the user-provided image into one of these classes: anime, Disney animation, soviet animation. 

Click this link to render it as a web-app:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RomanPlusPlus/animation_classifier.git/main?urlpath=%2Fvoila%2Frender%2Fanimation_classifier.ipynb)

# Optionally: create any image classifier from it
One can easily modify the code to make it work with other classes too. See the [Jupyter notebook](animation_classifier.ipynb) for details. In short, you just need to:
* replace the classes names with your own (e.g. "cats", "dogs")
* replace the Bing image search API key (you can get a 7-days demo [for free](https://forums.fast.ai/t/getting-the-bing-image-search-key/67417))
* uncomment a few lines of code: 
  * the get_new_model
  * additional dependencies, as indicated in the notebeook
* run all cells in the notebook to generate the new trained model

![Alt text](illustration_small.jpg?raw=true "Title")

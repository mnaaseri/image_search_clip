
Image search by text using Clip AI

Clip contains two big models: a vision transformer for image embedding and a text transformer for text embedding. Clip has been trained on pairs of images and texts. The idea is to get embeding vector for a match image and text as close as possible to each other. So, Clip is able to take both images and text and embed them both into a similar vector space. In this notebook I want to show how we can use clip to search into unlabled and uncaptioned images only with text in a random image dataset.

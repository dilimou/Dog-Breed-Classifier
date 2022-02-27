# Dog-Breed-Classifier

## Project Overview
This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will say so.

## File descriptions
- dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
- dog_app.html: A copy of dog_app.ipynb in html format.
- Haarcascades folder: Xml file for use with the OpenCv face detector class.
- images: Images in jpg and jpeg format used to test the algorithm's predictions.

## Findings/Results
1. CNN from scratch: 1.0766%.
2. CNN from VGG-16: 43.5407%.
3. CNN from ResNet-50: 81.4593%.

## Tests results
![image](https://user-images.githubusercontent.com/23463800/151916545-00ab99f7-3785-4578-a72d-c7e9fbe4d531.png)
![image](https://user-images.githubusercontent.com/23463800/151916554-211a71a3-c85c-408c-9df5-218b3bd5f604.png)
![image](https://user-images.githubusercontent.com/23463800/151916565-e52bb484-f276-40dc-a1a6-4192c35669f8.png)
![image](https://user-images.githubusercontent.com/23463800/151916575-019ee367-2248-4d3c-9c61-c0cb163f54f9.png)


More indepth article on the classifier can be found int the article here: [Medium Post](https://medium.com/@dilidev/dog-breed-classification-using-cnns-and-transfer-learning-a53bdb2b22f1)

## Licensing, Authors, Acknowledgements
All the dataset and starting codes was procided by udacity.

# image_classifier

### Data Collection:
Data was scraped from google images, and then it was manually cleaned finally, making aroud 350-400 images per category, ie. Aamir, Salman and Shahrukh Khan

### Labelling:
Labelling of each image, was not really done, rather the whole image was used for the prediction task.
which is actually not a good thing to do. Labelling the image would increase the accuracy a lot.

### Transfer Learning:
because of very very small dataset, it was but obvious to use the concept of transfer learning. The pretrained weights from the inception model were used, they were then trained by adding an additiojal layer, to finally classify among our desired classes

### Libraries Used
Primarily Tensorflow was used for the task, Prettytensor was also used, just for the sake of easy addition of the layer to the model

### Results: 
Results, were more or less average, owing to the small and poor quality dataset, also the orignal images were massiverly scaled down, because of the lack of computation power available. Improving the above mentioned would increase the accuracy a lot.
Also, labelling the images propely would also work better.

### Please See:
 To replicate this notebook, you will have to download some pre required files, from the inception model : https://github.com/tensorflow/models/tree/master/inception
 

# Image Recognition Website

## METHODOLOGY

### **Technologies Used**
a)	Python
b)	Streamlit
c)	PIL Image
d)	Numpy
e)	Tensorflow
f)	ResNet50
g)	Keras

### **Data Collection**
Gather an image dataset that is pertinent to the image recognition task. Make sure the dataset has the right labels and a range of item categories.

### **Model Selection**
Select the ResNet50 model as the image recognition pre-trained model. This model can categorize a variety of items because it was trained using the ImageNet dataset.

### **Model Loading**
Utilize the TensorFlow Keras library's weights to load the pre-trained ResNet50 model. This enables utilizing the learnt features and weights of the pre-trained model.

### **Image Preprocessing**
The uploaded image is preprocessed by scaling it to the ResNet50 model's needed input dimensions. Make any necessary adjustments, such as resizing or normalizing.

### **Prediction Generation**
Utilize the predict_image function to produce predictions by feeding the preprocessed image into the ResNet50 model. To obtain labels and confidence scores, decode the predictions.

### **Prediction Display**
Brief the client to transfer a picture and show the transferred picture on the site. After tapping the "Foresee" button, utilize the predict_image capability to produce forecasts. Show the top expectations and their comparing certainty scores.

### **User Interface**
Use the Streamlit structure to make an online connection point for clients to interface with the image recognition framework. Execute elements, for example, record transferring, expectation show, and route between pages.

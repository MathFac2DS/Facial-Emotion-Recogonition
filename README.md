# **Facial Emotion Detection**

## **Problem Definition**
**Context:** The goal of artifical intelligence is to replicate human intelligence in performing certain tasks. In recent years, research has focused on predictive tasks that require assessing nonstructured data to better respond to users. Humans convey meaning though multimodal communication strategies including language, gestures, facial expressions and tone of voice. Since human emotion is abstract and subjective, it is arguably the hardest to predict. AI models could better interpret a user's experience and requests by assessing their emotional state. <br> <br> If AI models can interpret a user's emotions in real time, they can improve a user's experience, and assist a human facilitator. For example, one application could be in online education platforms. An effective classroom instructor leverages multimodal communication strategies to design lessons, and assess learning goals in real time. AI models designed to detect and analyze nonverbal cues could provide real time feedback to instructors teaching online. <br> <br>

**The objectives:**
* Build, train, and test models designed to predict the emotion conveyed through facial expressions in images.
* Compare models and architecture, identify factors that improve accuracy or reduce computational demands. <br> <br>

**The key questions:**
* What emotions can be classified well? When, or how frequently, is an image misclassified?
* What emotions are difficult to classify? When, or how frequently, do expressions convey a combination of emotions?
* What features of the image best identify the emotion expressed? <br> <br>

**The problem formulation:** What are we trying to solve using data science?
* What models and architecture yield the highest accuracy?
* What models and architecture reduce computational demands?

## **About the dataset**

The data set consists of 3 folders, i.e., 'test', 'train', and 'validation'.
Each of these folders has four subfolders:

**‘happy’**: Images of people who have happy facial expressions.<br>
**‘sad’**: Images of people with sad or upset facial expressions.<br>
**‘surprise’**: Images of people who have shocked or surprised facial expressions.<br>
**‘neutral’**: Images of people showing no prominent emotion in their facial expression at all.<br>

## Setup
1. Mount the drive
2. Import the libraries
3. Load the data
4. Visualize the classes
5. Check distribution of classes

## Custom CNNS 
7. Create data loaders
7a. Build base CNN Model 1
7b. Compile and train Model 1
7c. Analyze accuracy and evaluate the Model 1
8a. Build Model 2 CNN with increased complexity
8b. Compile and train Model 2
8c. Analyze accuracy and evaluate Model 2

## Transfer Learning Architectures - VGG16
9. Clear the backend
10. Build data loaders
10a. Import VGG16 Architecture
10b. Add fully connected layers
10c. Compile and train Model 3
10d. Analyze accuracy and evaluate Model 3

## Transfer Learning Architectures - ResNet V2
11a. Import Resnet V2
11b. Add fully connected layers
11c. Compile and train Model 4
11d. Analyze accuracy and evaluate Model 4

## Transfer Learning Architectures - EfficientNet
12a. Import EfficientNet
12b. Add fully connected layers
12c. Compile and train Model 5
12d. Analyze accuracy and evaluate Model 5

## Custom Complex CNN
13. Clear backend
14. Create data loaders
15. Build Model 6 with five convolutional blocks
15b. Compile and train Model 6
15c. Analyze accuracy and evaluate Model 6

## Model Comparisons
16. Compare models' architectures, parameters, training times, training/validation accuracies, testing accuracies

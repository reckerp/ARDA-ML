# ARDA-ML
Fontys University of Applied Sciences: Applied Research and Data Analysis 
 
**Authors:**
- [Louis Ferger-Andrews](https://github.com/LouisFerger-Andrews)
- [Paul Recker](https://github.com/reckerp)

Find the Latex paper [here](https://github.com/reckerp/ARDA-ML/tree/main/report)


## 1. Research Questions
### 1.1 Research Question
How does the number of training iterations a machine learning algorithm conducts affect the object detection accuracy in a computer vision program?

### 1.2 Secondary Research Questions
Does the kernel stride length affect the object detection accuracy

## 2. Variables
### 2.1 Independent Variable
Training iteration count (the number of times the data set is used for training the machine learning algorithm)

### 2.2 Dependent Variable
Accuracy of the computer vision program (the accuracy of the program identifying certain objects expressed as a percentage)

### 2.3 Controlled Variables
- Neural network
- Data set
- Test data
- Same Laptop specifications 

## 3. Hypothesis
Based on the context provided, it can be hypothesised that increasing the training iterations for the machine learning algorithm will have a direct correlation with the accuracy of the object detection model. Hence the greater the number of training iterations the program goes through, the greater the accuracy should become. This hypothesis is based on the fact that each additional iteration of training, will allow the model to converge towards a more optimised state by adjusting its parameters to minimize the differences between the training and the test data.

It is expected that during the initial training phases of the given experiment, specifically between 1,000 and 3,000 iterations, the model might face challenges in identifying objects in the test images accurately. In the cases where it does recognise the given objects, it will probably do so with only a minimal degree of accuracy. This is thereafter expected to greatly change as the model rapidly begins to gain a basic understanding of the objects it is confronted with based on its training. Therefore, it is appropriate to assume that during the stage, between  4,000 and 13,000 the greatest increase in accuracy should be displayed.  Beyond this point, it can be expected that as the model reaches a substantial accuracy of around 80\%, it can be hypothesised that the growth in accuracy will steadily decrease as the model converges towards an optimal state and the accuracy plateaus.

Furthermore, it can be postulated that a decrease in the model's loss should lead to an increase in accuracy, considering the inverse relationship between loss and accuracy, where a loss reduction indicates an improved performance as loss is measured by testing for accuracy.

In summary, a significant correlation between the accuracy and the number of training iterations for the machine learning algorithm is expected, which will gradually decrease as the model approaches its optimal state.

## 4. Research Methodology
- Empirical research: relies on evidence that can be observed or measured
- Quantative research: based on iterations, accuracy and loss

- Identifying data:
    - Accuracy and loss: continuous ratio (0% means no predictions correct)
    - No. of iterations: continuous ratio (0 iterations mean no training)

### 4.1 Chapter overview
- Methodology
    - Research Design
    - Experiment setup and execution 
    - Experiment evaluation
    - Data transformation and visualisation


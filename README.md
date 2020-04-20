# AI-project
hello this brain tumor classifier with accuracy 96.6% in test set i build it to AI course and this quik overview 
# [AI demo video](https://youtu.be/JqU_cqCVm50)
# [Data I Use](https://figshare.com/articles/brain_tumor_dataset/1512427)

![image](https://drive.google.com/uc?export=view&id=1gFzQi2tobnaaMVXRuEk021Km5Kih6oCX)
![image](https://drive.google.com/uc?export=view&id=1oteK8fbJKfOWuX1DG2_YtmMBkwAOPLZ7)
<html>
<h1>AI Project Computer Scenice Department </h1>
<h2>Intelligent Agent<h2>
<h3>Agent (PEAS)</h3>
<h4>Performance : Speed. Profit. Safe. Private.</h4>
<h4>Environment : Clinic.</h4>
<h4>Actuators : Screen display: Diagnoses. </h4>
<h4>Sensors : Keyboard</h4>

<h3>ODESA</h3>
<h4>Observable (fully, Partial)
Partially observable.
</h4>
<h4>D (Deterministic, Stochastic, Strategic)
 Stochastic
</h4>
<h4>Episodic (Episodic, Sequential)
Episodic
</h4>
<h4>Dynamic (Static, Dynamic , Semi-Dynamic)
Dynamic
</h4>
<h4>Discrete Agents  (Single agent, Multi-agent)
Continues. Multi-cooperative.
</h4>
<h2>Problem Formulation</h2>
<h3>Initial State:</h3>
<h4>Random Weight Of All Neuron</h4>
<h3>Successor Function:</h3>
<h4>Change Weight In Neural Network</h4>
<h3>Goal Test:</h3>
<h4>Successes To Classified brain MRI Image</h4>
<h3>Path Cost:</h3>
<h4>Minimize Difference Between Predicate And Label or " Maximize accuracy " </h4>

<h2>Project Design</h2>
<h4>brain tumor dataset consisting of 3064 T-1 weighted CE-MRI images publicly available via figshare Cheng (Brain Tumor Dataset, 2017 [1]). Using our simple architecture we could achieve a training accuracy of 98.51% and validation accuracy of 96.3% at best.
This dataset consists of 708 images with glioma, 1426 images with meningioma, and 930 images with pituitary tumors. In our training phase, we equalize the amount of images that are used.
Split data into 1500 image in training set and 450 image in validation set and 150 image in training.
We used image preprocessing and thin using transfer learning fine tuning vgg16 and some new layer with dropout and using adam optimizer with start learninig rate 0.0003 and thin decay to 0.0002  after 25 epoch.</h4>

<h2>AI algorithm</h2>
<h4>CNN (convolutional-neural-networks)
First layer is vgg16 and thin new CNN layer with dropout</h4>
<h2>Tool I Use </h2>
<h4>python</h4>
<h4>google cloab to train model</h4>
<h4>tensorflow machine learning framework</h4>
<h4>tkinter python library to make desktop application</h4>



</html>


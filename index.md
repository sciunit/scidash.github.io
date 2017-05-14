### Good scientific models are *formalized hypotheses* that can make predictions about system behavior. How can scientists evaluate the strength of a candidate model, or which one is best among many such models of the same system?

<p style="text-align: center;"><img src="https://i.ytimg.com/vi/waexG16WZrE/maxresdefault.jpg" width="700">
<br>
Which model best predicts the experimental observations?</p>

### **SciDash** is a project that enables the reproducible execution and visualization of *data-driven unit tests* for assessing model quality.  It is a 21st century vision of the scientific method.

<p style="text-align: center;"><img src="assets/score-table.png">
<br>
What if every competing model was transparently evaluated against a suite of unit data-driven tests?</p>

### How can a wide variety of scientific disciplines, modeling technologies, and data types be engaged in systematic testing?  

### We provide [SciUnit](sciunit.html), a Pythonic framework for data-driven unit testing that separates the interface from the implementation, respecting the diversity of conventions for modeling and data collection.

<p style="text-align: center;"><a href="sciunit.html"><img src="https://raw.githubusercontent.com/scidash/assets/master/logos/sciunit.png" width="600"></a>
<br>
<a href="sciunit.html">SciUnit</a> is a discipline-agnostic framework for model validation, handling all of the testing workflow by using a implementation-independent interface to models.  SciUnit also contains code for visualization of model results, and command line tools for incorporating testing into continuous integration workflows.</p>

### Discipline-specific unit testing requires extensible libraries that can implement the interfaces to simulators, data repositories, and analysis tools.  

### We develop [NeuronUnit](neuronunit.html), a SciUnit-driven library for the investigation of neuron, neural circuit, and ion channel models.

<p style="text-align: center;"><a href="neuronunit.html"><img src="https://raw.githubusercontent.com/scidash/assets/master/logos/neuronunit.png" width="400"></a>
<br>
<a href="neuronunit.html">NeuronUnit</a> is a SciUnit library for validation of neuron and ion channel physiology models.  It implements an interface to several simulators and model description languages, handles test calculations according to domain standards, and enables automated construction of tests based on data from several major public data repositories.</p>

### SciUnit and discipline-specific libraries support testing and visualization of test results.  How can interested communities find these tests and their results?  

### We are developing a SciDash portal to identify test repositories on GitHub and make it easy to locate them, execute the tests locally or in the cloud, and visualize results online.

<img src="assets/cosmo-example-crop.png">

### The SciDash project aims to make validation of scientific models against experimental data easy, transparent, and continuously integrated into the model development process.
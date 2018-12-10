### How can a wide variety of scientific disciplines, modeling technologies, and data types be engaged in systematic testing?  

### We provide **[SciUnit](sciunit.html)**, a Pythonic framework for data-driven unit testing that separates the interface from the implementation, respecting the diversity of conventions for modeling and data collection.

<p style="text-align: center;"><a href="sciunit.html"><img src="https://raw.githubusercontent.com/scidash/assets/master/logos/SciUnit/sci-unit-tag.png" width="650"></a>
<p style="text-align: justify;"><a href="sciunit.html">SciUnit</a> is a discipline-agnostic framework for model validation, handling all of the testing workflow by using a implementation-independent interface to models.  SciUnit also contains code for visualization of model results, and command line tools for incorporating testing into continuous integration workflows.</p></p>

## Overview
[The conference paper](https://github.com/cyrus-/papers/raw/master/sciunit-icse14/sciunit-icse14.pdf)

## Basic Usage
```python
my_model = MyModel(**my_args) # Instantiate a class that wraps your model of interest.  
my_test = MyTest(**my_params) # Instantiate a test that you write.  
score = my_test.judge() # Runs the test and return a rich score containing test results and more.  
```

## Key features
- Applies to any scientific domain
- Makes no assumptions about model implementation
- Implementation satisfied by modular *Capabilities*
- Flexible, drop-in scoring framework
- Rich test score visualizations 
- Model parameter optimization
- Contingent test parameterization and execution
- Tight Jupyter integration
- Command line tools for headless systems

## Source Code
[![SciUnit GitHub Repository](assets/github.png)](https://github.com/scidash/sciunit)

Community participation is encouraged!

## Documentation
### Jupyter Tutorials
[Chapter 1](https://github.com/scidash/sciunit/blob/master/docs/chapter1.ipynb) / 
[Chapter 2](https://github.com/scidash/sciunit/blob/master/docs/chapter2.ipynb) /
[Chapter 3](https://github.com/scidash/sciunit/blob/master/docs/chapter3.ipynb) /

### Developer Reference
[API Documentation](http://sciunit.rtfd.io)

### Reproducible Research ID
RRID:[SCR_014528](https://scicrunch.org/resources/Any/record/nlx_144509-1/3faed1d9-6579-5da6-b4b4-75a5077656bb/search?q=sciunit&l=sciunit)

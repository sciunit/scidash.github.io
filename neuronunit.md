### Scientific discipline-specific unit testing requires extensible libraries that can implement the interfaces to simulators, data repositories, and analysis tools.  

### We develop **[NeuronUnit](neuronunit.html)**, a *[SciUnit](sciunit.html)*-driven library for the investigation of neuron, neural circuit, and ion channel models.

<p style="text-align: center;"><a href="neuronunit.html"><img src="https://raw.githubusercontent.com/scidash/assets/master/logos/neuronunit/NeuronUnitBlack2.png" width="800" align="center"></a>
<p style="text-align: justify;"><a href="neuronunit.html">NeuronUnit</a> implements an interface to several simulators and model description languages, handles test calculations according to domain standards, and enables automated construction of tests based on data from several major public data repositories.</p></p>

## Overview 
[The manuscript](https://www.overleaf.com/read/kjhjgtzjcsvq)

## Basic Usage
```python
my_model = ReducedModel('/path/to/file',backend='NEURON') # Instantiate a reduced neuron model.  
my_test = RheobaseTest(observation={'mean':100*pA,'std':5*pA}) # Instantiate a test based on 
                                                               # data from the literature or your lab.  
score = my_test.judge() # Runs the test and return a rich score containing test results and more.  
```

## Key features
- Generates tests using data from neuroelectro.org, the Allen Brain Institute, the Blue Brain project, or your lab.  
- Fully NeuroML 2.0 compliant
- Supports both NEURON and the jNeuroML reference simulator  
- Support for neuroConstruct via jython bridge
- Parallel test execution and/or parameter optimization
- Built-in test classes for commonly-measured experimental properties of cells and ion channels
- Neuroscience Gateway integration
- Docker containers for reproducible testing

## Source Code
[![NeuronUnit GitHub Repository](https://raw.githubusercontent.com/scidash/assets/master/logos/github.png)](https://github.com/scidash/neuronunit)

Community participation is encouraged!

## Documentation
### Jupyter Tutorials
(See [SciUnit documentation](http://github.com/scidash/sciunit/blob/master/docs/chapter1.ipynb) first)

[Chapter 1](http://github.com/scidash/neuronunit/blob/master/docs/chapter1.ipynb) / 
[Chapter 2](http://github.com/scidash/neuronunit/blob/master/docs/chapter2.ipynb) /
[Chapter 3](http://github.com/scidash/neuronunit/blob/master/docs/chapter3.ipynb)

### Developer Reference
[API Documentation](http://neuronunit.rtfd.io)

## Reproducible Research ID
RRID:[SCR_015634](https://scicrunch.org/scicrunch/Resources/record/nlx_144509-1/c70f9dfd-0fc6-5052-9d90-a571c2ebea2e/search)

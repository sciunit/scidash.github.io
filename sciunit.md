# SciUnit: A Test-Driven Framework for Formally Validating Scientific Models Against Data
![SciUnit Logo](https://raw.githubusercontent.com/scidash/assets/master/logos/sciunit.png)

## Concept
[The conference paper](https://github.com/cyrus-/papers/raw/master/sciunit-icse14/sciunit-icse14.pdf)

## Basic Usage
```python
my_model = MyModel(**my_args) # Instantiate a class that wraps your model of interest.  
my_test = MyTest(**my_params) # Instantiate a test that you write.  
score = my_test.judge() # Runs the test and return a rich score containing test results and more.  
```

## Source Code
[SciUnit  GitHub Repository](https://github.com/scidash/sciunit)

## Tutorial Documentation
[Chapter 1](https://github.com/scidash/sciunit/blob/master/docs/chapter1.ipynb) / 
[Chapter 2](https://github.com/scidash/sciunit/blob/master/docs/chapter2.ipynb) /
[Chapter 3](https://github.com/scidash/sciunit/blob/master/docs/chapter3.ipynb) /

## API Documentation:
[Read the Docs](http://sciunit.rtfd.io)
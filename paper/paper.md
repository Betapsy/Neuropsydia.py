---
title: 'Neuropsydia.py: A Python Module for Creating Experiments, Tasks and Questionnaires'
tags:
  - python
  - psychology
  - questionnaire
  - experiments
  - neuropsychology
  - tasks
  - assessment
authors:
 - name: Dominique Makowski
   orcid: 0000-0001-5375-9967
   affiliation: 1, 2
 - name: Léo Dutriaux
   affiliation: 1, 2
affiliations:
 - name: Memory and Cognition Lab', Institute of Psychology, University of Sorbonne Paris Cité, France
   index: 1
 - name: INSERM U894, Center for Psychiatry and Neuroscience, Paris, France
date: 03 April 2017
bibliography: paper.bib
---

# Summary

Neuropsychology encompasses two intimately related aspects: experimental research and clinical activity. Yet, the gap between these two facets has been severely increasing over the last decades due to the developpement of new technological facilities employed in research paradigms, often lacking portability to clinical practice. This gap, is restraining direct application and generalization of results from research to clinical practice, and *vice versa*. **Neuropsydia.py** is a Python module that provides a high-level set of tools to quickly and easily create computerized experiments, cognitive tests or questionnaires. This free, open-source solution allows neuropsychologists, psychologists and neuroscientists to build sophisticated tasks and focus on what is important: the results and their interpretation.

Neuropsydia.py is based on Pygame and the SDL library, allowing for maximum flexibility and compatibility. Unlike other python-based experiment creation modules, such as PyschoPy [@peirce2007psychopy] or OpenSesame [@mathot2012opensesame], it has no GUI, yet still mainly oriented toward for non-programmers. Indeed, its API is centered around a limited amount of functions with straighforward names such as `write`, `image`, `ask`, `scale` or `choice`. This function-oriented philosophy (contrary to class-oriented syntax such as the one used in Expyriment [@krause2014expyriment]) allows readability and understanding even for people with not much experience in programming.

Neuropsydia.py can be installed using pip from the Python Package Index [1](https://pypi.python.org/pypi/neuropsydia). Source code and issue tracker are available in Neuropsydia.py's GitHub repository [2](https://github.com/neuropsychology/Neuropsydia.py). Documentation, tutorials and examples are provided through Readthedocs [3](http://neuropsydia.readthedocs.io/en/latest/). Usage examples and a test script are also contained in the repository [4](https://github.com/neuropsychology/Neuropsydia.py/tree/master/examples), [5](https://github.com/neuropsychology/Neuropsydia.py/tree/master/tests).


![](wordcloud.png)


# References


---
layout: project
resources:
  - icon: ti-github
    name: GitHub
    content: Project repository
    url: https://github.com/Emilostuff/algoaid
  - icon: ti-bookmark
    name: PyPi
    content: Package page
    url: https://pypi.org/project/algoaid/
---

**Algoaid is a collection of useful tools for students taking an introductory course in algorithms and data structures.**
    
When I was diving into the world of algorithms and data structures at university I supplemented the theoretical parts of the course with a lot of programming, experimenting with all the exciting new concepts I encountered. When closing in on the exam I started writing tools for my self that could help me for example double-check my answers or even solve some problems completely. 

As I found these tools very useful, I believe that other students in the same situation would appreciate them as well, not just as a help for their exam but perhaps also as another way of interacting with the curriculum during the course. Hence I took some time to adapt all my code to an easy to use and well-documented Python package that is now available for everyone on PyPi (The Python Package Index) and that can be downloaded by running the simple command: ```pip install algoaid```.

As an example, algoaid can analyze the time complexity of simple functions that depends on a single parameter. For instance it could be the function:
```python
def f(n):
    j = 1
    while j * j < n:
        j += 1
```
By running `analyse(f)` we obtain the following result, which is indeed correct.

<img src="https://camo.githubusercontent.com/39ce294c4c64adf8e2602213368cda1b647f301f1911ef782ff6e56c397d8bf5/68747470733a2f2f692e696d6775722e636f6d2f70336c624c67442e706e67" class="img-fluid w-100 rounded">


Writing my first package to be published on PyPi was a great learning experience. Exploring how a Python package should be structured and writing the code as clean and user-friendly as possible helped my develop my Python skills significantly.

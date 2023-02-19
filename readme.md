# Computer Perception Extended - Winter 2022 / 2023

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/webslides/webslides.svg?style=social)](https://twitter.com/digideation)

[★★★ This repository is published here ★★★](https://digitalideation.github.io/compp_f2301/)

## Intro

In this module we will explore different applications of ML/AI/DL with a particular focus on design and art. We will first learn how neural networks work with simple code examples, then we will experiment with different techniques of Deep Learning:

- DL applied to Computer Vision (image classification, objects detection, pose estimation...)
- Generative Deep Learning (DeepDream, style transfer, Pix2Pix / CycleGAN...)
- etc...

Once we get a good grasp of the different techniques, we will experiment further by building our own ‘AI’ project. :space_invader:

## Schedule

### [Week 01](content/week01.md)

- Students intro :wave:
- Intro: General
- ML / AI / DL: History & Example
- Inner working of a Neural Network
- Intro to tools: Jupyter / Colab

## Evaluation

### Evaluation criteria:

- Attendance, participation and engagement in others' projects (1/3)
- Research, Documentation (1/3)
- Final Project (1/3)

### Deliverables:

- Presentation / Source code / Documentation

## Academic integrity

[_(Copied from Golan Levin's 2020 CMU class)_](https://courses.ideate.cmu.edu/60-212/f2020/syllabus/academic-integrity/)

### Use of free and open source code

**Credit is perhaps the most important form of currency** in the economies of commons-based peer production and open-source media arts. You are expected to cite the source of any code you use. Please note the following expectations and guidelines:

**Use Libraries**. In your Projects, the use of general, reusable libraries is strongly encouraged. The people who developed and contributed these components to the community worked hard, often for no pay; acknowledge them by citing their name and linking to their repository.

**Be Careful**. It sometimes happens that an artist places the entire source code for their sketch or artwork online, as a resource from which others can learn. The assignments professors give in new-media arts courses are often similar; you may discover the work of a student in some other class or school, who has posted code for a project which responds to a similar assignment. You should probably avoid this code. At the very least, you should be very, very careful about approaching such code for possible re-use. If it is necessary to do so, it is best to extract components that solve a specific technical problem, rather than those parts which operate to create a unique experience. Your challenge, if and/or when you work with others’ code, is to make it your own. It should be clear that forking an artwork from someone’s page on GitHub, Glitch, OpenProcessing, etc., and simply changing the colors would be disgracefully lazy. Doing so without proper citation would be plagiarism.

### Informal colaborations

Our course places a very high value on civic responsibility that includes, but is not limited to, helping others learn. In this course, we strongly encourage you to give help (or ask others for help) in using various toolkits, algorithms, libraries, or other facilities. Please note the following expectations:

- In this class, it’s OK to give and receive help. In fact, it’s better than OK! But students who receive help from someone else are obliged to acknowledge that person in their project report, clarifying the nature of the help that was received.
- We are all teachers. Students with advanced skills are expected to help others, yet refrain from doing another’s work for them. You can usually tell when you’re about to cross the line: Ask yourself whether you are teaching someone to fish, or merely giving them the fish.
- When in doubt: give credit to the people who have helped you.

### Formal colaborations

The assignments in this course are primarily intended to be executed by individuals. That said, I am in favor of students collaborating if such collaborations arise organically and can be conducted safely. Please note the following expectations:

- Use proper social distancing. In light of the ongoing the COVID-19 pandemic, please respect University and other health guidelines regarding personal distance. Do not share computer keyboards, sit at least 6 feet apart, etcetera.
- Notify the Professor. It’s helpful for me to know who is working with whom. Students who wish to collaborate should jointly inform the professor as early as possible.
- Only pairs. Unless permission is explicitly granted by the Professor, collaborations in this course are restricted to pairs of students.
- Describe who did what. Written reports for collaborative projects should describe how your effort was distributed.
- Only known collaborators. Your project collaborator, if you have one, must be in this class. You may not collaborate with people from outside the course (e.g. your housemate).
- Avoid co-dependency. You may not collaborate with the same person (i.e. submit an assignment jointly) on more than two projects.

## Tools

### System requirement

Modern machine with decent hardware and sufficient space on the hard drive (20+ Gb)

### Code editor

If you don’t have a code editor, please install one. Some suggestions (in no particular order)

- [Sublime Text](https://www.sublimetext.com)
- [Visual Studio](https://code.visualstudio.com)
- [Atom](https://atom.io)

### Web server

We will need a simple web server to run the experiments locally. Some suggestions

- If you have node.js/npm installed you can use _live-server_: `npm install -g live-server`
- [Other recommended options](https://github.com/digitalideation/hslu-ml-workshop#web-server)

### Tensorflow.js

A **JavaScript** library with a more advanced set of options, also for the web.

- [Getting Started](https://js.tensorflow.org/#getting-started)
- [Tutorials](https://js.tensorflow.org/tutorials/)
- [Keynote](https://www.youtube.com/watch?v=YB-kfeNIPCE)
- [Examples](https://github.com/tensorflow/tfjs-examples)
- [Video Tutorials](https://github.com/tensorflow/tfjs/blob/master/GALLERY.md#video-tutorials)

### Keras

Keras is a high-level neural networks API, written in **Python** and capable of running on top of **TensorFlow, CNTK, or Theano**. It was developed with a focus on enabling fast experimentation

- [Getting Started](https://keras.io/#getting-started-30-seconds-to-keras)
- [Tutorials](https://blog.keras.io/index.html)

### ML5.js

ML5.js is a simple **JavaScript** ML library for the web based on tensorflow.js.

- [Getting started](https://ml5js.org/docs/getting-started)
- [Experiments](https://ml5js.org/en/experiments)
- [Git source](https://github.com/ml5js)

### P5.js

[**p5.js** ](https://p5js.org/) is a high level creative programming framework with an [intuitive API](https://p5js.org/reference/). If some of you have used Processing before you should be confortable using p5.js. To get familiar with p5 you can go through this list of tutorials / guides:

- [P5 Learn](https://p5js.org/learn/)
- [P5 Wiki](https://github.com/processing/p5.js/wiki/)
- [Creative Coding](https://creative-coding.decontextualize.com/)
- [Shiffman's Foundation of programming in js](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
- [P5js reference](https://p5js.org/reference/)

### Magenta.js

Magenta.js is a collection of **TypeScript** libraries for doing inference with pre-trained Magenta models. All libraries are published as npm packages.

- [Demos](https://magenta.tensorflow.org/demos)
- [Blog](https://magenta.tensorflow.org)

### Conda

[**Conda**](https://conda.io) is an open source package management system and environment management system that runs on Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their dependencies. Conda easily creates, saves, loads and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language.

## References / Reading list

- History:
  - [History - Longer history of Machine Learning](http://www.andreykurenkov.com/writing/ai/a-brief-history-of-neural-nets-and-deep-learning/)
  - [History - History of Machine Learning](https://cloud.withgoogle.com/build/data-analytics/explore-history-machine-learning/)
- Intro:
  - [Neural Networks - Intro videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
  - [Neural Networks - Intro text](https://ml4a.github.io/ml4a/neural_networks/)
  - [Machine Learning - Getting started](https://www.youtube.com/watch?v=I74ymkoNTnw)
  - [Machine Learning is fun (series)](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471)
- Books:
  - [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python)
  - [Grokking Deep Learning](https://www.manning.com/books/grokking-deep-learning)
  - [Intelligence Artificielles, Miroirs de nos vies (BD) ](http://www.sceneario.com/bande-dessinee/intelligences-artificielles/miroirs-de-nos-vies/29059.html)
- Programming languages:
  - [Learn Python the hard way][ref-learn-python-the-hardway]: to (re)learn your basic in Python
  - [Google's Python Class][ref-google-python]: concise and clear
  - [CodeAcademy Python][ref-ca-python]: Code Academy Python class
  - [W3School js][ref-w3s-js]: JS simple tutorials
  - [CodeAcademy JS][ref-ca-js]: Code Academy JS class
  - [Eloquent JS][ref-el-js]: Eloquent JS

[ref-learn-python-the-hardway]: https://www.learnpythonthehardway.org
[ref-google-python]: https://developers.google.com/edu/python/
[ref-ca-python]: https://www.codecademy.com/learn/learn-python
[ref-w3s-js]: https://www.w3schools.com/js/default.asp
[ref-ca-js]: https://www.codecademy.com/learn/introduction-to-javascript
[ref-el-js]: https://eloquentjavascript.net

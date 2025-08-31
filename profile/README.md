# Applied AI in Risk and Finance
[`Course outline`](#course outline) | [`Lectures`](#lectures) | [`Prerequisites`](#prerequisites) | [`Discussion forum`](#discussion forum) | [`Technical setup`](#technical setup) | [`FAQ`](#faq) | [`License`](#license)

Welcome to the course website of the Applied AI course in Risk and Finance.

## Course outline

This is a hands on AI course thaugt by [Julian Dörr](https://juliandoerr.com/) to equip participants with essential skills to apply AI methods and models in real world use cases. Here is the course description taken from the course [repository](https://github.com/ai-analytics-jlu-ws25-26/courses) 

> This seminar is targeted at PhD students interested in learning how different subfields of Artificial Intelligence are applied in practice. This course will likely differ from other courses in your PhD program as it places great focus on how different methods which originate from research help to tackle real world use cases in the finance and risk industry. My goal is bring you up to speed on the practical tools, techniques and frameworks that I feel will most benefit your future career both in research but also in industry. While the typical core graduate curriculum places great focus on the theoretical foundations, this course focuses on how to put great methods and models into practice. We will cover topics like version control (Git); data cleaning and visualization; programming in Python; and most importantly the application of AI methods from the field of Machine Learning (ML), Natural Language Processing (NLP) and Generative Artificial Intelligence (GenAI). **In short, we will cover things that enable you to bridge the gap between theory and practice.**

## Lectures

1. Machine Learning - Developing a Risk Model \[[**.ipynb**](https://github.com/ai-analytics-jlu-ws25-26/courses/blob/main/1_ml/ml.ipynb) | [**.html**](https://juliandoerr.com/courses/1_course/#/)\]
2. Natural Language Processing - Automating Insurance Claims processing \[[**.ipynb**](https://github.com/ai-analytics-jlu-ws25-26/courses/blob/main/2_nlp/nlp.ipynb) | [**.html**](https://juliandoerr.com/courses/2_course/#/)\]
3. Generative AI - Build an Annual Reports Agent \[[**.ipynb**](https://github.com/ai-analytics-jlu-ws25-26/courses/blob/main/3_genai/genai.ipynb) | [**.html**](https://juliandoerr.com/courses/3_course/#/)\]

Please do read the rest of the README before you go through the lectures. This will detail software requirements and installation, and give you a better sense of the full aims and scope of the course.

## Prerequisites

All of the code in this course is written in Python. While coding itself is not the focus of the course, and much of the coding complexity is abstracted away via functions and classes, it is yet recommended to have some prior knowledge of Python or any other object-oriented programming language. This makes is just easier for you to dive into the actual content - AI methods and their applications - so you do not have to start from scratch with both the actual content _and_ technical means we use to do so, i.e. Python programming. To give you a better sense how good your Python knowledge is, I have prepared a short quiz that consists of short Python programming tasks. The quiz serves merely as self-assessment - so no grading nothing. If you manage to solve the majority of the tasks you are good to go to dive into the course material. If you struggle with the tasks, you may want to prepare yourself for the course by self-learning at least the basics of Python. There is ton great courses and tutorials out there. One that I can recommend is the following 2 hours crash [course](https://www.youtube.com/watch?v=K5KVEU3aaeQ) for complete beginners. It's free and engaging.

## Discussion forum
Throughout the course, you may face issues or questions that you may not be able to solve/answer yourself even after doing some research or asking your prefered conversational AI. For this case, the course website offers a discussion forum where you are free to pose any questions related to the course material or the technical setup. The forum is great place to get in touch with each other and help out one another. Often issues you are facing, have been faced (and possibly solved) by your peers before. Taking a look into the discussion forum can be a helpful source to check for solutions for the problems you are facing. If there has not been openend a suitable discussion, the forum is there to place your question. I will regularly visit the forum and answer open issues. But feel free to answer open questions yourself if you have a solution at hand. This way we can foster collaboration and make the best out of this course.

## Technical Setup-up
All of the software requirements for this course are open-source and/or free. Please aim to have everything installed by the start of our first lecture. I will be available for installation troubleshooting
during the first week before the start of this course via the discussion forum.

### Python
As outlined above we will be using Python, specifically **Python 3.12** throughout this course (download [here](https://www.python.org/downloads/release/python-3120/)). As Integrated Development Environment (IDE), we will be using JupyterLab the installation of which comes with the setup of the virtual environment . If you like to work with PyCharm or Visual Studio Code as your prefered IDE you can of course do so as well.

### Git and GitHub
We will also make use of the **Git** version control system (follow the OS-specific installation instructions [here](https://git-scm.com/downloads)).Once you have installed Git, please create an account on **GitHub** ([here](https://github.com/join)). While this course is not about Git and GitHub, we will need some basic Git operations to e.g. clone code from GitHub to our local machines. 

Regardless of this course, I highly encourage everyone to familiarize with Git for your own work and project management. In simple terms, Git is a version control system that helps you track changes in your code or files over time. GitHub, in turn, is an online hosting platform that provides an array of services built on top of the Git system. It allows multiple people to collaborate on a project or as in our case to organize a course (share course material, engage in discussion forum, ...). While Git is widely used in software development to ensure that changes are organized, documented, and easily manageable, it is also extremely beneficial in research. Just of the following:
- Benefits of version control and collaboration tools aside, Git(Hub) helps to operationalise the ideals of open science and reproducibility.
- Journals have increasingly strict requirements regarding reproducibility and data access. GitHub makes this easy (DOI integration, off-the-shelf licenses, etc.)
- I host all of the code and data for my papers on GitHub. Same for teaching materials. I even use it to host and maintain my website.

## FAQ

### How do I download this material and keep up to date with any changes?

Please note that this is a work in progress, with new material being added every week. 

If you just want to read the lecture slides or HTML notebooks in your browser, then you should simply scroll up to the [Lectures](#lectures) quicklinks section at the top of this page.

If you actually want to run the analysis and code on your own system (highly recommended), then you will need to download the material to your local machine. The best way to do this is to clone the repo via Git and then pull regularly to get updates. Please take a look at [these slides](https://raw.githack.com/uo-ec607/lectures/master/02-git/02-Git.html) if you are unfamiliar with Git or are unsure how to do any of that. Once that's done, you will find each lecture contained in a numbered folder (e.g. `1_ml`).

### I've spotted a mistake or would like to contribute

Please [open a new issue](https://help.github.com/articles/creating-an-issue/). Better yet, please fork the repo and [submit an upstream pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/). I'm very grateful for any contributions, but may be slow to respond while this course is still be developed. Similarly, I am unlikely to help with software troubleshooting or conceptual difficulties for non-enrolled students. Others may feel free to jump in, though.

### Can I use/adapt your material for a similar course that I'm teaching?

Sure. That's partly why I have made everything publicly available. I only ask two favours. 1) Please let me know [email](mailto:me@juliandoerr.com) if you do use material from this course, or have found it useful in other ways. 2) An acknowledgment somewhere in your own syllabus or notes would be much appreciated.

### Are you willing to teach a (condensed) version of this course at my institution?

Possibly. Please [contact me](mailto:me@juliandoerr.com) if you would like to discuss further.

### What are you using to produce these lecture slides/notebooks?

All of the lecture material is written in Jupyter Notebooks. For the html slidesow I am using the [jupyter nbconvert](https://github.com/jupyter/nbconvert) extension which allows to convert Jupyter Notebooks into various other formats.

## License

The material in this repository is made available under the [MIT license](http://opensource.org/licenses/mit-license.php). 


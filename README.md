# Final Assignment

In this assignment, you will either implement various policy gradient algorithms or model-based algorithms. You can choose to either continue working with the Catch environment or switch to a new one.

This template repository is almost the same as the previous one, with slight changes made to the Agent class.

If you decide not to use the Catch environment, make sure to adapt (or remove) the `environment.py` file.

## Installation

Before running the code, make sure you properly install the dependencies:

```
python3 -m pip install -r requirements.txt
```

The code has been tested with Python 3.11.

## Running the code

Now, you should be able to simply run the `main.py` as any other script.

In order to allow us for easy grading, we implemented a simple test that checks wheter your `requirements.txt` file is complete and that your code runs without errors. You can run this test by executing the following command:

```
source test.sh
```

## Tips and Resources

Here are a couple of hints and resources that might help you with this assignment:

1. To help you out with technical writing, check out these papers for inspiration. Reading real scientific papers can help you out with using correct nomenclature and ensuring a clear structure. In particular, you can draw inspiration as to how complex concepts and formulas are introduced
   and explained.

   a. Technical Report on implementing RL algorithms in CartPole environment - https://arxiv.org/pdf/2006.04938.pdf

   b. Paper summarising usage of RL in Chess - https://page.mi.fu-berlin.de/block/concibe2008.pdf

2. If you have duplicate code in multiple places, it’s probably a bad sign. Maybe you should try to group that functionality in a separate function?
3. The agent should be able to learn using different types of algorithms. Maybe there is a way to make these algorithms easily swappable?
4. Type hinting is not required, but it can help your partner understand your code - https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html
5. Git workshop by Cover - https://studysupport.svcover.nl/?a=1
6. YouTube Git tutorial - https://www.youtube.com/watch?v=RGOj5yH7evk
7. OOP in Python - https://www.youtube.com/watch?v=JeznW_7DlB0
8. How to document Python? - https://www.datacamp.com/tutorial/docstrings-python4

## Questions and help

If you are struggling with one part of the assignment, you're probably not alone. That's why we want to create a small FAQ throughout the next couple of weeks. In case of a question, raise an issue in the original, template repository: [https://github.com/Deep-Reinforcement-Learning-RUG/catch-assignment](https://github.com/Deep-Reinforcement-Learning-RUG/catch-assignment). We will answer your questions there, so that there are no duplicate questions.

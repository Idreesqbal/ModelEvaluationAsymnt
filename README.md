# Model evaluation challenge - US Income

![Dollar Bundles (Image)](assets/us-dollar-bundles.jpg)
[[Image source] Retrieved on 16/11/2020.](https://see.news/expert-us-dollar-inches-to-collapse-world-return-to-gold-standard/)

## Mission objectives

- Be able to analyze a machine learning problem
- Be able to reason about possible causes of overfitting
- Be able to remedy the causes of overfitting
- Be able to tune parameters of a machine learning model
- Be able to write clean and documented code.

## The Mission

One evening, while you were minding your own business watching the latest show on Netflix, you get an e-mail from a stock broker à la *Wolf of Wall Street*... the type of guy that only cares about sex, drugs and money.

He asks a favor from you.

At first, you are put off and stop reading. However, you remember that that guy has lots of money and likes to throw it around, so you read further.

He asks a simple question: *Are you able to predict the income of every US citizen?*

**How hard could that be ? Not that hard, no ?** True.

However, one has to be careful about how the data is processed to not give false results. That is why you are tasked, as a group, to discuss and implement various ways to get a correct prediction from a machine learning model.

### Must-have features

- Baseline accuracy
- Multiple evaluation metrics
- Hyper parameter tuning
- Some time of validation strategy

### Miscellanous information

The datasets `data_train.csv` and `data_test.csv` have already been downloaded (and cleaned) for you in here:

- [../../../additional_resources/datasets/US Income/cleaned/data_train.csv](../../../additional_resources/datasets/US%20Income/cleaned/data_train.csv)
- [../../../additional_resources/datasets/US Income/cleaned/data_test.csv](../../../additional_resources/datasets/US%20Income/cleaned/data_test.csv)

Also, make sure to check the README files for the attribute information :

- [README 1](../../../additional_resources/datasets/US%20Income/README.md)
- [README 2](../../../additional_resources/datasets/US%20Income/cleaned/README.md)

### Constraints

- You must use `RandomForestClassifier()` from `sklearn`. We want you to focus on model evaluation, not on the model choice nor on the data preprocessing.
- Create **functions**, do **not** create a single huge script
- Each **function or class** has to contain a docstring in a [consistent format](https://stackoverflow.com/a/24385103).
- Your code should be **commented**.
- Your code should be **cleaned of any commented unused code**.

## Deliverables

1. Publish your source code on the GitHub repository.
2. **Small presentation (5 minutes) about your findings**
3. Pimp up the readme file:
   - What, Why, When, How, Who.
   - Pending things to do

### Steps

Here is a proper description of what we expect from you.

We want you to focus on the model evaluation part, everything that you've seen in this chapter. Of course, don't forget things that you'be done in previous chapters, only this time, it is not the focus.

First of all, before doing anything complicated, just split the data set into a training and testing split, and with the default classifier, compute the score of the model. This will be your **baseline accuracy** against which you'll measure your improvements.

Then you can get more complicated and use multiple evaluation metrics, see if there is a hint of overfitting, tune your hyper-parameters to have a better score, etc...

**Think hard about what you do and if what you are doing will bias the model or not.**

1. Create the repository
2. Study the request (What & Why ?)
3. Identify technical challenges (How ?)

## Evaluation criterias

| Criteria       | Indicator                                                                             | Yes/No |
|----------------|---------------------------------------------------------------------------------------|--------|
| 1. Is complete | The student has realized all must-have features.                                      |        |
|                | There is a published GitHub page available.                                           |
|  |The hyper-parameters were tuned. |        |
|  |A baseline accuracy was established. |        |
| 2. Is Correct  | There are no warnings or errors when running the script.                                     |        |
|  |The code is well typed. |        |
|  |The code is well commented and every function has a docstring. |        |
|                | The constraints are respected.|        |

## A final note of encouragement

You've been waiting for this, and I'm certain that you are ready for it.

![You've got this!](https://media.giphy.com/media/gTURHJs4e2Ies/giphy.gif)

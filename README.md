# Finding Donors for CharityML

## Description
**CharityML** is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than **$50,000 annually**. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. With nearly 15 million working Californians, CharityML has brought you on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail. Your goal will be evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation yield while also reducing the total number of letters being sent.
## Model Information
The model used in prediction is **AdaBoostClassifier**

**Performance Metrics scores of the Model are:**
| Accuracy score| F-score |
| --- | --- |
| 0.8651 | 0.7401 |

## Important Features

The most important five features are:
- education-num
- marital-status
- capital-gain
- hours-per-week
- age

![feature importance](https://user-images.githubusercontent.com/54672453/179623493-0fce8608-bb36-4b7f-be43-d2ea303a52bb.png)

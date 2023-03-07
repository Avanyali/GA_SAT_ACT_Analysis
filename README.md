![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

**We hypothesize that high levels of participation in SAT and ACT testing on a per-state basis results in lower average scores on both tests in the state.**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|column name|int/float/object|ACT/SAT|This is an example|
|year|int|ACT/SAT|The year in which the data was taken|
|state|object|ACT/SAT|The State of the United States in which the data was taken|
|participation|float|ACT/SAT|The percentage of ACT/SAT takers out of all students that could have taken the ACT/SAT, per state|
|math_score|int|SAT|The average score per state for students taking the Math portion of the SAT|
|reading_writing_score|int|SAT|The average score per state for students taking the Comprehensive Reading and Writing portion of the SAT|
|total_score|int|SAT|The combined math_score and reading_writing_score per state, used for comparison to acceptance thresholds for universities|
|composite_score|float|ACT|The average final ACT score per state, calculated from the ACT's four section scores|

Through linear regression performed on rates of student participation and final state averages of both the SAT and ACT, we conclude that there is a negative correlation between the two variables. We recommend that states seeking higher average scores for the test of their choosing should restrict access to the test to those that have already prepared for it, and remove mandatory testing policies. Additionally, preparing students for the test overall should be as effective as preparing students for math or reading separately.

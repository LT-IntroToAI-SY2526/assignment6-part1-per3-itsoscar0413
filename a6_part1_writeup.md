# Assignment 6 Part 1 - Writeup

**Name:** _______________  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**
# R^2 tells you how much the change in test scores can be explained with the hours studied in the data. If R^2 is closer to 1, the model worked well and can explain the variation, with 0 being the opposite and making the model barley being able to epxlain anything.
---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**
# MSE is used to show how off your predictions were compared to the actual scores. We square the errors so no matter what we get a positive value, and if it's a huge difference, squaring it will make the inaccuracy more visable. This allows to make sure we have better accuracy and can explicity tell when it's off.
---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**
# No, I would not trust this model to predict this thing because it's outside of my data range, so it would be inaccurate and make assumptions instead of test data. The model COULD work, if it's alligned with the data, but it won't be accurate or account for other factors.
---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**
# It's a positive-linear slope. I'm not sure what strong/weak means, but the dots are close together so probably strong?
---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. # 1) Sleep/stress
2. # 2) Difficulty of the test
3. # 3) Curve/grading scale


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**
# We split our data so we can train the model to learn, so it's able to perform on new data that it's never seen. If it's trained with the same data, it might be "biased" in a sense it only appeals to the current data, and wouldn't be as accurate with new potential data from students.
---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**
# The most difficult part of this assignment was making the code consistent. In one of the functions it had X_train and x_test, but in another function I wrote it as X_train and y_train, making the trains come first. Because they weren't consistent, it caused errors in the code so I had to backtrack. I overcame it with using Ctrl-f to find the code which was wrong, and fix it, as well as debugging it.
---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**
# A real world example I could do is showing the relationship between inflation and prices. Inflation's on X-axis because it's the independent variable, while Prices (y) is affected by X, so prices would be on the y-axis. This relationship might be linear because it's commonly known that as inflation increases, so do prices. This could model not only a linear relationship, but a positive slope too.
---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
#### I would've done this but i need to study for another class, sorry :(

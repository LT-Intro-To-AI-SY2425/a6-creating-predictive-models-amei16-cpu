# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
The model is not accurate at all beccause it makes every predicted purchase a not purchased which is incorrect
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
I would say that the model is more accurate with the StandardScaler than without it but not accurate enough for the given use case because it could still make mistakes.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The pattern would be that it takes 2 numbers that are positive in the predicts which makes the prediction choose purchased instead when it is supposed to be not purchased.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No

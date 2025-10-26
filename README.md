This is a method I've learned from the book : 

Practical Statistics for Data Scientists, 2nd Edition by Peter Gedeck


Randomization Test: Another Way to Determine the Significance of A/B Testing
Steps:
Combine group A and B data, then random darw new groups A and B, then measure the different conversion rate for each.
Repeat the step 1 for multiple times, eg 1000 times resampling, records the conversion rate difference for each time.
Plot the hisgram of 1000 resample tests with the conversion rate different then compare it with the orgianal rate difference

For the coding please check the .ipynb file 

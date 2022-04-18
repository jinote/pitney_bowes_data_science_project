# Pitney Bowes Data Challenge 2021

### Summary
The best model selected is LGBM with an accuracy of 81.09% and F1 score of 51%. Decision Tree is underperforming (accuracy: 79.17%, f1 score: 50.50%) but it is easier to explain than LGBM.

Pitney Bowes should specially keep an eye on the following meter features:

1. Charge Cycle time below 12
2. Discharging/Charging Rate by day 3
3. Discharging/Charging Rate
4. Number days in use
5. Number of times that meter restarts

### Problem Statement
Pintey Bowes must be proactive about identifying potential problems early on to avoid any sort of disruption for their client business.
### Goal
Building the models and predicting which meters will fail within the next 7 days and features caused the failure.

# Business Understanding
### Lean Canvas
![Alt text](https://github.com/jinote/pitney_bowes_data_science_project/blob/main/lean-canvas.png)

**Problem Analysis**
- Be proactive about identifying potential problems to address to develop a solid customer relationship between P&B and their clients.

- **Apart from accuracy, predictive maintenance focus more on precision to decrease False Positive based on the assumption that visiting cost is low.**
- This is a battery life time prediction problem. Our team did some research and found that temperature and voltage are two major factors to battery life. From a business perspective, deployed date and product segmentation which can be inferred from deviceid or so may give us some clues on the prediction.


### Design Thinking
![Alt text](https://github.com/jinote/pitney_bowes_data_science_project/blob/main/design-thinking.jpg)


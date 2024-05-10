# **Steel Plate Defect Prediction**
<img src="https://www.steelsupplylp.com/uploads/general/_1200x630_crop_center-center_82_none/plate.jpg?mtime=1672945202" alt="SteelPlate" width="600" height="315">


## **Overview**
Welcome to the 2024 Kaggle Playground Series! We plan to continue in the spirit of previous playgrounds, providing interesting an approachable datasets for our community to practice their machine learning skills, and anticipate a competition each month.

Your Goal: Predict the probability of various defects on steel plates. Good luck!
<br>
## **Evaluation**
Submissions are evaluated using area under the ROC curve using the predicted probabilities and the ground truth targets.

To calculate the final score, AUC is calculated for each of the 7 defect categories and then averaged. In other words, the score is the average of the individual AUC of each predicted column.
<br>

## **Submission File**
For each id in the test set, you must predict the probability for each of 7 defect categories: Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, Other_Faults. The file should contain a header and have the following format:
<br>

|  id   | Pastry | Z_Scratch | K_Scatch | Stains | Dirtiness | Bumps | Other_Faults |
|------|--------|-----------|-----------|--------|-----------|-------|--------------|
| 19219| 0.5    | 0.5       | 0.5       | 0.5    | 0.5       | 0.5   | 0.5          |
| 19220| 0.5    | 0.5       | 0.5       | 0.5    | 0.5       | 0.5   | 0.5          |
| 19221| 0.5    | 0.5       | 0.5       | 0.5    | 0.5       | 0.5   | 0.5          |

<br>

## **My Grade**
![accuracy](https://github.com/jwyoon0917/kaggle_steel_plate_defect_prediction/assets/48899073/bb576d07-cc32-43ad-a946-69ca0adb332b)

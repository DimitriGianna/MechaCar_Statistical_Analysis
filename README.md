# MechaCar_Statistical_Analysis

## 1. Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/112590378/207770046-318896ea-23f1-4b28-8970-542efee24093.png)


- mpg:  0<0.05  statistically significant, non-random
- vehicle length: 0<0.05, statistically significant, non-random
- vehicle weight: 0.08>0.05, not statistically significant, random
- spoiler angle: 0.31>0.05, not statistically significant, random
- ground clearance: 0<0.05, statistically significant, non-random
- AWD:  0.19>0.05, not statistically significant, random

Vehicale length and ground clearance provided a non-random amount of variance to the mpg values in the dataset.
All of the variables have slopes that are not equal to zero however some are very close to zero.


## 2. Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/112590378/207770128-3d140f68-a43f-4cab-a3d1-0430a3016e70.png)

![image](https://user-images.githubusercontent.com/112590378/207770143-58b1dfde-743f-4548-93b0-54fa16cecc9e.png)



The variance for all of the lots does not exceed 100 (62<100). However, When the lots are examined individually, Lot 1 and Lot 2 are well within specification while Lot 3 far exceeds it (170>100).

## 3. T-Test on Suspension Coils

### T-Test for all Lots

![image](https://user-images.githubusercontent.com/112590378/207770167-85de861d-4c29-49db-8757-d2f39ef94f7f.png)

### T-Test for Individual Lots

![image](https://user-images.githubusercontent.com/112590378/207770224-0fd775f3-0a04-4074-b957-b920433b4c7d.png)



## 4. Study Design: MechaCar vs Competition

- What metrics to test: Maintenance cost
- Hypotheses: H~0~ The average maintenance cost is similar to that of the competitor's vehicles; H~a~ MechaCar vehicles' average maintenance costs are statistically higher or lower than that of the competitor's vehicles.
- Statisical test: Two-sample t-test because it is appropriate for determining wether two population means are equal.
- Data required: The average yearly maintenance costs of both MechaCar's and the competitor's vehicles of similar type.

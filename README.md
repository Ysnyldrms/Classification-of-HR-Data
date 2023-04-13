# Classification-of-HR-Data
Prediction of "Attrition" situation for HR Data

### DataFrame 

![image](https://user-images.githubusercontent.com/111190076/231758730-3a4af0f5-a934-4fe0-b6d9-93ae4674e4a7.png), ![image](https://user-images.githubusercontent.com/111190076/231758908-d9cf4b47-987a-4215-9958-3651e5f20c69.png)

We are going to predict "Attrition" column. 

### Exploratory Data Analysis

Let's look Heatmap 

![image](https://user-images.githubusercontent.com/111190076/231768574-95c99e5b-aef1-472f-b7a2-cf2ad8ebdec9.png)


If correlation between two column is bigger than %90, this means this columns has repated values. When we look at the data we can see some of them comlpetely same.

Correlation Heatmap after deleting repeated columns

![image](https://user-images.githubusercontent.com/111190076/231767432-d53b8a6e-26f7-47bf-a363-ab71e23cece6.png)


### Results 

Result of Gradient Boosting Classifier : 

![image](https://user-images.githubusercontent.com/111190076/231759871-664ef3d1-278d-4fb6-bb6e-00107ec61328.png)

I created an imaginary employee and predicted.

![image](https://user-images.githubusercontent.com/111190076/231760594-a2507cfa-9451-4bc7-9f7c-35ff2191f81b.png)

The answer is YES, we can say that this employee can quit the job.

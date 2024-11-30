<h1 style="color:green; font-family:Arial; text-align:center;">Diabetes Age Analysis: Statistical Hypothesis Test</h1>
<h2 style="color:blue; font-family:Arial; text-align:left;">Introduction:</h2>
<p>
This study aims to examine whether there is a difference in the average age of individuals with and without diabetes. My hypothesis is defined as: "There is no difference in the average age of individuals with and without diabetes." The "Outcome" variable, which indicates whether an individual has diabetes, will be used to analyze the age data and compare the average ages.
</p>

<h2 style="color:blue; font-family:Arial; text-align:left;">Development: 🩺📊</h2>
<p>
Dataset and EDA (Exploratory Data Analysis):
First, the key variables in the dataset (number of pregnancies, glucose, blood pressure, skin thickness, insulin, body mass index (BMI), diabetes pedigree function, and age) were reviewed. Each of these variables provides potentially significant information about diabetes. Additionally, the "Outcome" variable (diabetes status) was analyzed.
</p>

</p>
During data analysis, the assumption of normality for age data was tested. This step helps determine which statistical test is appropriate. If the data follows a normal distribution, parametric tests (e.g., t-test) can be used. Otherwise, non-parametric tests (e.g., Mann-Whitney U test) are preferred.
</p>

<img src="https://github.com/akay35/image/blob/main/1.png" alt="This is my world" width="600" height="600"/>   

<img src="https://github.com/akay35/image/blob/main/2%20Korelasyon%20analizi.png" alt="This is my world" width="730" height="360"/>   

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;">
<h2 style="color:blue; font-family:Arial; text-align:left;">Shapiro-Wilk Test (Normality Test): 🤔</h2>
<p>
The Shapiro-Wilk test is a non-parametric test used to determine whether the data follows a normal distribution. The null hypothesis (H0) of this test states that the data is normally distributed.

If the p-value obtained from the Shapiro-Wilk test is less than 0.05, it indicates that the data significantly deviates from a normal distribution, and parametric tests cannot be applied. In such cases, non-parametric tests are used.
<img src="https://github.com/akay35/image/blob/main/3%20shapiro.png" alt="This is my world" width="2100" height="260"/>   

<h2 style="color:blue; font-family:Arial; text-align:left;">Results of Shapiro-Wilk Test and Mann-Whitney U Test: 🧐</h2>
<p>
If the p-value in the Shapiro-Wilk test is less than 0.05 (e.g., in this case, 0.0000), this indicates that the data does not follow a normal distribution. As a result, non-parametric tests, such as the Mann-Whitney U Test, are applied.
</p>
The Mann-Whitney U Test examines whether the medians of two independent groups differ. This test is appropriate for non-parametric data when the normality assumption is not met.
<img src="https://github.com/akay35/image/blob/main/4%20mannwhitneyu.png" alt="This is my world" width="2100" height="260"/>   

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;">
<h2 style="color:purple; font-family:Arial; text-align:left;">Evaluation of Results: 🚀</h2>
Shapiro-Wilk Test Results: If the p-value is less than 0.05 (e.g., 0.0000 in this case), it indicates that the data does not follow a normal distribution. Thus, parametric tests (like the t-test) cannot be applied. Instead, non-parametric tests such as the Mann-Whitney U Test should be used.
Mann-Whitney U Test Results: If the p-value obtained from the Mann-Whitney U Test is less than 0.05 (e.g., 0.0000 in this case), this indicates that there is a statistically significant difference in the average age between the two groups (individuals with and without diabetes).

<h2 style="color:purple; font-family:Arial; text-align:left;">Actions: 🔧</h2>
<p>
Shapiro-Wilk Test: If the p-value had been greater than 0.05 (e.g., p = 0.08), the data would be considered normally distributed, and a parametric test such as the t-test would be applied. This test examines whether the means of two groups are significantly different.
Mann-Whitney U Test Results (p-value < 0.05): If the p-value is less than 0.05, we reject the null hypothesis (H0) and conclude that there is a significant difference in the average age of individuals with and without diabetes.
</p>
  
<h2 style="color:purple; font-family:Arial; text-align:left;">Conclusion: 🎯</h2>
<p>
In this analysis, the Shapiro-Wilk test was conducted to test the normality assumption, and it was concluded that the data does not follow a normal distribution. Therefore, the Mann-Whitney U Test, a non-parametric test, was applied. The results showed that the p-value is less than 0.05, indicating a significant difference in the average age between individuals with and without diabetes. These findings lead us to reject the null hypothesis (H0) and accept the alternative hypothesis (H1).
</p>

<h2 style="color:purple; font-family:Arial; text-align:left;">Summary: 📊</h2>
<ul>
<li>The Shapiro-Wilk Test checks whether the data follows a normal distribution. If the p-value is less than 0.05, non-parametric tests are applied.</li>
<li>The Mann-Whitney U Test evaluates the difference in medians between two groups. If the p-value is less than 0.05, it indicates a significant difference between the groups.</li>
</ul>

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;">

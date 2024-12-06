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

<img src="https://github.com/akay35/image/blob/main/ab%202.jpeg" alt="This is my world" width="950" height="950"/>  
<p style="text-align:center; font-style:italic; font-size:14px;">
This graphic was kindly provided by <a href="https://github.com/pelinsayar" target="_blank">Pelin Sayar</a> Special thanks for the design and contribution. 🌺
</p>

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;">


<h1 style="color:green; font-family:Arial; text-align:center;">Diyabet Yaş Analizi: İstatistiksel Hipotez Testi</h1>

<h2 style="color:blue; font-family:Arial; text-align:left;">Giriş:</h2>
<p>
Bu çalışma, diyabet hastası olan ve olmayan bireylerin yaş ortalamaları arasında bir fark olup olmadığını incelemeyi amaçlamaktadır. Hipotez: "Diyabet hastası olan ve olmayan bireylerin yaş ortalamaları arasında bir fark yoktur." şeklinde tanımlanmıştır. "Outcome" değişkeni, bir bireyin diyabet durumu hakkında bilgi verdiği için, yaş verisini analiz etmek ve yaş ortalamalarını karşılaştırmak için kullanılacaktır.
</p>

<h2 style="color:blue; font-family:Arial; text-align:left;">Gelişme: 🩺📊</h2>
<p>
Veri Seti ve Keşifsel Veri Analizi (EDA):  
Öncelikle, veri setindeki temel değişkenler (gebelik sayısı, glikoz, kan basıncı, deri kalınlığı, insülin, vücut kitle indeksi (BMI), diyabet aile geçmişi ve yaş) gözden geçirilmiştir. Her bir değişken, diyabetle ilgili potansiyel olarak anlamlı bilgiler sunmaktadır. Ayrıca, "Outcome" değişkeni (diyabet durumu) analiz edilmiştir.
</p>

<p>
Veri analizi sırasında, yaş verisi için normallik varsayımı test edilmiştir. Bu adım, hangi istatistiksel testin uygun olduğunu belirlemeye yardımcı olur. Eğer veri normal dağılıma uyuyorsa, parametrik testler (örneğin, t-test) kullanılabilir. Aksi takdirde, non-parametrik testler (örneğin, Mann-Whitney U testi) tercih edilir.
</p>

<img src="https://github.com/akay35/image/blob/main/1.png" alt="This is my world" width="600" height="600"/>  

<img src="https://github.com/akay35/image/blob/main/2%20Korelasyon%20analizi.png" alt="This is my world" width="730" height="360"/>  

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;"> 

<h2 style="color:blue; font-family:Arial; text-align:left;">Shapiro-Wilk Testi (Normallik Testi): 🤔</h2>
<p>
Shapiro-Wilk testi, verilerin normal dağılıma uyup uymadığını test etmek için kullanılan parametrik olmayan (non-parametrik) bir testtir. Bu test, özellikle küçük örneklemlerle normal dağılımın varlığını kontrol etmek için yaygın olarak kullanılır. Shapiro-Wilk testinin null hipotezi (H0), verilerin normal dağıldığı yönündedir.

Bu testin amacı, verilerin belirli bir normal dağılım modeline uygun olup olmadığını belirlemektir. Yani, eğer p-değeri 0.05'ten küçük çıkarsa, bu, verilerin normal dağılımdan önemli ölçüde sapmış olduğunu gösterir ve parametrik testlerin (örneğin, t-test) uygulanamayacağını ifade eder. Bu durumda non-parametrik testler (örneğin, Mann-Whitney U testi) tercih edilmelidir.

Shapiro-Wilk testinin temel işleyişi:

H0 hipotezi: Veriler normal dağılıyor.
H1 hipotezi: Veriler normal dağıtmıyor.
</p>
<img src="https://github.com/akay35/image/blob/main/3%20shapiro.png" alt="This is my world" width="2100" height="260"/>  

<h2 style="color:blue; font-family:Arial; text-align:left;">Shapiro-Wilk Testi ve Mann-Whitney U Testi Sonuçları: 🧐</h2>
<p>
Shapiro-Wilk testindeki p-değeri 0.05'ten küçük çıktığından dolayı, bu durum verinin normal dağılıma uymadığını gösterir. Normal dağılım varsayımının sağlanmadığı durumlarda parametrik testler (örneğin, t-test) kullanılamaz. Bu nedenle, Mann-Whitney U Testi gibi non-parametrik testler uygulanır.

Mann-Whitney U Testi, iki bağımsız grubun medyanlarının farklı olup olmadığını inceleyen bir testtir. Parametrik olmayan veriler için kullanılan bu test, özellikle normal dağılım varsayımının sağlanmadığı durumlarda uygun bir testtir. Bu test, verilerin sıralı veya ranks veriler olduğu durumlarda, gruplar arasındaki farkı test eder.
</p>
<img src="https://github.com/akay35/image/blob/main/4%20mannwhitneyu.png" alt="This is my world" width="2100" height="260"/>  

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;"> 

<h2 style="color:purple; font-family:Arial; text-align:left;">Sonuçların Değerlendirilmesi: 🚀</h2>
<p>
Shapiro-Wilk Testi Sonuçları:
Shapiro-Wilk testinde elde edilen p-değeri 0.05'ten küçük çıktığından dolayı, bu verinin normal dağılımdan sapmış olduğunu gösterir. Bu durumda, parametrik testler (örneğin, t-test) uygulanamaz, çünkü parametrik testler normal dağılım varsayımına dayanır. Bunun yerine, Mann-Whitney U Testi gibi non-parametrik testler kullanılmalıdır.

- Shapiro-Wilk testi, verilerin normal dağılıp dağılmadığını test eder. Eğer veriniz normal dağılım göstermiyorsa, tıp literatüründe genellikle Mann-Whitney U testi gibi non-parametrik testler kullanılır. Bu, özellikle biyomedikal ve tıbbi araştırmalarda yaygın bir uygulamadır, çünkü bu tür veriler genellikle normal dağılımı sağlamaz ve sıralı veri veya medyan analizine dayanarak sonuçlar elde edilir.
</p>
<p>
Mann-Whitney U Testi Sonuçları: Mann-Whitney U Testi sonucunda p-değeri 0.05'ten küçük çıktığından dolayı, bu durum diyabet hastası olan ve olmayan bireylerin yaş ortalamaları arasında istatistiksel olarak anlamlı bir fark olduğunu gösterir.

- Mann-Whitney U Testi, iki bağımsız grubun medyan değerlerini karşılaştırarak, bu gruplar arasında istatistiksel olarak anlamlı bir fark olup olmadığını test eder. Bu test, özellikle biyolojik ve klinik çalışmalarda, normal dağılıma uymayan veriler için yaygın olarak kullanılır. Bu testin sonuçları, belirli bir hasta grubunun yaş özelliklerinin diğerlerine kıyasla belirgin bir şekilde farklı olup olmadığını anlamamıza yardımcı olabilir.
</p>

<h2 style="color:purple; font-family:Arial; text-align:left;">Sonuç: 🎯</h2>
<p>
Bu çalışma, diyabetin yaş üzerindeki etkilerini araştırırken, verilerin normal dağılıp dağılmadığını test ederek, Mann-Whitney U Testi gibi non-parametrik testlere başvurmuştur. Bu testler, özellikle normal dağılım varsayımının sağlanmadığı durumlarda oldukça etkili bir şekilde gruplar arasındaki farkları tespit etmek için kullanılır.

Elde edilen bulgular, diyabet hastası olan bireylerin yaş ortalamalarının diğer gruptan istatistiksel olarak farklı olduğunu gösteriyorsa, bu durum diyabetin yaşa etkisini daha derinlemesine araştırmayı gerektirir. Bu, tıp literatürüne önemli katkılar sağlayabilir, çünkü diyabetin yaş üzerindeki etkileri ve tedaviye verdiği yanıtlar üzerine daha fazla araştırma yapılmasını teşvik edebilir.
</p>

<img src="https://github.com/akay35/image/blob/main/ab%202.jpeg" alt="This is my world" width="950" height="950"/>  
<p style="text-align:center; font-style:italic; font-size:14px;">
Bu grafik, <a href="https://github.com/pelinsayar" target="_blank">Pelin Sayar</a> tarafından sağlanmıştır. Tasarım ve katkılar için teşekkür ederim. 🌺
</p>

<hr style="border: 1px solid rgba(0,0,0,0.1); width: 50%;">


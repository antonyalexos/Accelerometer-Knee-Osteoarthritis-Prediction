This is the implementation of the paper "Physical activity as a risk factor in the progression of Osteoarthritis: A machine learning perspective". The paper was published in the [LION14](http://www.caopt.com/LION14/). You can find the paper here.


The accelerometer data were from The Osteoarthritis Initiative(OAI), which you can find [here](https://nda.nih.gov/oai/). Because the data that we use are for day accelerometer activity, the files have a small size, so we have included them in this repository.

<h3>Overview of the files</h3>
<ul>
  <li><b>put_data_together.ipynb:</b> In this file we put the accelerometer data together with the list of features.</li>
  <li><b>accel_day_pred.ipynb:</b> This is the file with the main code and the prediction of our data.</li>
  <li><b>KL.xlsx:</b> Excel file with the KL target feature from the big data. In this data file the KL feature is the prediction of Knee Osteoarthritis progression.</li>
  <li><b>AccelDataByDay06.txt</b> Excel file with he accelerometer data from KOA.
</ul>

<h3>Abstract</h3>
Knee osteoarthritis (KOA) comes with a variety of symptoms' intensity, frequency and pattern. Most of the current methods in KOA diagnosis are very expensive commonly measuring changes in joint morphology and function. So, it is very important to diagnose KOA early, which can be achieved with early identification of significant risk factors in clinical data. Our objective in this paper is to investigate the predictive capacity of physical activity measures as risk factors in the progression of KOA. In order to achieve this, a machine learning approach is proposed here for KOA prediction using features extracted from an accelerometer bracelet. Various ML models were explored for their suitability in implementing the learning task on different combinations of feature subsets. Results up to 77% were achieved indicating that physical activity measured by accelerometers may constitute an important risk factor for KOA progression prediction especially if it is combined with complementary data sources.
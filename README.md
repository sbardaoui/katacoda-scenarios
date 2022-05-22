## This report for the noSQL lab in which we use Spark SQL to query data from a "stocks" dataset

This readme file will contain installation procedure for scala


##Installation prcoedures

Since we are on windows platform the installation procedures are as follow : 

Spark download :
https://spark.apache.org/downloads.html

![image](https://user-images.githubusercontent.com/59623846/169703467-55f28fe3-1c9d-483f-ab77-c1f150a9f24e.png)

Adding winutils file : 
https://github.com/cdarlint/winutils

**pick the appropriate hadoop file**

Extract the downloaded spark file 

![image](https://user-images.githubusercontent.com/59623846/169703625-242f65f4-2ad4-4e4c-8631-3660dfccb022.png)

Next create a **Hadoop** folder in it create a second folder named **bin** and insert **winutils.exe** inside
![image](https://user-images.githubusercontent.com/59623846/169703731-c576077b-a221-4afa-9547-36f39d5cd351.png)

**next step is setting up environment variables**
![image](https://user-images.githubusercontent.com/59623846/169703772-3ffac7ae-1708-4858-830c-965929232aef.png)

<ul>
  <li> from start menu type environment and enter the environment variables settings </li>
  <li> click on new </li>
  <li> Enter in Variable name <b>HADOOP_HOME</b> and make sure you put the correct path to the <b> hadoop folder </b> </li>
  <li> repeat the <b> above step </b> only this time variable name should be <b> SPARK_HOME </b> and path should be the extracted spark folder </li>
  <li> <img src="https://user-images.githubusercontent.com/59623846/169703916-7926e5c9-b0c9-4944-9658-ebb8d2b76a87.png"> </li>
  <li> next click on PATH and click EDIT </li>
  <li> <img src="https://user-images.githubusercontent.com/59623846/169703955-b0956ccf-9e75-4597-9cbf-fb51c959527d.png"> </li>
  <li> click on <b> new </b> and type in <b> %HADOOP_HOME%\bin </b> and <b> %SPARK_HOME%\bin </b> </li>
  
</ul>
  
**finally start cmd and type in spark-shell and you will have the promp ready if you set up the variables above correctly**
![image](https://user-images.githubusercontent.com/59623846/169704129-c7861c40-e534-487e-b63d-7f956005b52b.png)




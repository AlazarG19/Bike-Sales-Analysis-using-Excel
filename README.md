# <a name="_s2kfy7lm9em"></a>Bike Sales Analysis using Excel
This project aims to conduct a comprehensive analysis on the bike sales data collected from a Bike store. The analysis is done mainly to identify which factors contribute mainly to the purchase of bikes.
## <a name="_2gphqd17md2a"></a>Objectives
### <a name="_27iwc9mxjgtx"></a>Data Cleaning
Cleaning the dataset to address any duplicates, missing and inconsistent data
### <a name="_iqzi0kwf1bic"></a>Data Preparation 
Making the Dataset Consistent for columns with inconsistent data. In addition to making the result more reliable we check for any outliers and aggreate some column values to include range values instead of individual values
### <a name="_hahya3ame4ij"></a>Creating Pivot Tables and Charts
Creating Pivot Tables in order to analyse each attributes individually to the overall result.
### <a name="_g2a415f1i7j4"></a>Creation of Dynamic Dashboards
Finally to bring it all together we collect all charts created from the pivot tables.Creating a slicer during this stage helps us identify the effect of an attribute to the various charts that is depicted.
## <a name="_883ke7g0yf8x"></a>Dataset
### <a name="_kc4p770t5yr"></a>Id
A unique Identifier for each customer
### <a name="_lttsyxkwhxym"></a>Martial Status
Attribute used to Identifying whether our customer is married or not
### <a name="_e8sdd6yghxz4"></a>Gender 
Attribute used to Identifying gender status
### <a name="_35hftb6t19m2"></a>Income
Attribute used to Identify income of the customer
### <a name="_rgc80rh58bat"></a>Children
Attribute used to identify amount of children a customer has
### <a name="_jrpzhzkv22qf"></a>Education
Attribute used to identify education status of customer
### <a name="_xspnhoi0qrbm"></a>Occupation
Attribute used to identify what job title the customer is holding
### <a name="_jpn7zvvniaxs"></a>Home Owner

Attribute used to identify whether or not customer owns a home 
### <a name="_v4nb654eefcg"></a>Cars
Attribute used to check amount of cars the customer has
### <a name="_dithsp9m9fyh"></a>Commute 
Attribute used to check the distance between the home and place of work of the customer
### <a name="_q44867xtpkxl"></a>Region
Attribute used to check the area/region where the customer is located
### <a name="_yuei5vsmmghh"></a>Age
Attritube used to determine age of customer
### <a name="_2s71lykymw00"></a>Purchased Bike
Attribute used to determine whether or not a customer has purchased a bike
## <a name="_8ytggkxqv3yg"></a>Tools
We’ll be using excel in order to explore our data and prepare the different pivot tables and charts we are going to use for the project.





## <a name="_h403hzmsxqb0"></a>Approach
### <a name="_t9y8edn50cqj"></a>Data Import and Initial Exploration
In data analysis, the initial step of importing a dataset and exploring its initial content is akin to opening a door to valuable insights.Down below is the table we’ll be analyzing

![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.001.png)
### <a name="_8zq312bfp265"></a>Identifying and Removing Duplicate Data
Now, we want to see if there are any duplicates in our data, which is mostly undesirable. To check duplicates- Select the table> go to data> select remove duplicates> select all columns> press ok. Our data had 26 duplicate values for some reason. 
### <a name="_qtqp5fe5c3so"></a>Identifying and Handling Missing Data
Here, we’re examining our dataset for missing values. Luckily our dataset doesn’t contain any null values.
### <a name="_wr9uu45fp7h"></a>Data Preparation and Column Transformation
In this step, we are preparing the dataset for analysis. We remove unnecessary columns and rename some columns to improve clarity and consistency.In this step, we are preparing the dataset for analysis. We remove unnecessary columns and rename some columns to improve clarity and consistency.This can be done simply by going to Home>Find and Select> Find and Replace.
### <a name="_ry4tb841c3h8"></a>Check for any outliers
In order to have a more predictable and more insightful result we will check if there are any outliers.We will use charts to see what’s happening with the data since they give an easy to understand picture of our data. For this analysis let’s use a boxplot for the Income column.![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.002.png)

.

As can be seen, there isn't much to worry about. Everything just seems fine.
## <a name="_jp05bo91jbee"></a>Trend Analysis
### <a name="_8k50o8r317tn"></a>Checking if there is any age group that dominates in the data.
Let’s analyze the age column to check which age group dominates in the data. We are using a histogram to see the trend, which looks like this:

![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.003.png)

As can be seen, there are more people in the age group 30–50, but it doesn't give much clear picture so We will have to add a column “age category” beside the age column so that every age falls into an age group using the following formula: =IF(L3>55,”Old”,IF(L3>31,”Middle Age”,IF(L3<=31,”Adolescent”,”Invalid”)))

Now, the data seems good to go.

### <a name="_74qj4airdz32"></a>Preparing the needed tables and charts
Now, let’s create some pivot tables to see what factors influence the sales of the bikes.

1. #### <a name="_y73uyuwwhsdo"></a>Avg Income of Females and Males who purchased and did not purchase bikes:
   ![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.004.png)

The chart explains it better

![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.005.png)
1. #### <a name="_jwgicxs5tkbo"></a>Bike purchased per age group:
The following Line Chart speaks for itself

![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.006.png)
1. #### <a name="_l296goo8sx85"></a>Commute Distance vs Bike purchased:
   ![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.007.png)

![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.008.png)

1. Preparing a Dynamic Dashboards

The crux of a data analysis project is to create visually appealing, easy to understand, dynamic and interactive dashboards.

To make dashboards more interactive and dynamic we will add slicers to filter results as per our needs.

We can add slicer from whoever column we wish, for the sake of this project I have included three, on Region, Cars and Occupation.

The final dashboard looks like this:

![](Aspose.Words.c2416a2e-c6a2-4495-a4cb-ff26cea33f78.009.png)

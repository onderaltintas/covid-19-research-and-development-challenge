# covid-19-research-and-development-challange
There is a COVID-19 pandemic situation. When will it end? How much people will be affected? What will be the peak points of spread? A challange of data science&amp;software development  to create predictions from historical data and visualize it.

# Introduction:

There is a COVID-19 pandemic situation. When will it end? How much people will be affected? What will be the peak points of spread? Data science & Software development might help to predict and GIS might help to visualize. A software can be developed to process data resources of countries (gdp, location, covid 19 time series data, money that was spent on medicines etc.) to make these estimations and visualize them with only using opensource technologies and open data.

# Scope&Rules:

1- Permissive opensource licensed libraries, frameworks etc. can/will be used.  
2- Application source will be open.  
3- Development will be done under source control, public, transparent to everyone. License can be either permissive or restrictive.  
4- Data will be used from open data sources (gdp, covid19 time seried&countries & geographical data etc.)  
5- Any programming language can be used.  
6- Application can be either web based or desktop or something but in the end application should be available to use publically.  
7- If the application is web based, it should be placed in a server for public usage. If it is a desktop or something, introductions to use and compiled (executable) code should be provided.  
8- All the resources that was used to create the application should be referred as well (write txt file, put links etc) under a "research" directory. Documents created for the project also will be in "research" directory.  
9- All the development will be under "development" directory.  
10- No cheating&stealing.  
11- For using any code&data&document etc from here, you should get permission from respective owner. In this case, this is "me (Önder ALTINTAŞ)" who is creating this project. If you are hosting another project that is using same challange template, this will be "you (put your name here)". In any case if the project is being done by more than 1 person, this will be "you(put your names here comma seperated)" in plural sense.  
12- You can work with team, you can do everything by yourself, you can give money to someone and make him/her do for you.  
13- Challange time starts with first push on source control. This is 24 hour challange but if noone can do it under 24 hours than the challange becomes 48 hour challange. Each day if challange is not completed, it becomes 24 + (daysPassed*24) hour challange.  
14- Important criterias: Fast release, Informative, Useable, Precise  
15- All of the goals&use cases should be completed to finish the challange.  
16- You don't have to use a world map. If you can achieve the goals&use cases of the project without using map, it is also okay. In that case, you change the "map" word with the visualization technique that you used.  
17- All the predictions&estimations should be done by using real data. It is not allowed to use personal&non data driven predictions and estimations. Predictions&models that was used and how was used should be explained in a document. Data sources should be referred or cited.  
18- No false, made up, fitting, lie data resource is allowed.  
19- Names&sentences can be changed with the ones that have exactly same meaning. For example: "First patient at" => "The first date which first patient apeared".  
20- Difference between historical data and what is predicted data should be clear. The understanding of what is "real" and what is "prediction" is important. Any kind of UI/UX or visualisation techniques must be used to achieve this distinction.  
21- The data used to create predictions have to be mentioned in the application and shown to user. For example: If you use gdp, location, time, currency to predict last patient date, then "gdp, location,time, currency was used" like sign should be visible to user.
22- As long as rules applied, any additions are welcome.

# Goal&Use cases:
You should research the data, tools and/or information to create an application that can make and visualize COVID-19 disease predictions. Application should have the following stories:

## Story - 1
**Name:** Colorization (Choropleth)  
**Explanation:**  
As a user, I want to see all countries visualized on a map with colors respective to covid-19 data and predictions. I will be able to choose "confirmed" as confirmed patients, "recovered" as recovered patients and "death" for death patients.  
**For example:** If a "x" country has more recovered patients than the "y" country, x country should have darker color than y country (see: google choropleth). Confirmed, recovered, death should have different colors. Countries can either be visualized by their borders or their locations as points. 

## Story - 2
**Name:** Timeline  
**Explanation:**  
As a user, I want to see the change of confirmed/recovered/death values with using timeline slider(list&combobox or whatever you use to show dates) by sliding from historical data to end of the disease predicted data.  
The timeline slider will have date values. The first date value should be the first COVID-19 obtained data date and the last date value should have the date of 1 day after the last country/last patient/last death/last recovered occurs from the prediction.  
**For example:** First confirmed patient date is 1/22/20 from CSSEGISandData/COVID-19 data resource. Slider should start from 1/22/20. Let's say, our prediction engine determined last confirmed patient in the world will occur at 4/22/2020 in x country then the slider should end at 4/23/2020.

## Story - 3 
**Name:** Country Predictions  
**Explanation:**  
As a user, I want to see the COVID-19 historical and estimated data of country that I select the country. Historical data should be marked as historical and predicted data should be marked as predicted. This can be done with colors or text or other UI/UX things.  
The country data should have the following information:  
  1- First patient confirmed at(historical): The first date when first confirmed patient appeared.  
  2- First recovery at(historical): The first date when first recovery happened.  
  3- First death at(historical): The first date when first death happened.  
  4- Last patient at(prediction): The last predicted patient will appear in the country.  
  5- Last recovery at(prediction): The last recovery will occur in the country.  
  6- Last death at(prediction): The last death will occur in the country.  
  

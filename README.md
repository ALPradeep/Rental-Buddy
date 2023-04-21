## SECTION 1 : PROJECT TITLE

## **RENTAL BUDDY**

![Image text](/resources/Project_Image.png)

------

## SECTION 2 : EXECUTIVE SUMMARY

Singapore is a popular destination for foreigners and expatriates who come here for work and study. However, searching for rental house can be difficult if you have minimal knowledge about the place. As such, we developed Rental Buddy, a one-stop platform that assists tenants-to-be in finding their rental place whether they’re new to Singapore or have already been here for years. Rental Buddy starts by collecting basic user preferences such as budget, comfortable travel time, frequent destination(s), and the choice of renting a room or a house, all through a form in the user interface. From there, a task bot will search for the nearest MRT station to the frequent destination(s) and shortlist the best location using a knowledge base to begin house-search given the user’s preferences. From there, the task bot scrapes through Property Guru and finally returns a list of ten best properties to the user, each with links that lead them to the sites. All these are done in real time so the user can rest assure that the house is still available at the time of the search. 

we developed Rental Buddy for our project, a one-stop platform that aims to provide helpful advice and recommendations for those seeking long-term accommodation in Singapore, whether they’re new to Singapore or have already been here for years. The project assumes that the user has no prior knowledge of Singapore and has not done any research on locations, which can save time and reduce stress for those embarking on their housing search. By providing insights on housing information in Singapore, this project hopes to kick-start the house-search process and potentially bypass the costs of engaging housing agents..

This report will introduce and analyse the project through 6 sections, which are the Business Problem Background, the Market Research, the Problem Description, the Project Solution, the Project Implementation and the Project Performance & Validation to present the project concept and project results.

------

## SECTION 3 : CREDITS

| Official Full Name      | Student ID (MTech Applicable) | Email (Optional)   |
| ----------------------  | ----------------------------- | ------------------ |
| Pradeep Kumar Arumugam  | A0261606J                     | e0983000@u.nus.edu |
| Jonathan Lim Ching Loong| A0261707E                     | e0983101@u.nus.edu |


------

## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

## Marketing Video

[![RENTAL BUDDY business vedio](/resources/RENTAL%20BUDDY.png)](/Demo%20Videos/Submission%20Video%201.mp4 "Business vedio")

## Technical Video

[![RENTAL BUDDY System Architecture](/resources/bg3.png)](/Demo%20Videos/Submission%20Video%202.mp4 "System Architecture")

------

## SECTION 5 : USER GUIDE

[UserGuide](/User%20Guide/Rental%20Buddy%20User%20Guide.pdf)

### [ 1 ] To run the webapp in local machine

>  (Notes: Preferred Python 3.7 or above)

> Open up your command prompt/terminal

> Do git clone this repository or go to git url mentioned above to directly download the project, unzip and keep it in your folder directory.

> pip install the components from requirements.txt

> cd <your folder path>\RentalBuddy

> Run the server.py with python
>
> - py server.py
> - py3 server.py (if you have different versions of python)

> Once it’s done, you’ll see this line in your command prompt “Running on http://192.168.10.106:8080/ (Press CTRL+C to quit)” wither copy paste this url or directly go to any of your web browser and type http://localhost:8080/ and you’ll be able to access our webapp



### [ 2 ] To run the webapp in VM

> Open up your terminal

> git clone <web url to this repository>

> pip install the components from RentalBuddy\requirements.txt

> cd <your folder path>\RentalBuddy	

> Run the server.py with python
>
> - $python server.py
>
> - $python3 server.py (if you have different versions of python)

> Go to URL using web browser http://localhost:8080/ or http://192.168.10.106:8080/



### [ 3 ] Additional comments

You might encounter issues with libraries like TagUI/Falsk. During such instances, please ensure to install those libraries in the environment where your python path variable is configured. This is common compatibility issue if you have multiple setups in different environments depending on the setup of your system. A simple solution might be to uninstall and reinstall those libraries.


Datasource we used:

​[Property Guru](https://www.propertyguru.com.sg/)

​[99 CO](https://www.99.co/)

[Fair Rates](https://mrt.sg/faret/)

[GMap](https://www.google.com/maps)

[SG Map](https://yoursingaporemap.com/)

[One Map](https://www.onemap.gov.sg/main/v2/)

[FaceBook](https://www.facebook.com/)

[Nestia](https://www.nestia.com/)

[Street Directory](https://www.streetdirectory.com/)

[GoThere](https://gothere.sg/maps)

------

## SECTION 6 : PROJECT REPORT / PAPER

[ProjectReport](/Report/Project%20Report.pdf)

------

## SECTION 7 : MISCELLANEOUS



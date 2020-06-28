# Covid 19 tracker app
The goal of this project is to provide a simple,interactive way to visualize the impact of covid-19,by providing a tracker to detect the number of patients being victimized all over the world.
This type of information will be useful for those on the front lines -including health care professionals,researchers, and government experts.
The project provides a quick and easy access to real-time critical data of several countries with their covid-19 case history.
The server Api we are using here is the covid -19 data from US john hopkins University.
Contents:
S.No	 Page	Body
1.	Welcome page	Welcomes the user.
2.	Login page	User can login using the username and password.
3.	Home page 	Provides information about corona virus by navigating between pages.
  Pages:
	Overview
	Statistics
	Symptoms
	precautions
4.	Select country	•	An Counter is to be run globally to show the total number of cases all over the world .
•	A list of countries are displayed in which the user can select the required country for knowing about it’s track.
5.	Country-wise page	On selecting the country,detailed case history of the country is generated.It includes
	Country
	Active cases
	Total Deaths
	Recovered cases
UI components:
![image](https://user-images.githubusercontent.com/65466888/85950348-d3928e00-b979-11ea-9892-abda8be45786.png)
![image](https://user-images.githubusercontent.com/65466888/85950374-fa50c480-b979-11ea-975c-2e7c8627b249.png)
![image](https://user-images.githubusercontent.com/65466888/85950380-03da2c80-b97a-11ea-8afd-a4984bb126fb.png)
![image](https://user-images.githubusercontent.com/65466888/85950382-076db380-b97a-11ea-9fed-695d6d85a8c6.png)
![image](https://user-images.githubusercontent.com/65466888/85950386-0c326780-b97a-11ea-9c63-f0567cdf3228.png)
![image](https://user-images.githubusercontent.com/65466888/85950391-10f71b80-b97a-11ea-99e1-b509e8e2dc50.png)
![image](https://user-images.githubusercontent.com/65466888/85950398-16546600-b97a-11ea-8937-4841ce0952f2.png)
![image](https://user-images.githubusercontent.com/65466888/85950402-194f5680-b97a-11ea-9d32-b5477ed3fe41.png)
![image](https://user-images.githubusercontent.com/65466888/85950406-1d7b7400-b97a-11ea-8877-8d8f6d02be6a.png)
![image](https://user-images.githubusercontent.com/65466888/85950409-20766480-b97a-11ea-9038-a58508078003.png)

Screen Flow:
 login ----------------------> master page(Country list) --------> detail page(country specific list)
        (on clicking login button )                             (On selecting country)
           
PAGE 0:
 Front end-page: welcome Page

PAGE 1:
Front end-page:Login Page
->Asks for username and password
Server: A list of username and Passwords are stored.
PAGE 2:
Front end-page: Home Page
->provides information about corona virus by navigating between pages
PAGE 3:
Front end - Page : Country select page
 - > displays all countries from server
Server :  REST APi - gets country list from server
PAGE 4:
Front end - Page :  On clicking on the covid-19 country page, it should display the details of Covid patients for the selected country
Server :
REST APi - call John hopkins University Rest APi.


Github repository link: https://github.com/ameena-shaheen/covid.git

INFERENCE FROM THE INTERNSHIP:
 	Got a brief idea about app development.
 	 Learnt how to use HTML and CSS styling for developing an attractive UI.
 	Got a clear cut idea on ionic ,angular and node-js framework.
 	Learnt how to call rest-api  on the server side by using json on typescript.
 	Got a few information on integrating firebase and mongo database.
 	Learnt how to create a repository and circulate files between the team and the lead.
 	Ultimately learnt how to work as a team and develop a complete project, within the given time framework.
 	Overall the internship was an eye-opener for us to learn about real-time software development and IT industry.


      

CREDITS:
            We would like to extend our sincere gratitude to Mr .Jey ,Mr .Giri, Mrs. Vasanthi, Mrs.Vishwalakshmi for providing us the right technical expertise and guidance during this entire internship. We are looking forward for more internships like this.


  



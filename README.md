# Canaria_Take_Home
Hello, Below is the attached Canar AI Take Home Project



### **Technologies and Tools:**

![Scrapy](https://img.shields.io/badge/Scrapy-558B2F?style=for-the-badge&logo=scrapy&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)






### **TechStack**
Python| Scrapy| Postgres| Docker|


### **Project Flow**
 
* 2 Json files given s01 and s02 which are to be scraped. With a spyder from scrapy, we scrape the information from json files
* We push it to the PostgresSQL . ( We make sure that we have written a service in docker which would create a db in postgres)
* Then we dockerise the application
* After building and doing a docker compose up, your project should be ready



### **Steps to run NewsScope :-**
* Clone the Github Repository 
* Go to the root directory (where docker-compose is located ) and Build the docker using "docker compose build"
* Then do a "docker compose up"
* You have your application ready. You should also have a jobs.csv file in the same root directory of all the jobs which have been scraped
* 








# PDD_18_hw
Python: Object Relational Mapping (ORM), SQLAlchemy
# Web site on Flask for collecting skills from hh.ru
## Description
This site performs requests to hh.ru via api, gets vacancies for given search criteria, parses the response and analyzes the required skills.
## How to start
Run main.py
## Dependencies
Used modules: 
* hhru.all_data
* sqlite.database_access
    
Each request to hh.ru persists to the database (see sqlite/hh_db.sqlite).
Then the last request is read from the database and displayed on the page.
The last request is additionally written to the file hhru_rezult.json.

## Site structure
The site consists of four pages:
* index.html
* form.html
* results.html
* contacts.html

![img.png](img.png)

![img_1.png](img_1.png)

![img_2.png](img_2.png)

![img_3.png](img_3.png)


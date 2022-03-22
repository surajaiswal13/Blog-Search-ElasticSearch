# Blog-Search-ElasticSearch
A Blog web app where Search Feature is Implemented using ElasticSearch and the web app is made using technologies such as Python, Django, Django Rest Framework, ElasticSearch, etc

To get started with this project

1. Create an virtual environment

```
python -m venv venv
```

2. Install all requirements

```
pip install -r requirements.txt
```

3. install ElasticSearch and Java on the System

4. Run the Server

```
python manage.py runserver
```

5. Use the below endoint to test the web app

    http://127.0.0.1:8000/search/user/mike/	            Returns user 'mike13'
    
    http://127.0.0.1:8000/search/user/jess_/	          Returns user 'jess_'
    
    http://127.0.0.1:8000/search/category/seo/	        Returns category 'SEO optimization'
    
    http://127.0.0.1:8000/search/category/progreming/	  Returns category 'Programming'
    
    http://127.0.0.1:8000/search/article/linux/	        Returns article 'Installing the latest version of Ubuntu'
    
    http://127.0.0.1:8000/search/article/java/	        Returns article 'Which programming language is the best?'
    
    
## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25> 

- Suraj Jaiswal

Features:
--------

1. Using Google Youtube API extract datas like Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments from a Youtube channel

2. Store those datas in mongoDB using pymongo

3. After that we can migrate those mongoDB datas in to Mysql server.

4. Using those mysql datas we can do simple EDA analysis.

5. streamlit used for visualisation.



Prerequisites
-------------
    1. Python 3.7 + , 
    2. mongoDB server, 
    3. Mysql server, 
    4. google youtube api key

installation
-------------

    1. pip install streamlit,
    2. pip install google-api-python-client,
    3. pip install pymongo,
    4. pip install mysql-connector-python,
    5. pip install sqlalchemy,
    6. pip install pymysql,
    7. pip install pandas,
    8. pip install numpy,
    9. pip install plotly-express.


Get Started:
-----------

streamlit run [filename.py]

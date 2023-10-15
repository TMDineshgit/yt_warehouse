Features:
--------

1. Using Google Youtube API extract datas like Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments from a Youtube channel

2. Store those datas in mongoDB using pymongo

3. After that we can migrate those mongoDB datas in to Mysql server.

4. Using those mysql datas we can do simple EDA analysis.

5. streamlit used for visualisation.



Installed & imported Libraries:
------------------------------
Prerequisites:
    Python 3.7 +

pip install streamlit
pip install google-api-python-client
pip install pymongo
pip install mysql-connector-python
pip install sqlalchemy 
pip install pymysql
pip install pandas
pip install numpy
pip install plotly-express.


Get Started:
-----------

streamlit run [filename.py]

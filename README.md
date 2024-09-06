# CRUD-SQLite3-PHP 
## (original README.md from [@lwbaqueros](https://github.com/lwbaqueros) original [repo](https://github.com/lwbaqueros/CRUD-SQLite3-PHP) 2019.10.22):
A SQLite3 CRUD with PHP and Bootstrap.

This is an example performed by Basic Programming youtube chanel. 
In the videos, the author creates this CRUD reusing code from www.W3School.com.

In this repository, you can find the complete project in the following manner:

1. Main Page: index.php
2. Subfolders: Others (bootstrap native library and JSquery (not used))
3. Database: A sqlite database

You should run this files in a web server. 

I used Xaamp. 

Youtube channel:

https://www.youtube.com/channel/UC86y1m_CNOigTV7sirO-T8Q

Youtube tutorial:
https://www.youtube.com/watch?v=Scq1wkaUAOo&t=245s
https://www.youtube.com/watch?v=uMU-IeF7RNs&t=14s
https://www.youtube.com/watch?v=-FzIubWH0Gw&t=391s
https://www.youtube.com/watch?v=Y2HQ0fHnLKo&t=6s
https://www.youtube.com/watch?v=dHhGRZu2Vng&t=7s
https://www.youtube.com/watch?v=Dggn0hkFLaY

________________

# CRUD-SQLite3-PHP 
## (modified README.md from [@JupyterJones](https://github.com/JupyterJones) forked [repo](https://github.com/JupyterJones/CRUD-SQLite3-PHP) 2022.04.12)
A SQLite3 CRUD with PHP and Bootstrap.

This is an example performed by Basic Programming youtube chanel. 
In the videos, the author creates this CRUD reusing code from www.W3School.com.

In this repository, you can find the complete project in the following manner:

1. Main Page: index.php
2. Subfolders: Others (bootstrap native library and JSquery (not used))
3. Database: A sqlite database

be sure to install the correct sqlite

For PHP5, use
sudo apt-get install php5-sqlite

For PHP7.0, use
sudo apt-get install php7.0-sqlite

For PHP7.1, use
sudo apt-get install php7.1-sqlite

For PHP7.2, use
sudo apt-get install php7.2-sqlite

For PHP7.3, use
sudo apt-get install php7.3-sqlite

For PHP 7.4.3
sudo apt-get install php7.3-sqlite

Step 2 :

Restart Server /Desktop/php$ php -S localhost:8000
<pre>
[Tue Apr 12 15:29:49 2022] PHP 7.4.3 Development Server (http://localhost:8000) started
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53288 Accepted
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53288 [200]: GET /
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53288 Closing
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53290 Accepted
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53290 [200]: GET /others/bootstrap/css/bootstrap.min.css
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53290 Closing
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53292 Accepted
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53292 [200]: GET /others/js/jquery.min.js
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53292 Closing
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53294 Accepted
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53294 [200]: GET /others/bootstrap/js/bootstrap.min.js
[Tue Apr 12 15:30:13 2022] 127.0.0.1:53294 Closing
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53296 Accepted
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53296 [200]: GET /update.php?u_id=1
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53296 Closing
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53300 Accepted
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53300 [200]: GET /others/bootstrap/css/bootstrap.min.css
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53300 Closing
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53302 Accepted
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53304 Accepted
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53302 [200]: GET /others/js/jquery.min.js
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53302 Closing
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53304 [200]: GET /others/bootstrap/js/bootstrap.min.js
[Tue Apr 12 15:30:29 2022] 127.0.0.1:53304 Closing
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53306 Accepted
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53306 [302]: POST /update2.php?u_id=1
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53306 Closing
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53308 Accepted
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53308 [200]: GET /index.php
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53308 Closing
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53310 Accepted
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53312 Accepted
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53314 Accepted
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53310 [200]: GET /others/bootstrap/css/bootstrap.min.css
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53312 [200]: GET /others/js/jquery.min.js
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53314 [200]: GET /others/bootstrap/js/bootstrap.min.js
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53312 Closing
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53310 Closing
[Tue Apr 12 15:30:41 2022] 127.0.0.1:53314 Closing

</pre>



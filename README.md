# productionalizing-data-pipelines-airflow
Productionalizing Data Pipelines with Apache Airflow course @ Pluralsight

docker-compose up --build
docker ps --format "table {{.Names}}:\t{{.Ports}}\t{{.Status}}"

pg_ctl -D /var/lib/postgresql/data -l logfile start

while running docker getting below error 

airflow   | /usr/bin/env: ‘bash\r’: No such file or directory
airflow   | /usr/bin/env: ‘bash\r’: No such file or directory
airflow   | /usr/bin/env: ‘bash\r’: No such file or directory
airflow exited with code 127

to solve this did 
http://sql313.com/index.php/43-main-blogs/maincat-dba/62-using-notepad-to-change-end-of-line-characters

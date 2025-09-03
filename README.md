**Simple Web Application**
This is a simple web application using Python Flask and MySQL database. This is used in the demonstration of the development of Ansible Playbooks.

Below are the steps required to get this working on a base linux system.

Install all required dependencies
Install and Configure Web Server
Start Web Server
1. Install all required dependencies
Python and its dependencies

apt-get install -y python3 python3-setuptools python3-dev build-essential python3-pip default-libmysqlclient-dev
2. Install and Configure Web Server
Install Python Flask dependency

pip3 install flask
pip3 install flask-mysql
Copy app.py or download it from a source repository
Configure database credentials and parameters
3. Start Web Server
Start web server

FLASK_APP=app.py flask run --host=0.0.0.0
4. Test
Open a browser and go to URL

http://<IP>:5000                            => Welcome
http://<IP>:5000/how%20are%20you            => I am good, how about you?




Instructions:
1. docker run -it ubuntu bash
2. apt-get update
3. apt-get install -y python-is-python3
4. python
5. apt-get install python-is-python3 pip

Docker image commands:
1. docker build -t flask-app .
2.docker run -p 8080:8080 flask-app
3.docker build . -t officesd88/docker-demo
4.docker push officesd88/docker-demo



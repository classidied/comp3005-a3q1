# comp3005-a3q1
A python script to perform CRUD operations on a Postgres database through the command line

Steps to compile and run:

- run `git clone https://github.com/classidied/comp3005-a3q1.git` in your terminal in a directory you'd like to download the application into
- create a virtual environment for `psycopg2` to run in by running   
1. `python3 -m venv ~/.environments/test`
2. `source ~/.environments/test/bin/activate`  
then install `psycopg2` so we can connect to the library  
3. `pip3 install psycopg2`  
- edit `script.py` to include the correct parameters according to your database (database name, host, user, port)
- to find this info, run `\conninfo` on the psql tool on pgAdmin in your database
- in the virtual environment created through the first two commands, run `python3 script.py` and run any commands you'd like  

Video demo link: https://youtu.be/6C0H_vUf5k8  

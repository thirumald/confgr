# Install

### Getting OS up-to-date

```
sudo apt-get install update
sudo apt-get install upgrade
```

### Installing pip

```
sudo apt-get install python-pip
```

### Installing sqlite3

```
sudo apt-get install sqlite3
```

### Create Application Directory

```
cd /opt
sudo mkdir confgr
cd confgr
```

### Clone git repo

```
sudo git clone https://github.com/WilliamMarti/confgr.git .
```

### Install packages from requirements.txt file 

```
sudo pip install -r requirements.txt
```

### Run the application

```
cd confgr
python confgr.py
```


This will get you up and running.  For a more scaleable server using gunicorn as a webserver will be the long term solution.
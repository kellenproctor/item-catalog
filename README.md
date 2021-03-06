#P3: Item Catalog

Common code for the Relational Databases and Full Stack Fundamentals courses
from Udacity.

Project 3 additions by Kellen Proctor on 12 November 2015

####INTRODUCTION:
Item Catalog contains a first stab at a fully functional full-stack python web
app! Let's hope it works! Written using Flask and based off of the excellent
workflow taught by Lorenzo, we're looking to exceed expectations.

####FILES:
database_setup.py - contains database schema
lotsofitems.py - contains python code for adding database items
application.py - contains the flask app

####DOWNLOAD:
Please clone to your most convenient directory (folder) via the following
command:


```
git clone https://github.com/kellenproctor/item-catalog.git item-catalog
```

####REQUIREMENTS:
[Vagrant](https://www.vagrantup.com/)

[Virtual Box](https://www.virtualbox.org/)

####RUNNING:
Please open a terminal, navigate to /vagrant inside the /item-catalog
directory, and run the following commands:

```
vagrant up
vagrant ssh
cd /vagrant/catalog
```

This will get you into the item_catalog directory, where you can interact with
the files as listed above. To initiate the item catalog web-app,
run the following command inside the directory containing **application.py**:

```
python database_setup.py
python lotsofitems.py
python application.py
```

Open **http://localhost:8000/** in your browser, and commence interacting with
the platform!


######Enjoy your experience! All feedback is welcome!

A third stab at these, thanks to some help from Udacity and some resources
from coach (unknown). Will check out the Readme class soon, I promise.
### online-shop
##### An e-commerce site, built on top of Django- Python's framework. (Django==2.1.7)
---
### Functions
* Creating the product catalog models, adding them to the administration site, and building the basic views to display the catalog
* Building a shopping cart system using Django sessions to allow users to keep selected products while they browse the site.
* Creating the form and functionality to place orders on the site.
* Sending an asynchronous email confirmation to users when they place an order.

---
### Set up

```
$ pip install requirements.txt
```

### Migrate Database & Create Super User
```
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage,py createsuperuser
```
---
### Add products form admin panel
Go to ```127.0.0.1:8000/admin``` in your browser and add products for the e-commerce site. 

---
### Site Demo
![alt text](https://i.imgur.com/SLYjnz4.gif)



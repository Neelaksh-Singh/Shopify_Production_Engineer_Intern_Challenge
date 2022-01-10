# Shopify_Engineer_Intern_Challenge

### Shopify Fall 2021 Back-end Developer / Production Engineer Intern Challenge Question (Inventory)
### Created Neelaksh Singh. (neelaksh48@gmail.com)

In this project, I designed an inventory tracking web application for a logistics company, with the functionality of creating, editing and deletion of product.

## 🚩 ABSTRACT

I leveraged two useful libraries: Python Flask and SQLAlchemy, and used four different programming languages: Python, HTML5(with Bootstrap and Jinja templating), CSS, and SQLite3. 

For this project, Flask is a framework that not only provides a user-friendly web interface but also handles functionalities of the webiste, including downloading and uploading data. SQLAlchemy, an object relational mapper (ORM), stores the product name, quantity and price, also avoids adding duplicate data.

For the backend design, I utilized Python Flask and sqlalchemy for product uploading, storing and duplicate checking purposes. In particular, we used the HTTP post action to trigger the upload process of product, and built-in functionality of HTML5 to check the data integrity. Also used WTForms for handling form data validation.
The webisite uses flash a component of Flask which makes user have a better sense of their interaction with the webpage.

There is an added functionality of exporting product data to a CSV file. This uses the csv library and stores the generated files in <b>Generated_CSV</b> folder.

## 💻 Installation

`!!! Must have Python installed. !!!` <br>

<b>Port 80 must be reserverd</b> <br>

Python 3.9+ is required to run code from this repo. 

```console
$ git clone https://github.com/Neelaksh-Singh/Shopify_Engineer_Intern_Challenge.git
$ cd Shopify_Engineer_Intern_Challenge/
$ pip install -r requirements.txt
$ python app.py
```
After this step Your Flask app will be running at **localhost:80** 

## What's next for this repo

I plan to add features that simulate a warehouse environment and handles balancing quantities over warehouses. Feature like Transfers which lets you move items into the central warehouse (and vice-versa), along with to and fro from various locations and also transfer tracking system are some of the most desired in the future.
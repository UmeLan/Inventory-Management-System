# itakeVer2

Group project

Go to the terminal and see if you have python installed by typing ‘python’.
See if you have Django 1.9 (pip install Django==1.9), MySQL installed.
Unzip the folder to wherever you want. Open up your terminal or PowerShell, and change directory into the folder containing manage.py.
We can access the database (hosted in AWS) through the command line. Follow these steps: mysql -h ecommerce3.cia2arykzkpz.us-west-2.rds.amazonaws.com -P 3306 -u admin -p
Now you’re inside the database in mysql shell. Type ‘use Ecommerce3;’ We are connected to our database on AWS.
Type the following command: python manage.py runserver
Url to the admin page: http://127.0.0.1:8000/admin/ username: admin1 password: pass1234 On logging in, we can view itake – which contains our tables Order items, Orders, Products, Vendors, Warehouses.
Next, navigate to our itake page, the url for which is: http://127.0.0.1:8000/itake/ This is our home page.
CRUD Functionality: 9)	On clicking the Product Button (http://127.0.0.1:8000/itake/product/) we can view the List of Products. 10)	On clicking the product in the list, you can view the detail information of each product. 11)	On clicking the ‘Add Product’ button in the product list page (http://127.0.0.1:8000/itake/product/), you can add new product to the table. 12)	On clicking the ‘Edit’ button in the product list (http://127.0.0.1:8000/itake/product/), you are directed to the update page of the specific product. 13)	On clicking the ‘Delete’ button in the product list (http://127.0.0.1:8000/itake/product/), you are directed to a confirmation page. By clicking on the ‘submit’ button, you can delete the product from the table.
URL of the homepage:http://itakev10.efh2tfmqw8.us-west-2.elasticbeanstalk.com/itake/

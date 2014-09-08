#Python

######

######Python was created by Guido Van Rossum in the early 90’s. It is now one of the most popular languages in existence. I fell in love with Python for its syntactic clarity. It’s basically executable pseudocode.

###Python learning curve depends how we learn things...

### I think i need a week to complete python.

```python
		http://learnxinyminutes.com/docs/python/
```

[Learn Python in 10 minutes](http://learnxinyminutes.com/docs/python/)


## Web Application Frameworks in Python

##### MVC Based Web Application Frameworks
######[Django](https://www.djangoproject.com/)

###### [Pyramid Framework](http://www.pylonsproject.org/projects/pyramid/about)




### Install Python,Django,Pyramid Framework on Ubuntu
```python
	sudo apt-get update
	sudo apt-get install python3-dev python3-setuptools
	sudo easy_install virtualenv


  #for pyramid framwork
  mkdir pyramid_sites
  cd pyramid_sites
  # To create virutal Environment,raries without affecting our system's tools.
  virtualenv --no-site-packages env  
  source env/bin/activate   # To Activate virtual Environment


```

``` Pyramid Commands
   #Some Commands for building up a pyramid project
   pcreate -l  # displays all commands
   pcreate -s starter starter_first_project  # to create a sample project
   pcreate -s alchemy example_app_with_alchemy  # Sql_alchemy is a ORM for Pyramid (Object Relational Mapper)
	
```
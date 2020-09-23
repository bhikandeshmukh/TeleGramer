# • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

# command line

```
$ pkg up -y

$ pkg install python -y

$ pkg install git

$ git clone https://github.com/thebhikandeshmukh/TeleGramer

$ cd TeleGramer 
```

Install requierments & Setup Configuration File. ( apiID, apiHash )

```
$ python setup.py
```

To Scare members from group.

```
$ python scraper.py
```

Add Scarped members to your group.

```
$ python adder.py
```

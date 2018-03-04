# Linkedin-Spider

A spider for linkedin written in Python3. 

It scrapes all the details in public information according to the name you input.

## Running Environment (what you need to install before running):
 * selenium</br>
 * BeautifulSoup4</br> 
 * chrome driver (for selenium) </br>
 * xldd</br>
 * xlrt</br>
 * xlutils

## Running Instructions:
  You will be asked to input: your username, you password, the name of input file and the name of output file.</br>
  
### Username and password:
  Used to login your account before scraping.

### Input file
  It should be a "xlx" or "xlsx" file which has three columns which includes id, first name and last last name of people.</br> 
  Id is that id you give. If you don't need it, you can keep the cells blank.</br>
  
### output file
  It is where the results stores.
  
  
## Running command:
```
$ python3 LinSpider.py
```

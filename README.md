
## Lab

1. Write a function to make a google maps api directions request. 
     1. The function should take in 3 parameters: origin, destination, api_key
2. Choose another API such as the one below and make 3 calls.

#### More APIs to Checkout <a id="apis"></a>

* Google Maps
* Twitter
* AWS
* IBM's Watson

## Question 1

1. Write a function to make a google maps api directions request. 
     1. The function should take in 3 parameters: origin, destination, api_key
     

Check out the documentation here:
https://developers.google.com/maps/documentation/directions/start


```python
import requests

#Starter code snippet
url = 'https://maps.googleapis.com/maps/api/directions/json?origin=Disneyland&destination=Universal+Studios+Hollywood4&key=YOUR_API_KEY'
response = requests.get(url)

def get_google_directions(input_variable1, input_variable2, etc.):
    """Your code goes here. Well, outside the comments section if you want it to do anything."""
    return Whatever your function returns...maybe nothing
```

## Question 2
2. Choose another API such as the one below and make 3 calls.


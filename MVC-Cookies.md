# MVC Cookies

A piece of data that the server sends to the user's browser.  



## Usage of cookies
1. Session Management.
2. Personalization.
3. Tracking.

## Prefixes

1. __Host-

If a cookie name has this prefix, it's accepted in a Set-Cookie header only if it's also marked with the Secure attribute,
was sent from a secure origin, does not include a Domain attribute, and has the Path attribute set to /. This way, these cookies can be seen as "domain-locked".  

2. __Secure-

If a cookie name has this prefix, it's accepted in a Set-Cookie header only
if it's marked with the Secure attribute and was sent from a secure origin. This is weaker than the __Host- prefix.


# Hash Table






## Hash

The result of algorithm taking strings and changing them for security.

## Bucket

The contents of each index inside the array, each one could be multiple values.


## Collision

When more than one key gets hashed to the same location in the bucket.





## Internal Methods

1. Add()  

This methods allows you to add a new key/value to the hash table.

2. Find()

Search for a key/value in the hash table

3. Contain()

Check if a hash is contained within a table.

4. GetHash()  

Takes in a string and returns the place (index) where it's stored.

Data Structure with Flask API
=============================

Based on:
https://www.youtube.com/watch?v=lOBu2zwxAm8&list=PL7g1jYj15RUP_Mri9ym6BdUais6_jvhrS

# Create user:

```
curl --location --request POST 'http://127.0.0.1:5000/user' --header 'Content-Type: application/json' --data-raw '{"name": "Bill", "email": "bil@example.com", "address": "tomss address", "phone": "+ 4412345667"}'  
```
output:
```
{
  "message": "User created"
}
```
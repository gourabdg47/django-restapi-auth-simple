# django-restapi-auth-simple
Learning django rest api with authentication 

* To create auth token run the cmd: python manage.py drf_create_token username

## Use postman
- Use the generated token in postman to get and resive values
- To save data in db, send POST request with body :
{
    "name":"any_string",
    "age":any_int
}
- To view all data, send a GET request

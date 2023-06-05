# Polling App
- - -

### Features:
- User authentication
- Add Polls
- Add Choices for each polls
- Record votes for each choice on the poll
- Read Polls with all the associated data
- JWT authentication and authorization

### Documentation:
1. JSON API specification at /swagger.json
2. YAML API specification at /swagger.yaml
3. Swagger UI API specification at /swagger/
4. ReDoc API specification at /redoc/

### Endpoints :

| URL                       | HTTP Verb | Functions                              |
|---------------------------|-----------|----------------------------------------|
| 'user/login'              | POST      | user login                             |
| 'user/'                   | POST      | user registration                      |
| '/polls'                  | GET       | return all polls                       |
| '/polls/{id}'             | GET       | get specified ID poll                  |
| '/polls/{id}/choices'     | GET       | get choices from specified poll        |
| '/polls/{id}/choices/{choice_id}/vote' | GET       | returns votes belonging to each choice |

### Tools :
1. Python
2. Django & Django Rest Framework
3. Postgres (Unplugged for dev)
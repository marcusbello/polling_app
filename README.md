## Polling App
- - -

#### Endpoints :

| URL                       | HTTP Verb | Functions                              |
|---------------------------|-----------|----------------------------------------|
| 'user/login'              | POST      | user login                             |
| 'user/'                   | POST      | user registration                      |
| '/polls'                  | GET       | return all polls                       |
| '/polls/{id}'             | GET       | get specified ID poll                  |
| '/polls/{id}/choices'     | GET       | get choices from specified poll        |
| '/polls/{id}/choices/{choice_id}/vote' | GET       | returns votes belonging to each choice |

#### Tools :
1. Python
2. Django & Django Rest Framework
3. Postgres
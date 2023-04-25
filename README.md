# jwt-example
A JWT Implementation in Spring

Create user with password:
http://localhost:8080/api/user/create
{
    "username": "PETER",
    "password": "oursecretkey",
    "confirmPassword": "oursecretkey"
}

Login with:
http://localhost:8080/login
{
    "username": "PETER",
    "password": "oursecretkey"
}

In the reponse body you get the jwt token
Key: Authorization
Value: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJQRVRFUiIsImV4cCI6MTY4MzMxNTE3NX0.G8adQO3gElMQI9f6Paq7EYMu8ZTIbFyGZqv1EM3kQx_UmGPb-diuuPOyTzhmkZahv3K8S1izgVNn1QK-yxcJpg


# Oauth2.0

Handling oauth 2.0 Authorization Grant type - Client Credentials



## Overview

OAuth

authorization server(AS) is an api that grant token for accessing backend apis(ex: bank account details,credit card details,etc..)

this Authorization server gives Access tokens(AT) for the Apis to access

OAuth has 3 types

1.client credentials - client id, client secret

2.password - uname & pw

3.Author code

(most companies use first two )

## prerequisites
Before going further please download this [file](https://github.com/Rakesh-592/Oauth2.0/blob/main/ClientCredentialsOAuth.postman_collection.json) and export it to postman for better understanding

## Api Contract Download

```Authorization Server EndPoint:

https://rahulshettyacademy.com/oauthapi/oauth2/resourceOwner/token



HTTP Method : POST



Form parameters :



client_id:

692183103107-p0m7ent2hk7suguv4vq22hjcfhcr43pj.apps.googleusercontent.com

client_secret:  erZOWM9g3UtwNRj340YYaK_W

grant_type:   client_credentials

scope:  trust

```
![Screenshot 2024-07-19 114605](https://github.com/user-attachments/assets/aed92c70-81fd-4845-a43a-044835e9329b)


``` 
GetCourseDetails EndPoint (Secured by OAuth) :

https://rahulshettyacademy.com/oauthapi/getCourseDetails



HTTP Method : GET

Query Parameter : access_token


access_token: "u7QO0FafmNwd0Wp2Jq1diA=="
```

![Screenshot 2024-07-19 115144](https://github.com/user-attachments/assets/3eaac878-370a-44e9-b9c9-4d85007e7033)

![Screenshot 2024-07-19 115324](https://github.com/user-attachments/assets/fda03d78-8128-4be2-8ada-54337a468af3)


## Console output
![Screenshot 2024-07-20 165745](https://github.com/user-attachments/assets/8fc8441f-3194-4173-b6d7-6dd559485dd9)

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.



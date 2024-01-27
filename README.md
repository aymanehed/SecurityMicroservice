# Security Oauth2, OIDC, JWT, Keycloak , SpringBoot

# Part 1: Keycloak, Jwt 

## Bullet Points :
### in this part we will cover the following topics:

- Download Keycloak 23
- Start Keycloak
- Create an Admin account
- Create a Realm
- Create a client to secure
- Create users
- Create roles
- Assign roles to users
- Using Postman:
    - Test authentication with the password
    - Analyze the contents of both JWT Access Token and Refresh Token
    - Test authentication with the Refresh Token
    - Test authentication with Client ID and Client Secret
    - Change the parameters of Access Token and Refresh Token

### Screenshots :

#### 1. In the following screenshot, i authenticated with the username and password and we got the Access Token and Refresh Token:
<img width="453" alt="Screenshot 2024-01-27 142547" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/7c40d0af-1592-43da-b2eb-7f617bd8f925">



#### 2. In the following screenshot, i decoded the Access Token and we can see its content using jwt.io:

<img width="408" alt="Screenshot 2024-01-27 142602" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/a73e9746-70e0-4433-8835-bf161e034774">



#### 3. In the following screenshot, i authenticated with the Refresh Token and we got the new Access Token and Refresh Token:
<img width="457" alt="Screenshot 2024-01-27 142610" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/8ba3c149-a269-401e-9ff7-0bb00bf48a6c">



#### 4. In the following screenshot, i authenticated with the Client ID and Client Secret and we got the Access Token and Refresh Token:
<img width="454" alt="Screenshot 2024-01-27 142620" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/ab9e8795-c0b9-4b1c-b529-a5a5eef35398">



#### 5. In the following screenshot, i changed the capabilitie configuration in keycloak and now even with the client username and password we can't get the Access Token and Refresh Token so we need to use the Client secret and Client ID to get the Access Token and Refresh Token:

<img width="458" alt="Screenshot 2024-01-27 142629" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/4d96d303-f3c7-4a7a-8b28-4fe32996dc21">
<img width="457" alt="Screenshot 2024-01-27 142643" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/5821fedd-ff72-4021-9d39-60ee19c0ec9d">



# Part 2: SpringBoot, Keycloak, Jwt , Oauth2 


## Bullet Points :

-   Develop and secure a microservices-based application using OAuth 2, OIDC, and Keycloak:
    - Inventory service
    - Frontend Thymeleaf
    - Frontend Angular


### Screenshots :

#### 1. In the following screenshot, i consulted the customer service and i get the list of customers:

<img width="363" alt="Screenshot 2024-01-27 142652" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/57a0bbdb-6fc4-4a2f-9bae-d8c260d59a7f">


#### 2. In the following screenshot, i added the webjar dependency to the pom.xml file so i can use bootstrap and jquery in my project:
<img width="459" alt="Screenshot 2024-01-27 142658" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/1bf19c5f-177a-48cf-8d76-85ffaed7d883">



#### 3. In the following screenshot, i added the template dependency to the pom.xml file so i can use thymeleaf template in my project that contains the navbar and the footer:

<img width="462" alt="Screenshot 2024-01-27 142704" src="https://github.com/aymanehed/SecurityMicroservice/assets/93987581/e15889c8-1039-404b-8426-700584185316">







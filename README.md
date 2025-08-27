# Venturo Assignment – Katalon WebService Automation for Reqres API

This project is created as part of **Venturo QA Automation Assignment**. It automates WebService tests for **Reqres API** using **Katalon Studio** and has been uploaded to **GitHub**.
## Endpoints Automated

- **GET list users**  
  - `/api/users?page=1`

- **GET single user**  
  - `/api/users/2`

- **PUT update user**  
  - `/api/users/2`

- **POST register successful**  
  - `/api/register`  
  -  - Uses `email` from **GET single user** response with `id=2`.

## Global Variable

- `token` → API key (`reqres-free-v1`)  
- Used in all requests as authentication.

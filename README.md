# Coffee Shop Full Stack

## Connection Details
### Auth0 Account
```
AUTH0_DOMAIN = 'fsnd-gt.us.auth0.com'
API_AUDIENCE = 'coffeeshop'
```

> Postman has been updated with new JWTs, but due to them potentially expiring, below are credentials for dummy accounts that can be used.

#### Manager Account
```
User: manager@fsnd-gt.us.auth0.com
password: fDSeGfffq8RDKh2
submitted token (which can be expired at the time of review = Monday, March 29, 2021 4:27:52 PM GMT-04:00 DST)
```
`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6InMyanZ1T01WSzlLTl9SY1l5eUxCRyJ9.eyJpc3MiOiJodHRwczovL2ZzbmQtZ3QudXMuYXV0aDAuY29tLyIsInN1YiI6ImF1dGgwfDYwNWQ1MGM5MmNkZDNlMDA2OWM1ZWE5NyIsImF1ZCI6ImNvZmZlZXNob3AiLCJpYXQiOjE2MTY5NjMyNzIsImV4cCI6MTYxNzA0OTY3MiwiYXpwIjoiRGpqcjROM0plcG5STU1wUmlyb2ZpNlFwdnFmR0RuTGwiLCJzY29wZSI6IiIsInBlcm1pc3Npb25zIjpbImRlbGV0ZTpkcmlua3MiLCJnZXQ6ZHJpbmtzLWRldGFpbCIsInBhdGNoOmRyaW5rcyIsInBvc3Q6ZHJpbmtzIl19.Xgvg4I2mUi44BSbrpOBx5gzuekRFyuaMLXQxTQGDbtDLndoEDwrvD4BVgxT8W1kC8uAEtqAUiOpiqok2b1Nqaix-9EY7GOCMAL3pUCqG-DS5QeyEyTgk4d4MQDDdueko6-lu7i5Cwl1DcSUgGANsZwdqJgNTfBKZQEPP9XRiF_0oo6QShzrsYeUDYz6tBrqkaHNBw0r9ry1A2LnxGcHiBMcTHyAcZpEKt3iI8EuKN8EgIs0at9FhAox7YswkjnVMcj9qARYj_UIEPMfYY8jXAzD6qvIipqxyAS6M4Xg6vWNGRlhRMh5wHwXNEi1Qp4rc0i0HU_E5GEdmyKjMMvJcxw`

#### Barista Account
```
User: barista@fsnd-gt.us.auth0.com
password: fDSeGfffq8RDKh2
submitted token (which can be expired at the time of review = Monday, March 29, 2021 4:26:43 PM GMT-04:00 DST)
```
`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6InMyanZ1T01WSzlLTl9SY1l5eUxCRyJ9.eyJpc3MiOiJodHRwczovL2ZzbmQtZ3QudXMuYXV0aDAuY29tLyIsInN1YiI6ImF1dGgwfDYwNWQ1MDIwZWQzZTI4MDA2ZjZkNDAyNyIsImF1ZCI6ImNvZmZlZXNob3AiLCJpYXQiOjE2MTY5NjMyMDMsImV4cCI6MTYxNzA0OTYwMywiYXpwIjoiRGpqcjROM0plcG5STU1wUmlyb2ZpNlFwdnFmR0RuTGwiLCJzY29wZSI6IiIsInBlcm1pc3Npb25zIjpbImdldDpkcmlua3MtZGV0YWlsIl19.VjjcH80S_f5qioEKSZRYWm2xKqQC0DaUXn5Q4bmTyiW6udWqQNAmwKv819oFnujAKgolvbVCt-grMFilR9mmK76wahRgdmF3QkaX0cbI6dsdi8UF_yxGJx4cvEypCGcsTfidrzw6ZYH_0hqa4Uk_kcwTjfnilM-1yGjJM60EOtUd0iEgKYF28ZgNkKWtpYLv9ns82TFXsxsMJBDNss08nzxtuxdhvNuqFPoRJCWPLBMKGEPlF5srCPGcA74tRp3h60_zgiMjIT4QJ3CEYIvCuYWTdcxfUw1xdZQIbP2uMHhcrSvKvXwSLwnNLYpNinckxaf3FVi6bdtYL0YpVn1lQg`

### Running the Backend
From within the `./backend` directory first ensure you are working using your created virtual environment, then pip install the requirements.

```bash
pip install -r requirements.txt
```

From within the `./backend/src`, run:
```bash
export FLASK_APP=api.py;
flask run --reload
```

### Running the Frontend
To run the development server, cd into the `frontend` directory and run:

```bash
ionic serve
```

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:

1) Display graphics representing the ratios of ingredients in each drink.
2) Allow public users to view drink names and graphics.
3) Allow the shop baristas to see the recipe information.
4) Allow the shop managers to create new drinks and edit existing drinks.

## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is desiged with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app. 

[View the README.md within ./frontend for more details.](./frontend/README.md)

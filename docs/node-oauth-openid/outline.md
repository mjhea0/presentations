# Introduction to OAuth2 and OpenID

The course serves as a practical, hands-on introduction to both the OAuth2 and OpenID standards.

## Audience

Mid to senior level web developers.

## Narrative

Throughout the course, we'll be developing a server-side Node application for handling authorization and authentication with OAuth2 and OpenID, respectively.

## Learning Objectives

After completing this course, you will be able to:

1. Describe the difference between authentication and authorization
1. Explain what OAuth 2.0 is and how it differs from OAuth 1.0
1. Describe the various OAuth 2.0 grant types and when it's appropriate to use each
1. Implement an OAuth 2.0 server with Node
1. Explain what OpenID is and how it works with OAuth
1. Implement OpenID with Node
1. Develop a client-side consumer app to interact with an OAuth 2.0 and OpenID server

## Day 1 Outline

### Theory (~2 hours)

#### Authentication vs Authorization

1. Authentication
1. Authorization

#### OAuth 2.0

1. What is OAuth 2.0?
1. OAuth 2.0 authorization flow
1. History of OAuth
    1. OAuth 1.0
    1. OAuth 1.0 authorization flow
    1. OAuth 1.0 vs Oauth 2.0
1. Grant Types
    1. Authorization Code (server apps)
    1. Implicit (browser-based and mobile apps)
    1. Password Credentials (logging in with a username and password)
    1. Client Credentials (application access)
    1. When is it appropriate to use each grant type?
1. Bearer Token
1. Authorization before OAuth

### Practice (~5 hours)

#### Oauth 2.0 with Node

1. What are we building?
1. Node and Express setup
1. Postgres setup
1. Authorization Codes and Tokens
    1. Authorization Codes
    1. Access Tokens
        1. Scope
    1. Refresh Tokens
1. Authorization endpoint (GET - `/authorize`)
1. Token endpoint (POST - `/token`)
1. Refresh Tokens
1. Error handling

## Day 2 Outline

### Theory (~1 hour)

#### Day 1 Review

1. OAuth 2.0
1. What did we build?

#### OpenID

1. What is OpenID?
1. How does OpenID work with OAuth 2.0?
1. JSON Web Tokens (JWT)

### Practice (~5 hours)

#### OpenID with Node

1. Adding authentication to the server
1. Update existing endpoints
1. JSON Web Tokens (JWT)
1. UserInfo endpoint (GET - `userinfo`)

#### Client-side Consumer with JavaScript

1. Setup
1. OAuth 2.0 flow
1. Route setup (`/` and `/callback`)
1. OpenID flow
1. Update routes

### Theory (~1 hour)

1. Final review
1. Questions

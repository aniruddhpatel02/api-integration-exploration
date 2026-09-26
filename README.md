# api-integration-exploration
Hands-on exploration of APIs, HTTP requests, JSON responses, and software integrations from a technical sales perspective.

# API Integration Exploration

A hands-on project exploring how applications communicate through APIs.

The goal of this project is to move beyond understanding APIs conceptually and interact with one directly by sending HTTP requests, working with endpoints, inspecting JSON responses, and understanding common status codes.

## Tools

- JSONPlaceholder
- Postman
- GitHub

## Concepts Applied

- REST APIs
- API endpoints
- HTTP requests and responses
- GET and POST methods
- Query parameters
- JSON
- HTTP status codes
- Response time / latency

## GET Request

I used the `/users/1` endpoint to retrieve a specific user.

**Method:** GET

**Endpoint:** `/users/1`

**Status:** 200 OK

The API returned the user's information as structured JSON.

## Query Parameters

I used:

`/posts?userId=1`

to retrieve posts associated with a specific user.

Changing the `userId` changes which records the API returns.

This demonstrated how query parameters can be used to filter API requests.

## POST Request

I sent a POST request to `/posts` with a JSON request body containing a title, body, and user ID.

The API returned the simulated newly created resource.

**Status:** 201 Created

## Error Handling

I intentionally requested a resource that did not exist to observe how the API handles an unsuccessful request.

**Status:** 404 Not Found

This helped connect HTTP status codes to actual API behavior rather than treating them as definitions to memorize.

## Technical Sales Takeaway

Working with an API directly helped me better understand what technical buyers mean when they ask about API integrations.

An integration conversation can involve much more than whether an API exists. Buyers may need to understand available endpoints, supported operations, authentication, request and response formats, rate limits, error handling, and whether the API can support their intended workflow and scale.

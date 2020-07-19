# Project Title

Mule4-global-Error-Handling

# Description

Here I am going to make an API using mule4 , which explains how to handle the errors globally in any API in mule4.

## Getting Started
```
So I used here a simple GET method which will handle two errors:
- NOT_FOUND (HTTP-status-code:404)
- METHOD_NOT_ALLOWED (HTTP-status-code:405)
And one default which is Internal server error i.e (HTTP status code :500)

Basically you will get an idea by using this code how to define the exception globally in an API.

Similarly you can do this for other methods and other exceptions also.

```

### Prerequisites

```
- Anypoint studio (7.5)
- Advance Rest Client or Postman
```

### Installing

Link for Downloading the Anypoint-studio for development:
```
https://www.mulesoft.com/lp/dl/studio
```
Link for Downloading Advance Rest Client for testing the API:
```
https://install.advancedrestclient.com/
```
Link for Downloading Postman for testing the API:
```
https://www.postman.com/downloads/
```

## Running the API

just hit the URL in postman which we configured in the API with ## GET method:
```
http://localhost:8081/api/Error
```

## Deployment

As of now for demo & understandiong purpose just run on mule server 4.3 by right clicking on main xml and select run.

## Built With

* [Anypoint-Studio(7.5)](https://www.mulesoft.com/lp/dl/studio) - The development tool.
* [Postman](https://www.postman.com/downloads/) - Testing tool.

## Authors

* **Shivangi Singh** - *API Developer* - [shivangisingh98](https://github.com/shivangisingh98).

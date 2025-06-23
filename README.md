alx-graphql-0x00: Character GraphQL Queries
This repository contains GraphQL queries designed to fetch details of specific characters using their IDs. Each query is provided in a .graphql file, and its expected output is in a corresponding .json file.

Objective
To demonstrate fetching character details using the character(id: ID!) field, including id, name, status, species, type, and gender.

Endpoint
The queries in this project are designed to be run against a GraphQL API endpoint. For testing and demonstration purposes, you can use a public GraphQL endpoint like:

https://rickandmortyapi.com/graphql

Directory Structure
.
├── character/
│   ├── README.md
│   ├── character-id-1.graphql
│   ├── character-id-1-output.json
│   ├── character-id-2.graphql
│   ├── character-id-2-output.json
│   ├── character-id-3.graphql
│   ├── character-id-3-output.json
│   ├── character-id-4.graphql
│   └── character-id-4-output.json

How to Use These Queries
You can run these GraphQL queries using a GraphQL client tool. Some popular options include:

Apollo Studio Explorer (Web-based):

Go to the endpoint URL (https://rickandmortyapi.com/graphql) in your web browser. This often opens an interactive GraphQL explorer.

Copy the content of a .graphql file (e.g., character-id-1.graphql) and paste it into the query editor.

Click the "Play" or "Run" button to execute the query.

Compare the result with the corresponding .json output file (e.g., character-id-1-output.json).

Insomnia / Postman (Desktop Applications):

Create a new HTTP Request.

Set the method to POST.

Set the URL to the GraphQL endpoint.

Set the body type to GraphQL Query.

Paste the query from a .graphql file into the query editor.

Send the request and observe the JSON response.



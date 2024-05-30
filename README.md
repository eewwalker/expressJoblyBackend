
## Jobly Backend
This is the RESTful API for Jobly, an application for browsing companies and job postings. Routes are protected with both user authentication and authorization using middleware. 

### Built With
[![My Skills](https://skillicons.dev/icons?i=nodejs,express,postgres)](https://skillicons.dev)

### Getting Started
1. Clone the repo
 ```
git clone https://github.com/eewwalker/expressJoblyBackend.git
```
2. Create and seed database
```
createdb jobly
psql jobly.sql 
```
3. From the root directory of the project, run:
```
npm install
```

#### To Run 
Backend server(Defaults to port 3001)
```
node server.js
```
#### To run tests
```
npm test
```
```
npm cov
```

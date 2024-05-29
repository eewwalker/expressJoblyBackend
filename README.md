
## Jobly Backend
This is the RESTful API for Jobly, an application for browsing companies and job postings. Routes are protected with both user authentication and authorization using middleware. 

### Built With
<img width="50" src="https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png" alt="Node.js" title="Node.js"/> <img width="50" src="https://user-images.githubusercontent.com/25181517/183859966-a3462d8d-1bc7-4880-b353-e2cbed900ed6.png" alt="Express" title="Express"/> <img width="50" src="https://user-images.githubusercontent.com/25181517/117208740-bfb78400-adf5-11eb-97bb-09072b6bedfc.png" alt="PostgreSQL" title="PostgreSQL"/> 

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

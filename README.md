#### Run The App Locally

npm run install && npm start

#### React Router 6

npm install react-router-dom@6

#### React Toastify

npm install --save react-toastify
import 'react-toastify/dist/ReactToastify.css'

#### Redux Toolkit

npm install @reduxjs/toolkit react-redux

#### React Bootstrap

npm install react-bootstrap bootstrap
import 'bootstrap/dist/css/bootstrap.min.css'

#### Axios HTTP Methods

- GET - get resources from the server
- POST - submit resource to the server
- PUT/PATCH - modify resource on the server
- DELETE - delete resource form the server

// GET
axios.get(url, options);
// POST
axios.post(url, resource, options);
// PATCH
axios.patch(url, resource, options);
// DELETE
axios.delete(url, options);

npm install axios

#### API

- Documentation - https://node-course-jobs-api.onrender.com/api-docs/
- https://jobify-prod.herokuapp.com/api/v1/toolkit

###### Register USER

- https://jobify-prod.herokuapp.com/api/v1/toolkit/auth/register

- POST /auth/register
- {name:'john',email:'john@gmail.com',password:'secret'}
- sends back the user object with token

###### Register USER - TESTING()

- POST /auth/testingRegister
- {name:'john',email:'john@gmail.com',password:'secret'}
- sends back the user object with token

###### Login USER

- POST /auth/login
- {email:'john@gmail.com',password:'secret'}
- sends back the user object with token

#### Login credentials

email : rv007@gmail.com
password : 123456

#### React Icons

[React Icons](https://react-icons.github.io/react-icons/)
npm install react-icons

###### Update USER

- PATCH /auth/updateUser
- { email:'john@gmail.com', name:'john', lastName:'smith', location:'my location' }
- authorization header : 'Bearer token'
- sends back the user object with token

#### Create Job Request

- POST /jobs
- { position:'position', company:'company', jobLocation:'location', jobType:'full-time', status:'pending' }
- authorization header : 'Bearer token'
- sends back the job object

#### GetAllJobs Request

- GET /jobs
- authorization header : 'Bearer token'
- returns {jobs:[],totalJobs:number, numOfPages:number }

#### Moment.js

[moment.js](https://momentjs.com/)
npm install moment

#### Delete Job Request

- DELETE /jobs/jobId
- authorization header : 'Bearer token'

#### Test User

- email : testUser@test.com
- password : secret
- read only!
- dummy data

#### Recharts Library

[Recharts](https://recharts.org)

npm install recharts

#### react-sticky-el

npm install react-sticky-el

# PROJECT ROAD MAP

## TECH TO USE

### DATABASE
- MongoDB

### LANGUAGE

#### Backend
- TypeScript/JavaScript
- Node.js

#### Frontend
- React.js
- Tailwind CSS

## API

### Endpoints

#### Seed Resources to the Database
**POST**: `<BaseUrl>/recommendia.api/createResource`

#### Get Resources from the Database
**GET**: `<BaseUrl>/recommendia.api/getResource?apiKey&projectName&projectLevel&language&type`

---

## Project Details

### Backend

#### Technologies:
- **Node.js**: Server-side JavaScript runtime environment.
- **TypeScript**: Superset of JavaScript with static type definitions.

#### Tools:
- **Express.js**: Web framework for Node.js.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.

#### Steps:
1. **Initialize Project**:
   - Set up a new Node.js project.
   - **Install necessary packages (Express, Mongoose, etc.)**.
     
        **Important Packages To Install**
     
        _Backend_
        - Typescript
        - mongoose

        _Frontend_
        - Axios
        - Tailwind CSS
        - All React necessary libraries (`react-dom`, `react-query`/`redux-tool-kit`)
   
2. **Configure TypeScript**:
   - Set up TypeScript configuration file (`tsconfig.json`).

3. **Database Connection**:
   - Establish a connection to MongoDB using Mongoose.

4. **API Endpoints**:
   - Implement `POST /createResource` to seed resources.
   - Implement `GET /getResource` to retrieve resources based on query parameters.

### Frontend

#### Technologies:
- **React.js**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling.

#### Tools:
- **Create React App with Vite**: CLI tool for setting up a modern web app by running one command.
- **Axios**: Promise-based HTTP client for the browser and Node.js.

#### Steps:
1. **Initialize Project**:
   - Set up a new React project using Create React App.
   - Install necessary packages (Axios, Tailwind CSS, etc.).

2. **Configure Tailwind CSS**:
   - Set up Tailwind CSS configuration and integrate it with the React project.

3. **Components**:
   - Create reusable components for the user interface.

4. **API Integration**:
   - Use Axios to make HTTP requests to the backend API.
   - Handle responses and update the UI accordingly.

### Deployment

#### Backend:
- **Hosting**: Render 

#### Frontend:
- **Hosting**: Vercel or Render Static Site Deployment

### Project Milestones

1. **Setup and Configuration**:
   - Backend and Frontend project initialization.
   - Configure TypeScript and Tailwind CSS.

2. **Database and API Development**:
   - Implement MongoDB connection.
   - Develop API endpoints for resource creation and retrieval.

3. **Frontend Development**:
   - Design and build UI components.
   - Integrate with the backend API.

4. **Testing**:
   - Write unit and integration tests for both backend and frontend.
   - Perform end-to-end testing.

5. **Deployment**:
   - Deploy backend and frontend applications.

6. **Monitoring and Maintenance**:
   - Implement logging and monitoring for the application.
   - Regularly update dependencies and fix bugs.

### Timeline

#### For the rest of May:
- Familiarize yourself with the listed tools above.
- Take crash courses on horizontal and vertical scalability.
- Refer to the Resources file if you stumble upon any resources.
- Finally, tackle each task as we move on.

#### From April:
- Project setup and initial configuration.
- Establish database connection and basic API endpoint structure.

#### Step 2:
- Develop and test API endpoints.
- Build frontend components and integrate them with the API.

#### Step 3:
- Comprehensive testing and bug fixing.
- Prepare for deployment.

#### Step 4:
- Deployment of the application.
- Set up monitoring and maintenance routines.

__NOTE__: Refer to the startup file to learn before forking the repo. Amend syntax only for me.

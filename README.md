# NumicubeAI - AI-Powered Intelligent Calculator  

NumicubeAI is an advanced, AI-powered calculator designed to simplify complex computations and offer dynamic visual insights. Inspired by cutting-edge technology like the new iPad, it combines traditional calculation features with AI-driven intelligence for an unparalleled user experience.  

## Features  
- **AI-Powered Calculations**: Solve complex mathematical problems and natural language queries using OpenAI API.  
- **Dynamic Graphing**: Visualize data and equations in real-time with Chart.js.  
- **Seamless Client-Server Communication**: Powered by Axios for fast, reliable interaction.  
- **Secure Data Storage**: Save and retrieve calculation history using MongoDB.  
- **Responsive Design**: Optimized for all devices with a sleek React-based interface.  

## Technologies Used  
- **Frontend**: React, CSS, Chart.js  
- **Backend**: Node.js, Express, OpenAI API  
- **Database**: MongoDB  
- **Others**: Axios, Multer  

## How It Works  
1. Users input queries (e.g., equations, natural language problems).  
2. The system categorizes inputs:  
   - Standard calculations are handled locally or on the backend.  
   - Complex or natural language queries are processed via the OpenAI API.  
3. Results are displayed instantly, with options for dynamic graphing and saving history.  

## Installation and Setup  

### Prerequisites  
- Node.js installed (v16+ recommended)  
- MongoDB database  
- OpenAI API key  

### Steps  
1. **Clone the Repository**:  
   ```bash  
   git clone <repository-url>  
   cd calc-ai
   ```
2. **Install Dependencies:**:  
   ```bash  
   npm install
   ```
3. **Set Environment Variables:**:  
   ```bash  
   OPENAI_API_KEY=<your-openai-api-key>  
    MONGO_URI=<your-mongodb-uri>  
    PORT=5000  
   ```
4. **Clone the Repository**:
   Create a .env file in the backend folder with the following keys: 
   ```bash  
   git clone <repository-url>  
   cd calc-ai
   ```
5. **Access the Application**:
   Open http://localhost:3000 in your browser.

### Contributing 
Contributions are welcome! Fork the repository, make changes, and submit a pull request.



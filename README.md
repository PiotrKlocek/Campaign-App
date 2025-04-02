# Campaign-App
This repository contains an application that enables sellers to create, edit, and delete individual campaigns for each product they intend to sell. The app provides a user-friendly interface for managing campaigns, allowing sellers to efficiently handle advertising details such as bids, keywords, and targeted locations.

## Technologies Used:

- **Backend**: Java with Spring Framework
- **Database**: H2 (in-memory database)
- **Frontend**: React

## How to Clone, Install, and Run the Application

### 1. Clone the Repository:

To clone this repository to your local machine, use the following Git command:
```bash
git clone https://github.com/PiotrKlocek/Campaign-App.git
cd Campaign-App
```
After cloning, initialize the submodules:
```bash
git submodule update --init --recursive
```

### 2. Backend - Java with Spring Framework

To run the backend, use the following commands:
```bash
cd backend
cd CampaignApplication
./mvnw spring-boot:run
```

### 3. React
To run the frontend, use the following commands:
1. Open new terminal
2. Use the folowing commands:
   ```bash
   cd Campaign-App
   cd frontend/
   cd my-react-app
   ```
3. Now install dependencies, use the following commands:
   ```bash
   npm install
   npm install react-icons
   npm install axios
   ```
4. Now you can run this application by typing the command:
   ```bash
   npm run dev
   ```
   

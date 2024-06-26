# The Project
This project is the typescript project of the [start2Impact](https://www.start2impact.it/)'s master.

# MOOVE - The Idea
The founder was born in a large city where to get around without a car you alternate between several different means of transport: tram, metro, bus. She has always dreamed of being able to make her bike materialize around the city on foot or when she didn't want to wait for the tram. With this idea, she created Moove.

# Requirements
- Define an IMezzo (Transport) interface to represent the means of transport (bikes, scooters, electric scooters) made available by Moove.
- Define an IUtente (User) interface to represent users of the service.
- Define an ICitta (City) interface to represent the cities in which Moove operates.
- Implements the Mezzo, Utente and Citta classes, which respectively implement the IMezzo, IUtente, and ICitta interfaces.

# How to Install and Run the Project

To get started with the project, follow these steps:

1. **Clone the Repository**: First, clone the repository to your local machine using the following command:
   
    git clone https://github.com/chiaracode1/project-typescript
    
2. **Navigate to the Project Directory**: After cloning the repository, navigate to the project directory using the command:

    cd project-typescript

3. **Install Dependencies**: Before running the project, you need to install its dependencies. To do this, run:

    npm install
  
4. **Compile TypeScript Code**: This project is written in TypeScript, so you need to compile the TypeScript code into JavaScript before running it. To compile, use:

    npx tsc

5. **Run the Project**: Once the TypeScript code has been successfully compiled, you can run the project using the command:

    node dist/index.js

   Ensure you have Node.js installed on your system to run the project successfully.

6. **Optional: Run Tests**: If there are tests available in the project, you can run them using:

    npm test

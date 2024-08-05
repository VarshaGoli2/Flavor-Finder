Flavor-Finder

A web application that allows users to generate and search for recipes based on ingredients using AI. This project is built with React for the frontend and Node.js 
with Express for the backend. It integrates with OpenAI’s GPT API to generate recipe ideas and instructions.

Features

  •	AI-Powered Recipe Generation: Generate unique recipes based on the ingredients you have using GPT-3.5 Turbo.
	•	Recipe Search: Search for existing recipes from a database.
  •	Recipe Details: View detailed instructions, ingredients, and preparation time for each recipe.
  •	Responsive Design: The application is optimized for both desktop and mobile devices.

Tech Stack

  •	Frontend:
	  React: A JavaScript library for building user interfaces.
	  CSS/Bootstrap: For styling and responsive design.
  •	Backend:
	  Node.js: JavaScript runtime for building server-side applications.
	  Express.js: A minimal and flexible Node.js web application framework.
  •	AI Integration:
	  OpenAI GPT-3.5 Turbo API: Used to generate recipes and instructions based on user-provided ingredients.
    You can also use GPT-4 API too

Installation
Prerequisites

  •	Node.js installed on your machine.
	•	OpenAI API key for accessing the GPT-3.5 Turbo API (you can create key -> https://platform.openai.com/api-keys)

 
Setup

  1.	Clone the repository:
       git clone https://github.com/YourUsername/recipe-generator.git
       cd recipe-generator
  2.	Install dependencies:
      npm install
	3.	Set up environment variables:
      Create a .env file in the root directory and add your API key:
      OPENAI_API_KEY=your_openai_api_key_here
	4.	Run the application:
      npm start


The application should now be running on http://localhost:3000.

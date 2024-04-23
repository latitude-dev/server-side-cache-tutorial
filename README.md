# Server-Side Cache Example with ExpressJS and React

This project demonstrates the implementation of a server-side cache to enhance the performance of a web application that interacts with an external API to fetch and display data. In this example, we've built a simple application using ExpressJS and React that fetches Pokémon data from an API and displays it using a React frontend.

## Introduction

Implementing a server-side cache can significantly reduce the load times and enhance the performance of applications dealing with large volumes of data or frequent data access. This example showcases a basic file-based caching system that stores JSON responses for Pokémon data fetched from the PokeAPI.

## Prerequisites

Before you start, ensure you have the following installed:
- Node.js
- npm (Node Package Manager)

## Installation

To set up the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/latitude-dev/server-side-cache-tutorial.git
   cd server-side-cache-tutorial
   ```

2. Install dependencies for the server:
   ```bash
   cd server
   npm install
   ```

3. Install dependencies for the client:
   ```bash
   cd ../client
   npm install
   ```

## Running the Application

To run the server and the client applications:

1. Start the server:
   ```bash
   cd server
   npm run start
   ```

2. In a new terminal, start the client:
   ```bash
   cd client
   npm run start
   ```

The server will be running on `http://localhost:4000`, and the client will be accessible through `http://localhost:3000`.

## Usage

Once both the server and client are running:
- Navigate to `http://localhost:3000` in your web browser.
- You can view Pokémon data by entering a Pokémon ID into the input field and clicking the search icon.

The application will display the Pokémon data fetched from the server, utilizing the server-side cache to speed up subsequent requests for the same data.

## Acknowledgements

- This project utilizes data from [PokeAPI](https://pokeapi.co/).

## Tutorial

For more information about this project, check out the [tutorial](https://github.com/latitude-dev/server-side-cache-tutorial).

# Gemini Clone

Gemini Clone is a web application that uses Google Generative AI to provide various functionalities such as suggesting places, summarizing concepts, brainstorming activities, and improving code readability.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/gemini-clone.git
   cd gemini-clone
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

3. Create a file in the root directory and add your Google Generative AI API key:
   ```env
   VITE_API_KEY=your_api_key_here
   ```

## Usage

1. Start the development server:

   ```sh
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

- `src/`: Contains the source code of the application.
  - `assets/`: Contains the static assets used in the application.
  - `components/`: Contains the React components.
    - `Main/`: Contains the main content of the application.
    - `Sidebar/`: Contains the sidebar component.
  - `config/`: Contains the configuration for the Google Generative AI.
  - `context/`: Contains the context provider for managing global state.
  - `index.css`: Contains the global CSS styles.
  - `main.jsx`: The entry point of the application.



# Programming Joker 🤡

This project is a simple web application that fetches programming jokes from an API and displays them on the web page.

## Features
- Fetches random programming jokes from the [JokeAPI](https://jokeapi.dev/).
- Displays jokes on the web page.
- Uses EJS for templating.

## Technologies Used

- **Frontend**: HTML, CSS
- **Backend**: Node.js, Express.js
- **Templating Engine**: EJS
- **HTTP Client**: Axios
- **Logging**: Morgan
- **Environment Variables**: Dotenv

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/programming-joker.git
   ```
2. Navigate to the project directory:
   ```
   cd programming-joker
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Create a `.env` file in the root directory and add your environment variables:
   ```
   PORT=3000
   ```

## Usage

1. Start the server:
   ```
   npm start
   ```
2. Open your browser and go to `http://localhost:3000`.

## Project Structure

```
programming-joker/
├── views/
│   └── index.ejs
├── .env
├── .gitignore
├── app.js
├── package.json
└── README.md
```

## Dependencies

- Express
- Axios
- Morgan
- EJS
- Dotenv

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

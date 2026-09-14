# Random Joke Generator

A fun web application that generates random jokes using an external API.

## Features

- Fetch random jokes from an external API
- Display jokes in a clean, user-friendly interface
- One-click joke generation
- Support for multiple joke categories
- Responsive design

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- External API: [JokeAPI](https://jokeapi.dev/) or [Official Joke API](https://official-joke-api.appspot.com/)

## Getting Started

1. Clone the repository
2. Open `index.html` in your web browser
3. Click the "Get Joke" button to fetch a random joke

## API Options

### JokeAPI
- Endpoint: `https://v2.jokeapi.dev/joke/Any`
- Returns: JSON with joke data
- Supports categories and filtering

### Official Joke API
- Endpoint: `https://official-joke-api.appspot.com/random_joke`
- Returns: Simple joke structure
- Lightweight and fast

## Project Structure

```
entonnoir-mail/
├── index.html          # Main HTML file
├── style.css          # Styling
├── script.js          # JavaScript logic
└── README.md          # This file
```

## Usage

Simply click the "Get Joke" button to load a new joke. The application will fetch from the API and display it on the page.

## License

MIT

# DareMate - Truth or Dare Game

DareMate is a web-based mobile-friendly app where users can create game rooms, customize question types, and play Truth or Dare with friends in real-time.

## Features

- Create and join game rooms with unique room codes
- Select from multiple question categories: Funny, Romantic, Strip, 18+, and Emotional
- Real-time turn system for Truth or Dare
- Chat with other players during the game
- Host controls for managing the game

## How to Run

1. Clone or download this repository
2. Open the `public` folder
3. Open `index.html` in your web browser

Alternatively, you can use a local development server:

```bash
# With Python 3
python -m http.server --directory public

# With Node.js and http-server
npx http-server public
```

## Technology Stack

- HTML5
- CSS3 with Tailwind CSS
- JavaScript (vanilla)
- LocalStorage as JSON database

## Game Flow

1. Create a room or join an existing one
2. Wait for players to join
3. Host starts the game
4. Players take turns choosing Truth or Dare
5. Complete challenges and continue playing

## Mobile Support

The game is fully responsive and works well on mobile devices. The chat interface is optimized for small screens.

## Data Storage

The game uses the browser's localStorage as a simple JSON database. Game data is stored locally in your browser and persists across sessions.

## License

This project is free to use for personal and educational purposes.

## Credits

Developed as a fun project to demonstrate front-end web development skills. 
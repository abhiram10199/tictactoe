# Tic-Tac-Toe Multiplayer Game

This project is a real-time multiplayer Tic-Tac-Toe game built using Flask for the backend, HTML/CSS/JavaScript for the frontend, and Socket.IO for real-time communication. The project is containerized using Docker and can be deployed on Vercel.

## Features
- Real-time multiplayer functionality using WebSockets (Socket.IO)
- Responsive user interface
- User authentication with nickname input
- Game state management on the server
- Dockerized setup for consistent development and deployment

## Technologies Used
- Flask
- Flask-SocketIO
- HTML/CSS
- JavaScript
- Docker
- Vercel

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe.git
   cd tic-tac-toe
   ```

2. Build the Docker image:
   ```bash
   docker build -t tic-tac-toe .
   ```

3. Run the Docker container:
   ```bash
   docker run -p 5000:5000 tic-tac-toe
   ```

4. Open your browser and navigate to `http://localhost:5000`.

## Deployment
1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy the project:
   ```bash
   vercel
   ```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with any improvements.

## License
This project is licensed under the MIT License.

---

Feel free to customize the description according to your needs and any additional details specific to your project.

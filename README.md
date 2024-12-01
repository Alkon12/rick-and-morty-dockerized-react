
# Rick and Morty React App (Dockerized)

A React project that consumes the Rick and Morty API, containerized with Docker for easy deployment. This project allows you to explore characters, episodes, and locations from the series.

---

## 🚀 Getting Started

Follow these steps to clone, build, and run the application in a Docker container.

### Prerequisites

- Make sure you have [Docker](https://www.docker.com/) installed on your machine.

---

## 📦 Cloning the Project

To get started, clone the repository:

```bash
git clone https://github.com/Alkon12/rick-and-morty-dockerized-react.git
cd rick-and-morty-dockerized-react
```

---

## 🛠️ Building the Docker Image

To build the Docker image for the application, run:

```bash
docker build -t react-app .
```

This command creates a Docker image named `react-app`.

---

## 🏃 Running the Docker Container

After building the image, you can run the application using:

```bash
docker run -p 3000:80 react-app
```

- The application will be accessible at `http://localhost:3000`.

---

## 📖 Project Structure

```
rick-and-morty-dockerized-react/
├── src/              # Source code for the React app
├── public/           # Public assets
├── Dockerfile        # Docker configuration
├── package.json      # Project dependencies
└── README.md         # Project documentation
```

---

## 🌟 Features

- **API Integration**: Fetches and displays data from the Rick and Morty API.
- **Dockerized**: Simple deployment using Docker.
- **React-Based**: A modern, interactive UI.

---

## 🛠️ Built With

- [React](https://reactjs.org/) - Frontend library.
- [Docker](https://www.docker.com/) - Containerization tool.
- [Rick and Morty API](https://rickandmortyapi.com/) - API for fetching show data.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

---

Made with ❤️ by [Alkon12](https://github.com/Alkon12).

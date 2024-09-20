# TravelTrackerMaps

**TravelTrackerMaps** is a web application designed to track and manage travel experiences, visualize trips on maps, and log detailed travel information such as visited cities and travel dates.

## Features

- Interactive maps powered by **Leaflet** and **React-Leaflet** to display visited cities.
- Date selection for trips with **React-Datepicker**.
- Routing with **React-Router-Dom** for smooth navigation between pages.
- Fake backend API using **JSON Server** for mock data.

## Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/raffimh/TravelTrackerMaps.git
cd TravelTrackerMaps
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Running the App

**Development Mode**
To run the application in development mode, execute:

```bash
npm run dev
```

The app will be available at `http://localhost:3000`.

**Fake API Server**
To run the mock API server (with a delay of 500ms):

```bash
npm run server
```

The API server will be available at `http://localhost:9000`.

## Technologies Used

- **React** for building the user interface.
- **Leaflet** for mapping and geolocation features.
- **Vite** for fast development and build setup.
- **JSON** Server for a mock API to simulate a real backend.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

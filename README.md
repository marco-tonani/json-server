# JSON Server with CORS and Sample Data
This project sets up a simple JSON server using `json-server` that serves data from a local JSON file. It also includes Cross-Origin Resource Sharing (CORS) support to allow requests from different origins.

## Features
- Serves data from `db/db.json`
- Supports CORS for cross-origin requests
- Easily configurable port
- Sample user data included

## Requirements
- Node.js (v14 or higher recommended)
- npm or yarn package manager

## Setup
1. Clone the repository or copy your files to your project directory.
2. Install dependencies: npm install or yarn install
3. Start the server: npm start or yarn start

The server will run on `http://localhost:3000` by default, or on the port specified in your environment variable `PORT`.

## Usage
- Access your API endpoints at `http://localhost:3000`
- Your data is stored in `db/db.json`

## Data
The `db.json` contains a large array of user objects, each with fields like `id`, `firstname`, `surname`, and `email`.
You can modify or extend this data as needed.

## Customization
- To change the port, set the `PORT` environment variable or modify the `PORT` constant in `server.js`.
- To add more data, update `db/db.json`.


## License
This project is for development and testing purposes. No license is specified.

## Notes
- Ensure `db/db.json` exists in the `db` directory.
- This setup is suitable for mock APIs and frontend testing.

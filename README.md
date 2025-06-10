# RADFish Cruise App

## Demo Cruise App

## Getting Started

### Prerequisites
- Node.js (recommended version 20 or higher)
- npm (comes with Node.js, recommended version 10 or higher)

### Installation

1. Clone this repository and navigate to the project directory
2. Install the required dependencies:

```bash
npm install
```

3. Set up the mock database by copying the original database file:

```bash
cp db.json.original db.json
```

### Running the Application

Start the development server:

```bash
npm start
```

This will start the application in development mode. Open your browser and navigate to the URL shown in the terminal (typically `http://localhost:3000`).

### Mock API

This project uses `json-server` to mock API endpoints. The endpoints are defined in the `db.json` file in the root of the project.

The project includes a starter db file `db.json.original`. To use the `json-server` make a copy of `db.json.original` **-->** `db.json`. As you work make edits to the `db` through the API the `db.json` file will be updated. To "reset", just copy the `db.json.original` over `db.json`.

To use the mock API run

```bash
npm run serve:json
```

This should produce the following output letting you know it is running.

```bash
JSON Server started on PORT :5000
Press CTRL-C to stop
Watching db.json...

♡⸜(˶˃ ᵕ ˂˶)⸝♡
```

# Kerem Page

A simple Hebrew page for the Kerem application.

## Running Locally

### Option 1: Using npm (Recommended)

```bash
npm install
npm start
```

### Option 2: Using npx directly

```bash
npx http-server -p 3000 -o
```

### Option 3: Using Python

```bash
python3 -m http.server 3000
```

### Option 4: Using Node.js

```bash
node -e "require('http').createServer((req, res) => { require('fs').readFile('index.html', (err, data) => { res.writeHead(200, {'Content-Type': 'text/html'}); res.end(data); }); }).listen(3000, () => console.log('Server running at http://localhost:3000/'));"
```

## Development Mode

For development with auto-reload (no caching):

```bash
npm run dev
```

## Access

After running any of the commands above, open your browser and go to:

- http://localhost:3000

The page will automatically open in your default browser when using the npm scripts.

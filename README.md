# Front-End Assignment

## Getting started

Install JSON Server 

```
npm install -g json-server
```

Start JSON Server

```bash
json-server --watch database.json
```

### Alternative port

You can start JSON Server on other ports with the `--port` flag:

```bash
$ json-server --watch database.json --port 3004
```

### Alternative way to start JSON Server

Go to `package.json` file and add:

```json
"scripts": {
  "json--server": "json-server --watch database.json"
}
```

You can start JSON Server:

```bash
npm run json--server
```

# Decompressor

Serverside middleware for CouchDB's `_bulk_docs` and `_all_docs` that uses lz compression to decompress requests.

## Installation

This app requires pm2. 

````
npm install -g pm2
````

Easier to install pm2 globally so it's in the path.

## Configuration

See ecosystem.json to configure ports and paths.

## Starting the app

````
npm start
````
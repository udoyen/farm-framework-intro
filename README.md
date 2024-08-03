# FARM-Intro

Introducing FARM - FastAPI, React &amp; MongoDB

## Running on Linux

export DEBUG_MODE=True
export DB_URL="mongodb+srv://<user>:<oassword>@<url>/farmstack?retryWrites=true&w=majority"
export DB_NAME="farmstack"

## Running on Windows

$env:DEBUG_MODE = "True"
$env:DB_URL="mongodb+srv://<user>:<oassword>@<url>/farmstack?retryWrites=true&w=majority"
$env:DB_NAME="farmstack"

## Running frontend on Windows and Linux

### On Linux

export NODE_OPTIONS=--openssl-legacy-provider

### on Windows

$env:NODE_OPTIONS=--openssl-legacy-provider

EQUEATION SOLVER
--

## What's this?

This is a web app that solves multivariate linear equations.

## For developer

Run Locally
```
# build
wasm-pack build --target web --out-name wasm --out-dir ./public/dist

# serve
miniserve ./public --index index.html --port 8089
```
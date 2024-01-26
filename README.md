[![Dockerfile Build and Push](https://github.com/NeckBeardPrince/simple-fibonacci-app/actions/workflows/build.yml/badge.svg)](https://github.com/NeckBeardPrince/simple-fibonacci-app/actions/workflows/build.yml)

# Fibonacci Web Server

Simple Fibonacci web server.

## How to use

If you want to template the helm chart.

- Go into the `chart/` directory.
- Make your changes to the `values.yaml`.
- Then run `helm template fibonacci ./ --values values.yaml > deploy.yaml`.
- `kubectl apply -f deploy.yaml --namespace <your_namespace>`.
- ???
- Profit

## Items I did not get to due to time

- I would've liked to have gotten Liveness, Readiness, and Startup Probes configured.
- I did not get to fully test ingress.

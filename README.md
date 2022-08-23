# Charts

Here are my [Helm](https://helm.sh) charts for various projects. Charts extend [this library chart](https://github.com/bjw-s/helm-charts/blob/13c511dc13e1f31c1ccfd81f67aafd369c86e1a0/charts/library/common) for common configuration.

## Installation

Add the chart repo and install a chart:

```sh
helm repo add brettinternet https://brettinternet.github.io/charts
helm install brettinternet/plex
```

## Develop

Install [go-task](https://github.com/go-task/task).

Setup and install dependencies:

```sh
task init
```

Create boilerplate for a new chart:

```sh
task charts:create -- new-chart
```

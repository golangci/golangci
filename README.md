# GolangCI

[GolangCI](https://golangci.com) is an automated golang codereview tool.

This repository contains the [central issue
tracker](https://github.com/golangci/golangci/issues) for the GolangCI project.

## Other repositories

GolangCI consists of sub-projects. The main ones are:

### golangci-api

[golangci-api](https://github.com/golangci/golangci-api) is the Golang server with REST API for [golangci-web](https://github.com/golangci/golangci-web).

### golangci-web

[golangci-web](https://github.com/golangci/golangci-web) is a frontend of [golangci.com](https://golangci.com). It uses React, Redux, Typescript, Webpack.

### golib

[golib](https://github.com/golangci/golib) is a small Golang HTTP framework. It's used in [golangci-api](https://github.com/golangci/golangci-api).

### golangci-worker

[golangci-worker](https://github.com/golangci/golangci-worker) is the queue worker. When user creates or updates GitHub pull request,
[golangci-api](https://github.com/golangci/golangci-api) gets webhook event about it. Then it send this event to distributed queue.
[golangci-worker](https://github.com/golangci/golangci-worker) handles such queue events and runs code analysis.

# Issues, Features
Create issue in [central issue tracker](https://github.com/golangci/golangci/issues).
Also you can create issue in one of subprojects repo if you know which one you need.


Contact email is [admin@golangci.com](mailto:admin@golangci.com).

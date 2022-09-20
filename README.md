# Geo-TraceRoute

#### 01. Description

Virtualize every trip in Cyber Space.

#### 02. Background

This project originated from Microsoft's 2022 Hackathon.

I also saw some similar projects on the Internet, however,  their effects are not good enough, like:

- https://geotraceroute.com/
- https://gsuite.tools/traceroute
- etc

There are also some projects on GitHub, but lack of engineering.

Therefore, we come up with a idea. Creating a open source project, which could visualize the router path on the map, to help people better understand the storied behind the Web.

#### 03. Architecture

The whole project is divided into two parts: FrontEnd and BackEnd.

The main function of the FrontEnd is to do the visualization, which also need to interact with users and BackEnd to get requirements and enough computed data.

The BackEnd is to get the trace routes, and turn them into a series of locations.

#### 04. Technology Stack

##### 4.1 FrontEnd 

- Cesium

##### 4.2 BackEnd

- Gin
- Go TraceRoute
- IP location API

##### 4.3 API Spec

- API documentation: https://documenter.getpostman.com/view/11549524/2s7YzyK6NB
- Mock Server: https://527091d1-395a-401a-a4e4-d5e6f5e17881.mock.pstmn.io/ip2locations?server=plantree.me

#### 05. Result



#### Reference

1. https://pkg.go.dev/github.com/aeden/traceroute#section-readme
2. https://api.iplocation.net/

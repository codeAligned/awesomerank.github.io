---
layout: default
title: Awesome Rank for veggiemonk/awesome-docker
---

<p align="center">
	This list is a copy of <a href="https://github.com/veggiemonk/awesome-docker">veggiemonk/awesome-docker</a> with ranks
</p>
---

# Awesome Docker [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★87749](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/veggiemonk/awesome-docker](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/veggiemonk/awesome-docker) [![Say Thanks](https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg)](https://saythanks.io/to/veggiemonk)

> A curated list of Docker resources and projects
Inspired by [@sindresorhus](https://github.com/sindresorhus)' [awesome][sindresorhus] and improved by these **[amazing contributors](https://github.com/veggiemonk/awesome-docker/graphs/contributors)**.

If you would like to contribute, please read [CONTRIBUTING.md][CONTRIBUTING] first.
It contains a lot of tips and guidelines to help keep things organized.
Just click [README.md][editREADME] to submit a [pull request][editREADME].
If this list is not complete, you can [contribute][editREADME] to make it so. Here is a great video tutorial to learn how to [contribute on Github](https://egghead.io/lessons/javascript-identifying-how-to-contribute-to-an-open-source-project-on-github)

***You can see the updates from [TWITTER](https://twitter.com/awesome_docker)***

> **Please**, help organize these resources so that they are _easy to find_ and _understand_ for new comers. See how to **[Contribute][CONTRIBUTING]** for tips!

#### *If you see a link here that is not (any longer) a good fit, you can fix it by submitting a [pull request][editREADME] to improve this file. Thank you!*

The creators and maintainers of this list do not receive any form of payment to accept a change made by any contributor. This page is not an official Docker product in any way. It is a list of links to projects and is maintained by volunteers. Everybody is welcome to contribute. The goal of this repo is to index open-source projects, not to advertise for profit.

All the links are monitored and tested with [awesome_bot ★489](https://github.com/dkhamsing/awesome_bot) made by [@dkhamsing](https://github.com/dkhamsing)

# Contents

<!-- TOC -->
- [What is Docker](#what-is-docker)
- [Where to start](#where-to-start)
- [Where to start (Windows)](#where-to-start-windows)
- [Projects](#projects)
  - [Container Operations](#container-operations)
    - [Container Composition](#container-composition)
    - [Deployment and Infrastructure](#deployment-and-infrastructure)
    - [Monitoring](#monitoring)
    - [Networking](#networking)
    - [Orchestration](#orchestration)
    - [PaaS](#paas)
    - [Reverse Proxy](#reverse-proxy)
    - [Security](#security)
    - [Service Discovery](#service-discovery)
    - [Volume Management / Data](#volume-management--data)
    - [User Interface](#user-interface)
      - [Desktop](#desktop)
      - [Terminal](#terminal)
      - [Web](#web)
  - [Docker Images](#docker-images)
    - [Base Tools](#base-tools)
    - [Builder](#builder)
    - [Dockerfile](#dockerfile)
    - [Linter](#linter)
    - [Metadata](#metadata)
    - [Registry](#registry)
  - [Development with Docker](#development-with-docker)
    - [API Client](#api-client)
    - [CI/CD](#cicd)
    - [Development Environment](#development-environment)
    - [Garbage Collection](#garbage-collection)
    - [Serverless](#serverless)
    - [Testing](#testing)
    - [Wrappers](#wrappers)
  - [Services based on Docker (:heavy_dollar_sign:)](#services-based-on-docker-heavy_dollar_sign)
    - [CI Services](#ci-services)
    - [CaaS](#caas)
    - [Monitoring Services](#monitoring-services)
- [Useful Resources](#useful-resources)
  - [Awesome Lists](#awesome-lists)
  - [Good Tips](#good-tips)
  - [Raspberry Pi & ARM](#raspberry-pi--arm)
  - [Security](#security-1)
  - [Videos](#videos)
- [Communities and Meetups](#communities-and-meetups)
  - [Brazilian](#brazilian)
  - [Chinese](#chinese)
  - [English](#english)
  - [Russian](#russian)

<!-- /TOC -->

# Legend

- Abandoned :skull:
- Beta :construction:
- Monetized :heavy_dollar_sign:

# What is Docker

> Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. Consisting of Docker Engine, a portable, lightweight runtime and packaging tool, and Docker Hub, a cloud service for sharing applications and automating workflows, Docker enables apps to be quickly assembled from components and eliminates the friction between development, QA, and production environments. As a result, IT can ship faster and run the same app, unchanged, on laptops, data center VMs, and any cloud.

_Source:_ [What is Docker](https://www.docker.com/what-docker)

# Where to start

- [Basics – Docker, Containers, Hypervisors, CoreOS](http://etherealmind.com/basics-docker-containers-hypervisors-coreos/)
- [Dive Into Docker: From "What is Docker?" to "Hello World"](https://www.youtube.com/watch?v=XeSD17YRijk&list=PL-v3vdeWVEsXT-u0JDQZnM90feU3NE3v8) (60:25) by [@nickjanetakis][nickjanetakis]
- [Docker Curriculum](https://docker-curriculum.com): A comprehensive tutorial for getting started with Docker. Teaches how to use Docker and deploy dockerized apps on AWS with Elastic Beanstalk and Elastic Container Service.
- [Docker Documentation](https://docs.docker.com/)
- [Docker for all - Developers, Testers, DevOps, Product Owners + Videos ★63 ⏳1Y](https://github.com/machzqcq/docker-for-all) Docker Training Videos for all
- [Docker Jumpstart ★2746 ⏳2Y](https://github.com/odewahn/docker-jumpstart): a quick introduction
- [Docker Toolbox](https://docs.docker.com/toolbox/overview/) :skull: - Quick setup and launch of a Docker environment on older Mac (10.10 and below) and Windows (8.1 and below) systems. On newer systems it's recommended to use the [Docker for Mac][docker-for-mac] or [Docker for Windows][docker-for-windows].
- [Docker Training](https://training.docker.com/) - Includes a free self-paced hands-on tutorial (free registration required or sign-in with DockerHub ID)
- [Katacoda](https://www.katacoda.com/): Learn Docker using Interactive Browser-Based Labs
- [Learn Docker ★67 ⏳2Y](https://github.com/dwyl/learn-docker) Full environment set up, screenshots, step-by-step tutorial and more resources (video, articles, cheat sheets) by [@dwyl](https://github.com/dwyl)
- [Play With Docker](https://training.play-with-docker.com/) - PWD is a great way to get started with Docker from beginner to advanced users. Docker runs directly in your browser.
- [Play With Moby](http://play-with-moby.com/) - PWM is a web based Moby playground which allows you to try different components of the platform in seconds. It gives you the experience of having a free Alpine Linux Virtual Machine in the cloud where you can build and run Moby projects and even create clusters to experiment.
- [Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/) The landscape for container technologies is larger than just docker. Without a good handle on the terminology, It can be difficult to grasp the key differences between docker and (pick your favorites, CRI-O, rkt, lxc/lxd) or understand what the Open Container Initiative is doing to standardize container technology.

**Cheatsheets** by

- [@eon01 ★2454](https://github.com/eon01/DockerCheatSheet)
- [@dimonomid][docker-quick-ref] (PDF)
- [@JensPiegsa](http://docker.jens-piegsa.com)
- [@wsargent][docker-cheat-sheet]

# Where to start (Windows)

- [A Comparative Study of Docker Engine on Windows Server vs Linux Platform](http://collabnix.com/a-comparative-study-of-docker-engine-on-windows-server-vs-linux-platform/) Comparing the feature sets and implementations of Docker on Windows and Linux
- [Build And Run Your First Docker Windows Server Container](https://blog.docker.com/2016/09/build-your-first-docker-windows-server-container/) Walkthrough installing Docker on Windows 10, building a Docker image and running a Windows container
- [Docker on Windows behind a firewall](https://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/) by [@kaitoedter](https://twitter.com/kaitoedter)
- [Docker Reference Architecture: Modernizing Traditional .NET Framework Applications](https://success.docker.com/article/modernizing-traditional-dot-net-applications) - You will learn to identify the types of .NET Framework applications that are good candidates for containerization, the "lift-and-shift" approach to containerization.
- [Docker with Microsoft SQL 2016 + ASP.NET](https://blog.alexellis.io/docker-does-sql2016-aspnet/) Demonstration running ASP.NET and SQL Server workloads in Docker
- [Exploring ASP.NET Core with Docker in both Linux and Windows Containers](https://www.hanselman.com/blog/ExploringASPNETCoreWithDockerInBothLinuxAndWindowsContainers.aspx) Running ASP.NET Core apps in Linux and Windows containers, using [Docker for Windows][docker-for-windows]
- [Running a Legacy ASP.NET App in a Windows Container](https://blog.sixeyed.com/dockerizing-nerd-dinner-part-1-running-a-legacy-asp-net-app-in-a-windows-container/) Steps for Dockerizing a legacy ASP.NET app and runnning as a Windows container
- [Windows Containers and Docker: The 101](https://www.youtube.com/watch?v=N7SG2wEyQtM) :movie_camera: - A 20-minute overview, using Docker to run  PowerShell, ASP.NET Core and ASP.NET apps
- [Windows Containers Quick Start](https://docs.microsoft.com/en-us/virtualization/windowscontainers/about/index) Overview of Windows containers, drilling down to Quick Starts for Windows 10 and Windows Server 2016

----

# Projects

- Moby      = open source development
- Docker CE = free product release based on Moby
- Docker EE = commercial product release based on Docker CE.

> Docker EE is on the same code base as Docker CE, so also built from Moby, with commercial components added, such as "docker data center / universal control plane"

- [Moby ★49330](https://github.com/moby/moby)
- [Docker Images](https://hub.docker.com)
- [Docker Compose ★12941](https://github.com/docker/compose) (Define and run multi-container applications with Docker)
- [Docker Machine ★4711](https://github.com/docker/machine) (Machine management for a container-centric world)
- [Docker Registry][distribution] (The Docker toolset to pack, ship, store, and deliver content)
- [Docker Swarm ★5141](https://github.com/docker/swarm) (Swarm: a Docker-native clustering system)

## Container Operations

### Container Composition

- [bocker ★69 ⏳1Y](https://github.com/icy/bocker) (2) - Write Dockerfile completely in Bash. Extensible and simple. --> Reusable by [@icy](https://github.com/icy)
- [bocker ★5011](https://github.com/p8952/bocker) (1) :skull: - Docker implemented in 100 lines of bash by [p8952](https://github.com/p8952)
- [box ★220](https://github.com/box-builder/box) - Build Dockerfile images with a mruby DSL, includes flattening and layer manipulation
- [Capitan ★16 ⏳1Y](https://github.com/byrnedo/capitan) - Composable docker orchestration with added scripting support by [@byrnedo](https://github.com/byrnedo).
- [compose_plantuml](hhttps://github.com/funkwerk/compose_plantuml) -  Generate Plantuml graphs from docker-compose files by [@funkwerk](https://github.com/funkwerk)
- [Composerize ★132](https://github.com/magicmark/composerize) - Convert docker run commands into docker-compose files
- [crowdr ★75 ⏳2Y](https://github.com/polonskiy/crowdr) - Tool for managing multiple Docker containers (`docker-compose` alternative) by [@polonskiy](https://github.com/polonskiy/)
- [docker-compose-graphviz ★31 ⏳2Y](https://github.com/abesto/docker-compose-graphviz) - Turn a docker-compose.yml files into Graphviz .dot files by [@abesto](https://github.com/abesto)
- [draw-compose ★47 ⏳1Y](https://github.com/Alexis-benoist/draw-compose) - Utility to draw a schema of a docker compose by [@Alexis-benoist](https://github.com/Alexis-benoist)
- [elsy ★38](https://github.com/cisco/elsy) - An opinionated, multi-language, build tool based on Docker and Docker Compose
- [habitus ★826](https://github.com/cloud66/habitus) - A Build Flow Tool for Docker by [@cloud66](https://github.com/cloud66)
- [Maestro ★615 ⏳4Y](https://github.com/toscanini/maestro) :skull: - Maestro provides the ability to easily launch, orchestrate and manage mulitiple Docker containers as single unit by [@tascanini](https://github.com/toscanini)
- [percheron][percheron] :skull: - Organise your Docker containers with muscle and intelligence by [@ashmckenzie](https://github.com/ashmckenzie)
- [plash ★24](https://github.com/ihucos/plash) - A container run and build engine - runs inside docker.
- [rocker-compose ★419](https://github.com/grammarly/rocker-compose) - Docker composition tool with idempotency features for deploying apps composed of multiple containers. By [@grammarly](grammarly)
- [rocker ★1269](https://github.com/grammarly/rocker) - Extended Dockerfile builder. Supports multiple FROMs, MOUNTS, templates, etc. by [grammarly](grammarly).
- [Stacker ★48 ⏳1Y](https://github.com/stacker/stacker-cli) - Docker Compose Templates. Stacker provides an abstraction layer over Docker Compose and a better DX (developer experience).
- [Zodiac ★177 ⏳2Y](https://github.com/CenturyLinkLabs/zodiac) :skull: - A lightweight tool for easy deployment and rollback of dockerized applications. By [@CenturyLinkLabs][CenturyLinkLabs]

### Deployment and Infrastructure

- [blackfish](https://gitlab.com/blackfish/blackfish) - a CoreOS VM to build swarm clusters for Dev & Production by [@DataMC](http://datamc.io/)
- [Centurion ★1706](https://github.com/newrelic/centurion) - Centurion is a mass deployment tool for Docker fleets. It takes containers from a Docker registry and runs them on a fleet of hosts with the correct environment variables, host volume mappings, and port mappings. By [@newrelic](https://github.com/newrelic)
- [Clocker ★427](https://github.com/brooklyncentral/clocker) - Clocker creates and manages a Docker cloud infrastructure. Clocker supports single-click deployments and runtime management of multi-node applications that run as containers distributed across multiple hosts, on both Docker and Marathon. It leverages [Calico][calico] and [Weave][weave] for networking and [Brooklyn][brooklyn] for application blueprints. By [@brooklyncentral](https://github.com/brooklyncentral)
- [Conduit ★99 ⏳1Y](https://github.com/ehazlett/conduit) - Experimental deployment system for Docker by [@ehazlett](https://github.com/ehazlett)
- [depcon ★86](https://github.com/ContainX/depcon) - Depcon is written in Go and allows you to easily deploy Docker containers to Apache Mesos/Marathon, Amazon ECS and Kubernetes.  By [@ContainX][ContainX]
- [deploy ★45 ⏳1Y](https://github.com/ttiny/deploy) :skull: - Git and Docker deployment tool. A middle ground between simple Docker composition tools and full blown cluster orchestration by [@ttiny](https://github.com/ttiny)
- [dockit ★103 ⏳3Y](https://github.com/humblec/dockit) :skull: - Do docker actions and Deploy gluster containers! By [@humblec](https://github.com/humblec)
- [gitkube ★1843](https://github.com/hasura/gitkube) - Gitkube is a tool for building and deploying docker images on Kubernetes using `git push`. By [@Hasura](https://github.com/hasura/).
- [Grafeas ★545](https://github.com/Grafeas/Grafeas) - A common API for metadata about containers, from image and build details to security vulnerabilities. By [Grafeas](https://github.com/Grafeas)
- [Longshoreman ★426 ⏳3Y](https://github.com/longshoreman/longshoreman) :skull: - Longshoreman automates application deployment using Docker. Just create a Docker repository (or use a service), configure the cluster using AWS or Digital Ocean (or whatever you like) and deploy applications using a Heroku-like CLI tool. By [longshoreman](https://github.com/longshoreman)

### Monitoring

- [Axibase Collector](https://github.com/axibase/atsd-use-cases/tree/master/integrations/docker) - Axibase Collector streams performance counters, configuration changes and lifecycle events from the Docker engine(s) into Axibase Time Series Database for roll-up dashboards and integration with upstream monitoring systems.
- [cAdvisor ★7473](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers. Created by [@Google][google]
- [Docker-Alertd ★66](https://github.com/deltaskelta/docker-alertd) - Monitor and send alerts based on docker container resource usage/statistics
- [Docker-Flow-Monitor ★36](https://github.com/docker-flow/docker-flow-monitor) - Reconfigures Prometheus when a new service is updated or deployed automatically by [@vfarcic][vfarcic]
- [Docker-Fluentd][fluentd] - Docker container to Log Other Containers' Logs. One can aggregate the logs of Docker containers running on the same host using Fluentd by [@kiyoto][kiyoto]
- [Dockerana ★192 ⏳3Y](https://github.com/dockerana/dockerana) :skull: - packaged version of Graphite and Grafana, specifically targeted at metrics from Docker.
- [Dynatrace](https://www.dynatrace.com/technologies/cloud-and-microservices/docker-monitoring/) :heavy_dollar_sign: - Monitor containerized applications without installing agents or modifying your Run commands
- [Glances ★10096](https://github.com/nicolargo/glances) - A cross-platform curses-based system monitoring tool written in Python by [@nicolargo](https://github.com/nicolargo)
- [Grafana Docker Dashboard Template](https://grafana.com/dashboards/179) - A template for your Docker, Grafana and Prometheus stack [@vegasbrianc][vegasbrianc]
- [InfluxDB, cAdvisor, Grafana ★365](https://github.com/vegasbrianc/docker-monitoring) - InfluxDB Time series DB in combination with Grafana and cAdvisor by [@vegasbrianc][vegasbrianc]
- [LogJam ★121 ⏳2Y](https://github.com/gocardless/logjam) - Logjam is a log forwarder designed to listen on a local port, receive log entries over UDP, and forward these messages on to a log collection server (such as logstash) by [@gocardless](https://github.com/gocardless)
- [Logsene for Docker][spm] Monitoring of Metrics, Events and Logs implemented in Node.js. Integrated [logagent-js ★201](https://github.com/sematext/logagent-js) to detect and parse various log formats. [@sematext][sematext]
- [Logspout ★3244](https://github.com/gliderlabs/logspout) - Log routing for Docker container logs by [@gliderlabs][gliderlabs]
- [Out-of-the-box Host/Container Monitoring/Logging/Alerting Stack ★288](https://github.com/uschtwill/docker_monitoring_logging_alerting) - Docker host and container monitoring, logging and alerting out of the box using cAdvisor, Prometheus, Grafana for monitoring, Elasticsearch, Kibana and Logstash for logging and elastalert and Alertmanager for alerting. Set up in 5 Minutes. Secure mode for production use with built-in [Automated Nginx Reverse Proxy (jwilder's)][nginxproxy].
- [Zabbix Docker module ★715](https://github.com/monitoringartist/Zabbix-Docker-Monitoring) - Zabbix module that provides discovery of running containers, CPU/memory/blk IO/net container metrics. Systemd Docker and LXC execution driver is also supported. It's a dynamically linked shared object library, so its performance is (~10x) better, than any script solution.
- [Zabbix Docker ★34](https://github.com/gomex/docker-zabbix) - Monitor containers automatically using zabbix LLD feature.

### Networking

- [Calico-Docker][calico] - Calico is a pure layer 3 virtual network that allows containers over multiple docker-hosts to talk to each other.
- [Flannel ★3129](https://github.com/coreos/flannel) - Flannel is a virtual network that gives a subnet to each host for use with container runtimes. By [@coreos][coreos]
- [netshoot ★347](https://github.com/nicolaka/netshoot) - The netshoot container has a powerful set of networking tools to help troubleshoot Docker networking issues by [@nicolaka](https://github.com/nicolaka)
- [Weave][weave] (The Docker network) - Weave creates a virtual network that connects Docker containers deployed across multiple hosts.

### Orchestration

- [athena ★67 ⏳1Y](https://github.com/athena-oss/athena) - An automation platform with a plugin architecture that allows you to easily create and share services.
- [blimp ★17 ⏳3Y](https://github.com/tubesandlube/blimp) :skull: - Uses Docker Machine to easily move a container from one Docker host to another, show containers running against all of your hosts, replicate a container across multiple hosts and more by [@defermat](https://github.com/defermat) and [@schvin](https://github.com/schvin)
- [CloudSlang ★181](https://github.com/CloudSlang/cloud-slang) - CloudSlang is a workflow engine to create Docker process automation
- [clusterdock ★20](https://github.com/clusterdock/clusterdock) - Docker container orchestration to enable the testing of long-running cluster deployments
- [ContainerShip ★222](https://github.com/containership/containership) A simple container management platform
- [Crane ★714](https://github.com/Dataman-Cloud/crane) - Control plane based on docker built-in swarm [@Dataman-Cloud](https://github.com/Dataman-Cloud)
- [Docker Flow Swarm Listener ★91](https://github.com/vfarcic/docker-flow-swarm-listener) - Docker Flow Swarm Listener project is to listen to Docker Swarm events and send requests when a change occurs. By [@vfarcic][vfarcic]
- [gantryd ★274 ⏳1Y](https://github.com/DevTable/gantryd) :skull: - A framework for easy management of docker-based components across machines by [@DevTable](https://github.com/DevTable)
- [Haven ★161](https://github.com/codeabovelab/haven-platform) - Haven is a simplified container management platform that integrates container, application, cluster, image, and registry managements. By [@codeabovelab](https://github.com/codeabovelab)
- [Helios ★1923](https://github.com/spotify/helios) - A simple platform for deploying and managing containers across an entire fleet of servers by [@spotify](spotify)
- [Kontena ★1355](https://github.com/kontena/kontena) - Application Containers for Masses [website](https://www.kontena.io/)
- [Kubernetes ★38089](https://github.com/kubernetes/kubernetes) - Open source orchestration system for Docker containers by Google
- [ManageIQ ★662](https://github.com/ManageIQ/manageiq) - Discover, optimize and control your hybrid IT. By [ManageIQ](https://github.com/ManageIQ)
- [Mantl ★3028](https://github.com/mantl/mantl) - Mantl is a modern platform for rapidly deploying globally distributed services
- [Marathon ★3674](https://github.com/mesosphere/marathon) - Marathon is a private PaaS built on Mesos. It automatically handles hardware or software failures and ensures that an app is "always on"
- [Mesos ★3734](https://github.com/apache/mesos) - Resource/Job scheduler for containers, VM's and physical hosts [@apache](https://mesos.apache.org/)
- [Mesosphere DC/OS](https://mesosphere.com/product/) :heavy_dollar_sign: - Integrated platform for data and containers built on Apache Mesos by [@mesosphere](https://mesosphere.com)
- [Nebula](https://github.com/nebula-orchestrator) - A Docker orchestration tool designed to manage massive scale distributed clusters.
- [Nomad ★3579](https://github.com/hashicorp/nomad) - Easily deploy applications at any scale. A Distributed, Highly Available, Datacenter-Aware Scheduler by [@hashicorp][hashicorp]
- [Panamax ★1454 ⏳2Y](https://github.com/CenturyLinkLabs/panamax-ui) :skull: - An open-source project that makes deploying complex containerized apps as easy as Drag-and-Drop by [@CenturyLinkLabs][CenturyLinkLabs].
- [Rancher ★8709](https://github.com/rancher/rancher) - An open source project that provides a complete platform for operating Docker in production by [@rancher][rancher].
- [Swarmpit ★474](https://github.com/swarmpit/swarmpit) - Lightweight Docker Swarm orchestration. Swarmpit provides clean way to manage your Docker Swarm cluster with various handful features such Service management, smart search, shared access and private registries.

### PaaS

- [Atlantis ★375 ⏳2Y](https://github.com/ooyala/atlantis) :skull: - Atlantis is an Open Source PaaS for HTTP applications built on Docker and written in Go
- [CaptainDuckDuck ★3269](https://github.com/githubsaturn/captainduckduck) - Open source Heroku-like platform with a one-liner installer and a GUI for managing apps - with serveral one-click databases and apps.
- [Convox Rack ★1679](https://github.com/convox/rack) - Convox Rack is open source PaaS built on top of expert infrastructure automation and devops best practices.
- [Dcw ★5 ⏳1Y](https://github.com/pbertera/dcw) - Docker-compose SSH wrapper: a very poor man PaaS, exposing the docker-compose and custom-container commands defined in container labels.
- [Dokku][dokku] - Docker powered mini-Heroku that helps you build and manage the lifecycle of applications (originally by [@progrium][progrium])
- [Empire ★2411](https://github.com/remind101/empire) - A PaaS built on top of Amazon EC2 Container Service (ECS)
- [Flynn ★6714](https://github.com/flynn/flynn) - A next generation open source platform as a service
- [Jelastic](https://jelastic.com/) :heavy_dollar_sign: - An advanced PaaS for developers that simplifies clustering and complex cloud deployments with powerful web UI and usage-only pricing
- [Nanobox ★1241](https://github.com/nanobox-io/nanobox) :heavy_dollar_sign: - An application development platform that creates local environments that can then be deployed and scaled in the cloud.
- [OpenShift][openshift] - An open source PaaS built on [Kubernetes][kubernetes] and optimized for Dockerized app development and deployment by [Red Hat](https://www.redhat.com/)
- [Tsuru ★2789](https://github.com/tsuru/tsuru) - Tsuru is an extensible and open source Platform as a Service software
- [Workflow ★1139](https://github.com/deis/workflow) - The open source PaaS for Kubernetes by [Deis](https://github.com/deis). Formerly Deis v1.
- [ZEIT Now ★2118](https://github.com/zeit/now-cli) - A universal serverless single-command deploy for Node.js applications or any application with a Dockerfile.

### Reverse Proxy

- [docker-flow-proxy ★616](https://github.com/vfarcic/docker-flow-proxy) - Reconfigures proxy every time a new service is deployed, or when a service is scaled. By [@vfarcic][vfarcic]
- [docker-proxy ★190](https://github.com/silarsis/docker-proxy) :skull: - Transparent proxy for docker containers, run in a docker container. By [@silarsis](https://github.com/silarsis)
- [fabio ★4798](https://github.com/fabiolb/fabio) - A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by consul. By [@magiconair](https://github.com/magiconair) (Frank Schroeder)
- [h2o-proxy ★37 ⏳2Y](https://github.com/zchee/h2o-proxy) :skull: - Automated H2O reverse proxy for Docker containers. An alternative to [jwilder/nginx-proxy][nginxproxy] by [@zchee](https://github.com/zchee)
- [Let's Encrypt Nginx-proxy Companion ★2983](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion) - A lightweight companion container for the nginx-proxy. It allow the creation/renewal of Let's Encrypt certificates automatically. By [@JrCs](https://github.com/JrCs)
- [muguet ★154 ⏳1Y](https://github.com/mattallty/muguet) - DNS Server & Reverse proxy for Docker environments. By [@mattallty](https://github.com/mattallty)
- [nginx-proxy][nginxproxy] - Automated nginx proxy for Docker containers using docker-gen by [@jwilder][jwilder]
- [Swarm Ingress Router ★172 ⏳1Y](https://github.com/tpbowden/swarm-ingress-router) - Route DNS names to Swarm services based on labels. By [@tpbowden](https://github.com/tpbowden/)
- [Swarm Router ★15](https://github.com/flavioaiello/swarm-router) - A «zero config» service name based router for docker swarm mode with a fresh and more secure approach. By [@flavioaiello](https://twitter.com/flavioaiello)
- [Træfɪk ★16029](https://github.com/containous/traefik) - Automated reverse proxy and load-balancer for Docker, Mesos, Consul, Etcd... By [@EmileVauge](https://github.com/emilevauge)

### Security

- [Anchor Cloud](https://anchore.com/cloud/) :heavy_dollar_sign: - Hosted version of Anchor Engine by [@Anchor][anchore]
- [Anchor Engine ★288](https://github.com/anchore/anchore) - Analyze images for CVE vulnerabilities and against custom security policies by [@Anchor][anchore]
- [Aqua Security](https://www.aquasec.com) :heavy_dollar_sign: - Securing container-based applications from Dev to Production on any platform
- [bane ★564](https://github.com/genuinetools/bane) - AppArmor profile generator for Docker containers by [@genuinetools][genuinetools]
- [CIS Docker Benchmark ★112](https://github.com/dev-sec/cis-docker-benchmark) - This [InSpec][inspec] compliance profile implement the CIS Docker 1.12.0 Benchmark in an automated way to provide security best-practice tests around Docker daemon and containers in a production environment. By [@dev-sec](https://github.com/dev-sec)
- [Clair ★3687](https://github.com/coreos/clair) - Clair is an open source project for the static analysis of vulnerabilities in appc and docker containers. By [@coreos][CoreOS]
- [Dagda ★371](https://github.com/eliasgranderubio/dagda) - Dagda is a tool to perform static analysis of known vulnerabilities, trojans, viruses, malware & other malicious threats in docker images/containers and to monitor the docker daemon and running docker containers for detecting anomalous activities. By [@eliasgranderubio](https://github.com/eliasgranderubio)
- [docker-bench-security ★3777](https://github.com/docker/docker-bench-security) - script that checks for dozens of common best-practices around deploying Docker containers in production. By [@docker][docker]
- [docker-explorer ★163](https://github.com/google/docker-explorer) - A tool to help forensicate offline docker acquisitions by [@Google][google]
- [notary ★1392](https://github.com/theupdateframework/notary) - a server and a client for running and interacting with trusted collections. By [@TUF](https://github.com/theupdateframework)
- [oscap-docker ★322](https://github.com/OpenSCAP/openscap) - OpenSCAP provides oscap-docker tool which is used to scan Docker containers and images. By RedHat
- [Sysdig Falco ★809](https://github.com/draios/falco) - Sysdig Falco is an open source container security monitor. It can monitor application, container, host, and network activity and alert on unauthorized activity.
- [Sysdig Secure](https://sysdig.com/product/secure/) :heavy_dollar_sign: - Sysdig Secure addresses run-time security through behavioral monitoring and defense, and provides deep forensics based on open source Sysdig for incident response.
- [Twistlock](https://www.twistlock.com/) :heavy_dollar_sign: - Twistlock Security Suite detects vulnerabilities, hardens container images, and enforces security policies across the lifecycle of applications.

### Service Discovery

- [Docker Grand Ambassador ★193 ⏳3Y](https://github.com/cpuguy83/docker-grand-ambassador) :skull: - This is a fully dynamic docker link ambassador. + [Article](https://docs.docker.com/engine/admin/ambassador_pattern_linking/) by [@cpuguy83][cpuguy83]
- [docker-consul ★1023](https://github.com/gliderlabs/docker-consul) by [@progrium][progrium]
- [etcd ★18952](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery by [@coreOS][coreos]
- [istio ★8548](https://github.com/istio/istio) - An open platform to connect, manage, and secure microservices by [@IstioMesh](istio)
- [proxy ★49 ⏳3Y](https://github.com/factorish/proxy) :skull: - lightweight nginx based load balancer self using service discovery provided by registrator. by [@factorish](https://github.com/factorish)
- [registrator ★3648](https://github.com/gliderlabs/registrator) - Service registry bridge for Docker by [@gliderlabs][gliderlabs] and [@progrium][progrium]

### Volume Management / Data

- [Blockbridge ★72](https://github.com/blockbridge/blockbridge-docker-volume) - The Blockbridge plugin is a volume plugin that provides access to an extensible set of container-based persistent storage options. It supports single and multi-host Docker environments with features that include tenant isolation, automated provisioning, encryption, secure deletion, snapshots and QoS. By [@blockbridge][blockbridge]
- [Convoy ★990 ⏳1Y](https://github.com/rancher/convoy) - an open-source Docker volume driver that can snapshot, backup and restore Docker volumes anywhere. By [@rancher][rancher]
- [Docker Machine NFS ★726](https://github.com/adlogix/docker-machine-nfs) Activates NFS for an existing boot2docker box created through Docker Machine on OS X.
- [Docker Unison ★164 ⏳1Y](https://github.com/leighmcculloch/docker-unison) A docker volume container using Unison for fast two-way folder sync. Created as an alternative to slow boot2docker volumes on OS X. By [@leighmcculloch](https://github.com/leighmcculloch)
- [Local Persist ★367](https://github.com/CWSpear/local-persist) Specify a mountpoint for your local volumes (created via `docker volume create`) so that files will always persist and so you can mount to different directories in different containers.
- [Minio ★30](https://github.com/jelastic-jps/minio) - S3 compatible object storage server in Docker containers
- [Netshare ★670](https://github.com/ContainX/docker-volume-netshare) Docker NFS, AWS EFS, Ceph & Samba/CIFS Volume Plugin. By [@ContainX][ContainX]
- [portworx](https://portworx.com) :heavy_dollar_sign: - Decentralized storage solution for persistent, shared and replicated volumes.
- [quobyte](https://www.quobyte.com/) :heavy_dollar_sign: - fully fault-tolerant distributed file system with a docker volume driver
- [REX-Ray ★1222](https://github.com/rexray/rexray) provides a vendor agnostic storage orchestration engine. The primary design goal is to provide persistent storage for Docker, Kubernetes, and Mesos. By[@thecodeteam](https://github.com/thecodeteam) (DELL Technologies)

### User Interface

#### Desktop

Native desktop applications for managing and montoring docker hosts and clusters

- [Captain](https://getcaptain.co/) - Manage containers from the MacOSX menu bar by [@RickWong](https://github.com/rickwong)
- [Dockeron ★332](https://github.com/dockeron/dockeron) - A project built on Electron + Vue.js for Docker on desktop. [@fluency03](https://github.com/fluency03)
- [DockStation ★423](https://github.com/DockStation/dockstation) - A developer centric UI to configure, monitor, and manage services and containers [@dock_station](https://twitter.com/dock_station)
- [Lifeboat ★82](https://github.com/jplhomer/lifeboat) - An easy way to launch Docker projects with a graphical interface on your Mac. [@jplhomer](https://github.com/jplhomer)

#### Terminal

- [captain ★48](https://github.com/jenssegers/captain) - Easily start and stop docker compose projects from any directory. By [@jenssegers](https://github.com/jenssegers)
- [ctop (1) ★373](https://github.com/yadutaf/ctop) - A command line / text based Linux Containers monitoring tool that works just like you expect (Python) by [@yadutaf](https://github.com/yadutaf)
- [ctop (2) ★7091](https://github.com/bcicen/ctop) - Top-like interface for container metrics (Golang) by [@bcicen](https://github.com/bcicen/)
- [dext-docker-registry-plugin ★1 ⏳1Y](https://github.com/vutran/dext-docker-registry-plugin) - Search the Docker Registry with the Dext smart launcher.
- [docker-ls ★240](https://github.com/mayflower/docker-ls) - CLI tools for browsing and manipulating docker registries by [@mayflower](https://github.com/mayflower)
- [Docker-mon ★748 ⏳2Y](https://github.com/icecrime/docker-mon) :skull: - Console-based Docker monitoring by [@icecrime](https://github.com/icecrime)
- [docker.el ★256](https://github.com/Silex/docker.el) Manage docker from Emacs by [Silex](https://github.com/Silex)
- [dockercraft ★4872](https://github.com/docker/dockercraft) - Docker + Minecraft = Dockercraft by [@docker][docker]
- [dockerfile-mode ★257](https://github.com/spotify/dockerfile-mode) An emacs mode for handling Dockerfiles by [spotify][spotify]
- [dockersql ★85 ⏳3Y](https://github.com/crosbymichael/dockersql) - A command line interface to query Docker using SQL by [@crosbymichael][crosbymichael]
- [dockly ★1024](https://github.com/lirantal/dockly) - An interactive shell UI for managing Docker containers by [@lirantal](https://github.com/lirantal)
- [dry ★1105](https://github.com/moncho/dry) - An interactive CLI for Docker containers by [@moncho](https://github.com/moncho)
- [DVM ★463](https://github.com/howtowhale/dvm) - Docker version manager by [@howtowhale](https://github.com/howtowhale)
- [MultiDocker ★6](https://github.com/marty90/multidocker) - Create a secure multi-user Docker machine, where each user is segregated into an indepentent container.
- [ns-enter ★1965 ⏳1Y](https://github.com/jpetazzo/nsenter) - no more ssh, enter name spaces of container by [@jpetazzo][jpetazzo]
- [Powerline-Docker ★30 ⏳1Y](https://github.com/adrianmo/powerline-docker) - A Powerline segment for showing the status of Docker containers by [@adrianmo](https://github.com/adrianmo)
- [proco ★34](https://github.com/shiwaforce/proco) - Proco will help you to organise and manage Docker, Docker-Compose, Kubernetes projects of any complexity using simple YAML config files to shorten the route from finding your project to initialising it in your local environment. by [@shiwaforce](https://github.com/shiwaforce)
- [reg ★458](https://github.com/genuinetools/reg) - Docker registry v2 command line client by [@genuinetools][genuinetools]
- [scuba ★28](https://github.com/JonathonReinhart/scuba) - Transparently use Docker containers to encapsulate software build environments, by [@JonathonReinhart](https://github.com/JonathonReinhart)
- [sen ★695](https://github.com/TomasTomecek/sen) - Terminal user interface for docker engine, by [@TomasTomecek](https://github.com/TomasTomecek)
- [supdock ★8](https://github.com/segersniels/supdock) - :construction: Allows for slightly more visual usage of Docker with an interactive prompt by [@segersniels](https://github.com/segersniels)
- [tsaotun ★30](https://github.com/qazbnm456/tsaotun) - Python based Assistance for Docker by [@qazbnm456](https://github.com/qazbnm456)
- [wharfee ★569](https://github.com/j-bennet/wharfee) - Autocompletion and syntax highlighting for Docker commands. by [@j-bennet](https://github.com/j-bennet)

#### Web

- [Docker Registry Browser ★47](https://github.com/klausmeyer/docker-registry-browser) - Web Interface for the Docker Registry HTTP API v2 by [@klausmeyer](https://github.com/klausmeyer)
- [Docker Registry UI ★778](https://github.com/squidnyan/docker-registry-ui) - A web UI for easy private/local Docker Registry integration by [@squidnyan](https://github.com/squidnyan)
- [docker-registry-web ★309](https://github.com/mkuchin/docker-registry-web) - Web UI, authentication service and event recorder for private docker registry v2 by [@mkuchin](https://github.com/mkuchin)
- [docker-swarm-visualizer ★2213](https://github.com/dockersamples/docker-swarm-visualizer) - Visualizes Docker services on a Docker Swarm (for running demos).
- [dockering-on-rails ★13 ⏳2Y](https://github.com/Electrofenster/dockerding-on-rails) :skull: - Simple Web-Interface for Docker with a lot of features by [@Electrofenster](https://github.com/Electrofenster/)
- [DockerSurfer ★2](https://github.com/Simone-Erba/DockerSurfer) :construction: - A web service for analyze and browse dependencies between Docker images in the Docker registry, by [@Simone-Erba](https://github.com/Simone-Erba/)
- [OctoLinker ★2734](https://github.com/OctoLinker/OctoLinker) - A browser extension for GitHub that makes the image name in a `Dockerfile` clickable and redirect you to the related Docker Hub page.
- [Portainer ★8169](https://github.com/portainer/portainer) - A lightweight management UI for managing your Docker hosts or Docker Swarm clusters by [@portainer](https://github.com/portainer)
- [Portus ★1879](https://github.com/SUSE/Portus) - Authorization service and frontend for Docker registry (v2) by [@SUSE](https://github.com/SUSE)
- [Rapid Dashboard ★72](https://github.com/ozlerhakan/rapid) - A simple query dashboard to use Docker Remote API by [@ozlerhakan](https://github.com/ozlerhakan/)
- [Seagull ★1739](https://github.com/tobegit3hub/seagull) - Friendly Web UI to monitor docker daemon. by [@tobegit3hub](https://github.com/tobegit3hub)
- [Swirl ★138](https://github.com/cuigh/swirl) - Swirl is a web management tool for Docker, focused on swarm cluster By [@cuigh](https://github.com/cuigh/)

## Docker Images

### Base Tools

Tools and applications that are either installed inside containers or designed to be run as a [sidecar](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar)

- [amicontained ★332](https://github.com/genuinetools/amicontained) - Container introspection tool. Find out what container runtime is being used as well as features available by [@genuinetools][genuinetools]
- [autodock ★44](https://github.com/prologic/autodock) - Daemon for Docker Automation by [@prologic][prologic]
- [Chaperone ★138](https://github.com/garywiz/chaperone) - A single PID1 process designed for docker containers. Does user management, log management, startup, zombie reaping, all in one small package. by [@garywiz](https://github.com/garywiz)
- [CoreOS][coreos] - Linux for Massive Server Deployments
- [docker-alpine][alpine] - A super small Docker base image *(5MB)* using Alpine Linux by [@gliderlabs][gliderlabs]
- [docker-gen ★2845](https://github.com/jwilder/docker-gen) - Generate files from docker container meta-data by [@jwilder][jwilder]
- [dockerize ★1890](https://github.com/jwilder/dockerize) - Utility to simplify running applications in docker containers by [@jwilder][jwilder]
- [GoSu ★2208](https://github.com/tianon/gosu) - Run this specific application as this specific user and get out of the pipeline (entrypoint script tool) by [@tianon](https://github.com/tianon)
- [is-docker ★52 ⏳1Y](https://github.com/sindresorhus/is-docker) - Check if the process is running inside a Docker container by [@sindresorhus][sindresorhus]
- [lstags ★177](https://github.com/ivanilves/lstags) - sync Docker images across registries by [@ivanilves](https://github.com/ivanilves)
- [NVIDIA-Docker ★5880](https://github.com/NVIDIA/nvidia-docker) - The NVIDIA Container Runtime for Docker by [@NVIDIA](https://github.com/NVIDIA)
- [su-exec ★417](https://github.com/ncopa/su-exec) - This is a simple tool that will simply execute a program with different privileges. The program will be excuted directly and not run as a child, like su and sudo does, which avoids TTY and signal issues. Why reinvent gosu? This does more or less exactly the same thing as gosu but it is only 10kb instead of 1.8MB. By [ncopa](https://github.com/ncopa)
- [supercronic ★410](https://github.com/aptible/supercronic) - crontab-compatible job runner, designed specifically to run in containers by [@aptible](https://github.com/aptible/)
- [TrivialRC ★22](https://github.com/vorakl/TrivialRC) - A minimalistic Runtime Configuration system and process manager for containers [@vorakl](https://github.com/vorakl)

### Builder

Applications designed to help or simplify building **new** images

- [buildah ★761](https://github.com/projectatomic/buildah) - A tool that facilitates building OCI images by [@projectAtomic][projectatomic]
- [container-diff ★1706](https://github.com/GoogleContainerTools/container-diff) - An image tool for comparing and analzying container images by [@GoogleContainerTools][GoogleContainerTools]
- [container-factory ★54 ⏳3Y](https://github.com/mutable/container-factory) - Produces Docker images from tarballs of application source code by [@mutable](https://github.com/mutable)
- [copy-docker-image ★11](https://github.com/mdlavin/copy-docker-image) - Copy a Docker image between registries without a full Docker installation by [@mdlavin](https://github.com/mdlavin)
- [Derrick ★210](https://github.com/alibaba/derrick) - A tool help you to automate the generation of Dockerfile and dockerize application by scanning the code. By [@alibaba](https://github.com/alibaba).
- [dlayer ★71](https://github.com/wercker/dlayer) - Stats collector for Docker layers by [@wercker](https://github.com/wercker)
- [docker-companion ★22](https://github.com/mudler/docker-companion) - A command line tool written in Golang to squash and unpack docker images by [@mudler](https://github.com/mudler/)
- [docker-make ★66](https://github.com/CtripCloud/docker-make) - Build, tag,and push a bunch of related docker images via a single command.
- [docker-replay ★130](https://github.com/bcicen/docker-replay) - Generate `docker run`command and options from running containers. By [bcicen](https://github.com/bcicen)
- [DockerSlim ★1456](https://github.com/docker-slim/docker-slim) shrinks fat Docker images creating the smallest possible images.
- [Dockly ★199](https://github.com/swipely/dockly) - Dockly is a gem made to ease the pain of packaging an application in Docker by [@swipely](https://github.com/swipely/)
- [dockramp ★264 ⏳2Y](https://github.com/jlhawn/dockramp) :skull: - Proof of Concept: A Client Driven Docker Image Builder by [@jlhawn](https://github.com/jlhawn)
- [flyimg](http://flyimg.io/) - Docker image resizing, cropping, and compression on the fly.
- [img ★1535](https://github.com/genuinetools/img) - Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder by [@genuinetools][genuinetools]
- [kaniko ★1584](https://github.com/GoogleContainerTools/kaniko) - Build Container Images In Kubernetes. By [@GoogleContainerTools][GoogleContainerTools]
- [MicroBadger][microbadger] - Analyze the contents of images and add metadata labels
- [packer](https://www.packer.io/docs/builders/docker.html) - Hashicorp tool to build machine images including docker image integrated with configuration management tools like chef, puppet, ansible
- [portainer ★128 ⏳1Y](https://github.com/duedil-ltd/portainer) - Apache Mesos framework for building Docker images by [@duedil-ltd](https://github.com/duedil-ltd)
- [runlike ★138](https://github.com/lavie/runlike) 🚧 - Generate `docker run`command and options from running containers by [@lavie](https://github.com/lavie)
- [SkinnyWhale ★173](https://github.com/djosephsen/skinnywhale) :skull: - Skinnywhale helps you make smaller (as in megabytes) Docker containers.
- [Whaler ★305](https://github.com/P3GLEG/Whaler) - Program to reverse Docker images into Dockerfiles by [@P3GLEG](https://github.com/P3GLEG/).
- [Whales ★97](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications by [@icalialabs](https://github.com/IcaliaLabs).

### Dockerfile

- [chaperone-docker ★46](https://github.com/garywiz/chaperone-docker) - A set of images using the Chaperone process manager, including a lean Alpine image, LAMP, LEMP, and bare-bones base kits.
- [Dockerfile Generator](http://jrruethe.github.io/blog/2015/09/20/dockerfile-generator/)
- [Dockerfile Project](http://dockerfile.github.io/) : Trusted Automated Docker Builds. Dockerfile Project maintains a central repository of Dockerfile for various popular open source software services runnable on a Docker container.
- [Vektorcloud](https://github.com/vektorcloud) - A collection of minimal, Alpine-based Docker images

Examples by:

- [@arun-gupta ★175 ⏳1Y](https://github.com/arun-gupta/docker-images)
- [@awesome-startup ★42 ⏳1Y](https://github.com/awesome-startup/docker-compose)
- [@crosbymichael ★297 ⏳1Y](https://github.com/crosbymichael/Dockerfiles)
- [@jessfraz ★6281](https://github.com/jessfraz/Dockerfiles)
- [@komljen ★403 ⏳1Y](https://github.com/komljen/dockerfile-examples)
- [@kstaken ★668](https://github.com/kstaken/dockerfile-examples)
- [@ondrejmo ★22](https://github.com/ondrejmo/Dockerfiles)
- [@pandrew](https://gitlab.com/pandrew/dockerfiles)
- [@vimagick ★910](https://github.com/vimagick/dockerfiles)

### Linter

- [dockerfile_lint ★220](https://github.com/projectatomic/dockerfile_lint) - A rule-based 'linter' for Dockerfiles by [@projectatomic][projectatomic]
- [Dockerfilelint ★283](https://github.com/replicatedhq/dockerfilelint) - A node module that analyzes a Dockerfile and looks for common traps, mistakes and helps enforce best practices by [@replicatedhq](https://github.com/replicatedhq)
- [dockfmt ★212](https://github.com/jessfraz/dockfmt) :construction: - Dockerfile formatter and parser by [@jessfraz][jessfraz]
- [Hadolint ★987](https://github.com/hadolint/hadolint) - A Dockerfile linter that checks for best practices, common mistakes, and is also able to lint any bash written in `RUN` instructions; by [@lukasmartinelli](https://github.com/lukasmartinelli)
- [Whale-linter ★30](https://github.com/jeromepin/whale-linter) - A simple and small Dockerfile linter written in Python3+ without dependencies by [@jeromepin](https://github.com/jeromepin)

### Metadata

- [opencontainer](https://github.com/opencontainers/image-spec/blob/master/annotations.md) - A convention and shared namespace for Docker labels defined by OCI Image Spec.

### Registry

Services to securely store your Docker images.

- [Amazon EC2 Container Registry :heavy_dollar_sign:](https://aws.amazon.com/ecr/) - Amazon EC2 Container Registry (ECR) is a fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images.
- [Azure Container Registry :heavy_dollar_sign:](https://azure.microsoft.com/de-de/services/container-registry/) - Manage a Docker private registry as a first-class Azure resource
- [CargoOS ★4 ⏳1Y](https://github.com/RedCoolBeans/cargos-buildroot) - A bare essential OS for running the Docker Engine on bare metal or Cloud. By [@RedCoolBeans](https://github.com/RedCoolBeans)
- [Cycle.io :heavy_dollar_sign:](https://cycle.io/) - Bare-metal container hosting.
- [cleanreg ★15](https://github.com/hcguersoy/cleanreg) - A small tool to delete image manifests from a Docker Registry implementing the API v2, dereferencing them for the GC by [@hcguersoy](https://github.com/hcguersoy)
- [Docker Hub](https://hub.docker.com/) provided by Docker Inc.
- [Docker Registry v2][distribution] - The Docker toolset to pack, ship, store, and deliver content
- [Docket ★616 ⏳3Y](https://github.com/netvarun/docket) - Custom docker registry that allows for lightning fast deploys through bittorrent by [@netvarun](https://github.com/netvarun/)
- [Europa :heavy_dollar_sign: ★101](https://github.com/puppetlabs/europa) - Private docker registry with support for image pipelines and webhooks. By [@puppetlabs](https://github.com/puppetlabs)
- [GCE Container Registry :heavy_dollar_sign:](https://cloud.google.com/container-registry/) Fast, private Docker image storage on Google Cloud Platform
- [GitLab Container Registry](https://docs.gitlab.com/ce/user/project/container_registry.html) - Repositories focused on using it images in GitLab CI
- [JFrog Artifactory :heavy_dollar_sign:](https://jfrog.com/artifactory/) - Artifact Repository Manager, can be used as private Docker Registry as well
- [Private Docker Registry :heavy_dollar_sign:](https://private-docker-registry.com) - Dedicated Conainer Registry Service with unlimited private repositories, users, teams, namespaces together with enterprise grade authentication LDAP/AD/OAuth/SAML.
- [Quay.io :heavy_dollar_sign:](https://quay.io/) (part of CoreOS) - Secure hosting for private Docker repositories
- [Rescoyl ★10 ⏳1Y](https://github.com/noteed/rescoyl) - Private Docker registry (free and open source) by [@noteed][noteed]
- [Sonatype Nexus](https://www.sonatype.com/nexus-repository-oss) - Repository with Universal Support, also for Docker images
- [TreeScale](https://github.com/treescale) - Build and Distribute container based applications. By [@tigranbs](https://github.com/tigranbs)
- [VMWare Harbor](http://vmware.github.io/harbor/) Project Harbor by VMWare is an enterprise-class registry server that stores and distributes Docker images. Harbor extends the open source Docker Distribution by adding the functionalities usually required by an enterprise, such as security, identity and management.

## Development with Docker

### API Client

- [ahab ★117](https://github.com/instacart/ahab) - Docker event handling with Python by [@instacart](https://github.com/instacart)
- [Docker Client for JVM ★55](https://github.com/gesellix/docker-client) - A Docker remote api client library for the JVM, written in Groovy by [@gesellix][gesellix]
- [Docker Client TypeScript](https://gitlab.com/masaeedu/docker-client) - Docker API client for JavaScript, automatically generated from Swagger API definition from moby repository. By [@masaeedu](https://github.com/masaeedu)
- [docker-it-scala ★303](https://github.com/whisklabs/docker-it-scala) - Docker integration testing kit with Scala by [@whisklabs](https://github.com/whisklabs)
- [docker-maven-plugin ★871](https://github.com/fabric8io/docker-maven-plugin) - A Maven plugin for running and creating Docker images by [@fabric8io](https://github.com/fabric8io)
- [Docker-PowerShell ★257](https://github.com/Microsoft/Docker-PowerShell) - PowerShell Module for Docker
- [Docker.DotNet ★550](https://github.com/Microsoft/Docker.DotNet) - C#/.NET HTTP client for the Docker remote API by [@ahmetalpbalkan](ahmetalpbalkan)
- [dockerfile-maven ★771](https://github.com/spotify/dockerfile-maven) - A Maven plugin for building and pushing Docker images by [@spotify][spotify]
- [dockerode ★1815](https://github.com/apocas/dockerode) - Docker Remote API node.js module by [@apocas](https://github.com/apocas)
- [DoMonit ★53 ⏳1Y](https://github.com/eon01/DoMonit) - A simple Docker Monitoring wrapper For Docker API
- [go-dockerclient ★1290](https://github.com/fsouza/go-dockerclient) - Go HTTP client for the Docker remote API by [@fsouza](https://github.com/fsouza/)
- [Gradle Docker plugin ★71](https://github.com/gesellix/gradle-docker-plugin) - A Docker remote api plugin for Gradle by [@gesellix][gesellix]
- [libcompose ★516](https://github.com/docker/libcompose) - Go library for Docker Compose.
- [sbt-docker-compose ★127](https://github.com/Tapad/sbt-docker-compose) - Integrates Docker Compose functionality into sbt by [@kurtkopchik](https://github.com/kurtkopchik/)
- [sbt-docker ★566](https://github.com/marcuslonnberg/sbt-docker) - Create Docker images directly from sbt by [@marcuslonnberg](https://github.com/marcuslonnberg)

### CI/CD

- [Buddy :heavy_dollar_sign:](https://buddy.works) - The best of Git, build & deployment tools combined into one powerful tool that supercharged our development.
- [Captain ★642](https://github.com/harbur/captain) - Convert your Git workflow to Docker containers ready for Continuous Delivery by [@harbur](https://github.com/harbur).
- [Cyclone ★545](https://github.com/caicloud/cyclone) - A cloud native CI/CD platform built for container workflow by [@caicloud](https://github.com/caicloud).
- [Docker plugin for Jenkins ★365](https://github.com/jenkinsci/docker-plugin) - The aim of the docker plugin is to be able to use a docker host to dynamically provision a slave, run a single build, then tear-down that slave.
- [Drone ★14753](https://github.com/drone/drone) - Continuous integration server built on Docker and configured using YAML files.
- [GitLab CI](https://about.gitlab.com/gitlab-ci/) - GitLab has integrated CI to test, build and deploy your code with the use of GitLab runners.
- [GOCD-Docker ★98 ⏳1Y](https://github.com/gocd/gocd-docker)Go Server and Agent in docker containers to provision.
- [Microservices Continuous Deployment ★122](https://github.com/francescou/docker-continuous-deployment) - Continuous deployment of a microservices application.
- [mu ★361](https://github.com/stelligent/mu) - Tool to configure CI/CD of your container applications via AWS CodePipeline, CodeBuild and ECS [@Stelligent](https://github.com/stelligent)
- [Screwdriver :heavy_dollar_sign:](http://screwdriver.cd/) - Yahoo's OpenSource buildplatform designed for Continous Delivery.
- [Skipper ★21](https://github.com/Stratoscale/skipper) - Easily dockerize your Git repository by [@Stratoscale](https://github.com/Stratoscale)
- [SwarmCI ★42 ⏳1Y](https://github.com/ghostsquad/swarmci) - Create a distributed, isolated task pipeline in your Docker Swarm.
- [Watchtower ★2076](https://github.com/v2tec/watchtower) - Automatically update running Docker containers by [@CenturyLinkLabs][CenturyLinkLabs]

### Development Environment

- [Binci ★582](https://github.com/binci/binci) - Containerize your development workflow. (formerly DevLab by [@TechnologyAdvice](https://github.com/TechnologyAdvice))
- [Boot2Docker ★7431](https://github.com/boot2docker/boot2docker) - Docker for OSX and Windows
- [construi ★19](https://github.com/lstephen/construi) - Run your builds inside a Docker defined environment by [@lstephen](https://github.com/lstephen)
- [Devstep ★201](https://github.com/fgrehm/devstep) :skull: - Development environments powered by Docker and buildpacks by [@fgrehm][fgrehm]
- [Dinghy ★1785](https://github.com/codekitchen/dinghy) - An alternative way to use Docker on Mac OS X using Docker Machine with virtualbox, vmware, xhyve or parallels
- [DLite ★2403](https://github.com/nlf/dlite) - Simplest way to use Docker on OSX, no VM needed. By [@nlf](https://github.com/nlf)
- [dobi ★147](https://github.com/dnephin/dobi) - A build automation tool for Docker applications. By [@dnephin](https://github.com/dnephin)
- [Docker Missing Tools ★10](https://github.com/nandoquintana/docker-missing-tools) - A set of bash commands to shortcut typical docker dev-ops. An alternative to creating typical helper scripts like "build.sh" and "deploy.sh" inside code repositories. By [@NandoQuintana](https://github.com/nandoquintana).
- [Docker osx dev ★1439](https://github.com/brikis98/docker-osx-dev) - A productive development environment with Docker on OS X by [@brikis98](https://github.com/brikis98)
- [Docker-Arch ★18](https://github.com/ph3nol/docker-arch) - Generate Web/CLI projects Dockerized development environments, from 1 simple YAML file. By [@Ph3nol](https://github.com/ph3nol)
- [Docker-sync](http://docker-sync.io/) - Drastically improves performance ([50-70x](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance)) when using Docker for development on Mac OS X/Windows and Linux while sharing code to the container. By [@EugenMayer](https://github.com/EugenMayer)
- [docker-vm ★33 ⏳1Y](https://github.com/shyiko/docker-vm) - Simple and transparent alternative to boot2docker (backed by Vagrant) by [@shyiko](https://github.com/shyiko)
- [Dusty](http://dusty.gc.com/) - Managed Docker development environments on OS X
- [Eclipse Che](http://www.eclipse.org/che/) - Developer workspace server with Docker runtimes, cloud IDE, next-generation Eclipse IDE
- [EnvCLI ★5](https://github.com/PhilippHeuer/EnvCLI) - Replace your local installation of Node, Go, ... with project-specific docker containers. By [@PhilippHeuer](https://github.com/PhilippHeuer)
- [forward2docker ★77 ⏳2Y](https://github.com/bsideup/forward2docker) :skull: - Utility to auto forward a port from localhost into ports on Docker containers running in a boot2docker VM by [@bsideup](https://github.com/bsideup)
- [Lando ★786](https://github.com/lando/lando) - Lando is for developers who want to quickly specify and painlessly spin up the services and tools needed to develop their projects. By [Tandem](https://thinktandem.io/)
- [Vagga ★1410](https://github.com/tailhook/vagga) - Vagga is a containerisation tool without daemons. It is a fully-userspace container engine inspired by Vagrant and Docker, specialized for development environments by [@tailhook](https://github.com/tailhook/)

### Garbage Collection

- [caduc ★9](https://github.com/tjamet/caduc) - A docker garbage collector cleaning stuff you did not use recently
- [Docker Clean ★958](https://github.com/zzrotdesign/docker-clean) - A script that cleans Docker containers, images and volumes by [@zzrotdesign](https://github.com/zzrotdesign)
- [Docker-cleanup ★511](https://github.com/meltwater/docker-cleanup) - Automatic Docker image, container and volume cleanup by [@meltwater](https://github.com/meltwater)
- [docker-custodian ★279](https://github.com/Yelp/docker-custodian) - Keep docker hosts tidy. By [@Yelp](https://github.com/Yelp)
- [docker-garby ★28](https://github.com/konstruktoid/docker-garby) - Docker garbage collection script by [@konstruktoid](https://github.com/konstruktoid).
- [docker-gc ★4252](https://github.com/spotify/docker-gc) - A cron job that will delete old stopped containers and unused images by [@spotify][spotify]
- [sherdock ★111 ⏳2Y](https://github.com/rancher/sherdock) :skull: - Automatic GC of images based on regexp by [@rancher][rancher]

### Serverless

- [AMP ★73](https://github.com/appcelerator/amp) - The open source unified CaaS/FaaS platform for Docker, batteries included. By [@Appcelerator](https://github.com/appcelerator/)
- [Apache OpenWhisk ★3232](https://github.com/apache/incubator-openwhisk) - a serverless, open source cloud platform that executes functions in response to events at any scale. By [@apache](https://github.com/apache)
- [Docker-Lambda ★2278](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment. By [@lamb-ci](https://github.com/lambci)
- [Funker ★16 ⏳1Y](https://github.com/bfirsh/funker-example-voting-app) - Functions as Docker containers example voting app. By [@bfirsh](https://github.com/bfirsh)
- [IronFunctions ★2216](https://github.com/iron-io/functions) - The serverless microservices platform FaaS (Funcitons as a Service) which uses Docker containers to run Any language or AWS Lambda functions
- [OpenFaaS ★10353](https://github.com/openfaas/faas) - A complete serverless functions framework for Docker and Kubernetes. By [OpenFaaS](https://github.com/openfaas)
- [SCAR ★266](https://github.com/grycap/scar) - Serverless Container-aware Architectures (SCAR) is a serverless framework that allows easy deployment and execution of containers (e.g. Docker) in Serverless environments (e.g. Lambda) by [@grycap](https://github.com/grycap)

### Testing

- [Container Structure Test ★709](https://github.com/GoogleContainerTools/container-structure-test) - A framework to validate the structure of an image by checking the outputs of commands or the contents of the filesystem. By [@GoogleContainerTools][GoogleContainerTools]
- [dgoss](https://github.com/aelsabbahy/goss/tree/master/extras/dgoss) - A fast YAML based tool for validating docker containers.
- [DockerSpec ★154](https://github.com/zuazo/dockerspec) - A small Ruby Gem to run RSpec and Serverspec, Infrataster and Capybara tests against Dockerfiles or Docker images easily. By [@zuazo](https://github.com/zuazo)
- [Dockunit ★43 ⏳2Y](https://github.com/dockunit/platform) :skull: - Docker based integration tests. A simple Node based utility for running Docker based unit tests. By [@dockunit](https://github.com/dockunit)
- [InSpec][inspec] - InSpec is an open-source testing framework for infrastructure with a human- and machine-readable language for specifying compliance, security and policy requirements. By [@chef](https://github.com/chef)
- [Pumba ★907](https://github.com/alexei-led/pumba) - Chaos testing tool for Docker. Can be deployed on kubernetes and CoreOS cluster. By [@alexei-led](https://github.com/alexei-led)

### Wrappers

- [Ansible](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) - Manage the life cycle of Docker containers. By RedHat
- [Azk ★855 ⏳1Y](https://github.com/azukiapp/azk) - Orchestrate development enviornments on your local machine by [@azukiapp](https://github.com/azukiapp)
- [Beluga ★167](https://github.com/cortexmedia/Beluga) :skull: - CLI to deploy docker containers on a single server or low amount of servers. By [@cortextmedia](https://github.com/cortexmedia)
- [dexec ★292 ⏳1Y](https://github.com/docker-exec/dexec) - Command line interface written in Go for running code with Docker Exec images.
- [docker-do ★15 ⏳2Y](https://github.com/benzaita/docker-do) - hassle-free docker run, like `env` but for docker by [@benzaita](https://github.com/benzaita)
- [Dray ★342 ⏳2Y](https://github.com/CenturyLinkLabs/dray) - An engine for managing the execution of container-based workflows by [@CenturyLinkLabs][CenturyLinkLabs]
- [FuGu ★140 ⏳2Y](https://github.com/mattes/fugu) - Docker run wrapper without orchestration by [@mattes](https://github.com/mattes)
- [SaltStack Docker module](https://docs.saltstack.com/en/latest/ref/modules/all/salt.modules.dockerng.html#module-salt.modules.dockerng) - SaltStack Docker module
- [Shutit](http://ianmiell.github.io/shutit/) - Tool for building and maintaining complex Docker deployments by [@ianmiell][ianmiell]
- [subuser ★691](https://github.com/subuser-security/subuser) - Makes it easy to securely and portably run graphical desktop applications in Docker
- [Turbo ★12 ⏳1Y](https://github.com/ramitsurana/turbo) - Simple and Powerful utility for docker. By [@ramitsurana][ramitsurana]
- [udocker ★315](https://github.com/indigo-dc/udocker) - A tool to execute simple docker containers in batch or interactive systems without root privileges by [@inidigo-dc](https://github.com/indigo-dc)
- [Vagrant - Docker provider](https://www.vagrantup.com/docs/docker/basics.html) - Good starting point is [vagrant-docker-example ★94 ⏳2Y](https://github.com/bubenkoff/vagrant-docker-example) by [@bubenkoff](https://github.com/bubenkoff)

## Services based on Docker (:heavy_dollar_sign:)

### CI Services

- [CircleCI](https://circleci.com/) - Push or pull Docker images from your build environment, or build and run containers right on CircleCI.
- [CodeFresh](https://codefresh.io) - Everything you need to build, test, and share your Docker applications. Provides automated end to end testing.
- [CodeShip](https://codeship.com/features/pro) - Work with your established Docker workflows while automating your testing and deployment tasks with our hosted platform dedicated to speed and security.
- [ConcourseCI](https://concourse-ci.org) - A CI SaaS platform for developers and DevOps teams pipeline oriented.
- [IBM Bluemix Continous Delivery](https://console.bluemix.net/devops/getting-started?auth=false) - Continuous delivery using a pipeline deployment onto IBM containers on Bluemix.
- [Semaphore CI](https://semaphoreci.com/product/docker) — A high-performance cloud solution that makes it easy to build, test and ship your containers to production.
- [Shippable](https://app.shippable.com/) - A SaaS platform for developers and DevOps teams that significantly reduces the time taken for code to be built, tested and deployed to production.
- [TravisCI](https://travis-ci.org/) - A Free github projects continuous integration Saas platform for developers and Devops.
- [Wercker](http://www.wercker.com/) - A Docker-Native continous integration & deployment Automation platform for Kubernetes & Microservice Deployments.

### CaaS

- [Amazon ECS](https://aws.amazon.com/ecs/) - A management service on EC2 that supports Docker containers.
- [Arukas](https://arukas.io/) - Heroku-inspired CaaS
- [Azure AKS](https://azure.microsoft.com/en-us/services/kubernetes-service/) - Simplify Kubernetes management, deployment, and operations. Use a fully managed Kubernetes container orchestration service.
- [Cloud 66](https://www.cloud66.com) - Full-stack hosted container management as a service
- [Codenvy](https://codenvy.com) - One-click Docker environments and cloud workspace for development teams
- [ContainerShip Cloud][containership] - Multi-Cloud Container Hosting Automation Platform.
- [Docker Cloud](https://cloud.docker.com/) - Former Tutum
- [Dockhero](https://dockhero.io/) - Dockhero is a Heroku add-on which turns a Docker image into a microservice attached to the Heroku app. Currently in beta.
- [Giant Swarm](https://giantswarm.io/) - Simple microservice infrastructure. Deploy your containers in seconds.
- [Google Container Engine](https://cloud.google.com/kubernetes-engine/docs/) - Docker containers on Google Cloud Computing powered by [Kubernetes][kubernetes].
- [Hyper_](https://hyper.sh/) - Secure container hosting service with "nano-containers" and per-second billing.
- [IBM Bluemix Container Service](https://console.bluemix.net/docs/containers/container_index.html) - Run Docker containers in a hosted cloud environment on IBM Bluemix.
- [Jelastic Cloud](https://jelastic.cloud/) - "Easy-to-use" container hosting platfrom with automatic vertical and horizontal scaling. Available over 50+ hosting providers worldwide.
- [OpenShift Dedicated](https://www.openshift.com/products/dedicated/) - A hosted [OpenShift][openshift] cluster for running your Docker containers managed by Red Hat.
- [Sloppy.io](https://sloppy.io/en/) - all-in-one solution for container deployment and hosting – made and hosted in Germany
- [Triton](https://www.joyent.com/) - Elastic container-native infrastructure by Joyent.

### Monitoring Services

- [AppDynamics](https://www.appdynamics.com/community/exchange/extension/docker-monitoring-extension/) - AppDynamics gives enterprises real-time insights into application performance, user performance, and business performance so they can move faster in an increasingly sophisticated, software-driven world.
- [Axibase Time-Series Database](https://axibase.com/products/axibase-time-series-database/writing-data/docker-cadvisor/) - Long-term retention of container statistics and built-in dashboards for Docker. Collected with native Google cAdvisor storage driver.
- [CA Technologies Docker Monitoring](https://www.ca.com/us/products/docker-monitoring.html) - Agile Operations solutions from CA deliver the modern Docker monitoring businesses need to accelerate and optimize the performance of microservices and the dynamic Docker environments running them. Monitor both the Docker environment and apps that run inside them.
- [Collecting docker logs and stats with Splunk](https://www.splunk.com/blog/2015/08/24/collecting-docker-logs-and-stats-with-splunk.html)
- [CoScale](https://www.coscale.com/docker-monitoring) - Full stack monitoring for containerized applications and microservices. Powered by anomaly detection to find performance problems faster.
- [Datadog](https://www.datadoghq.com/) - Datadog is a full-stack monitoring service for large-scale cloud environments that aggregates metrics/events from servers, databases, and applications. It includes support for Docker, Kubernetes, and Mesos.
- [Meros](https://meros.io) - Analyzes containers resources, captures logs, remote web SSH terminal and powerful DevOps alerts.
- [Prometheus](https://prometheus.io/) - Open-source service monitoring system and time series database
- [Site24x7](https://www.site24x7.com/docker-monitoring.html) - Docker Monitoring for DevOps and IT is a SaaS Pay per Host model
- [SPM for Docker][spm] - Monitoring of host and container metrics, Docker events and logs. Automatic log parser. Anomaly Detection and alerting for metrics and logs. [@sematext][sematext]
- [Sysdig Monitor](https://sysdig.com/product/monitor/) - Sysdig Monitor can be used as either software or a SaaS service to monitor, alert, and troubleshoot containers using system calls. It has container-specific features for Docker and Kubernetes.

# Useful Resources

- __[Valuable Docker Links](https://www.nkode.io/2014/08/24/valuable-docker-links.html)__ High quality articles about docker! __MUST SEE__
- [Cloud Native Landscape ★2734](https://github.com/cncf/landscape)
- [Docker Weekly](https://blog.docker.com/docker-weekly-archives/) Huge resource
- [Programming Community Curated Resources for learning Docker](https://hackr.io/tutorials/learn-docker)

Blogs by

- [@codeship](https://blog.codeship.com/)
- [@crosbymichael](http://crosbymichael.com/)
- [@gliderlabs](https://gliderlabs.com/devlog/)
- [@jessfraz](https://blog.jessfraz.com/)
- [@jpetazzo](http://jpetazzo.github.io/)
- [@jwilder](http://jasonwilder.com/)
- [@nickjanetakis](https://nickjanetakis.com/blog/tag/docker-tips-tricks-and-tutorials)
- [@progrium](http://progrium.com/blog/)
- [@sebgoa](http://sebgoa.blogspot.be/)
- [Container solutions](https://container-solutions.com/blog/)
- [Container42](https://container42.com/)

## Awesome Lists

- [Awesome CI/CD ★683](https://github.com/ciandcd/awesome-ciandcd) - Not specific to docker but relevant.
- [Awesome Kubernetes ★2766](https://github.com/ramitsurana/awesome-kubernetes) by [@ramitsurana][ramitsurana]
- [Awesome Linux Container ★555](https://github.com/Friz-zy/awesome-linux-containers) more general about container than this repo, by [@Friz-zy](https://github.com/Friz-zy).
- [Awesome Selfhosted ★23808](https://github.com/Kickball/awesome-selfhosted) list of Free Software network services and web applications which can be hosted locally by running in a classical way (setup local web server and run applications from there) or in a Docker container. By [@Kickball](https://github.com/Kickball)
- [Awesome Sysadmin ★6727](https://github.com/n1trux/awesome-sysadmin) by [@n1trux](https://github.com/n1trux)
- [ToolsOfTheTrade ★7194](https://github.com/cjbarber/ToolsOfTheTrade) a list of SaaS and On premise applications by [@cjbarber](https://github.com/cjbarber)

## Good Tips

- [Dealing with linked containers dependency in docker-compose](http://brunorocha.org/python/dealing-with-linked-containers-dependency-in-docker-compose.html) by [@rochacbruno](https://github.com/rochacbruno)
- [Docker Caveats](http://docker-saigon.github.io/post/Docker-Caveats/) What You Should Know About Running Docker In Production (written 11 APRIL 2016) __MUST SEE__
- [Docker Containers on the Desktop][jessblog] - The **funniest way** to learn about docker by [@jessfraz][jessfraz] who also gave a [presentation][jessvid] about it @ DockerCon 2015
- [Docker vs. VMs? Combining Both for Cloud Portability Nirvana](https://www.rightscale.com/blog/cloud-management-best-practices/docker-vs-vms-combining-both-cloud-portability-nirvana)
- [Don't Repeat Yourself with Anchors, Aliases and Extensions in Docker Compose Files](https://medium.com/@kinghuang/docker-compose-anchors-aliases-extensions-a1e4105d70bd) by [@King Chung Huang](https://github.com/kinghuang)
- [GUI Apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/) by [@fgrehm][fgrehm]

## Raspberry Pi & ARM

- [Docker Pirates ARMed with explosive stuff](http://blog.hypriot.com/) Huge resource on clustering, swarm, docker, pre-installed image for SD card on Raspberry Pi
- [Get Docker up and running on the RaspberryPi in three steps](https://github.com/umiddelb/armhf/wiki/Get-Docker-up-and-running-on-the-RaspberryPi-%28ARMv6%29-in-three-steps)
- [git push docker containers to linux devices](https://resin.io/) Modern DevOps for IoT, leveraging git and Docker.
- [Installing, running, using Docker on armhf (ARMv7) devices](https://github.com/umiddelb/armhf/wiki/Installing,-running,-using-docker-on-armhf-(ARMv7)-devices)

## Security

- [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
- [CVE Scanning Alpine images with Multi-stage builds in Docker 17.05 ★6 ⏳1Y](https://github.com/tomwillfixit/alpine-cvecheck) by [@tomwillfixit](https://twitter.com/tomwillfixit)
- [Docker and SELinux](http://www.projectatomic.io/docs/docker-and-selinux/)
- [Docker Secure Deployment Guidelines ★485 ⏳1Y](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
- [Docker Securitiy - Quick Reference](https://binarymist.io/publication/docker-security/)
- [Docker Security Cheat Sheet](https://github.com/konstruktoid/Docker/blob/master/Security/CheatSheet.adoc)
- [Docker Security: Are Your Containers Tightly Secured to the Ship? SlideShare](https://fr.slideshare.net/MichaelBoelen/docker-security-are-your-containers-tightly-secured-to-the-ship)
- [How CVE's are handled on Offical Docker Images](https://github.com/docker-library/official-images/issues/1448)
- [Improving Docker Security with Authenticated Volumes](https://www.blockbridge.com/improving-docker-security-with-authenticated-volumes/)
- [Lynis is an open source security auditing tool including Docker auditing](https://cisofy.com/lynis/)
- [Security Best Practices for Building Docker Images](https://linux-audit.com/tag/docker/)
- [Software Engineering Radio interview of Docker Security Team Lead (Diogo Mónica)](http://www.se-radio.net/2017/05/se-radio-episode-290-diogo-monica-on-docker-security/)
- [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)
- [Understanding Docker security and best practices](https://blog.docker.com/2015/05/understanding-docker-security-and-best-practices/) (written 5 MAY 2015)

## Videos

- [Contributing to Docker by Andrew "Tianon" Page (InfoSiftr)](https://www.youtube.com/watch?v=1jwo8-1HYYg) (34:31)
- [Deploying and scaling applications with Docker, Swarm, and a tiny bit of Python magic](https://www.youtube.com/watch?v=GpHMTR7P2Ms) (3:11:06) by [@jpetazzo][jpetazzo]
- [Docker and SELinux by Daniel Walsh from Red Hat](https://www.youtube.com/watch?v=zWGFqMuEHdw) (40:23)
- [Docker for Developers][docker4dev] (54:26) by [@jpetazzo][jpetazzo]  <== Good introduction, context, demo
- [Docker in Production](https://www.youtube.com/watch?v=Glk5d5WP6MI) by [@jpetazzo][jpetazzo] (36:05)
- [Docker: How to Use Your Own Private Registry](https://www.youtube.com/watch?v=CAewZCBT4PI) (15:01)
- [Extending Docker with Plugins](https://vimeo.com/110835013) (15:21)
- [From Local Docker Development to Production Deployments](https://www.youtube.com/watch?v=7CZFpHUPqXw) by [@jpetazzo][jpetazzo] @ AWS re:Invent 2015
- [Immutable Infrastructure with Docker and EC2 by Michael Bryzek (Gilt)](https://www.youtube.com/watch?v=GaHzdqFithc) (42:04)
- [Introduction to Docker and containers](https://www.youtube.com/watch?v=ZVaRK10HBjo) (3:09:00) by [@jpetazzo][jpetazzo]
- [Logging on Docker: What You Need to Know][loggingDocker] (51:27)
- [Performance Analysis of Docker - Jeremy Eder](https://www.youtube.com/watch?v=6f2E6PKYb0w) (1:36:58)
- [Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) Free Udacity course
- [State of containers: a debate with CoreOS, VMware and Google](https://www.youtube.com/watch?v=IiITP3yIRd8) (27:38)
- [SysAdminCasts: Introduction to Docker](https://sysadmincasts.com/episodes/31-introduction-to-docker) (15:49)

# Communities and Meetups

## Brazilian

- [Docker BR on Slack](http://docker-br.herokuapp.com) - Auto invite url
- [Docker BR on Telegram](https://telegram.me/dockerbr)

## Chinese

- [DockerOne](http://dockone.io/) Docker Community (in Chinese) by [@LiYingJie](http://dockone.io/people/%E6%9D%8E%E9%A2%96%E6%9D%B0)

## English

- [Docker Community](https://www.docker.com/docker-community)
- [Docker Events](https://events.docker.com)
- [Docker On Line Meetup](https://www.meetup.com/Docker-Online-Meetup/)
- [Docker Reddit Community](https://www.reddit.com/r/docker/)

## Russian

- [Docker Russian-speaking Community](https://t.me/docker_ru)

[ahmetalpbalkan]: https://github.com/ahmetalpbalkan
[alpine]: https://github.com/gliderlabs/docker-alpine
[anchore]: https://github.com/anchore
[arun-gupta]: https://github.com/arun-gupta
[blockbridge]: https://github.com/blockbridge
[brooklyn]: http://brooklyn.apache.org/
[CONTRIBUTING]: https://github.com/veggiemonk/awesome-docker/blob/master/.github/CONTRIBUTING.md
[calico]: https://github.com/projectcalico/calicoctl
[CenturyLinkLabs]: https://github.com/CenturyLinkLabs
[containership]: https://containership.io
[ContainX]: https://github.com/ContainX
[coreos]: https://github.com/coreos
[cpuguy83]: https://github.com/cpuguy83
[crosbymichael]: https://github.com/crosbymichael
[dimonomid]: https://github.com/dimonomid
[distribution]: https://github.com/docker/distribution
[docker-cheat-sheet]: https://github.com/wsargent/docker-cheat-sheet
[docker-compose]: https://docs.docker.com/compose/
[docker-for-mac]: https://docs.docker.com/docker-for-mac/
[docker-for-windows]: https://docs.docker.com/docker-for-windows/
[docker-quick-ref]: https://github.com/dimonomid/docker-quick-ref
[docker]: https://github.com/docker
[docker4dev]: https://www.youtube.com/watch?v=FdkNAjjO5yQ
[dokku]: https://github.com/dokku/dokku
[editREADME]: https://github.com/veggiemonk/awesome-docker/edit/master/README.md
[fgrehm]: https://github.com/fgrehm
[fluentd]: https://github.com/kiyoto/docker-fluentd
[gesellix]: https://github.com/gesellix
[genuinetools]:  https://github.com/genuinetools
[gliderlabs]: https://github.com/gliderlabs
[google]: https://github.com/google
[GoogleContainerTools]: https://github.com/GoogleContainerTools
[grammarly]: https://github.com/grammarly
[hashicorp]: https://github.com/hashicorp
[ianmiell]: https://github.com/ianmiell
[inspec]: https://github.com/inspec/inspec
[JensPiegsa]: https://github.com/JensPiegsa
[jessblog]: https://blog.jessfraz.com/post/docker-containers-on-the-desktop/
[jessfraz]: https://github.com/jessfraz
[jessfrazdockerfiles]: https://github.com/jessfraz/dockerfiles
[jessfrazdotfiles]: https://github.com/jessfraz/dotfiles
[jessvid]: https://www.youtube.com/watch?v=1qlLUf7KtAw
[jpetazzo]: https://github.com/jpetazzo
[jwilder]: https://github.com/jwilder
[kartar]: https://twitter.com/kartar
[kiyoto]: https://github.com/kiyoto
[kubernetes]: https://kubernetes.io
[loggingDocker]: https://vimeo.com/123341629
[microbadger]: https://microbadger.com
[nginxproxy]: https://github.com/jwilder/nginx-proxy
[nickjanetakis]: https://twitter.com/nickjanetakis
[noteed]: https://github.com/noteed
[ondrejmo]: https://github.com/ondrejmo
[openshift]: https://www.openshift.org/
[pandrew]: https://github.com/pandrew
[percheron]: https://github.com/ashmckenzie/percheron
[progrium]: https://github.com/progrium
[projectatomic]: https://github.com/projectatomic
[prologic]: https://github.com/prologic
[ramitsurana]: https://github.com/ramitsurana
[rancher]: https://github.com/rancher
[sebgoa]: https://twitter.com/sebgoa
[sematext]: https://twitter.com/sematext
[sindresorhus]: https://github.com/sindresorhus/awesome
[spm]: https://github.com/sematext/sematext-agent-docker
[spotify]: https://github.com/spotify
[vegasbrianc]: https://github.com/vegasbrianc
[vfarcic]: https://github.com/vfarcic
[vimagick]: https://github.com/vimagick
[weave]: https://github.com/weaveworks/weave
[wsargent]: https://github.com/wsargent
---
<p align="center">
	This list is a copy of <a href="https://github.com/veggiemonk/awesome-docker">veggiemonk/awesome-docker</a> with ranks
</p>

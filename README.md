# Geoportal 2.0

**Geoportal 2.0** is a map server platform designed to host, visualize, and analyze geospatial data from various sources such as national censuses, INEGI, and other regional datasets. This portal enables users to review, analyze, and export geographic information in an intuitive and accessible way.

## 📌 Project Overview

Geoportal 2.0 is a locally hosted geospatial platform that integrates data processing and visualization capabilities using a combination of powerful GIS tools and microservice architecture. It is built to support the MXSIG standard and deliver reliable access to spatial datasets.

## 🧩 Tech Stack

- **PostgreSQL** with **PostGIS** – Spatial database for storing and querying geospatial data
- **Apache MapServer** – Core map server to publish and render geospatial data
- **Apache Tomcat** – Serves Java-based components or middleware, if required
- **Docker** – Containerization for microservices and environment consistency
- **Local Server (On-Premise)** – Deployment will be fully managed within a local network

## ⚙️ Architecture

The system is designed as a collection of microservices, each running in its own Docker container. These containers communicate internally and are orchestrated to provide a seamless backend for the Geoportal interface.


## 📁 Data Sources

- INEGI datasets
- Census and demographic data
- Custom regional and municipal layers

## 🔒 Deployment

Geoportal 2.0 is designed to be deployed **on-premise**, using a secure internal server environment. Docker ensures consistent configuration across deployments.

## 🗺️ Features

- Serve geospatial layers compatible with MXSIG
- Export and analyze map data through an interactive interface
- Support for spatial queries and layer overlays
- Modular microservice setup for scalable deployment

## 🚧 Development Status

This project is under active development. We are currently:

- Integrating datasets into PostGIS
- Setting up Docker containers for each service
- Testing Apache MapServer layer rendering
- Preparing the frontend for user interaction and export tools

## 📚 License

This project is currently private and intended for internal institutional use.

---

## 🤝 Contributing

If you're part of the development team, please follow the internal contribution guidelines and branch naming conventions.

---

## 📬 Contact

For more information or access to the project, please contact the Geoportal 2.0 development team.

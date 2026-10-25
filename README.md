# Apache Airflow Docker Setup

This repository provides instructions for setting up Apache Airflow using Docker Compose.

---

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed on your machine.
- [Docker Compose](https://docs.docker.com/compose/install/) installed.

---

## Setup & Installation

### 1. Directory Preparation
Copy the `docker-compose.yaml` file into the folder where you want to create and run your Airflow environment.

### 2. Configure Environment Variables
Create a file named `.env` in the same directory and paste the following configuration:

```env
AIRFLOW_IMAGE_NAME=apache/airflow:2.7.3
AIRFLOW_UID=50000

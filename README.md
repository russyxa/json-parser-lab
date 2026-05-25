# JSON Parser Lab

A Python script that reads and displays student enrollment data from a JSON file, running inside a Docker container.

## Project Structure
json-parser-lab/
├── data/
│   └── students.json
├── src/
│   └── parse_json.py
├── Dockerfile
├── README.md
└── .gitignore

## Requirements

- Docker Desktop
- Git

## How to Run

1. Build the Docker image: docker build -t json-parser-lab .
2. Run the container: docker run --rm json-parser-lab.


## What It Does

- Reads student data from `data/students.json`
- Displays school info, student details, enrolled courses, and total units per student

## Course

Integrative Programming Technologies | Ateneo de Davao University
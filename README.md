# Automated Git Action Pipeline

A simple, automated workflow demonstrating how to deploy a static web project using **GitHub Actions**. This repository serves as a boilerplate for setting up continuous integration and deployment (CI/CD) for HTML-based projects.

## 🚀 Features
* **Automated Deployment:** Automatically pushes updates to GitHub Pages on every commit to the `main` branch.
* **Lightweight:** Pure HTML implementation with no heavy dependencies.
* **Workflow Integration:** Includes a pre-configured `.github/workflows` directory.

## 🛠️ Getting Started

### Prerequisites
You only need a GitHub account to fork and test this pipeline.

### Setup
1. Fork this repository.
2. Navigate to **Settings > Pages**.
3. Under **Build and deployment > Source**, select "GitHub Actions".
4. Make a change to `index.html` and push to `main` to trigger the pipeline.

## 📂 Project Structure
* `.github/workflows/`: Contains the YAML configuration for the automation.
* `index.html`: The main entry point of the website.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

# AI Resume App

This project is an AI-powered resume builder that incorporates various technologies and APIs. Follow this guide to learn how to create a React Vite app, implement authentication, set up a CMS, work with databases, generate AI content, and deploy your app.

## Features

- **Create React Vite App and Library Installation**
- **Social and Email Password Authentication with Clerk**
- **Learn Tailwind CSS**
- **Strapi CMS Setup from Scratch**
- **MySQL Database Setup**
- **Generate AI Form with Google Gemini API**
- **Setup Gemini API: AI Model**
- **Generate Content from AI for Resume**
- **Build Dynamic Forms**
- **Convert React HTML to PDF**
- **Step-by-Step Tutorial**
- **Deploy App on Cloud / Vercel**

## Table of Contents

- [Installation](#installation)
- [Setup and Configuration](#setup-and-configuration)
- [Authentication](#authentication)
- [CMS Setup](#cms-setup)
- [Database Setup](#database-setup)
- [AI Integration](#ai-integration)
- [Dynamic Forms](#dynamic-forms)
- [PDF Generation](#pdf-generation)
- [Deployment](#deployment)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Rida-Lamiini/ai-resume-Strapi-admin.git
    cd ai-resume-Strapi-admin
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

## Setup and Configuration

1. **Create a React Vite app:**
    ```bash
    npm create vite@latest my-app --template react
    cd my-app
    npm install
    ```

2. **Install required libraries:**
    ```bash
    npm install tailwindcss postcss autoprefixer clerk-js strapi mysql google-gemini-api react-pdf
    ```

## Authentication

1. **Implement social and email password authentication with Clerk:**
    - Follow Clerk's documentation to set up and integrate authentication in your React app.

## CMS Setup

1. **Strapi CMS Setup from Scratch:**
    - Install Strapi globally: `npm install strapi@latest -g`
    - Create a new Strapi project: `strapi new my-project`
    - Follow the setup wizard to configure your Strapi CMS.

## Database Setup

1. **MySQL Database Setup:**
    - Install MySQL and create a database for your project.
    - Configure the database connection in your Strapi project.

## AI Integration

1. **Generate AI Form with Google Gemini API:**
    - Sign up for Google Gemini API and get your API key.
    - Integrate the API in your project to generate AI forms.

2. **Setup Gemini API: AI Model:**
    - Configure and train your AI model using Google Gemini API.

3. **Generate Content from AI for Resume:**
    - Use the AI model to generate content for resumes dynamically.

## Dynamic Forms

1. **Build Dynamic Forms:**
    - Create forms that dynamically generate fields based on user input and AI suggestions.

## PDF Generation

1. **Convert React HTML to PDF:**
    - Use the `react-pdf` library to convert your React components into PDF documents.

## Deployment

1. **Deploy App on Cloud / Vercel:**
    - Set up deployment scripts and configurations for deploying your app on cloud platforms like Vercel.

## Step by Step Tutorial

For a detailed step-by-step tutorial, please refer to the `docs` directory in this repository.

## Contributing

Feel free to contribute to this project by opening issues and submitting pull requests.

## License

This project is licensed under the MIT License.

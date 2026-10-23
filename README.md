# Customer Support Ticket Priority Prediction and Automated Assignment System Using Agentforce

A Salesforce-based Customer Support Ticket System designed to manage support requests, predict ticket priorities, identify potential SLA breaches, and support automated ticket assignment using Salesforce and Agentforce.

## Project Overview

The system aims to improve customer support efficiency by organizing tickets and helping support teams identify urgent issues and manage them effectively.

## Key Features

- **Ticket Management:** Store and manage customer support tickets.
- **Priority Prediction:** Support priority classification based on ticket information.
- **Automated Assignment:** Designed to assign tickets to appropriate support agents.
- **SLA Breach Risk:** Track potential risks of missing service-level agreements.
- **Ticket Status Tracking:** Monitor ticket progress and resolution.
- **Salesforce Integration:** Built using Salesforce metadata and Salesforce CLI.

## Technology Stack

- Salesforce Platform
- Salesforce CLI
- Visual Studio Code
- Git and GitHub
- Agentforce

## Project Structure

- `force-app/main/default/` — Salesforce metadata, including custom objects, fields, and other components.
- `config/` — Salesforce project configuration.
- `scripts/` — Project scripts, if present.
- `sfdx-project.json` — Salesforce DX project configuration.

## Prerequisites

- Salesforce CLI
- Visual Studio Code with Salesforce Extension Pack
- A Salesforce development org
- Git

## Setup

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal in the project directory.
4. Authenticate with your Salesforce org:

   ```bash
   sf org login web
   ```

5. Deploy the required metadata:

   ```bash
   sf project deploy start
   ```

## Project Status

The Salesforce project structure and custom ticket metadata have been created. Priority prediction logic, automated assignment, and other advanced features should be implemented and tested before describing them as fully functional.

## Future Enhancements

- AI-assisted ticket priority prediction.
- Rule-based or AI-assisted agent assignment.
- SLA breach alerts.
- Explainable ticket classification and reporting.

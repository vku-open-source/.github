# Emergix - Unified Emergency Operations and Planning Platform

[Live Demo](http://34.67.28.143/app/olp-oss-application/dashboard-674b5eaa29bd2146155b36c8?branch=master)

Emergix is a cutting-edge emergency management application designed to support communities before, during, and after natural disasters. Built using low-code technologies, Emergix provides tools for disaster planning, real-time updates, and post-event analysis, empowering communities to act swiftly and effectively.

It includes four repositories:

- [User Interface](https://github.com/vku-open-source/lcdp-ui)
- [Backend](https://github.com/vku-open-source/lcdp-backend)
- [LLM Service](https://github.com/vku-open-source/llm-service)
- [Notification Service](https://github.com/vku-open-source/notification_service)
- [Dify Agents](https://github.com/vku-open-source/dify-agents)

> **Note** : You can find information about third-party licenses which used in this project in [this file](THIRD_PARTY_LICENSE_README.txt).

---

## 🚀 Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Node.js (v20+)](https://nodejs.org/)
- [Python (v3.10+)](https://www.python.org/downloads/)
- [AppSmith](https://www.appsmith.com/)
- [Strapi](https://strapi.io/)
- [Dify](https://dify.ai/)

---

### 🛠️ Project Setup

#### Clone the Repository

```bash
mkdir emergix
cd emergix
git clone https://github.com/vku-open-source/lcdp-ui
git clone https://github.com/vku-open-source/lcdp-backend.git
git clone https://github.com/vku-open-source/llm-service.git
git clone https://github.com/vku-open-source/notification_service.git
```

#### User Interface (vku-open-source/lcdp-ui)

- Go to [installation tutorial](https://github.com/vku-open-source/lcdp-ui#installation)

#### Backend (vku-open-source/lcdp-backend)

- Go to [installation tutorial](https://github.com/vku-open-source/lcdp-backend?tab=readme-ov-file#ii-installation-and-running-applications)

#### AI Service (vku-open-source/llm-service)

- Go to [installation tutorial](https://github.com/vku-open-source/llm-service?tab=readme-ov-file#launch-app)

#### Notification Serivce (vku-open-source/notification_service)

- Go to [installation tutorial](https://github.com/vku-open-source/notification_service#installation)

#### Dify agents (vku-open-source/dify-agents)

- Go to [installation tutorial](https://github.com/vku-open-source/dify-agents?tab=readme-ov-file#installation)

<!-- #### Set Up the Environment

Each module (UI, backend, AI service, etc.) has its own `.env` file for configuration. Refer to the `.env.example` files provided in each repository and adjust them as needed.   -->

---

### 🌐 Components

1. **UI Service**

   - Built with [Appsmith](https://www.appsmith.com/).
   - Provides an intuitive interface for users to interact with disaster plans, updates, and analysis tools.

2. **Backend Service**

   - Developed using [Strapi](https://strapi.io/) for flexible content management.
   - Manages user data, disaster records, and API interactions.

3. **AI Service**

   - Powered by [Dify](https://dify.ai/).
   - Supports EOP generation, task automation, and disaster data analysis.

4. **Notification Service**

   - Real-time alerts and updates via push notifications, email or SMS.

5. **Crawl Service**
   - Gathers relevant data from external sources to inform disaster planning and updates.

---

## 🛠️ Technologies

Emergix is built using modern low-code and open-source tools to ensure flexibility, scalability, and ease of use:

- **[Appsmith](https://www.appsmith.com/):** Front-end development and interface design.
- **[Strapi](https://strapi.io/):** Content management and backend services.
- **[Dify](https://dify.ai/):** AI-powered data analysis and task automation.
- **Docker:** Simplified containerization for deployment and scaling.
- **Python:** Data processing and backend logic.

---

## ✨ Key Features

- **Disaster Visualization:** Analyze and visualize conditions such as floods, landslides, and other hazards based on location-specific data.
- **Emergency Operation Plan (EOP):** Automatically generate comprehensive EOPs based on collected data, customized for specific disaster scenarios.
- **Rescue Task Automation:** Define and generate rescue tasks aligned with the EOP, reducing manual overhead during emergencies.
- **Supportive Documentation:** Provide essential documentation and guidelines tailored to disaster situations to assist responders and affected individuals.
- **Community Collaboration:** Enable users to share updates, report conditions, and request assistance within their local communities.
- **Post-Disaster Analysis:** Analyze data after disasters to inform recovery efforts and improve future disaster response strategies.

#### System architecutre

![image](https://github.com/user-attachments/assets/89c43480-73a3-4a55-a9d9-8d911b019109)

####

<!-- ---

## 🐳 Deployment

All services can be deployed using Docker Compose.

### Run Services Locally

\`\`\`bash
docker compose up -d --build
\`\`\`

### Stopping Services

\`\`\`bash
docker compose down
\`\`\`
 -->

---

## 📜 License

This project is licensed under the terms of the [Apache V2.0](LICENSE)

---

## 🤝 Contributing

We welcome contributions to Emergix! Please check out our [Contributing Guidelines](CONTRIBUTING.md) for more details.

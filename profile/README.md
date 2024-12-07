# Emergix - Unified Emergency Operations and Planning Platform

[Live Demo](#) | [Documentation](#)  

Emergix is a cutting-edge emergency management application designed to support communities before, during, and after natural disasters. Built using low-code technologies, Emergix provides tools for disaster planning, real-time updates, and post-event analysis, empowering communities to act swiftly and effectively.

It includes four repositories:
- [User Interface](https://github.com/vku-open-source/lcdp-ui)
- [Backend](https://github.com/vku-open-source/lcdp-backend)
- [LLM Service](https://github.com/vku-open-source/llm-service)
- [Notification Service](https://github.com/vku-open-source/notification_service)


---

## 🚀 Getting Started  

### Prerequisites  
- [Docker](https://docs.docker.com/get-docker/)  
- [Node.js (v20+)](https://nodejs.org/)  
- [Python (v3.10+)](https://www.python.org/downloads/)  

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

#### vku-open-source/lcdp-ui

- Go to [installation tutorial](https://github.com/vku-open-source/lcdp-ui#installation)

#### vku-open-source/lcdp-backend

- Go to [installation tutorial](https://github.com/vku-open-source/lcdp-backend#installation) 


#### vku-open-source/llm-service

- Go to [installation tutorial](https://github.com/vku-open-source/llm-service#installation) 

#### vku-open-source/notification_service

- Go to [installation tutorial](https://github.com/vku-open-source/notification_service#installation)

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
- **Supportive Task Automation:** Define and generate supportive tasks aligned with the EOP, reducing manual overhead during emergencies.  
- **Real-time Documentation:** Provide essential documentation and guidelines tailored to disaster situations to assist responders and affected individuals.  
- **Community Collaboration:** Enable users to share updates, report conditions, and request assistance within their local communities.  
- **Post-Disaster Analysis:** Analyze data after disasters to inform recovery efforts and improve future disaster response strategies.  

#### System architecutre

![image](https://hackmd.io/_uploads/BJpq6obVyx.png)


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

This project is licensed under the terms of the [MIT License](LICENSE) 

---

## 🤝 Contributing  

We welcome contributions to Emergix! Please check out our [Contributing Guidelines](CONTRIBUTING.md) for more details.  

---

## 📧 Support  

For questions, feedback, or feature requests, please [open an issue](https://github.com/<your-org>/emergix/issues) or contact us at [support@emergix.com](mailto:support@emergix.com).  

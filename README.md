# 🚀 Project Name  
**Building and Monitoring a Containerized URL Shortener Service**

---

## 👥 Team Members  

- Mazen Yasser Mohamed Hussein  
- Ahmed Saad El Sayed El Abd  
- Ziad Ahmed Sabry Abd El Fataah  
- Ibrahim ELsayed Ibrahim Elnaggar  
- Omar Mohamed Abdulmonem Ali  
- Sameh Reda Makram Labib  

---

## 🎯 Objective  

Design, containerize, and monitor a scalable URL shortener service. The project aims to provide a simple yet efficient application for generating and managing short links, while ensuring visibility into system performance through integrated monitoring tools (Prometheus and Grafana). All components will be deployed and orchestrated locally using Docker.  

---

## 📖 Description  

This project focuses on developing a lightweight web application that shortens URLs, stores the mapping data, and manages redirections.  

- The application will be **containerized** to guarantee portability and consistency across environments.  
- The service will be **instrumented with metrics**, enabling performance monitoring.  
- **Prometheus** will collect metrics and **Grafana** will visualize them through interactive dashboards.  

This setup provides both functionality and observability in a unified environment.  

---

## 📅 4-Week Project Plan  

### **Week 1 – Project Setup & Basics**  
- Finalize project requirements and architecture  
- Set up GitHub repository and initial documentation  
- Develop basic URL shortener logic (shorten & redirect)  
- Choose and configure the database  

### **Week 2 – Containerization & Persistence**  
- Write Dockerfile for the application  
- Configure Docker Compose for multi-service setup  
- Add database container for persistence  
- Implement basic error handling & validations  

### **Week 3 – Monitoring & Metrics**  
- Add application instrumentation for Prometheus  
- Set up Prometheus for metrics collection  
- Integrate Grafana and design dashboards  
- Test system performance under load  

### **Week 4 – Testing & Finalization**  
- Conduct end-to-end testing of all components  
- Optimize Docker setup and resource usage  
- Write final project documentation (README, usage guide)  
- Prepare project presentation/demo  

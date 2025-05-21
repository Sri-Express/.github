# Sri Express

<div align="center">
  
![Organization](https://img.shields.io/badge/organization-Sri_Express-blue?style=for-the-badge&logo=github)
![Private Repositories](https://img.shields.io/badge/repositories-private-red?style=for-the-badge&logo=github)

### Project Status
![Release](https://img.shields.io/badge/release-v0.1.alpha-blue?style=flat-square)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-proprietary-lightgrey?style=flat-square)
  
### Technology Stack
  
![NodeJS](https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
  
### Development Activity
![Active Developers](https://img.shields.io/badge/active_developers-4+-orange?style=flat-square)
![Development Status](https://img.shields.io/badge/status-active_development-success?style=flat-square)
![Last Update](https://img.shields.io/badge/last_update-2025-informational?style=flat-square)
</div>

Sri Express is a comprehensive transportation management platform designed to streamline client bookings, customer service, bus/train operations, and administrative tasks. The system leverages modern web and mobile technologies, AI, and robust backend services to deliver a seamless experience for users and administrators.

# Architecture

![Architecture Diagram](Architecture.png)

### Frontend

- **Landing, LogIn & Registration:** Built with VITE for fast and modern web experiences.
- **Client App:** Developed using Flutter for cross-platform mobile support.
- **Customer Service Portal:** Built with Next.js for efficient server-side rendering.
- **Bus/Train Operations:** Managed via a React Native application.
- **Route Admin:** Flutter-based interface for route management.
- **System Admin:** Next.js application for system-wide administration.
- **Fleet Manager:** Next.js application for fleet management of large transport companies.

### Backend

- **NodeJS:** Handles business logic, API endpoints, and integration with external services.
- **Weather API:** Provides real-time weather data to enhance route planning for passengers.
- **AI Module (Python):** Powers intelligent features such as arrival time prediction.
- **Database (MongoDB):** Stores all operational, user, and analytics data.

### Features
- **Real-time Tracking:** Live location tracking for buses and trains.
- **Operational Dashboards:** Interfaces for bus/train operators to monitor routes, ETAs, and receive weather updates.
- **Route Administration:** Tools for managing and dynamically updating routes, schedules, and stops.
- **Fleet Management:** Comprehensive system for large transport companies to manage vehicles, drivers, maintenance, and performance, with revenue/cost estimation.
- **System Administration:** Centralized control over user accounts, system analytics, AI module management, and fleet registration approvals.
- **AI-Powered Insights:** Arrival time prediction and driving pattern analysis.
- **Weather Integration:** Real-time weather updates for passengers and operations.
- **Secure Authentication:** Safe login and registration for all users.
- **Cross-Platform Accessibility:** Client app available on mobile (Flutter), with web portals for various administrative roles (Vite, Next.js, React Native).

### Future Enhancements
- **Booking & Management:** Seamless ticket booking, management, and trip notifications for clients.
- **Customer Support:** Dedicated portal for handling inquiries, complaints, and feedback, supplemented by an AI-powered chatbot.

## Logo

![Sri Express Logo](Logo.jpeg)

## Details and Functionality

### Landing, LogIn & Registration
Built with VITE for fast and modern web experiences.
- The landing page provides an overview of the services offered by Sri Express, including features, pricing, and testimonials.
- The login and registration pages allow users to create accounts and access their profiles securely.

### Client App
Developed using Flutter for cross-platform mobile support.
- The client app will provide a map interface to show the location of the next bus/train in real-time, along with estimated arrival times and provide real-time updates on bus/train schedules.
- Users can book tickets, manage their bookings, and receive notifications about their trips.
- Raise complaints and provide feedback on their experiences.
- Whether API integration to provide real-time weather updates for the user's location and destination.
- Automated chatbot with automatically generated responses to common queries and escalation to customer service when needed.


### Customer Service Portal
Built with Next.js for efficient server-side rendering.
- The customer service portal allows support agents to manage client inquiries, complaints, and feedback.

### Bus/Train Operations
Managed via a React Native application.
- A fixed device on buses and trains will be used to track the location of the vehicle in real-time, along with other metrics such as driving patterns for AI analysis.
- A map interface will show the map of the bus or train with the current location of the vehicle and the estimated time of arrival at the next stop.
- Whether API integration to provide real-time weather updates for the vehicle's route.

### Route Admin
Flutter-based interface for route management.
- The route admin application allows administrators to manage bus/train routes, schedules, and stops.
- Routes to be added and modified as per the requirements of the day.
- The bus/train operations to be viewed and confirmed 15 minutes before the start of the journey.

### Fleet Manager
Flutter application for fleet management of large transport companies.
- The fleet manager application allows large transport companies to add and manage their fleet of buses/trains, including maintenance schedules, driver assignments, and performance metrics pending System Admin approval.
- Fleet managers can view real-time data on vehicle locations, driving patterns, and other metrics to optimize operations.
- Revenue and cost estimates for the fleet can be generated based on the data collected from the vehicles, with the planned ticketing system.

### System Admin
Next.js application for system-wide administration.
- The system admin application allows administrators to manage user accounts, roles, and permissions.
- System admins can view analytics and reports on system usage, performance, and user feedback.
- The system admin application also provides tools for managing the AI module, including training and testing data sets.
- Activating and deactivating the AI module for the system.
- Approving or rejecting bus registration requests from the bus/train fleet managers.

## Getting Started

> _Project source code and setup instructions will be provided in future updates._

---

© 2025 Sri Express by XForce

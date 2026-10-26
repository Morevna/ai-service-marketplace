# AI-Powered Cleaning Service Marketplace 🛒🤖

[Deployed Application](https://ai-service-marketplace-sooty.vercel.app/)

# AI-Powered Cleaning Service Marketplace 🛒🤖

👥 **Team Final Project | Full-Stack SPA E-Commerce Platform**  
A production-ready e-commerce SPA platform engineered for browsing, ordering, and managing professional cleaning services. The platform features a complex role-based access control system (Admin/User) and integrates an **AI-driven content automation engine**. Administrators can generate semantic service packages via natural language prompts; the backend AI compiles this into a structured JSON schema, which the client application dynamically intercepts, parses, and maps into rich interactive catalog views.

---

### 💻 My Technical Contributions

I spearheaded the core administrative data pipelines, built the client-side AI integration interface, implemented URL-driven state synchronization, and managed the application's verification layers.

#### 🔹 AI Interface Engineering & Admin Features
* **AI Content Compilation Engine:** Designed and implemented the administrative client layer for AI processing (`feat: add UI generate-ai-page for admin and logic for working with response from ai`). Developed asynchronous parsing streams that map generic AI-generated JSON payloads straight into UI components.
* **Synchronized State & URL Routing Architecture:** Designed a URL-driven state sync pattern (`put the statistics dates in the URL and created a state for authorization`). This ensures complex administrative views, charts, and statistics states remain fully persistent over hard reloads and deep linking using query parameters.
* **Data Mutation & CRUD Controls:** Engineered comprehensive administrative workspaces allowing on-the-fly mutations of systemic datasets, user accounts, and package metrics (`add the ability for the admin to edit users data`, `transfer editing logic to the services page`).
* **Complex Modals & Graph Projections:** Built multi-step order configuration systems (`fix order modal and add orders page`) and debugged asynchronous state injection anomalies in administrative charts (`fix bug with user graphs for the admin`).

#### 🔹 Interface Optimization, Adaptability & i18n
* **Advanced Internationalization Pipeline:** Integrated the multi-locale application engine (`add internationalization`), managing language contexts across data-heavy view nodes, charts, and informational models (`optimize AboutPage and add RU/EN language toggle`).
* **Layout Adaptability & Token-Based Styling:** Standardized layout stability by debugging responsive layouts (`fix adaptive`, `fix bag with css about page`) and linking interfaces via centralized design tokens (`using the variables`).
* **Asynchronous UX Loading States:** Implemented global fallback states, skeleton loaders, and UI spinners (`add loading state`) to handle data-fetching delays.

#### 🔹 Testing, Pipeline Integrity & Environment Setup
* **Unit Testing Ecosystem:** Initialized the automated test workspace by configuring `Vitest` and writing the baseline core unit tests (`setup vitset, add 5 tests`).
* **Continuous Integration Support:** Maintained repository workflow sanitary conditions by fixing build/CI blockers (`fix ci and order fields`) and refactoring deployment delivery targets (`ci: change branch from master to main`).

---

### 🛠️ Detailed Tech Stack & Architecture
* **Core Engine:** React 18, Vite, TypeScript
* **State Management:** URL Query Parameters, Dynamic Routing (React Router DOM)
* **Form Validation & AI Data Parsing:** Native JSON Compilation, Dynamic Schema Mapping
* **UI Architecture:** Material UI (MUI), CSS Modules, CSS Design Tokens
* **Testing Suite:** Vitest (Unit & Integration Testing)
* **Localization Ecosystem:** i18next Framework (RU/EN Core Toggle)
* **Backend:** Node.js/Express, Docker Containerization, Nginx (Reverse Proxy)



## Video Demonstration (Week 7 Checkpoint)

In this video we demonstrate all the features of our application:

- [Watch Video Demo](https://youtu.be/vlEtWECzbrQ?si=JYgDVZ1a0ye0EUHY)

## Video Demonstration (Week 5 Checkpoint)

In this video, we demonstrate the handling of 404 pages, loading states, and API error handling:
- [Watch Video Demo](https://youtu.be/EbpQGCGB3jc)



## Our Team

| Name      | GitHub                                               |                                                          Diary Links                                                           |                                      Self-assessment PR                                      |
|-----------|------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------:|
| Andrei    | [@andrski](https://github.com/andrski)               |                                                               -                                                                |                                              -                                               |
| Maria     | [@Morevna](https://github.com/Morevna)               |    [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/tree/development/development-notes/morevna)     | [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/pull/98/changes) |
| Mikhail   | [@bssier](https://github.com/bssier)                 |     [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/tree/development/development-notes/bssier)     |    [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/pull/101)     |
| Roman     | [@Rorodeathless1](https://github.com/Rorodeathless1) | [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/tree/development/development-notes/rorodeathless1) |                                              -                                               |
| Rostislav | [@MegaRostBLR1](https://github.com/MegaRostBLR1)     |  [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/tree/development/development-notes/megarostblr1)  |          [link](https://github.com/MegaRostBLR1/eCommerceLegendaryFrontendDevelopers/pull/107/changes)                                                                                    |


<img width="1884" height="1092" alt="image" src="https://github.com/user-attachments/assets/282fb60f-856d-4b8c-a50a-ed7ccaebf3d0" />


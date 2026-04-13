# DevBlog: Full-Stack Hybrid-Agile Capstone

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Strapi](https://img.shields.io/badge/Strapi-2E7EEA?style=for-the-badge&logo=strapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 📋 Project Overview
**DevBlog** is a flagship portfolio project developed over a rigorous 14-week timeline. This modern blogging platform was built using a **Hybrid-Agile framework**, balancing structured planning with iterative development to ensure a high-quality, scalable product. 

The application features a decoupled architecture with a high-performance React front-end and a robust Strapi back-end, seamlessly integrated via GraphQL. It was built with a focus on responsiveness, security, and professional deployment standards.

## 🎥 Project Demos
See the application in action:
* [**Full Stack Integration Demo**](https://youtu.be/szyq4l1fwig) - Comprehensive walkthrough of the React front-end interacting with the Strapi CMS.
* [**Responsive Design Demo**](https://youtu.be/6KD34YFLGy8) - Showcasing the fluid UI/UX across mobile, tablet, and desktop breakpoints.

## 🛠 Tech Stack
### Frontend
* **Vite & React:** Next-generation tooling for a lightning-fast development experience.
* **TailwindCSS:** For a modern, utility-first approach to responsive styling.
* **Apollo Client:** Efficiently managing GraphQL state and queries.

### Backend
* **Strapi (Headless CMS):** Centralized content management with custom schemas.
* **GraphQL:** Optimized API query language to prevent over-fetching of data.

## 🏗 Quality Assurance & Process
This project was validated through a rigorous testing lifecycle to ensure production readiness:
* **Methodology:** Developed using Hybrid-Agile, utilizing Sprints for feature implementation while maintaining a clear project roadmap.
* **Testing:** Validated via **Integration Testing**, **End-to-End (E2E)** workflows, and **User Acceptance Testing (UAT)** to meet stakeholder requirements.
* **Optimization:** Focused on SEO best practices, secure API communication, and optimized asset loading.

## 📂 Project Structure
```
.
├── devblog/        # Frontend application (Vite + React + Tailwind)
└── devblog-cms/    # Backend application (Strapi Headless CMS)
```

## 🚀 Getting Started

### Prerequisites
* **Node.js:** Refer to `devblog-cms/package.json` for the specific version.
* **npm** or **yarn**

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/tyler-sanderson-tech/Full-Stack-Hybrid-Agile-Capstone.git](https://github.com/tyler-sanderson-tech/Full-Stack-Hybrid-Agile-Capstone.git)
    cd Full-Stack-Hybrid-Agile-Capstone
    ```

2.  **Setup Frontend:**
    ```bash
    cd devblog
    npm install
    ```

3.  **Setup CMS:**
    ```bash
    cd ../devblog-cms
    npm install
    ```

### Running the Application
1.  **Start the Strapi CMS:**
    ```bash
    cd devblog-cms
    npm run develop
    ```
2.  **Start the Frontend (in a new terminal):**
    ```bash
    cd devblog
    npm run dev
    ```
3.  **Access the App:** Navigate to `http://localhost:5173`

## 🤝 Contributing
Contributions are welcome! If you have suggestions for improvements, please feel free to submit a Pull Request.

## ⚖️ License
This project is licensed under the [MIT License](https://mit-license.org/).

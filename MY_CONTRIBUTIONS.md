# My Contributions to TRUSTDBLE

This document outlines my specific contributions to the **TRUSTDBLE** project, developed at the **Data and AI Systems Lab, TU Darmstadt** between **October 2021 and July 2023**.

> *"Notably, he played a key role in developing a dashboard for TRUSTDBLE, a trusted data management system utilizing blockchain technology."*  
> — **Reference Letter, Technische Universität Darmstadt**

---

## About TRUSTDBLE

TRUSTDBLE (pronounced *"trustable"*) is a novel trusted database management system developed by the **Data Management Lab at TU Darmstadt**. It combines **Blockchain and Database technology** to provide trustworthy and auditable data management, built on top of **Oracle MySQL** with custom plugins and a special storage engine that stores data on a blockchain.

The project consists of three core components:

| Component | Description |
| :--- | :--- |
| **`trustdble-server`** | Core trusted DBMS — Oracle MySQL extended with custom plugins and a blockchain-backed storage engine for auditable data management. |
| **`dashboard`** | Full-stack web application: a Node.js backend providing an API to execute SQL statements on `trustdble-server`, paired with a Vue.js frontend. *(My Primary Area)* |
| **`benchmark`** | Performance evaluation tooling using standard benchmarks such as YCSB (Yahoo Cloud Serving Benchmark). |

---

## My Area: Dashboard

I was the primary developer responsible for the **dashboard** component — a full-stack web application consisting of:

* A **Node.js / Express.js backend** providing a RESTful API to execute SQL statements on the `trustdble-server` (the blockchain-backed database engine).
* A **Vue.js 2 frontend** for user interaction, data visualization, and system management.
* A **Blockchain Monitor** service for processing live Ethereum transactions and storing results in MySQL.

*The dashboard can be executed manually or containerized via Docker.*

---

## Detailed Contributions

### 🎨 Frontend Development
* Built user interfaces using **Vue.js 2**, **Bulma**, and the **Buefy** component library, providing a clean and responsive user experience.
* Managed global application state and component architecture for scalability and maintainability.
* Maintained code quality and consistency using **ESLint**.

### ⚙️ Backend & API Development
* Designed and implemented **RESTful APIs** using **JavaScript**, **Node.js**, and **Express.js**.
* Adopted a **layered architecture** with dependency injection to ensure a modular codebase — separating concerns across controller, service, and data access layers.

### 🔗 Blockchain Monitor
* Implemented a dedicated **Blockchain Monitor** service to bridge the Ethereum blockchain with the application's MySQL database.
* Processed and ingested live Ethereum blockchain transactions using **Web3.js**.
* Mapped on-chain transaction data directly to relational database records in **MySQL**.

### 🧪 Testing & Documentation
* Wrote comprehensive **integration tests** using **Jest** and **Supertest**, ensuring API endpoint reliability and correctness.
* Automated **API documentation** generation using **swagger-ui-express**, keeping the endpoints self-documenting and accessible.

### 🛠️ DevOps & Automation
* Containerized the application using **Docker** for consistent, reproducible deployments across development, staging, and production environments.
* Established robust **CI/CD pipelines** using **Bitbucket Pipelines**, automating build, test, and deployment workflows.
* Automated routine development processes through **shell scripts** and **Git hooks**, reducing manual overhead and enforcing pre-commit quality checks.

### 👥 Mentorship
* Guided and mentored junior computer science students joining the project, conducting code reviews and onboarding sessions.

---

## Tech Stack (Dashboard)

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | Vue.js 2, Bulma, Buefy, ESLint |
| **Backend** | Node.js, Express.js, JavaScript |
| **Blockchain** | Web3.js, Ethereum |
| **Database** | MySQL |
| **Testing** | Jest, Supertest |
| **Documentation** | swagger-ui-express |
| **DevOps** | Docker, Bitbucket CI/CD |
| **Automation** | Shell scripts, Git hooks |

---

## Note on Commit History

The repository was maintained in a **private institutional repository** throughout the active development period (2021–2023). It was published publicly by TU Darmstadt as a single release commit at project completion. The single-commit history does not reflect the full development activity — all iterative work, code reviews, and incremental changes occurred within the private institutional Bitbucket environment.

---

## Links

* 🔗 **TRUSTDBLE Repository:** [github.com/DataManagementLab/trustdble](https://github.com/DataManagementLab/trustdble)
* 🔗 **Dashboard Component:** [github.com/DataManagementLab/trustdble/tree/master/dashboard](https://github.com/DataManagementLab/trustdble/tree/master/dashboard)
* 🔗 **TU Darmstadt Data Management Lab:** [informatik.tu-darmstadt.de/datamanagement](https://www.informatik.tu-darmstadt.de/datamanagement)

---

### Author

**Shafqat Mehmood**  
*Scientific Assistant & Lead Dashboard Developer*  
Data and AI Systems Lab, TU Darmstadt (Oct 2021 – Jul 2023)  

💼 [LinkedIn](https://linkedin.com/in/shafqat-mehmood) | 🐙 [GitHub](https://github.com/cs-shafqat) | 📧 cs.shafqat@gmail.com

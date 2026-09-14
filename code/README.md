<p align="center">
  <a href="#forensic-medical-records-management-system">
    <img src="./images/Mythix_logo.png" alt="Team Mythix Logo" width="160" height="160" style="border-radius: 50%; box-shadow: 0 4px 20px rgba(0,0,0,0.35);" />
  </a>
</p>

<h1 align="center">Forensic Medical Records Management System</h1>

<p align="center">
  <strong>CO2050 — Database Systems Module Project</strong><br />
  Department of Computer Engineering | Faculty of Engineering | University of Peradeniya
</p>

<p align="center">
  <em>Designed and engineered by <strong>Team Mythix</strong> (Group 03)</em>
</p>

<p align="center">
  <a href="./Group03_Report.pdf"><img src="https://img.shields.io/badge/Project_Report-Group03__Report.pdf-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Project Report" /></a>
  <a href="#cloud-architecture--devops-pipeline"><img src="https://img.shields.io/badge/AWS-EC2_Deployed-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="AWS EC2" /></a>
  <a href="#cloud-architecture--devops-pipeline"><img src="https://img.shields.io/badge/Docker-Compose_Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" /></a>
  <a href="#cloud-architecture--devops-pipeline"><img src="https://img.shields.io/badge/Jenkins-CI%2FCD_Automated-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins" /></a>
</p>

<p align="center">
  <a href="#technologies-used"><img src="https://img.shields.io/badge/PostgreSQL-15+-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /></a>
  <a href="#technologies-used"><img src="https://img.shields.io/badge/Express.js-5.x-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js" /></a>
  <a href="#technologies-used"><img src="https://img.shields.io/badge/React-18.x-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" /></a>
  <a href="#technologies-used"><img src="https://img.shields.io/badge/Node.js-v18+-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" /></a>
  <a href="#technologies-used"><img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  <a href="#technologies-used"><img src="https://img.shields.io/badge/TailwindCSS-v4-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /></a>
  <a href="#testing--quality-assurance"><img src="https://img.shields.io/badge/Jest-Tested-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest" /></a>
  <a href="#testing--quality-assurance"><img src="https://img.shields.io/badge/Vitest-Verified-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" /></a>
</p>

---

## 📑 Quick Navigation

- [📄 Project Report & Documentation](#-project-report--documentation)
- [📌 Executive Overview](#-executive-overview)
- [🛠️ Technology Stack](#️-technology-stack)
- [☁️ Cloud Architecture & DevOps Pipeline](#️-cloud-architecture--devops-pipeline)
- [🏛️ Database Architecture & Relational Design](#️-database-architecture--relational-design)
- [👥 Role-Based Access Control (RBAC)](#-role-based-access-control-rbac)
- [📋 Medico-Legal Form Pipelines](#-medico-legal-form-pipelines)
- [🚀 Quick Start & Deployment Guide](#-quick-start--deployment-guide)
- [🧪 Testing & Quality Assurance](#-testing--quality-assurance)
- [🔐 Pre-Seeded Test Accounts](#-pre-seeded-test-accounts)
- [👥 Team Mythix](#-team-mythix-group-03)

---

## 📄 Project Report & Documentation

The official academic report for this project is available in this repository:

> 📘 **[Download Group 03 Project Report (Group03_Report.pdf)](./Group03_Report.pdf)**
> 
> *Comprehensive 60+ page submission detailing domain problem analysis, relational database schema normalization (3NF/BCNF), entity relationship diagrams, query optimization, indexing benchmarks, system security policies, and deployment logs.*

- **UI/UX Prototype**: [Figma Design File](https://www.figma.com/design/ocMZgrr7VfgLWN6aYm8OC2/Forensic-Medical-System-Design)
- **Source Repository**: [GitHub - saninduhansara/Forensic-Medical-Project](https://github.com/saninduhansara/Forensic-Medical-Project)

---

## 📌 Executive Overview

In Sri Lanka's healthcare and judicial ecosystem, forensic medical records (MLEF, MLR, PMR, and Autopsy reports) have traditionally relied on handwritten paperwork, physical registries, and fragmented departmental archives. This introduces critical vulnerabilities: loss or degradation of sensitive evidence, slow turnaround times for court trials, unauthorized record manipulation, and delayed laboratory specimen analysis.

Developed for the **CO2050 Database Systems** module at the **University of Peradeniya**, the **Forensic Medical Records Management System** transforms this workflow into an enterprise-grade, paperless, tamper-evident digital platform.

### Core Objectives:
1. **Relational Integrity & Legal Compliance**: Strict adherence to relational database constraints, cascading integrity, and foreign-key validation reflecting Sri Lankan legal procedures.
2. **Chain of Custody & Tamper Evidence**: End-to-end auditable trails for evidence collected during post-mortems, autopsy dissection notes, and specimen routing.
3. **Role-Based Security**: Cryptographically secure separation of duties between Police Officers, Medical Officers (MO), Judicial Medical Officers (JMO), and Forensic Lab Technicians.
4. **Court-Ready Document Automation**: Automated, instantaneous generation of standardized, formatted legal PDF reports containing SLMC registration details, hospital seals, and chronological injury maps.
5. **Modern Cloud Native Operations**: Containerized via **Docker**, automated via **Jenkins CI/CD**, and deployed live on **AWS EC2**.

---

## 🛠️ Technology Stack

The project adopts the modern **PERN Stack** (PostgreSQL, Express, React, Node.js) paired with cloud DevOps tools to deliver speed, reliability, and security:

### 🌟 Core PERN & Cloud DevOps Infrastructure

<div align="center">
  <table>
    <tr>
      <td align="center" width="14%">
        <a href="https://www.postgresql.org/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="60" height="60" alt="PostgreSQL" />
        </a><br />
        <strong>PostgreSQL</strong><br />
        <sub>v15+ Relational DB</sub>
      </td>
      <td align="center" width="14%">
        <a href="https://expressjs.com/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" width="60" height="60" alt="Express.js" />
        </a><br />
        <strong>Express.js</strong><br />
        <sub>v5.x REST API</sub>
      </td>
      <td align="center" width="14%">
        <a href="https://react.dev/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="60" height="60" alt="React 18" />
        </a><br />
        <strong>React 18</strong><br />
        <sub>SPA Frontend</sub>
      </td>
      <td align="center" width="14%">
        <a href="https://nodejs.org/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="60" height="60" alt="Node.js" />
        </a><br />
        <strong>Node.js</strong><br />
        <sub>v18+ Runtime</sub>
      </td>
      <td align="center" width="14%">
        <a href="https://www.docker.com/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="60" height="60" alt="Docker" />
        </a><br />
        <strong>Docker</strong><br />
        <sub>Container Engine</sub>
      </td>
      <td align="center" width="14%">
        <a href="https://www.jenkins.io/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" width="60" height="60" alt="Jenkins" />
        </a><br />
        <strong>Jenkins</strong><br />
        <sub>CI/CD Pipeline</sub>
      </td>
      <td align="center" width="14%">
        <a href="https://aws.amazon.com/ec2/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="60" height="60" alt="AWS EC2" />
        </a><br />
        <strong>AWS EC2</strong><br />
        <sub>Cloud Deployment</sub>
      </td>
    </tr>
  </table>
</div>

### 🎨 Frontend Ecosystem & Testing Tools

<div align="center">
  <table>
    <tr>
      <td align="center" width="16%">
        <a href="https://www.typescriptlang.org/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="50" height="50" alt="TypeScript" />
        </a><br />
        <strong>TypeScript</strong><br />
        <sub>Type Safety</sub>
      </td>
      <td align="center" width="16%">
        <a href="https://tailwindcss.com/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" width="50" height="50" alt="Tailwind CSS" />
        </a><br />
        <strong>Tailwind CSS</strong><br />
        <sub>v4 Utility Styling</sub>
      </td>
      <td align="center" width="16%">
        <a href="https://vitejs.dev/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vitejs/vitejs-original.svg" width="50" height="50" alt="Vite" />
        </a><br />
        <strong>Vite</strong><br />
        <sub>Bundler & Dev</sub>
      </td>
      <td align="center" width="16%">
        <a href="https://jestjs.io/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jest/jest-plain.svg" width="50" height="50" alt="Jest" />
        </a><br />
        <strong>Jest</strong><br />
        <sub>API Testing</sub>
      </td>
      <td align="center" width="16%">
        <a href="https://nginx.org/">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="50" height="50" alt="Nginx" />
        </a><br />
        <strong>Nginx</strong><br />
        <sub>Web Reverse Proxy</sub>
      </td>
    </tr>
  </table>
</div>

### Architectural Roles:
- **PostgreSQL 15+**: Primary relational engine storing users, examinees, legal forms, and autopsy findings. Utilizes B-Tree indexing, array types (`TEXT[]`), and foreign key cascade rules.
- **Node.js & Express 5 (ES Modules)**: High-throughput REST API with centralized error boundaries, recursive request sanitization, connection pooling (`pg.Pool`), and JWT auth guards.
- **React 18 & TypeScript 5**: Component-driven Single Page Application (SPA) powered by Vite, Tailwind CSS v4, Lucide icons, and interactive form validations.
- **Docker & Docker Compose**: Multi-container setup isolating the `forensic-frontend` (Nginx) and `forensic-backend` (Node.js) on a private bridge network.
- **Jenkins CI/CD**: Automated integration testing (Jest + Vitest) and zero-downtime container rolling deployments on every git push.
- **AWS EC2 (Ubuntu Linux)**: Production host running Docker Engine with hardened security groups and persistent volume management.

---

## ☁️ Cloud Architecture & DevOps Pipeline

The application is hosted on an **AWS EC2** instance with an automated continuous integration and continuous deployment pipeline managed by **Jenkins** and **Docker Compose**.

### System Architecture Flow

<p align="center">
  <img src="./images/architecture_flow.svg" alt="System Architecture Flow Diagram" width="100%" style="border-radius: 12px; box-shadow: 0 8px 30px rgba(0,0,0,0.5);" />
</p>

### End-to-End Delivery Lifecycle:

```mermaid
flowchart LR
    Dev([💻 Developer Push]) -->|git push origin main| GH[🐙 GitHub Repository]
    GH -->|Webhook Trigger| JK[⚙️ Jenkins CI/CD on EC2]

    subgraph AWS["☁️ Amazon Web Services (AWS EC2 Instance)"]
        subgraph Pipeline["Jenkins Pipeline Execution"]
            JK --> S1[1. Checkout SCM]
            S1 --> S2[2. Backend Tests: Jest]
            S2 --> S3[3. Frontend Tests: Vitest]
            S3 --> S4[4. Inject Secrets /project_secrets]
            S4 --> S5[5. Docker Compose Build & Up]
            S5 --> S6[6. Docker Image Pruning]
        end

        subgraph Containers["Docker Engine Orchestration"]
            S5 -.-> FE["🌐 Container: forensic-frontend (Port 80: Nginx + React)"]
            S5 -.-> BE["⚡ Container: forensic-backend (Port 3000: Express 5)"]
        end

        FE -->|REST API Calls /api/*| BE
        BE -->|PostgreSQL Protocol :5432| DB[("🐘 PostgreSQL Relational DB")]
        BE -->|SMTP / 2FA Verification| Mail["✉️ Email Notification Service"]
    end

    Users([👥 Doctors / JMOs / Police / Lab Techs]) -->|HTTP Port 80| FE
```

### Key DevOps & Cloud Engineering Highlights:

1. **Webhook-Triggered CI/CD**: Pushes to `main` instantly trigger the `Jenkinsfile` pipeline on the AWS EC2 instance.
2. **Automated Quality Gates**:
   - Backend tests run across 7 suites with **Jest** and **Supertest**.
   - Frontend tests run with **Vitest** and **React Testing Library**.
   - Builds abort immediately if any test fails, keeping production safe.
3. **Secret Decoupling**: Database connection strings, SMTP credentials, and JWT secret keys reside strictly outside version control in `/var/lib/jenkins/project_secrets/` on the EC2 host and are injected during build time.
4. **Zero-Downtime Deployment**: Executed via `docker compose build --no-cache` and `docker compose up -d --remove-orphans`.
5. **Storage Safeguard**: Jenkins automatically runs `docker image prune -af` post-deployment, guaranteeing the EC2 instance's 30GB disk volume never fills up.

---

## 🏛️ Database Architecture & Relational Design

The database schema (`schema.sql`) adheres to **3NF/BCNF** standards to eliminate anomaly risks while accommodating complex forensic workflows.

### Entity-Relationship Diagram (ERD)

```mermaid
erDiagram
    users ||--o{ patients : "registers"
    users ||--o{ mlef_forms : "creates / examines"
    users ||--o{ mlr_reports : "compiles"
    users ||--o{ pmr_forms : "conducts"
    users ||--o{ autopsy_forms : "performs"
    users ||--o{ lab_requests : "orders / processes"

    patients ||--o{ mlef_forms : "has"
    patients ||--o{ mlr_reports : "has"
    patients ||--o{ pmr_forms : "has"
    patients ||--o{ autopsy_forms : "has"
    patients ||--o{ lab_requests : "subject_of"

    mlr_reports ||--|{ mlr_injuries : "catalogs"
    mlr_reports ||--o{ mlr_grievous_entries : "classifies"

    pmr_forms ||--|{ pmr_identifiers : "verified_by"

    autopsy_forms ||--o{ autopsy_articles : "secures"

    users {
        varchar id PK
        varchar name
        varchar role "doctor | jmo | admin | lab"
        varchar email UK
        varchar password_hash
        boolean email_verified
        varchar verification_code_hash
        timestamp verification_expires_at
    }

    patients {
        varchar id PK
        varchar nic UK
        varchar name
        date dob
        varchar sex
        text address
        timestamp registered_at
    }

    mlef_forms {
        varchar id PK
        varchar patient_id FK
        varchar mlef_no
        varchar police_station
        text[] body_harm_types
        text[] causative_weapon
        varchar hurt_category
        varchar status "draft | complete"
    }

    mlr_reports {
        varchar id PK
        varchar patient_id FK
        text[] non_grievous_nos
        varchar doctor_name
        varchar status "draft | submitted"
    }

    mlr_injuries {
        serial id PK
        varchar mlr_id FK
        varchar injury_no
        text description
    }

    mlr_grievous_entries {
        varchar id PK
        varchar mlr_id FK
        varchar injury_no
        varchar limb
        text remarks
    }

    pmr_forms {
        varchar id PK
        varchar patient_id FK
        varchar inquest_no
        varchar case_no
        varchar doctor_conducting
        varchar status "draft | submitted"
    }

    pmr_identifiers {
        serial id PK
        varchar pmr_id FK
        varchar name
        text address
    }

    autopsy_forms {
        varchar id PK
        varchar patient_id FK
        varchar pm_register_serial_no
        text cause_of_death
        text locus_examination
        text external_examination
        varchar status "draft | complete"
    }

    autopsy_articles {
        serial id PK
        varchar autopsy_id FK
        text description
        text purpose
    }

    lab_requests {
        varchar id PK
        varchar patient_id FK
        varchar form_type "mlef | mlr | pmr"
        text[] test_types
        varchar urgency "routine | urgent | stat"
        varchar status "pending | in_progress | completed"
        text test_results
    }
```

### Relational Schema Highlights:
- **Foreign Key Cascades**: Child entities (`mlr_injuries`, `mlr_grievous_entries`, `pmr_identifiers`, `autopsy_articles`) maintain referential integrity via `ON DELETE CASCADE`.
- **PostgreSQL Native Arrays**: Employed for multi-select legal fields (`body_harm_types`, `causative_weapon`, `sexual_assault_signs`, `test_types`) to preserve normalized representation without unnecessary junction table overhead.
- **B-Tree Query Optimization**: Secondary performance indexes are automatically created at backend startup to eliminate sequential scans on frequent joins:
  ```sql
  CREATE INDEX IF NOT EXISTS idx_mlef_forms_patient_id ON mlef_forms(patient_id);
  CREATE INDEX IF NOT EXISTS idx_mlr_reports_patient_id ON mlr_reports(patient_id);
  CREATE INDEX IF NOT EXISTS idx_pmr_forms_patient_id ON pmr_forms(patient_id);
  CREATE INDEX IF NOT EXISTS idx_autopsy_forms_patient_id ON autopsy_forms(patient_id);
  CREATE INDEX IF NOT EXISTS idx_lab_requests_patient_id ON lab_requests(patient_id);
  ```

---

## 👥 Role-Based Access Control (RBAC)

The system implements strict separation of concerns through 4 dedicated roles:

| Role | Badge | Permissions & System Scope |
| :--- | :---: | :--- |
| **Medical Officer (MO / Doctor)** | `doctor` | Examines live clinical examinees, completes **Part B of MLEF**, drafts and submits **MLR reports**, tracks injury classifications, and orders forensic lab investigations. |
| **Judicial Medical Officer (JMO)** | `jmo` | Oversees death investigations, conducts post-mortem inquests (**PMR**), performs comprehensive anatomical **Autopsy examinations**, records causes of death, and logs evidentiary articles. |
| **Police Officer / Hospital Clerk** | `admin` | Registers new examinees and patients, records basic demographics and National Identity Cards (NIC), issues **Part A of MLEF**, and manages staff accounts. |
| **Forensic Lab Technician** | `lab` | Manages diagnostic queues, accepts specimen orders (**Toxicology**, **Blood Alcohol Content**, **Drug Screening**), updates specimen processing states, and certifies forensic findings. |

---

## 📋 Medico-Legal Form Pipelines

```
 ┌─────────────────┐       ┌────────────────────────┐       ┌──────────────────────┐
 │  Police Intake  │ ───►  │  Clinical Examination  │ ───►  │  Legal Certification │
 │  (MLEF Part A)  │       │  (MLEF Part B / MLR)   │       │  (Court-Ready PDF)   │
 └─────────────────┘       └────────────────────────┘       └──────────────────────┘
                                       │
                                       ▼
                           ┌────────────────────────┐
                           │   Lab Investigation    │
                           │ (Routine/Urgent/STAT)  │
                           └────────────────────────┘
```

1. **MLEF (Medico-Legal Examination Form)**: Two-stage clinical intake. Part A records police requisition and alleged assault history; Part B records clinical harm, weapon correlation, alcohol/narcotic influence, and life danger status.
2. **MLR (Medico-Legal Report)**: Comprehensive legal injury report. Distinctly catalogs non-grievous vs. grievous injuries according to the Sri Lankan Penal Code.
3. **PMR (Post-Mortem Report)**: Magistrate court inquest documentation with body identification witnesses and external post-mortem examination.
4. **Detailed Autopsy Form**: Full systemic anatomical dissection form covering cranial, thoracic, abdominal, cardiovascular, and skeletal structures, including evidentiary articles secured for criminal trials.
5. **Forensic Lab Requests**: Diagnostic ordering pipeline categorized by urgency (`routine`, `urgent`, `stat`) with real-time feedback into clinical records.

---

## 🚀 Quick Start & Deployment Guide

### Prerequisites
- **Docker** & **Docker Compose** installed (or **Node.js 18+** & **PostgreSQL 15+** for bare-metal setup).
- Git.

---

### Option 1: Docker Compose Deployment (Recommended)

To run the entire multi-container production stack:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/saninduhansara/Forensic-Medical-Project.git
   cd Forensic-Medical-Project
   ```

2. **Configure environment variables**:
   ```bash
   cp backend/.env.example backend/.env
   ```
   *Edit `backend/.env` with your PostgreSQL connection string and JWT secret.*

3. **Launch with Docker Compose**:
   ```bash
   docker compose up -d --build
   ```

4. **Access the application**:
   - **Frontend UI**: `http://localhost` (Port 80)
   - **Backend API**: `http://localhost:3000/api` (Port 3000)

To stop the containers:
```bash
docker compose down
```

---

### Option 2: Local Development Setup

#### 1. Backend Setup:
```bash
cd backend
npm install

# Initialize database schema & seed initial demo data
npm run db:init
npm run db:seed

# Start backend in development mode with nodemon
npm start
```

#### 2. Frontend Setup:
```bash
cd ../frontend
npm install

# Start Vite development server
npm run dev
```
*Frontend runs on `http://localhost:5173`.*

---

## 🧪 Testing & Quality Assurance

Both the backend and frontend are guarded by rigorous test suites integrated into the Jenkins CI/CD pipeline:

```bash
# Run Backend Integration Tests (Jest + Supertest)
cd backend
npm test

# Run Frontend Component Tests (Vitest + React Testing Library)
cd ../frontend
npm test
```

### Test Coverage Highlights:
- **Backend**: Complete coverage of authentication (login, JWT verification, password reset, 2FA code hashing), input sanitization, and CRUD operations across all 7 route modules (`auth`, `patients`, `mlef`, `mlr`, `pmr`, `autopsy`, `lab`).
- **Frontend**: Tests for UI badge rendering, form validation sections, input error handling, read-only view state protections, and PDF generator output structures.

---

## 🔐 Pre-Seeded Test Accounts

When the database is seeded using `npm run db:seed`, the following accounts are pre-configured and pre-verified:

| Role | Name | Email | Password |
| :--- | :--- | :--- | :--- |
| **Doctor / MO** | Dr. Amal Perera | `dr.perera@forensic.gov` | `Doctor@123` |
| **Doctor / MO** | Dr. Saman Fernando | `dr.fernando@forensic.gov` | `Doctor@456` |
| **JMO** | Dr. Ruwan Perera | `dr.ruwan@forensic.gov` | `Jmo@123` |
| **Admin / Police** | Nimal Silva | `nimal.silva@forensic.gov` | `Admin@123` |
| **Admin / Police** | Kamani Dissanayake | `kamani.d@forensic.gov` | `Admin@456` |
| **Lab Tech** | Chaminda Wickramasinghe | `chaminda.w@forensic.gov` | `Lab@123` |
| **Lab Tech** | Dilini Jayawardena | `dilini.j@forensic.gov` | `Lab@456` |

---

## 👥 Team Mythix (Group 03) — Contributors

Developed with pride for the **CO2050 Database Systems** module:
- **Department of Computer Engineering**, Faculty of Engineering
- **University of Peradeniya**, Sri Lanka

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <img src="https://people.ce.pdn.ac.lk/images/students/e22/e22130.jpg" width="115" height="115" alt="S.H.S. Hansara" style="border-radius: 50%; object-fit: cover; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" /><br /><br />
        <strong>S.H.S. Hansara</strong><br />
        <code>E/22/130</code><br />
        <a href="mailto:e22130@eng.pdn.ac.lk">e22130@eng.pdn.ac.lk</a>
      </td>
      <td align="center" width="25%">
        <img src="https://people.ce.pdn.ac.lk/images/students/e22/e22008.jpg" width="115" height="115" alt="T.H. Abeywickrama" style="border-radius: 50%; object-fit: cover; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" /><br /><br />
        <strong>T.H. Abeywickrama</strong><br />
        <code>E/22/008</code><br />
        <a href="mailto:e22008@eng.pdn.ac.lk">e22008@eng.pdn.ac.lk</a>
      </td>
      <td align="center" width="25%">
        <img src="https://people.ce.pdn.ac.lk/images/students/e22/e22126.jpg" width="115" height="115" alt="H.P.J. Gunawardhana" style="border-radius: 50%; object-fit: cover; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" /><br /><br />
        <strong>H.P.J. Gunawardhana</strong><br />
        <code>E/22/126</code><br />
        <a href="mailto:e22126@eng.pdn.ac.lk">e22126@eng.pdn.ac.lk</a>
      </td>
      <td align="center" width="25%">
        <img src="https://people.ce.pdn.ac.lk/images/students/e22/e22135.jpg" width="115" height="115" alt="H.T.D. Hatharasinghe" style="border-radius: 50%; object-fit: cover; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" /><br /><br />
        <strong>H.T.D. Hatharasinghe</strong><br />
        <code>E/22/135</code><br />
        <a href="mailto:e22135@eng.pdn.ac.lk">e22135@eng.pdn.ac.lk</a>
      </td>
    </tr>
  </table>
</div>

### Repository & Artifacts:
- **Project Report**: [Group03_Report.pdf](./Group03_Report.pdf)
- **CI/CD Configuration**: [Jenkinsfile](./Jenkinsfile)
- **Container Definition**: [docker-compose.yml](./docker-compose.yml)
- **Database Schema**: [backend/schema.sql](./backend/schema.sql)

---

<p align="center">
  <sub>© 2026 Team Mythix — Built for academic evaluation under CO2050 Database Systems module.</sub>
</p>

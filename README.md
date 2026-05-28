# MAWUMS / ProcuraX

### Enterprise Procurement & Workflow Intelligence Platform

ProcuraX is a secure, enterprise-grade procurement, approval, and compliance management platform designed to digitize and govern end-to-end purchasing operations across enterprises, ministries, institutions, and regulated organizations.

The platform transforms fragmented, manual procurement processes including spreadsheets, emails, paper-based approvals, and disconnected communication channels into a centralized, fully auditable, workflow-driven digital ecosystem.

ProcuraX enforces structured approval governance, procurement transparency, budget accountability, and operational traceability across every stage of the procurement lifecycle.

---

# Executive Summary (Investor View)

MAWUMS / ProcuraX is a **workflow automation and procurement governance platform** that enforces structured approval hierarchies, budget controls, and vendor accountability.

It is designed for:

- Government procurement systems (GovTech)
- Large enterprises with strict audit requirements
- Financially controlled procurement environments
- Multi-department organizations with layered approvals

---

# Core Value Proposition

ProcuraX is not simply a procurement application.

It is a **workflow intelligence and approval governance platform** built to ensure that every operational step follows controlled authorization pathways before progressing to the next stage.

Every procurement activity — from requisition creation to goods receipt — is governed by configurable approval workflows where authorized personnel can:

- Approve
- Reject
- Escalate
- Delegate
- Route

before the process advances to the next operational level.

This guarantees:

- Procurement control
- Financial accountability
- Regulatory compliance
- Audit traceability
- Segregation of duties
- Enterprise governance enforcement

---

# Core Modules

## 1. Dashboard

Centralized operational visibility into procurement activities, pending approvals, purchase orders, supplier activities, inventory movement, and workflow status metrics.

---

## 2. Requisitions Management

- Create procurement requests
- Attach supporting documents
- Define item requirements
- Submit requests into approval workflows
- Track requisition lifecycle in real time
- Department-based categorization

---

## 2. Suppliers

Centralized supplier and vendor management module supporting procurement governance and supplier lifecycle visibility.

- Supplier onboarding
- Supplier profile management
- Vendor categorization
- Compliance & documentation tracking
- Supplier relationship visibility
- Approved supplier management

---

## 3. Workflow & Approval Engine

Enterprise workflow engine supporting:

- Multi-level approval routing
- Approval delegation
- Conditional workflow escalation
- Approval limit enforcement
- Rejection and return workflows
- Full approval audit trail

No process advances without authorized approval.

---

## 4. Suppliers

- Supplier onboarding
- Supplier profile management
- Vendor categorization
- Supplier compliance tracking
- Procurement relationship visibility

---

## 5. Purchase Orders

- Generate purchase orders from approved requisitions
- Track PO lifecycle
- Supplier assignment and fulfillment monitoring
- Procurement execution tracking

---

## 6. Receive Goods

- Goods receipt processing
- Quantity validation
- Delivery verification
- Procurement completion tracking
- Inventory synchronization

---

## 7. Inventory

- Inventory monitoring
- Stock movement tracking
- Item availability visibility
- Procurement-to-stock integration

---

## 8. Documents

Centralized procurement document repository for:

- Quotations
- Invoices
- Purchase orders
- Contracts
- Delivery documents
- Approval attachments

---

## 9. Administration

### Approval Limit Management

Defines financial thresholds and authorization boundaries for approvers.

### Approval Delegation

Supports temporary approval reassignment and operational continuity.

### Approval Routing Matrix

Configurable workflow routing engine controlling approval sequences and escalation logic.

### Users & Roles

Enterprise-grade RBAC (Role-Based Access Control) for secure operational segregation.

---

## 10. Reports

Operational and compliance reporting including:

- Procurement history
- Approval performance
- Supplier analytics
- Budget tracking
- Audit reporting
- Inventory reports

---

# System Architecture

ProcuraX follows enterprise-grade architectural principles including:

- Clean Architecture
- CQRS (Command Query Responsibility Segregation)
- Workflow-driven domain modeling
- Role-Based Access Control (RBAC)
- Audit-first system design
- Modular service separation
- Secure API boundaries

---

# Technology Stack

| Layer        | Technology                |
| ------------ | ------------------------- |
| Frontend     | Blazor Server             |
| Backend      | ASP.NET Core Web API      |
| Database     | SQL Server                |
| ORM          | Entity Framework Core     |
| Auth         | Duende IdentityServer     |
| Real-time    | SignalR                   |
| Deployment   | Azure / Docker            |
| Architecture | Clean Architecture + CQRS |

---

# End-to-End Procurement Flow

```text
Requisition Created
        ↓
Workflow Engine Evaluates Rules
        ↓
Budget Validation Check
        ↓
Multi-Level Approval Process
        ↓
Purchase Order Generation
        ↓
Vendor Fulfillment
        ↓
Audit Logging & Reporting
```

---

# Target Sectors

ProcuraX is designed for organizations requiring structured procurement governance including:

- Government institutions
- Ministries & public sector agencies
- Financial institutions
- Universities & educational institutions
- NGOs & donor-funded organizations
- Enterprise procurement departments

---

# Security & Compliance

- Role-Based Access Control (RBAC)
- Workflow authorization enforcement
- Immutable audit trails
- Approval traceability
- Controlled operational segregation
- Secure authentication & authorization

---

# System Screenshots

## Dashboard Overview

![Dashboard](screenshots/dashboard.png)

---

## Requisition Management

![Requisitions](screenshots/requisitions.png)

---

## Approval Workflow Engine

![Approvals](screenshots/approvals.png)

---

## Vendor Management

![Vendors](screenshots/vendors.png)

---

## Purchase Orders

![Purchase Orders](screenshots/purchase-orders.png)

---

## Good Receive

![Purchase Orders](screenshots/good-receipt.png)

---

## Audit Logs & Compliance

![Audit Logs](screenshots/audit-logs.png)

---

# Key Differentiators

### Workflow Engine (Core Strength)

Not just CRUD approvals — a **rule-driven workflow system** with dynamic routing.

### Budget Enforcement Layer

Prevents financial approval bypass and uncontrolled spending.

### Audit-First Design

Every action is logged, traceable, and compliance-ready.

### Enterprise Security Model

RBAC + IdentityServer integration for strict access control.

---

# Roadmap

### Completed

- Requisition Management
- Approval Workflow Engine
- Vendor Management
- Purchase Orders
- Audit Logging
- RBAC Security Model

### In Progress / Future

- Budget forecasting engine
- AI procurement recommendations
- ERP integrations (SAP / Oracle)
- Mobile approval application
- Advanced analytics dashboard

---

# Security Model

- Role-Based Access Control (RBAC)
- IdentityServer authentication layer
- Audit trail immutability
- Workflow-level permission enforcement
- Secure API boundaries

---

# Business & Market Positioning

ProcuraX sits in the intersection of:

- GovTech modernization
- Enterprise workflow automation
- Financial control systems
- ERP augmentation layer (not replacement)

---

### Ideal Customers:

- Government ministries
- Universities & public institutions
- Large enterprises
- Financial institutions
- NGOs with procurement governance needs

---

# Author

**Somad Yessoufou**
Senior Software Engineer specializing in:

- Enterprise .NET systems
- Workflow & approval engines
- Microservices architecture
- Real-time distributed systems
- GovTech & logistics platforms

---

# Portfolio Context

This project is part of a broader enterprise systems portfolio including:

- **Haulix** – Fleet Operations & Logistics Intelligence Platform
- **ProcuraX / MAWUMS** – Procurement & Workflow Governance System

Together, these systems demonstrate expertise in:

- Enterprise architecture design
- Workflow automation systems
- Real-time distributed systems
- SaaS-grade backend engineering

---

# License

This project is a portfolio and demonstration system.

Commercial use, redistribution, or replication without permission is prohibited.

For licensing or enterprise deployment inquiries, contact the author.

---

# Support

If you find this project valuable:

- Star the repository
- Watch for updates
- Connect for collaboration opportunities
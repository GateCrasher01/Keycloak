# 🔐 Secure Authentication with OpenID Connect using Keycloak and Flask

## 📌 Purpose

This project demonstrates how to integrate **Keycloak** with **OpenID Connect (OIDC)** to enable **Single Sign-On (SSO)** functionality across web applications. It leverages Keycloak as an **Identity and Access Management (IAM)** solution to secure user authentication and session management in a Python-based web application using **Flask**.

---

## 📦 Scope

- ✅ Set up **Keycloak** as an **OpenID Connect Identity Provider**.
- ✅ Configure **SSO** across multiple websites so users can log in once and access all linked services.
- ✅ Provide detailed configuration for:
  - Keycloak
  - Client application (Flask)
  - Underlying **OpenID Connect Authorization Code Flow**

---

## 📁 Deliverables

### 1. 🐍 Flask Backend Application
A fully functional Flask app that integrates with Keycloak via OpenID Connect.  
Handles:
- User authentication and authorization
- Token handling (ID, Access, Refresh)
- Session management

### 2. ⚙️ Keycloak Configuration
A detailed setup of Keycloak to act as the central IdP:
- Client configuration
- Realm and user creation
- Role and policy assignment
- Access token settings

### 3. 🔁 OIDC Flow Implementation
Demonstration of **OpenID Connect Authorization Code Flow**:
- Redirects to Keycloak login
- Receives Authorization Code
- Exchanges for tokens securely
- Validates and uses ID token for session creation

# UiTM Mobile SecOps 21 Days Challenge

> **"Mobile Defense and Intelligence: Build Fast, Defend Smarter"**

## 📋 Challenge Information

- **Organizer:** UiTM Cawangan Perak, Kampus Tapah
- **Industry Partner:** Metairflow R&D Sdn. Bhd.
- **Duration:** 24 November - 22 December 2025
- **Prize Pool:** RM 4,000 (including feature bonuses)
- **Submission Deadline:** 17 December 2025

## 🎯 Overview

The Mobile SecOps 21 Days Challenge is a 3-week applied competition designed to uncover UiTM's most capable full-stack engineers. Participants develop secure, intelligent mobile prototypes that blend front-end usability, back-end integrity, and AI-driven defense.

This challenge simulates real DevSecOps environments using the Rentverse architecture, integrating best practices from:
- Frontend Engineering
- Backend Architecture
- AI/ML Systems
- DevOps & Systems Integration

## 🎓 Team Information

**Team Name:** `[Your Team Name]`

<table>
  <tr>
    <td align="center">
      <img src="[member1-photo-url]" width="150px;" alt="Member 1"/><br />
      <sub><b>[Member 1 Name]</b></sub><br />
      <sub>[Role/Specialization]</sub>
    </td>
    <td align="center">
      <img src="[member2-photo-url]" width="150px;" alt="Member 2"/><br />
      <sub><b>[Member 2 Name]</b></sub><br />
      <sub>[Role/Specialization]</sub>
    </td>
    <td align="center">
      <img src="[member3-photo-url]" width="150px;" alt="Member 3"/><br />
      <sub><b>[Member 3 Name]</b></sub><br />
      <sub>[Role/Specialization]</sub>
    </td>
  </tr>
</table>

## 🏗️ Core Development Modules

### Module 1: Secure Login & MFA ⭐⭐
Multi-factor authentication with OTP-based login and role-based access control.

**Security Focus:** Authentication & Authorization (OWASP M1–M3)

### Module 2: Secure API Gateway ⭐⭐
HTTPS implementation, JWT tokens, rate-limiting, and access validation.

**Security Focus:** Secure Communication (OWASP M5–M6)

### Module 3: Digital Agreement (Mobile) ⭐⭐
Secure signature validation and access permissions for rental agreements.

**Security Focus:** Data Integrity & Workflow Validation

### Module 4: Smart Notification & Alert System ⭐⭐
Activity logging with suspicious login pattern detection.

**Security Focus:** DevSecOps Monitoring & Incident Detection

### Module 5: Activity Log Dashboard ⭐⭐⭐
Admin-level logs for failed logins and critical actions.

**Security Focus:** Threat Visualization & Accountability

### Module 6: CI/CD Security Testing (Bonus) ⭐⭐⭐
GitHub Actions or Jenkins integration for static code analysis (SAST) and deployment checks.

**Security Focus:** Continuous Testing (DevSecOps)

## 🌟 Feature Innovation Pool (RM 2,000)

Our team has implemented the following bonus features:

- [ ] **Threat Intelligence System** (RM 500) - AI/rule-based detection for unusual access patterns
- [ ] **Zero-Trust Access Logic** (RM 500) - Conditional access based on device/location
- [ ] **Adaptive Defense Dashboard** (RM 500) - Interactive risk visualization with auto-response
- [ ] **Automated Security Testing** (RM 500) - OWASP ZAP/MobSF/GitHub Actions integration

## 🚀 Getting Started

### Prerequisites
```bash
[List your prerequisites here, e.g.:]
- Node.js v18+
- Flutter 3.x
- Firebase/Supabase account
- Docker (optional)
```

### Installation

1. Clone this repository:
```bash
git clone [your-repo-url]
cd uitm-devops-challenge_[team-name]
```

2. Install dependencies:
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

3. Configure environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Run the application:
```bash
# Development mode
npm run dev

# Production build
npm run build
```

## 📱 Application Features

### Security Features
- [Describe your security implementations]
- Multi-factor authentication (MFA/OTP)
- JWT-based session management
- Rate limiting and API protection
- Real-time threat monitoring
- Secure data encryption

### User Roles
- **Student:** Browse properties, create rental agreements
- **Owner:** Manage properties, approve agreements
- **Admin:** System monitoring, user management, security dashboard

## 🏛️ Architecture
```
[Add your architecture diagram or description here]

Frontend (Flutter/React Native)
    ↓
API Gateway (JWT Auth, Rate Limiting)
    ↓
Backend Services (Node.js/Python)
    ↓
Database (PostgreSQL/MongoDB)
    ↓
AI/ML Services (Anomaly Detection)
```

## 🔒 Security Implementation

### OWASP Mobile Top 10 Coverage
- **M1:** Improper Platform Usage - [Your implementation]
- **M2:** Insecure Data Storage - [Your implementation]
- **M3:** Insecure Communication - [Your implementation]
- **M5:** Insufficient Cryptography - [Your implementation]
- **M6:** Insecure Authorization - [Your implementation]

### DevSecOps Practices
- Automated security testing in CI/CD pipeline
- Static Application Security Testing (SAST)
- Dynamic Application Security Testing (DAST)
- Dependency vulnerability scanning
- Security monitoring and alerting

## 📊 Testing
```bash
# Run unit tests
npm test

# Run security tests
npm run security-test

# Run integration tests
npm run test:integration
```

## 📸 Screenshots

[Add screenshots of your application here]

## 🎥 Demo

- **Live Demo:** [Your deployment link]
- **Demo Video:** [Your video link]
- **Presentation Slides:** [Your slides link]

## 📚 Documentation

- [API Documentation](./docs/API.md)
- [Security Architecture](./docs/SECURITY.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)
- [User Manual](./docs/USER_GUIDE.md)

## 🛠️ Technology Stack

**Frontend:**
- [Your frontend tech]

**Backend:**
- [Your backend tech]

**Database:**
- [Your database]

**DevOps:**
- [Your DevOps tools]

**Security Tools:**
- [Your security tools]

## 👥 Consultation Support

We received guidance from:
- [Consultant name and area, if applicable]

## 🏆 Awards Target

- [ ] 🥇 Top Technical Team (RM 1,200)
- [ ] 🥈 Best Secure Design Team (RM 800)
- [ ] 🌟 Feature Bonus Pool (RM 2,000)

## 📄 License

This project is developed for the UiTM Mobile SecOps Challenge. All rights remain with the student team, with Metairflow R&D Sdn. Bhd. holding review and adaptation rights for internal research.

## 🙏 Acknowledgments

- UiTM Cawangan Perak, Kampus Tapah
- Metairflow R&D Sdn. Bhd.
- All mentors and consultants

---

**Built with 💻 and 🔒 by [Team Name]**

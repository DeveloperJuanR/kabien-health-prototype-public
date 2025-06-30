# Kabien Health - Patient Flow Management System

> **A SwiftUI-based iPad application designed to streamline patient workflow tracking in Ambulatory Surgery Centers and Hospitals**

![Platform](https://img.shields.io/badge/Platform-iOS%2015%2B-blue)
![Language](https://img.shields.io/badge/Language-Swift%205.5%2B-orange)
![Framework](https://img.shields.io/badge/Framework-SwiftUI-green)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-purple)

---

## 📋 **Repository Notice**

**This repository serves as a comprehensive project introduction and technical overview for Kabien Health.** It is designed specifically for technical visitors, potential collaborators, and portfolio review purposes. 

⚠️ **Please note:** This repository contains **documentation and project overview materials only** - it does not include the actual application source code, which remains proprietary.

---

## 🏥 **What is Kabien Health?**

Kabien Health is a tablet-first patient tracking application that transforms how healthcare teams manage patient flow in surgical environments. The app provides real-time visibility into patient status across the perioperative journey, from registration through discharge.

**Target Users:** Nursing staff, surgical coordinators, and administrative personnel in ASCs and hospitals

**Problem Solved:** Eliminates communication gaps and reduces patient wait times by providing centralized, visual patient status tracking with instant updates across all team members.

---

## 🎯 **Why I Built This**

Having observed inefficiencies in healthcare communication firsthand, I recognized that many surgical facilities rely on outdated systems like whiteboards, phone calls, and fragmented software solutions. This creates:

- **Communication bottlenecks** between departments
- **Lost visibility** into patient status and location  
- **Increased wait times** due to coordination delays
- **Staff frustration** from constant status updates

Kabien Health addresses these pain points through intuitive visual design and real-time status management, allowing healthcare teams to focus on patient care rather than administrative coordination.

---

## ✨ **Key Features & User Experience**

### **Visual Workflow Management**
- Intuitive patient tracking through six workflow stages
- Color-coded rooms and status indicators for instant recognition
- Streamlined interface for quick status updates

### **Smart Bay Assignment System**
- Configurable Pre-Op and Post-Op bay management
- Custom bay naming per facility requirements
- Automatic bay-to-room associations with visual indicators

### **Real-Time Communication**
- Structured comment system with predefined templates
- Team-wide chat functionality with message categorization  
- Audio notifications for critical status changes

### **Administrative Controls**
- Room color configuration and management
- Physician and procedure type customization
- Device location assignment and permissions

### **Responsive Design**
- Optimized for iPad portrait and landscape orientations
- Touch-friendly interface with appropriate sizing for clinical gloves
- Consistent visual hierarchy and accessibility considerations

---

## 🛠 **Technical Implementation**

### **Architecture & Design Patterns**
- **MVVM Architecture** with clear separation of concerns
- **SwiftUI-only implementation** with no third-party dependencies
- **Reactive UI updates** using `@Published` properties and Combine framework
- **Modular component design** for maintainability and reusability

### **Core Technologies**
- **SwiftUI** for declarative UI development
- **Combine** for reactive programming and state management
- **UserDefaults** for local settings persistence
- **AVFoundation** for audio notification system

### **Key Technical Features**
- **State Management:** Centralized through `BoardViewModel` with computed properties for derived states
- **Data Modeling:** Comprehensive `Patient` model with workflow-specific properties and validation
- **UI Components:** Reusable components with consistent styling through custom text hierarchy system
- **Sound System:** Configurable audio feedback with multiple notification types
- **Device Management:** Unique device identification and location-based permissions

### **Code Quality & Organization**
```
Patient-Tracker/
├── Models/           # Core data structures (Patient, ProcedureStage, etc.)
├── ViewModels/       # Business logic and state management  
├── Views/           # SwiftUI UI components
│   ├── Components/   # Modular UI components
│   └── Admin/       # Administrative configuration interfaces
├── Utilities/       # Shared utilities (DateFormatters, SoundPlayer)
└── Resources/       # Audio files and assets
```

---

## 🚀 **What I Personally Contributed**

As the **sole developer** on this project, I was responsible for:

### **Product Strategy & Design**
- Conducted user research to understand healthcare workflow pain points
- Designed intuitive user interface optimized for clinical environments
- Created comprehensive feature specifications and user stories

### **Full-Stack iOS Development**
- Architected and implemented complete SwiftUI application from scratch
- Built robust MVVM architecture with reactive state management
- Developed 25+ custom SwiftUI components with consistent design system
- Implemented complex business logic for patient workflow management

### **System Design & Architecture**
- Designed scalable data models supporting multiple workflow types
- Created flexible configuration system for different facility requirements
- Implemented device management system with location-based permissions
- Built comprehensive activity logging and audit trail system

### **User Experience Engineering**
- Optimized touch interactions for clinical glove usage
- Implemented sophisticated visual feedback system with animations
- Created accessible interface following iOS Human Interface Guidelines
- Designed responsive layouts supporting multiple iPad orientations

---

## 📚 **What I Learned**

### **Healthcare Domain Expertise**
- Deep understanding of perioperative workflows and clinical terminology
- Knowledge of healthcare communication patterns and regulatory considerations
- Insight into medical device usability requirements and constraints

### **Advanced SwiftUI Development**
- Mastered complex state management patterns in SwiftUI applications
- Developed expertise in custom UI components and animation systems
- Learned performance optimization techniques for large dataset rendering

### **Product Development**
- Experience translating user needs into technical requirements
- Skills in iterative design and feature prioritization
- Understanding of healthcare software validation and testing approaches

### **Technical Architecture**
- Proficiency in designing maintainable MVVM architectures
- Experience with reactive programming patterns using Combine
- Knowledge of iOS app lifecycle management and data persistence strategies

---

## 📱 **Current Status & Future Development**

### **Prototype Completion**
This represents a **fully functional prototype** with complete UI/UX implementation. The application demonstrates:
- ✅ Complete patient workflow management
- ✅ Real-time status tracking and updates  
- ✅ Configurable administrative settings
- ✅ Comprehensive comment and communication systems

### **Production Readiness Roadmap**
Future development priorities for production deployment:
- **Backend Integration:** RESTful API with real-time synchronization
- **Data Persistence:** Core Data or cloud database implementation
- **Authentication System:** Role-based access control and user management
- **Analytics Dashboard:** Patient throughput metrics and performance tracking
- **HIPAA Compliance:** Security enhancements and audit logging

---

## 🎥 **See It In Action**

**Interested in a live demonstration?** 

Since this is a healthcare application with sensitive workflow information, the app is not publicly available for download. However, I'm happy to provide a **personalized demo** showcasing:

- Complete patient workflow management system
- Real-time status tracking and team communication
- Administrative configuration capabilities
- Technical architecture and code walkthrough

**Contact me to schedule a demo:**
- 📧 **Email:** developerjuanr@gmail.com
- 💼 **LinkedIn:** https://www.linkedin.com/in/dev-juanr/

---

## 🌐 **Learn More About Kabien Health**

This prototype represents the core patient tracking functionality of the broader Kabien Health platform vision. To learn more about the company's mission, team, and comprehensive approach to surgical workflow optimization, visit:

**🔗 [Kabien Health - Official Website](https://kabienhealth.com/)**

The marketing site provides additional context about:
- **Company Vision:** "Where Surgical Teams Move as One"
- **Platform Overview:** Real-time clarity and communication solutions for surgical environments
- **Team Background:** Healthcare professionals who've experienced workflow challenges firsthand
- **Broader Value Proposition:** Comprehensive surgical team coordination beyond individual patient tracking

---

## 🔗 **Additional Resources**

<!-- Placeholder links for portfolio presentation -->
- 📊 **[System Architecture Diagram]** *(Link to technical architecture visualization)*
- 🎨 **[UI/UX Design Showcase]** *(Link to blurred interface screenshots)*  
- 📋 **[Feature Specifications]** *(Link to detailed feature documentation)*
- 🏗️ **[Code Architecture Overview]** *(Link to code structure diagram)*

---

## 📄 **Project Information**

**Development Timeline:** March 2025 - Present  
**Current Version:** 0.9.3 (Prototype)  
**Platform Requirements:** iOS 15.0+, iPadOS optimized  
**Development Tools:** Xcode 15+, Swift 5.5+, SwiftUI  

---

*This project demonstrates full-stack iOS development capabilities, healthcare domain knowledge, and user-centered design thinking. The application showcases advanced SwiftUI techniques, robust architecture patterns, and deep understanding of clinical workflow requirements.*

**© 2025 - Developed by Juan Rodriguez | All rights reserved** 

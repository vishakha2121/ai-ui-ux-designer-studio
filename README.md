# 🚀 AI UI/UX Designer Studio

> *"Transform your ideas into production-ready UI designs, React components, and accessible interfaces using the power of AI."*

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/ai-ui-ux-designer-studio)](https://github.com/vishakha2121/ai-ui-ux-designer-studio/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/ai-ui-ux-designer-studio)](https://github.com/vishakha2121/ai-ui-ux-designer-studio/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/ai-ui-ux-designer-studio)](https://github.com/vishakha2121/ai-ui-ux-designer-studio/issues)
[![GitHub license](https://img.shields.io/github/license/vishakha2121/ai-ui-ux-designer-studio)](https://github.com/vishakha2121/ai-ui-ux-designer-studio/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Technology Stack](#technology-stack)
- [Architecture](#architecture)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [API Documentation](#api-documentation)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 Overview

**AI UI/UX Designer Studio** is an intelligent, AI-powered web application that acts as your personal design assistant. It uses **Google's Gemini AI** to convert simple text descriptions into professional UI designs, React components, and ensures accessibility compliance - all in real-time.

### What Makes It Revolutionary?

- ⚡ **Generate designs in seconds** - Not hours or days
- 🎨 **Professional quality** - Production-ready outputs
- ♿ **Accessibility first** - WCAG 2.1 compliance built-in
- 📱 **Responsive by default** - Works on all devices
- 💰 **Cost-effective** - Free alternative to expensive design tools
- 🚀 **No GPU required** - Runs on any modern CPU

---

## ✨ Features

### 🎨 1. AI Design Generator
Turn your text descriptions into beautiful UI designs instantly.

### ♿ 3. Accessibility Checker
Ensure your designs are WCAG 2.1 compliant and inclusive.
- Automated accessibility scanning
- Detailed violation reports
- Specific fix suggestions
- Accessibility score (0-100)

### 📱 4. Responsive Layout Generator
Create layouts that work perfectly on all devices.
- Mobile (320px)
- Tablet (768px)
- Desktop (1200px)
- Custom breakpoints

### 📚 5. Design History & Library
Never lose your work again.
- Auto-save all generations
- Search and filter designs
- Reuse previous work
- Design consistency across projects

### 🎯 6. Design Specifications
Get professional design documentation.
- Color palette with hex codes
- Typography system
- Spacing guidelines
- Component specifications

---

## 🖥️ Demo

### Live Demo
🔗 [View Live Demo](https://ai-ui-ux-designer-studio.vercel.app) *(Coming soon)*

### Video Demo
🎥 [Watch Demo Video](https://youtu.be/your-video-link) *(Coming soon)*

### Screenshots
<p align="center">
  <img src="https://via.placeholder.com/800x400/6C63FF/FFFFFF?text=Design+Generator" alt="Design Generator" width="45%" />
  <img src="https://via.placeholder.com/800x400/FF6584/FFFFFF?text=Component+Generator" alt="Component Generator" width="45%" />
</p>

---

## 🛠️ Technology Stack

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| Python | 3.9+ | Core programming language |
| FastAPI | 0.100.0 | High-performance API framework |
| PostgreSQL | 15+ | Primary database |
| SQLAlchemy | 2.0.19 | ORM for database operations |
| Alembic | 1.11.1 | Database migrations |
| Pydantic | 2.1.1 | Data validation |
| Google Generative AI | 0.2.1 | Gemini API integration |
| Uvicorn | 0.23.1 | ASGI server |

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| React | 18.2.0 | UI library |
| Tailwind CSS | 3.3.2 | Styling framework |
| Vite | 4.4.0 | Build tool |
| React Router | 6.14.2 | Routing |
| Axios | 1.4.0 | HTTP client |
| Framer Motion | 10.12.18 | Animations |
| React Hook Form | 7.45.4 | Form handling |

### Database
- **PostgreSQL 15+**
- **Tables:** 6 (users, designs, components, accessibility_reports, layouts, history)

### AI/ML
- **Google Gemini Pro** - Advanced AI model for design generation

---

## 🏗️ Architecture



---

## 📦 Installation

### Prerequisites
- **Node.js** (v16 or higher)
- **Python** (v3.9 or higher)
- **PostgreSQL** (v15 or higher)
- **Git** (for cloning)

### Step-by-Step Setup

#### 1. Clone the Repository
```bash
git clone https://github.com/vishakha2121/ai-ui-ux-designer-studio.git
cd ai-ui-ux-designer-studio


# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env

# Edit .env file with your credentials

# Navigate to frontend directory
cd ../frontend

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Edit .env file with your API URL
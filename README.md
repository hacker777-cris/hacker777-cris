# 🎵 TrackSniff
> *Discover. Track. Identify. The Ultimate Music Intelligence Platform.*

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-%23121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tracksniff)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-%234F46E5?style=for-the-badge&logo=vercel&logoColor=white)](https://tracksniff.com)
[![License](https://img.shields.io/badge/License-MIT-%23green?style=for-the-badge)](LICENSE)

*Building the future of music discovery with AI-powered track identification and analysis*

</div>

---

## 💫 About TrackSniff

TrackSniff is a **next-generation music intelligence platform** that leverages advanced technologies to help users discover, identify, and analyze music tracks in real-time. Our platform provides comprehensive music data, from track metadata to artist information and curated playlists.

### 🎯 Key Features

- 🔍 **Smart Track Recognition** - Identify songs with AI-powered algorithms
- 📊 **Advanced Analytics** - Track statistics and listening patterns
- 🎤 **Artist Profiles** - Detailed artist information and discographies
- 🎵 **Music Discovery** - Personalized recommendations and curated playlists
- 🌍 **Global Database** - Millions of tracks and artists indexed
- ⚡ **Real-time Updates** - Live music data and trending tracks

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                      TrackSniff Stack                       │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Frontend Layer:                                            │
│  ├─ React App (tracksniff.com)                             │
│  ├─ Marketing Frontend (marketing.tracksniff.com)          │
│  └─ Ticket System (ticket.tracksniff.com)                  │
│                                                             │
│  API Layer:                                                 │
│  └─ Django REST API (api.tracksniff.com)                   │
│                                                             │
│  Infrastructure:                                            │
│  ├─ Nginx (Reverse Proxy & Load Balancer)                 │
│  ├─ Docker & Docker Compose                               │
│  ├─ PostgreSQL/MongoDB                                     │
│  ├─ Redis (Caching & Session Management)                  │
│  ├─ Celery (Async Task Processing)                        │
│  └─ Let's Encrypt (SSL/TLS Certificates)                  │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🚀 Tech Stack

### **Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### **Backend**
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django REST](https://img.shields.io/badge/Django%20REST-A30000?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37B24D?style=for-the-badge&logo=celery&logoColor=white)

### **Database & Cache**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### **DevOps & Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### **Tools & Services**
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📁 Project Structure

```
TrackSniff/
├── frontend/                          # Main React Application
│   └── TrackSniff/
│       ├── src/
│       ├── public/
│       ├── Dockerfile.dev
│       └── vite.config.js
│
├── marketing-frontend/                # Marketing & Landing Page
│   └── TrackSniff/
│       ├── src/
│       ├── Dockerfile.dev
│       └── vite.config.js
│
├── ticket-frontend/                   # Ticket Management System
│   └── TrackSniff/
│       ├── src/
│       ├── Dockerfile.dev
│       └── vite.config.js
│
├── backend/                           # Django Backend API
│   └── TrackSniff/
│       ├── apps/
│       ├── settings/
│       ├── manage.py
│       └── requirements.txt
│
├── orchestrator/                      # Docker Compose & Nginx Config
│   ├── docker-compose.yml
│   ├── nginx/
│   │   └── nginx.conf
│   └── Dockerfile.cron
│
└── README.md
```

---

## 🛠️ Getting Started

### Prerequisites
- Docker & Docker Compose
- Node.js 20+ (for local development)
- Python 3.11+
- Git

### Quick Start

1. **Clone the Repository**
```bash
git clone https://github.com/tracksniff/TrackSniff.git
cd TrackSniff
```

2. **Deploy with Docker**
```bash
cd orchestrator
docker-compose up -d
```

3. **Access the Applications**
- Main App: https://tracksniff.com
- Marketing: https://marketing.tracksniff.com
- Tickets: https://ticket.tracksniff.com
- API: https://api.tracksniff.com

---

## 📚 Documentation

### Deployment
- [Docker Compose Setup](./orchestrator/README.md)
- [Nginx Configuration](./orchestrator/nginx/README.md)
- [SSL/TLS Certificates](./orchestrator/CERTBOT_COMMANDS.txt)

### Development
- [Frontend Setup](./frontend/README.md)
- [Backend API](./backend/README.md)
- [Contributing Guide](./CONTRIBUTING.md)

---

## 🔄 CI/CD Pipeline

Our GitHub Actions workflows automate deployments:

```yaml
Deploy Frontend  → Build → Test → Push to VPS
Deploy Backend   → Build → Test → Migrate DB → Restart Services
Deploy Marketing → Build → Test → Push to VPS
```

**Deployment Triggers:**
- `main` branch → Production
- `Tracksniff-marketing` branch → Marketing site
- `backend` branch → Backend API
- `ticket-frontend` branch → Ticket system

---

## 🌐 Current Services

| Service | URL | Status | Tech |
|---------|-----|--------|------|
| Main App | tracksniff.com | ✅ Live | React + Django |
| Marketing | marketing.tracksniff.com | ✅ Live | React + Vite |
| API | api.tracksniff.com | ✅ Live | Django REST |
| Tickets | ticket.tracksniff.com | ✅ Live | React |
| Blog | tracksniff.com/blog | ✅ Live | WordPress |

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 💬 About the Developer

### 👨‍💻 Chrispus Gikonyo

🌱 **Currently Learning:** Go, Advanced DevOps  
💻 **Expertise:** Full-Stack Development, Django, React, DevOps  
🎯 **Focus:** Building scalable music intelligence platforms  

### 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chrispuswandia)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/__crispus__)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/crispus.dev)
[![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hacker777-cris)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:crispusgikonyo@gmail.com)

### 📊 GitHub Stats

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hacker777-cris&theme=radical&hide_border=true&show_icons=true)](https://github.com/hacker777-cris)

[![GitHub Streak](https://streak-stats.demolab.com?user=hacker777-cris&theme=radical&hide_border=true)](https://github.com/hacker777-cris)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hacker777-cris&theme=radical&hide_border=true&layout=compact)](https://github.com/hacker777-cris)

</div>

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Django & Django REST Framework community
- React & Vite ecosystem
- Open source contributors
- Our amazing users and supporters

---

<div align="center">

### ⭐ If you find TrackSniff useful, please give us a star!

Made with 💜 by [Chrispus Gikonyo](https://github.com/hacker777-cris)

*The future of music intelligence is here.*

</div>

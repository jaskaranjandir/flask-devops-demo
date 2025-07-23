# DevOps CI/CD Flask App 🚀

A simple Flask app containerized with Docker, tested and built via GitHub Actions, and deployed on Render/Railway.

## 🔧 Stack

- Python + Flask
- Docker
- GitHub Actions (CI)
- Railway / Render (Free Hosting)

## 📦 How to Run

```bash
docker build -t flask-devops-demo .
docker run -p 5000:5000 flask-devops-demo

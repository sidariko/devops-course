# Multi-Container Docker App

## 🔧 Опис

Багатоконтейнерний застосунок з використанням Docker Compose, що включає:
- nginx (вебсервер)
- postgres (база даних)
- redis (кеш)

## 📜 Команди

```bash
docker-compose up -d
docker-compose ps
docker network ls
docker volume ls
docker exec -it <db_container_name> psql -U user -d mydb
docker-compose up -d --scale web=3
```

## 🐙 Git

```bash
git init
git add .
git commit -m "Initial commit: multi-container docker app"
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
```

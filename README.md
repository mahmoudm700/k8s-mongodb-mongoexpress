# MongoDB & Mongo Express on Kubernetes

This project deploys MongoDB with persistent storage
and Mongo Express UI on Kubernetes using best practices
(ConfigMaps, Secrets, PVC, StorageClass).

## 🛠 Tech Stack
- Kubernetes
- MongoDB
- Mongo Express
- AWS EBS CSI Driver

## 📁 Project Structure
k8s-mongodb/
├── mongodb/
│   ├── mongodb-app.yaml
│   ├── mongodb-svc.yaml
│   ├── mongodb-pvc.yaml
│   ├── mongodb-sc.yaml
│   ├── mongodb-cm.yaml
│   └── mongodb-secret.example.yaml
│
├── mongo-express/
│   ├── mongo-express-app.yaml
│   └── mongo-express-svc.yaml

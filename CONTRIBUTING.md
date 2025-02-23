# Guide to Contributing

## Team Norms

## Git workflow that the team follows

## Rules of contributing

## Local development enviroment setup
Follow these steps to set up the **Smart Refrigerator Management System (SRMS)** for local development:  

### 1️⃣ Prerequisites  
Ensure you have the following installed:  
- **Python 3.9+**  
- **Node.js 16+**
- **MangoDB**
- **Docker**
- **Git**  
- etc...

### 2️⃣ Clone the Repository  
```sh
git clone https://github.com/agiledev-students-spring2025/4-final-smart-refrigerator-management-system
```

### 3️⃣ Setups
**1. Create a virtual environment**
```sh
python -m venv venv
source venv/bin/activate
```
**2. Install dependencies**
```sh
pip install -r requirements.txt
```
**3. Database setup (using Docker)**
```sh
docker run --name mongodb_dockerhub -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=secret -d mongo:latest
```
**4. Back-end setup**
```sh
cd back-end
npm install
npm start
```
**5. Front-end Setup**
```sh
cd front-end
npm install
npm start
```
### 4️⃣ Run tests
```sh
pytest
npm test
```
### 5️⃣ Access the app
- Backend API:
- Frontend API:
For addtional configuration details, see [CONTRIBUTING.md](https://github.com/agiledev-students-spring2025/4-final-smart-refrigerator-management-system/blob/master/CONTRIBUTING.md)

## Building & testing instructions
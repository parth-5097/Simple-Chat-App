### Clone the repository:
```
git clone https://github.com/SiddharthSsb11/MERN-chat-app.git
```

### Env Variables

Create a .env file in the root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = <yourMongoDbUri>
JWT_SECRET = <yourSecret>
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run
Run frontend (:3000) & backend (:5000)
```
# Run frontend only
cd frontend
npm start 

# Run backend only
npm start
```

## Build & Deploy

```
# Create frontend production build
cd frontend
npm run build
```
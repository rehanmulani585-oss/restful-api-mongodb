# STEP 1 — Create Folder

Open terminal:

```bash id="6t4wzr"
mkdir RESTfulAPIMongoDB
```

# STEP 2 — Open Folder

```bash id="5n7qkp"
cd RESTfulAPIMongoDB
```

# STEP 3 — Initialize Node Project

```bash id="2m8vde"
npm init -y
```

# STEP 4 — Install Packages

```bash id="4q1xwu"
npm install express mongoose cors dotenv
```

# STEP 5 — Open VS Code

```bash id="7k3mnp"
code .
```

# STEP 6 — Create Folder Structure

```text id="8w6rqt"
RESTfulAPIMongoDB
│
├── app.js
├── package.json
├── .env
├── database
│   └── db.js
├── routes
│   └── apiRoutes.js
├── models
│   └── Product.js
└── controllers
    └── apiController.js
```

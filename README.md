<<<<<<< HEAD
# My Project
=======
# Instructions for running this project
**NOTE:**
Replace Python3 with Python if your computer has Python installed

1. Create python environment
```bash
python3 -m venv .venv
```

2. Activate python environment.\

- For linux
```bash
source .venv/bin/activate 
```
- For windowns
```bash
.venv\Scripts\activate
```
The cursor in the terminal should look like this (with .env)
```cmd
(.venv) johnny@johnny-Inspiron-5502:/media/johnny/Data/Code/cloud_service/be_test$
```

3. Run project
```bash
python3 main.py
```

# API User Guide
1. Test api
- Link: `http://192.168.1.101:5000`
- Respone: 
```console
BE Hello
```

2. Create data api
- Link: `http://192.168.1.101:5000/api/account/create`
- Respone: 
```console
Account added
```

3. Get all data api
- Link: `http://192.168.1.101:5000/api/account/all`
- Respone: 
```console
[
  {
    "id": 1,
    "name": "Nguyen Van A"
  }
]
```

**NOTE:**
Every time you call create api, all api will have 1 more data with incremental id
>>>>>>> 24d7b01 (first update)



### Setup
```bash
python -m venv env
source env/bin/activate
python -m pip install temporalio

brew install temporal
```

### Running 
```bash 
temporal server start-dev --db-filename your_temporal.db --ui-port 8080
```

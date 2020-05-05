# ml_system_design_pattern(WIP)

This is a very good article, so I want to write it little by little.
    

(ml-system-design-pattern)[https://mercari.github.io/ml-system-design-pattern/]

## Setup


```
# I tried by MacOS and Python 3.5 or later.
pip install -r requirements.txt
pip install connexion[swagger-ui] --user
```

## Run Synchronous-pattern


```
cd flask-swagger_api
# run app
python main.py
# Check the path below
curl http://localhost:8080/api/user
# Swagger UI
# http://localhost:8080/api/ui/#

```

## TODO

- Basice
    
- [ ] Test code
- [ ] Docker-compose

- Serving patterns
    

- [ ] Web-single-pattern
- [x] Synchronous-pattern
- [ ] Asynchronous pattern
- [ ] Batch pattern
- [ ] Prep-pred pattern
- [ ] Microservice vertical pattern
- [ ] Microservice horizontal pattern
- [ ] Prediction cache pattern
- [ ] Data cache pattern
- [ ] Prediction circuit break pattern
- [ ] Multiple stage prediction pattern

- QA patterns
    

- [ ] Shadow-ab-test-pattern
- [ ] Online AB-testing pattern
- [ ] Loading test pattern

- Operation patterns
    

- [ ] Model-in-image pattern
- [ ] Model-load pattern
- [ ] Data model versioning pattern
- [ ] Prediction log pattern
- [ ] Prediction monitoring pattern
- [ ] Parameter-based serving pattern
- [ ] Condition-based-serving pattern

- Lifecycle patterns
    

- [ ] Train-then-serve pattern
- [ ] Training-to-serving pattern
- [ ] Antipatterns




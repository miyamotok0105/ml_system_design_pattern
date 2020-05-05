
# README


```
pip install -r requirements.txt
pip install connexion[swagger-ui] --user
```

Run    

```
python main.py
```


Simple test code    


```
test.sh
```


## Swagger

Generate swagger text easier.    

https://editor.swagger.io/
    


## How to use


```
paths:
  #URI
  /user:
    # call http get 
    get:
      # method name.
      operationId: read_all
      # file name and path. 
      x-swagger-router-controller: app.controllers.user_controller
```

## Swagger

Swagger UI    

```
http://localhost:8080/api/ui/#/
```


## Refarence

https://qiita.com/Aruneko/items/2adbf12bb5bace32e002

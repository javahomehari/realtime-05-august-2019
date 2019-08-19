# realtime-05-august-2019

### Persisting data into emp-api

```
   curl -H "Content-Type: application/json" -X POST --data = '{"id":1,"name":"Hari"}'  http://<your-ip>:8080/employee
   curl -H "Content-Type: application/json" -X POST --data = '{"id":2,"name":"Ravi"}'  http://<your-ip>:8080/employee
   curl -H "Content-Type: application/json" -X POST --data = '{"id":3,"name":"Rahul"}'  http://<your-ip>:8080/employee
   
```

### Fetch data from emp-api

```
  curl -H "Accept: application/json" -X Get  http://<your-ip>:8080/employees

```


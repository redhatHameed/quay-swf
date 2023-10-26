# Run
```bash
mvn clean package
mvn quarkus:dev
```

# Test
```bash
curl -v -X POST -H "Content-Type: application/json" http://localhost:8080/quay-service -d '{"namespace": "X", "repository": "Y", "visibility": "Z"}'
```

# Dev UI
```
open -t http://localhost:8080/q/dev/org.kie.kogito.kogito-quarkus-serverless-workflow-devui/workflowInstances
```
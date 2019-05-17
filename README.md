# Golang Implementation for AwsLambda

Test scripts for AWS lambda

## Requirement

These commands are required to make executable and zip the executable and upload it on AWS lambda UI 

```bash
CMD>> GOOS=linux GOARCH=amd64 go build -o main main.go 
```
```bash
CMD>> zip main.zip main
```

# Note
Name the executable file what you named the lambda function in AWS console 

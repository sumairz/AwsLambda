# AwsLambda
AWS lambda tests in golang

<b> These commands are required to make executable and zip the executable and upload it on AWS lambda UI </b>
<br />
<b>NOTE: Name the file what you named the lambda function in AWS console </b><br />
CMD>> GOOS=linux GOARCH=amd64 go build -o main main.go
<br />
CMD>> zip main.zip main

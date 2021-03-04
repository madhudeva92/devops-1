
AWS Lambda is a responsive cloud service that inspects actions within the application and responds by deploying the user-defined codes, known as functions. 
It automatically manages the compute resources across multiple availability zones and scales them when new actions are triggered.

AWS Lambda supports the code written in Java, Python and Node.js, and the service can launch processes in languages supported by Amazon Linux (includes Bash, Go & Ruby).

Following are some recommended tips while using AWS Lambda.

Write your Lambda function code in a stateless style.

Never declare any function variable outside the scope of the handler.

Make sure to have a set of +rx permissions on your files in the uploaded ZIP to ensure Lambda can execute code on your behalf.

Delete old Lambda functions when no longer required.

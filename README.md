# gcp-serverless
deploy cloud fuctions using serverless framework.

### installing serverless 
npm install -g serverless

### To see which version of serverless you have installed run:
serverless --version

### Installing the Google Cloud Functions Provider Plugin
npm install --save serverless-google-cloudfunctions

### Deploy functions
sls deploy

### Invoke function
serverless invoke --function first

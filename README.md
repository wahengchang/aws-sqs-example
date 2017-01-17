#AWS sqs example
Fast setup Node.js Helloworld in AWS SQS(Message Queuing Service). For more informatino please check the blog: 

##Remark
 - All the examples here is clone from AWS offical sample: https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/javascript/example_code/sqs
 - AWS offical document: http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/sqs-examples-using-queues.html

####Step 
1. set up access-key and secret-key
2. $ node sqs_createqueue.js
3. $ node sqs_listqueues.js
4. $ node sqs_getqueueurl.js (the reture url is used in step 5 and 6)
5. $ node sendMessage.js
6. $ node receiveMessage.js


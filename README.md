Initialise the application

AWS SAM Template
```
AWSTemplateFormatVersion: '2010-09-09'
Transform: AWS::Serverless-2016-10-31
Description: Set 
    Properties:
      TopicName: MySnsTopic
```


Build the application

This will create the sam-build directory. It includes the template and zipped (or image) f your code.

Clean up

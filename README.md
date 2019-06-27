# aws_codedeploy
- install code deploy agent
- create proper IAM role and attach it to the instances

then configure code deploy, in codedeploy you can use blue/green deployment to deploy your new application.

If you launch your instance from custom AMI, you may clear the logs from the previous code deploy activity.
- stop codedeploy-agent
- clear everything inside /opt/codedeploy-agent/deployment-root/
- start codedeploy-agent

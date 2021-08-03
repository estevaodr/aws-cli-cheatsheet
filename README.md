# aws-cli-cheatsheet

## ElasticBeanstalk

List all elasticbeanstalk applications

```bash
aws elasticbeanstalk describe-applications --query 'Applications[*].[ApplicationName]' --output text
```


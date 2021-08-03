# aws-cli-cheatsheet

## ElasticBeanstalk

List all application

```bash
aws elasticbeanstalk describe-applications --query 'Applications[*].[ApplicationName]' --output text
```


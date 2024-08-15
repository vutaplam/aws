```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "AccessAnalyzerServiceRolePolicy",
            "Effect": "Deny",
            "Action": ["ec2:TerminateInstances", "ec2:StopInstances"],
            "Resource": "arn:aws:ec2:us-east-1:372590035713:instance/i-02deb63ac80133786"
        }
        {
        "Effect": "Allow",
        "Action": "ec2:*",
        "Resource": "*"
        }

    ]
}
```

# cicd123
{
  "Id": "Policy1635955764085",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1635955762873",
      "Action": "s3:*",
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::aws-codepipeline-demo-second/*",
      "Principal": "*"
    }
  ]
}
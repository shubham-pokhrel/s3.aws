# [Read about S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html#S3Features)

## [Document](https://docs.google.com/document/d/1lBdoNP9MViLQNIcjZOwYEQ9qHeu1osvc/edit?usp=sharing&ouid=100535802890695018069&rtpof=true&sd=true)


# Bucket Policy for S3

```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
       "Resource": [
                "arn:aws:s3:::bucketname/*",
                "arn:aws:s3:::bucketname"
            ]
    }
  ]
}
```


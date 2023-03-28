Logs GitHub Context to S3 Bucket

Example:

```
- id: log_to_s3
  uses: jlieow/action_github_log_to_s3@V1 # Uses an action in the repo action_github_log_to_s3 owned by jlieow tagged as V1
  with:
    aws_access_key_id: INPUT_AWS_ACCESS_KEY_ID
    aws_secret_access_key: INPUT_AWS_SECRET_ACCESS_KEY
    profile_name: INPUT_PROFILE_NAME
```

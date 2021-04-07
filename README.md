# s3wer
Python CLI to empty / delete S3 buckets with filters such as timestamp, name, and ranges.

Currently, many utilities exist to clear out files inside S3 buckets, but there are no _good_ utilities that empty buckets, then delete multiple S3 buckets. Furthermore, no utility seems to exist that allows us to filter by timestamp, range, name, or other common aspects that we might want for convenience. Amazon UI is painstakingly slow if you have hundreds of buckets, and scripts feel dangerous.

Thus, we have s3wer. I plan to use Python3, Boto3, and whatever else is needed to make its use as a CLI work great.

## WIP

If you searched for this, I am sorry, this utility is currently under development and I appreciate any issues or PRs contributed here.


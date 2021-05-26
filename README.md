<img width="608" alt="Screen Shot 2021-05-26 at 11 22 24 AM" src="https://user-images.githubusercontent.com/15917939/119711683-a7df8880-be14-11eb-8633-85d4640f8dc1.png">

# s3wer
Python CLI to empty / delete S3 buckets with filters such as timestamp, name, and ranges.

Currently, many utilities exist to clear out files inside S3 buckets, but there are no _good_ utilities that empty buckets, then delete multiple S3 buckets. Furthermore, no utility seems to exist that allows us to filter by timestamp, range, name, or other common aspects that we might want for convenience. Amazon UI is painstakingly slow if you have hundreds of buckets, and scripts feel dangerous.

Thus, we have s3wer: Python3, Boto3, and whatever else is needed to make its use as a CLI work great.

## Where's the code?

Update: the code is intentionally not pushed as I fear it might accidentally explode someone's prod S3 and I don't want to be liable for that.
If you work in the same company as me (check Workday to figure that out) I will gladly help you out with S3 and this utility.

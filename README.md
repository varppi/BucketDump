![Logo](https://github.com/Varppi/BucketDump/assets/72181445/d005bad0-1cd7-4dc3-af6b-cf62e6210590)

## Description
<b>A minimalistic tool to dump a whole S3 bucket to your local computer WITHOUT AN API KEY. Note that this program only works for buckets where the www root is the bucket listing.</b>

## Installation
```
go install github.com/Varppi/BucketDump@latest
```

## Usage
### Help page
```
Usage of BucketDump:
  -bucket string
        Bucket to dump
  -save-dir string
        Directory to dump the files to (default "./out/")
```
### Commands
```
BucketDump -bucket randombucket -save-dir ./randombucket1

BucketDump -bucket randombucket
```

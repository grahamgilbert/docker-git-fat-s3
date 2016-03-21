# docker-git-fat-s3

## Usage

```
docker run -d -v /some/munk_repo:/munki_repo -e S3_IDENTITY=SOMEIDENTITY -e S3_CREDENTIAL="SOMECRED" -e S3_BUCKET=SOMEBUCKET --device /dev/fuse --name=git-fat --cap-add SYS_ADMIN grahamgilbert/git-fat-s3
```

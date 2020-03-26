# Blog

## About
Blog is a static web blog built with [Hugo](https://gohugo.io) that contains Tony Lopez's journal entries and blog posts. Blog is hosted at http://blog.tonelope.com

## Deployment
Blog is deployed to Amazon S3. Make sure to have [aws-cli](https://aws.amazon.com/cli/) installed and configured prior to attempting to deploy.

```
$ cd blog
$ aws s3 sync public/ s3://blog.tonelope.com
```

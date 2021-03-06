# LibreOffice for AWS Lambda as a layer

> 85 MB LibreOffice to fit inside AWS Lambda Layer compressed with Brotli

Based on the [serverless-libreoffice](https://github.com/vladgolubev/serverless-libreoffice) project.

## Getting Started

You can add this layer to any Lambda function you want – no matter what runtime

Click on Layers and choose "Add a layer", and "Provide a layer version
ARN" and enter the following ARN.

```
arn:aws:lambda:us-east-1:764866452798:layer:libreoffice:8
```

See the table below for other supported regions.

Works well with [aws-lambda-libreoffice npm package](https://github.com/shelfio/aws-lambda-libreoffice)

## What does this layer contain?

This layer contains `lo.tar.gz` file which is LibreOfficee v6.1.0.0.alpha (https://github.com/vladgolubev/serverless-libreoffice/releases/tag/v6.1.0.0.alpha0).

## Where is LibreOffice inside of Lambda?

It is at `/opt/lo.tar.gz`.

## Version ARNs

### LibreOffice 6.1.0.0.alpha0

* `arn:aws:lambda:us-east-1:764866452798:layer:libreoffice:8`
* `arn:aws:lambda:eu-west-1:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:eu-central-1:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:us-west-2:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:us-east-2:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:ap-southeast-2:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:eu-west-2:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:ap-southeast-1:764866452798:layer:libreoffice:1`
* `arn:aws:lambda:ap-south-1:764866452798:layer:libreoffice:1`

## License

MIT © [Shelf](https://shelf.io)

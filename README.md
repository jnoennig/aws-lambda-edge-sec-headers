# Add HTTP Security Response Headers Using Lambda@Edge and Python with CloudFront

## Overview

Adds six(6) HTTP security headers to the CloudFront response. The values listed in the [Python example](securityHeaders.py) should get you a high mark on the Mozilla Observatory scan.

## Deployment

The Python Lambda function needs be deployed to a Lambda@Edge and be triggered by a
CloudFront response event. The origin response works well as the trigger.

## Helpful Links

* [AWS blog adding HTTP security headers](https://aws.amazon.com/blogs/networking-and-content-delivery/adding-http-security-headers-using-lambdaedge-and-amazon-cloudfront/)
* [Information about HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
* [Mozilla Observatory](https://observatory.mozilla.org/)

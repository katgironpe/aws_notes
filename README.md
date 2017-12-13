# AWS Notes

## Amazon Resource Names

* [Amazon Resource Names (ARNs) and AWS Service Namespaces](http://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html)

## Amazon API Gateway

### [API Gateway Mapping Template Reference](http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-mapping-template-reference.html)

### Mapping Template Variables

* `$context` - variable holds all the contextual information of your API call. 
* `$input` - represents the input payload and parameters to be processed by your template.
* `$util` - variable contains utility functions for use in mapping templates.

#### Most important `$context` variables

* `$apiId` - The identifier API Gateway assigns to your API.
* `$context.identity.accountId` - The AWS account ID associated with the request.
* `$context.identity.sourceIp` - The source IP address of the TCP connection making the request to API Gateway. 
* `$context.identity.userAgent` - The User Agent of the API caller.






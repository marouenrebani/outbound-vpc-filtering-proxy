## Outbound VPC proxy behind NAT Gateway

Outbound VPC proxy with domain whitelisting and content filtering without exposing directly the proxy ec2.
This makes the scalability of the solution much easier.
The proxy instance must be placed behing a NAT Gateway (NAT Gateway not included in the template).

## Orignal project

For more information see AWS Security Blog [How to set up an outbound VPC proxy with domain whitelisting and content filtering](https://aws.amazon.com/blogs/security/how-to-set-up-an-outbound-vpc-proxy-with-domain-whitelisting-and-content-filtering)

## License Summary

This sample code is made available under the MIT-0 license. See the LICENSE file.

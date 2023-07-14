# AWS-challenge

1 created a bucket and added a static web page to the bucket 
2 created a domain and certificate from the certificate manager 
3 route 53 already created because the domain was created with aws
4 created a record for the certificate in route 53 hosted zone
5 created a cloudfront distribution and linked the bucket to it
6 restricted the bucket access just to the cloudfront with the OAI key
7 added DNS name and certificate to the cloudfront
8 made it accessable only on https
9 once everything was created we made a record so the domain name redirected to the cloudfront url

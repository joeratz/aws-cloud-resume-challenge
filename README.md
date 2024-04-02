# **Cloud Resume Challenge**
My attempt at the AWS [Cloud Resume Challenge](https://cloudresumechallenge.dev/) by Forrest Brazeal.


![](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*Czb6G5RcJ3_wkQIRpxF0_w.png)

* I deployed my resume as a S3 static website, utilizing HTTPS and Amazon CloudFront.
* I created a custom DNS domain name using Route 53 and pointed it at my CloudFront Distribution.
* I wrote a viewer counter for my website using Javascript.
* I utilized DynamoDB to log the view counter.
* I created an API Gateway to communicate my Javascript code with DynamoDB.
* I wrote a Lambda Function using Python, triggered by my API Gateway, that reads from my DynamoDB table and updates the view counter. This also includes tests for my Python code.
* Setup GitHub repo for front-end, utilized GitHub Actions to automate updates and deployment.

## Work In Progress
* Please note: website is constantly undergoing updates and is NOT a final product until this ReadMe is updated saying so.
* Writing Infrastructure as Code using Terraform
* Setup GitHub repo for back-end

## Other Links
LinkedIn: [Joe Ratzlaff](https://www.linkedin.com/in/joe-ratzlaff-95b582159/)

My Resume Website: [My Cloud Resume](https://real.jratzresume.com/)****

# AWS_Project
A Multi-tier maven application deployed on AWS platform (Manually)

# Flow of Execution
Login to AWS Account.
Create a keypair (optional).
Create a dedicated security groups for all different services.
Launch instances manually or with userdata (bash script) for different packages.
Update the IP address of each instances in Route53 by creating private hosted zone.
Build the application from source code withn the help of Apache maven (locally or in AWS).
Create a new bucket in S3 with the unique name and upload the artifact to S3 bucket.
Copy the Artifact from bucket to default path of tomcat instance.
Verify the application

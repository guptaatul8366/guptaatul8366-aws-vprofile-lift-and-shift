# Commands Used

## Build application
mvn install

## Upload artifact to S3
aws s3 cp target/vprofile-v2.war s3://vprofile-las-artifacts/

## SSH into EC2
ssh -i key.pem ubuntu@public-ip

## Deploy WAR to Tomcat
systemctl stop tomcat10
cp /tmp/vprofile-v2.war /var/lib/tomcat10/webapps/ROOT.war
systemctl start tomcat10

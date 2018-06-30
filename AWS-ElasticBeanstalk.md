# Elastic Beanstalk

### Deploying a Flask application on Elastic Beanstalk

1. Install the Elastic Beanstalk CLI.  
`pip install awsebcli`

2. Initialise your EB repository and create an application name.    
`eb init -p python-3.6 [ application name ] --region us-west-2`  

3. Configure a default keypair so you can connect to the EC2 instance via. SSH:  
`eb init`

4. Create an EB environment within your app and deploy your app to it:  
`eb create [ environment name ]`  


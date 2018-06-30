# Elastic Beanstalk

### Deploying a Flask application on Elastic Beanstalk

1. Install the Elastic Beanstalk CLI.  
`pip install awsebcli`

2. Initialise your EB repository
`eb init -p python-3.6 brian-personal --region us-west-2`
This command creates a new application named flask-tutorial and configures your local repository to create environments with the latest Python 3.6 platform configuration.  

3. Configure a default keypair so you can connect to the EC2 instance via. SSH:
`eb init`

4. Create an EB environment and deploy your application to it:
`eb create flask-project-brian`


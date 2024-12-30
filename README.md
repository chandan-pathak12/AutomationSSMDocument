
Aim:- AWS Systems Manager (SSM) Document to install and configure Nginx on an EC2 instance

Steps taken:- ..

1. Install SSM agent on your machine(I am taking ubuntu EC2 instance here)
   1. sudo snap install amazon-ssm-agent --classic 
   2. sudo systemctl start snap.amazon-ssm-agent.amazon-ssm-agent 
   3. sudo systemctl enable snap.amazon-ssm-agent.amazon-ssm-agent
   https://docs.aws.amazon.com/systems-manager/latest/userguide/agent-install-ubuntu-64-snap.html

2. Create IAM role and policy.
3. Create SSM document and save it.
4. Create a work flow on github action.


![Alt Text](/AutomationwithSSM.png)


By: chandan
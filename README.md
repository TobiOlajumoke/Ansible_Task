## TASK

1. Create a Security Group (on existing VPC) that only allows access from the following: 
- Inbound - Your IP address (SSH, HTTP); Ansible Server IP address (SSH); 
- Outbound – HTTPS & HTTP to any IP address
2. Launches a Linux instance from an AMI (select t2.micro for instance type) and assign the Security Group you created in the first step.
- You can select which flavor of Linux to launch
3. Add a tag "EnvName" with the value “Test Environment”
4. Deploy a Linux web application (you can choose a web application that you like) to the instance that you provisioned.
5. Present a web page that shows the local IP address of the machine on which it is running and have the web-app to listen on port 80
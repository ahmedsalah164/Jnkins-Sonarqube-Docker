Project: Automating the E-health website deployment

Architecture Diagram:

<img width="1192" height="311" alt="image" src="https://github.com/user-attachments/assets/a588252f-dc47-4bd3-8574-6bc53e4d723c" />

Implementation Steps:

Provisioning the three Ubuntu EC2 instances and configuring network security groups.

Configuring the GitHub webhook for automated push events.

Integrating Jenkins with SonarQube using the sonar-scanner CLI.

Writing the Jenkins shell execution block to securely transfer files via SCP and execute Docker commands on a remote server.

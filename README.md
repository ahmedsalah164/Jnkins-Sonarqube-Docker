Project: End-to-End Continuous Deployment Pipeline on AWS

Architecture Diagram:

<img width="1192" height="311" alt="image" src="https://github.com/user-attachments/assets/a588252f-dc47-4bd3-8574-6bc53e4d723c" />

Implementation Steps:

Provisioning the three Ubuntu EC2 instances and configuring network security groups.

Configuring the GitHub webhook for automated push events.

Integrating Jenkins with SonarQube using the sonar-scanner CLI.

Writing the Jenkins shell execution block to securely transfer files via SCP and execute Docker commands on a remote server.

<img width="1811" height="447" alt="Screenshot 2026-09-05 165400" src="https://github.com/user-attachments/assets/c4d4c311-2187-492e-9394-d6b824010bb0" />

<img width="1822" height="577" alt="Screenshot 2026-09-05 165254" src="https://github.com/user-attachments/assets/79a3c0de-e216-4002-8ef5-8763287df773" />

<img width="1856" height="891" alt="Screenshot 2026-09-05 165231" src="https://github.com/user-attachments/assets/fdcca5e0-ae2b-44f5-8a54-42af0f02ebb4" />

<img width="1862" height="995" alt="Screenshot 2026-09-05 165448" src="https://github.com/user-attachments/assets/b1168eb4-1b9d-4017-9a32-bcf046b2d34b" />

<img width="1863" height="938" alt="Screenshot 2026-09-05 165652" src="https://github.com/user-attachments/assets/b0b206ed-0a46-4abd-8950-f30bd6bca139" />

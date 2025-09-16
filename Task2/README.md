Task 2: MySQL Pod with Secret
📋 Description
Run a MySQL Pod using a Secret to pass the root password.
Verify access to MySQL using the password stored in the Secret.
Ensure that credentials are not hardcoded in the deployment YAML.
🛠️ Components Used
Pod: Runs MySQL container
Secret: Stores sensitive data (MySQL root password)
Service: Exposes MySQL internally (optional)

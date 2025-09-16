# Task 4: Two Containers in a Single Pod

## 📋 Description
- Create a Pod with two containers:
  1. Container one listens on port 80.
  2. Container two uses a ConfigMap to change port to 50.
- Map separate index.html files for each container.
- Expose the Pod via a Service.

## 🛠️ Components Used
- **Pod**: Runs two containers sharing the same network namespace
- **ConfigMap**: Configures Nginx ports and custom HTML content
- **Service**: Exposes both containers externally

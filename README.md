# Kubernetes Mosquitto Deployment

This project demonstrates the deployment of an Eclipse Mosquitto MQTT broker on a Kubernetes cluster using YAML configuration files. It includes the necessary deployment, service, and configuration for secure communication.

## Project Structure

```plaintext
.
├── ca.crt
├── mosquitto.yaml
├── route.yaml
├── server.crt
├── server.key
└── screenshots
To deploy this project on your Kubernetes cluster, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/KhizraGhaffar/kubernetes-mosquitto.git
cd kubernetes-mosquitto
2. Apply the configuration files to your Kubernetes cluster:
```bash
kubectl apply -f mosquitto.yaml
```bash
3. Verify the deployment:
```bash
4. Access the Mosquitto broker using the exposed service.
## Screenshots
Screenshots of the deployment process and broker usage can be found in the screenshots directory.

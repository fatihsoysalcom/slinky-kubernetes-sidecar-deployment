# Slinky Kubernetes Sidecar Deployment

This example demonstrates a simplified Kubernetes deployment of a hypothetical Slinky oracle as a sidecar container alongside a validator node. It illustrates how Slinky, a high-performance oracle solution for Cosmos SDK chains, could be structured within a Kubernetes Pod, sharing resources and network with its main application. Configuration is managed via a ConfigMap and environment variables.

## Language

`yaml`

## How to Run

1. Ensure you have `kubectl` installed and configured to connect to a Kubernetes cluster.
2. Save the code as `slinky-deployment.yaml`.
3. Apply the manifest: `kubectl apply -f slinky-deployment.yaml`.
4. Verify deployment: `kubectl get pods -l app=slinky-validator`.

## Original Article

This example accompanies the Turkish article: [DigitalOcean Kubernetes Üzerinde Slinky Kurulum Rehberi](https://fatihsoysal.com/blog/digitalocean-kubernetes-uzerinde-slinky-kurulum-rehberi/).

## License

MIT — see [LICENSE](LICENSE).

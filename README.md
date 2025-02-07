# k8s_gpt_ai_driven_kubernetes
K8sGPT is an innovative approach to leveraging AI for Kubernetes (K8s) management and operations. By integrating advanced machine learning techniques with Kubernetes, K8sGPT aims to streamline the deployment, scaling, and management of containerized applications

## Installation
1. Ensure you have a Kubernetes cluster
2. brew install k8sgpt
   Follow the steps below based on your operating system. For detailed installation instructions, please refer to the official documentation: [K8sGPT Installation Guide] 
   (https://docs.k8sgpt.ai/getting-started/installation/)
3. Verify using `k8sgpt version` command.

## K8sGPT Commands

1. First, we need to add an Open AI Key
   using `k8sgpt auth add` command

2. Analyse a namespace
   ``k8sgpt analyze --explain --namespace <namespace_name>``

3. Filter a specific kind eg: service/deployement/pod
   ```
   k8sgpt analyze --explain --filter=Service --namespace <namespace name>
   k8sgpt analyze --explain --filter=Deployment --namespace <namespace name>
   k8sgpt analyze --explain --filter=pod --namespace <namespace name>
   ```

5. Output as a JSON
   ``k8sgpt analyze --explain --namespace k8sgpt --output=json``

6. Output as a JSON then add to a file
   ``k8sgpt analyze --explain --namespace k8sgpt --output=json --anonymize > /root/app-anonymize.json``




   



# assignment1
ISEC6000 Secure DevOps Assignment-1 

This repository contains the completed tasks for the ISEC6000 Secure DevOps Assignment-1.

Task 1: Set Up Initial Infrastructure
1. Create a Kubernetes Cluster on GKE (or equivalent tool)
Created a Kubernetes cluster on Google Kubernetes Engine (GKE) using the Google Cloud Console. Configured cluster settings including cluster name, location, and node pool configuration. Chose the desired Kubernetes version. Provisioned the GKE cluster.

2. Install and configure kubectl to manage the Kubernetes cluster
Configured the local environment to interact with the GKE cluster using kubectl. Accessed the GKE cluster through the Google Cloud Console. Successfully authenticated kubectl with the GKE cluster.

3. Set up a private GitHub repository to store project files
Created a private GitHub repository named "ISEC6000-Secure-DevOps-Project" for storing project files. Added a meaningful description and initialized the repository with a README. Pushed the initial setup code to the repository.

Task 2: Microservices Architecture and Deployment
1. Acquainted with core projects and their purposes
Explored Saleor API functionalities at Saleor API Repository. Understood Saleor storefront mechanics at Saleor Storefront Repository. Dived into Saleor dashboard intricacies at Saleor Dashboard Repository. Accessed Saleor platform repository at Saleor Platform Repository.

3. Forked the Saleor platform repository
Created a personal GitHub account and forked the Saleor platform repository.

4. Followed step-by-step guidelines to effectively run a Saleor stack
Followed the instructions in the Saleor platform repository to run a Saleor stack enriched with sample data.

5. Tailored the Compose file for optimal functionality
Configured the React Storefront to operate on port 3009. Assigned port 9003 for the Saleor Dashboard. Initiated the stack and verified the successful launch of all services.

6. Committed modifications and pushed them to the forked repository
Committed the modifications to the Saleor platform Compose file. Pushed the changes to the forked repository with the tag "isec6000-assignment1".

Task 3: Implementing Security Measures
1. Container Security
Ensured secure configuration of containers. Implemented container image vulnerability scanning using Trivy.

Task 4: Architecture Visualization
1. Presented an architecture diagram
Created an architecture diagram illustrating the essential functionalities of each Saleor service and their interactions within the stack. Included details about volumes, networks, and communication channels used by different Saleor services.

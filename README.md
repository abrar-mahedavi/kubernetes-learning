# kubernetes-learning

Simple tryouts for Kubernetes.

## Onwards to Kubernetes

1. The Why's and What's of Kubernetes
2. Kubernetes in Development and Production
3. Docker Desktop's Kubernetes Setup and Installation - macOS
4. Docker Desktop's Kubernetes Setup and Installation - Windows
5. Updated Minikube Install and Setup Info - macOS
6. Minikube Setup on MacOS
7. Minikube Setup on Windows
8. Minikube Setup on Linux
9. Mapping Existing Knowledge
10. Quick Note to Prevent an Error
11. Adding Configuration Files
12. Object Types and API Versions
13. Running Containers in Pods
14. Service Config Files in Depth
15. Connecting to Running Containers
16. The Entire Deployment Flow
17. Imperative vs Declarative Deployments

## Maintaining Sets of Containers with Deployments

1. Updating Existing Objects
2. Declarative Updates in Action
3. Limitations in Config Updates
4. Running Containers with Deployments
5. Quick Note to Prevent an Error
6. Deployment Configuration Files
7. Walking Through the Deployment Config
8. Applying a Deployment
9. Why Use Services?
10. Scaling and Changing Deployments
11. Updating Deployment Images
12. Rebuilding the Client Image
13. Triggering Deployment Updates
14. Imperatively Updating a Deployment's Image
15. Reminder for Docker Desktop's Kubernetes Users
16. Multiple Docker Installations
17. Reconfiguring Docker CLI
18. Why Mess with Docker in the Node?

## A Multi-Container App with Kubernetes

1. The Path to Production
2. Checkpoint Files
3. A Quick Checkpoint
4. Recreating the Deployment
5. NodePort vs ClusterIP Services
6. The ClusterIP Config
7. Applying Multiple Files with Kubectl
8. Express API Deployment Config
9. Cluster IP for the Express API
10. Combining Config Into Single Files
11. The Worker Deployment
12. Reapplying a Batch of Config Files
13. Creating and Applying Redis Config
14. Important Note about Expected Postgres Error
15. Last Set of Boring Config!
16. The Need for Volumes with Databases
17. Kubernetes Volumes
18. Volumes vs Persistent Volumes
19. Persistent Volumes vs Persistent Volume Claims
20. Claim Config Files
21. Persistent Volume Access Modes
22. Where Does Kubernetes Allocate Persistent Volumes?
23. Designating a PVC in a Pod Template
24. Applying a PVC
25. Defining Environment Variables
26. Adding Environment Variables to Config
27. Creating an Encoded Secret
28. Postgres Environment Variable Fix
29. Passing Secrets as Environment Variables
30. Environment Variables as Strings

## Handling Traffic with Ingress Controllers

1. Load Balancer Services
2. A Quick Note on Ingresses
3. One Other Quick Note!
4. Behind the Scenes of Ingress
5. More Behind the Scenes of Ingress
6. Optional Reading on Ingress Nginx
7. Docker Driver and Ingress - IMPORTANT
8. Important - DO NOT SKIP - Ingress Nginx Installation Info
9. Setting up Ingress Locally with Minikube
10. Ingress v1 API Update + "this.state.seenIndexes.map..." + 404 errors
11. Creating the Ingress Configuration
12. Testing Ingress Locally
13. The Minikube Dashboard
14. Docker Desktop's Kubernetes Dashboard

## Kubernetes Production Deployment

1. The Deployment Process
2. Google Cloud vs AWS for Kubernetes
3. Creating a Git Repo
4. Linking the Github Repo to Travis
5. Free Google Cloud Credits
6. Creating a Google Cloud Project
7. Linking a Billing Account
8. Updated GKE creation steps for new Google Cloud UI
9. Kubernetes Engine Init
10. Creating a Cluster with Google Cloud
11. Don't Forget to Cleanup!
12. Kubernetes Dashboard on Google Cloud
13. Travis Deployment Overview
14. Installing the Google Cloud SDK
15. Updated Service Account steps for new GCP UI
16. Generating a Service Account
17. Ruby Version Fix
18. Running Travis CLI in a Container
19. Travis Login Issues, "iv undefined" or "repository not known"
20. Encrypting a Service Account File
21. More Google Cloud CLI Config
22. Fix For Failing Travis Builds
23. Running Tests with Travis
24. Custom Deployment Providers
25. Unique Deployment Images
26. Unique Tags for Built Images
27. Updating the Deployment Script
28. Configuring the GCloud CLI on Cloud Console
29. Creating a Secret on Google Cloud
30. Helm v3 Update
31. Helm Setup
32. Kubernetes Security with RBAC
33. Assigning Tiller a Service Account
34. Ingress-Nginx with Helm
35. Quick Note about the Default Backend
36. The Result of Ingress-Nginx
37. Finally - Deployment!
38. Did I Really Type That?
39. Verifying Deployment
40. A Workflow for Changing in Prod
41. Merging a PR for Deployment
42. That's It! What's Next?
43. Completed Code For Google Cloud Deployment

## HTTPS Setup with Kubernetes

1. HTTPS Setup Overview
2. Domain Purchase
3. Domain Name Setup
4. Required Updates for Cert Manager Install
5. Cert Manager Install
6. How to Wire Up Cert Manager
7. Required Update for Issuer
8. Issuer Config File
9. Required Update for the Certificate
10. Certificate Config File
11. Deploying Changes
12. No Resources Found?
13. Verifying the Certificate
14. Required Update for the HTTPS Ingress
15. Ingress Config for HTTPS
16. It Worked!
17. Google Cloud Cleanup
18. Local Environment Cleanup

## Local development with Skaffold

1. Awkward Local Development
2. Installing Skaffold
3. The Skaffold Config File
4. Skaffold Sync Update and Example Source Code
5. Live Sync Changes
6. Automatic Shutdown
7. Testing Live Sync with the API Server

## Extras

1. Bonus!

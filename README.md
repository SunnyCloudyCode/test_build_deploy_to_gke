# Github Actions example to integrate with GCP

In this example we are demonstrating a workflow where we will be doing the following using GitHub Actions

1. Build a container using Google Cloud Build.

2. Run unit tests on the container.

3. If the unit tests is successful, then create an image and publish it to Artifact Registry

4. Authenticate with a GKE Cluster

5. Deploy the image from the Artifact Registry into the GKE Cluster

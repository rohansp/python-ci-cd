**python-ci-cd**
A project that uses a Python script to demonstrate a CI/CD pipeline.

```mermaid
graph LR
    A[Lint and test the Python code] --> B[Build and push the container image to GHCR]
    B --> C[Pull and run the image to verify output]
```

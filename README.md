CI/CD Pipeline Documentation
This project uses GitHub Actions to simulate a basic CI/CD pipeline.

The workflow is defined in .github/workflows/deploy.yml and is triggered automatically on every push to the master branch.

Pipeline Steps:
Checkout Code – Retrieves the latest version of the repository.

Set up Python – Configures Python 3.11 as the runtime environment.

Run Test – Executes a simple Python script (test.py) to simulate automated testing.

Build Step – Prints a message to simulate a build process.

Deploy Step – Prints a message to simulate deployment.

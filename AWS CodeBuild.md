It's a service for building the application in the cloud.

1. Compiles the source code
2. Run tests
3. Produces packages

It retrieves the code from [[AWS CodeCommit]], builds the code and generates the ready-to-deploy artifact (all dependencies are obtain via [[AWS CodeArtifact]]).
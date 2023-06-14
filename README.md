# cpplayground-github-actions
This is a sample project that demonstrates how to use GitHub Actions and Docker to build C++ code. It can be used as a starting point for C++ apps and libraries.

The `Dockerfile` installs the toolchain and other desired tools, and a container from this Docker image is used to build the code with Cmake. 

GitHub Actions workflow is specified under `.github` and demonstrates a basic multi-job build functionality. 

## Running a build
A build can be kicked off by clicking Actions > Select `C++ Docker build` > Run Workflow pulldown > Click on “Run Workflow”.

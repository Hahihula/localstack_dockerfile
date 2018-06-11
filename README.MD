# Dockerfile for Localstack

This is simple modification of localstack/localstack Dockerfile which changes it's entrypoint to cmd. The reason for this is bad propagation of SIGTERM in jenkins CI with old docker version.
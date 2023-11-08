FROM alpine:latest

# For the E2E Test for Retrieved Files, nothing needs to be done, since alpine:latest comes baked with a /etc/passwd file
# and by helm chart default, the KhulnaSoft Analyzer will pull it out

# For the Content Search, we need to throw a file we know in the image
COPY ./khulnasoft-e2e-content-search-test.txt /khulnasoft-e2e-content-search-test.txt
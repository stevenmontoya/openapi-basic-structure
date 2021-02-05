# Basic Structure to Define OpenApi

This repository contains a basic structure to define and generate an html API report

## Setup 🚀

You can run the following docker image to generate html report

```
 docker run --rm \
    -v $PWD:/local openapitools/openapi-generator-cli generate \
    -i /local/openapi-rest.yml \
    -g html \
    -o /local/out/
```

# {TEMPLATE_SERVICE_NAME} Service
Template generated service that includes, server stubs, clients and IaC

![](logo/bh_grpc_kotlin.png)

## Overview

This directory contains a generated repos for the service - {TEMPLATE_SERVICE_HYPHEN_NAME}

- This repo was created using builder-hub from a starter template for service creation.
- For more details on the starter template, see the [project on github](https://github.com/builder-hub/starter-service).

## Package Structure

The starter sources are organized into the following top-level folders and files:

- [{TEMPLATE_SERVICE_HYPHEN_NAME}-service-server]({TEMPLATE_SERVICE_HYPHEN_NAME}-service-server): Server that runs on a Kotlin coroutine inside a docker container.
- [{TEMPLATE_SERVICE_HYPHEN_NAME}-infrastructure]({TEMPLATE_SERVICE_HYPHEN_NAME}-infrastructure): Infrastructure-as-code to deploy and run server remotely on AWS.
- [{TEMPLATE_SERVICE_HYPHEN_NAME}-service-kotlin-client]({TEMPLATE_SERVICE_HYPHEN_NAME}-service-kotlin-client): Client that runs on a Kotlin coroutine

## Deploy and destroy from macOS
<details>
<summary> Run the server locally </summary>

Follow the instructions from the server package to run locally

</details>
<details>
<summary> Run the server remotely </summary>

Follow the instructions from the infrastructure package to deploy and destroy your infrastructure

</details>
<details>
<summary> Run the client </summary>

Follow the instructions from the client package to run the client test.

</details>
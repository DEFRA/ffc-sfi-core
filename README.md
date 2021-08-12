# FFC SFI Core
Local development support for orchestrating all FFC SFI microservices.

## Overview

This repository contains helper scripts to clone, update and run all Sustainable Farming Incentive (SFI) microservices locally with Docker Compose.

## Prerequisites

Ensure you have satisfied the prerequisites of all individual repositories.

## SFI Microservices

### Apply web

Front end service for external users to apply for SFI and submit an agreement.

- https://github.com/DEFRA/ffc-sfi-apply-web

### Apply API

Abstraction layer to support integration with Siti Agri.

- https://github.com/DEFRA/ffc-sfi-apply-api

### Siti Agri mock

Siti Agri stub

- https://github.com/DEFRA/ffc-sfi-siti-agri-mock

### Agreement calculator

Spatial calculation engine to validate and calculate value of SFI agreement.

- https://github.com/DEFRA/ffc-sfi-agreement-calculator

### Agreement processing

Post submission validation and internal user case working service.

- https://github.com/DEFRA/ffc-sfi-processing-web

### Payment batch processor

Validate and process payment batch files from Siti Agri.

- https://github.com/DEFRA/ffc-sfi-payment-batch-processor

### Payments

Validation, mapping and processing of payment requests supporting integration with Dynamics 365.

- https://github.com/DEFRA/ffc-sfi-payments

### Payment web

Internal user admin web application to manage payment holds and processing.

- https://github.com/DEFRA/ffc-sfi-payment-web

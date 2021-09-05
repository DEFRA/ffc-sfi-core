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

### Agreement API

Agreement management service

- https://github.com/DEFRA/ffc-sfi-agreement-api
- 
### Apply API

Abstraction layer to support integration with Siti Agri.

- https://github.com/DEFRA/ffc-sfi-apply-api

### Agreement calculator

Spatial calculation engine to validate and calculate value of SFI agreement.

- https://github.com/DEFRA/ffc-sfi-agreement-calculator

### Agreement processing

Post submission validation and internal user case working service.

- https://github.com/DEFRA/ffc-sfi-processing-web

### Payment batch processor

Validate and process payment batch files from Siti Agri.

- https://github.com/DEFRA/ffc-sfi-payment-batch-processor

### Payment enrichment

Validation and mapping of payment requests.

- https://github.com/DEFRA/ffc-sfi-payment-enrichment

### Payment processing

Processing of payment requests including post payment adjustment and ledger splitting.

- https://github.com/DEFRA/ffc-sfi-payments

### Payment submission

Publish payment requests to Dynamics 365.

- https://github.com/DEFRA/ffc-sfi-payment-submission

### Payment responses

Process payment responses from Dynamics 365.

- https://github.com/DEFRA/ffc-sfi-payment-responses

### Payment web

Internal user admin web application to manage payment holds and processing.

- https://github.com/DEFRA/ffc-sfi-payment-web

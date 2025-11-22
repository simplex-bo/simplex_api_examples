# simplex_api_examples
This repo contains sample requests for interacting with simplex invoice service using Bruno


## Setup

1. [Download Bruno](https://www.usebruno.com/downloads).

2. Clone this repo locally.
    ```
    git clone https://github.com/simplex-bo/simplex_api_examples.git
    ```
3. Open Bruno

4. Go to file -> Open Collection -> Select cloned repo from file manager

5. Setup an environment with the following variables:
    - host: `https://dzk79a7bzp.us-east-1.awsapprunner.com`
    - token: `your_token`

## API usage

The Simplex invoice service has several groups of endpoints which can be used for different tasks of the invoice emission process. The 3 main components for invoice emission are:

 1. Product Management. This includes list, create and update products. These products are used for filling the invoice data at emission time.
 2. Client Management. This  includes list and create clients for invoice emission.
 3. Invoice Emission. This includes the enpoints related to invoice emission and pdf retrieval.

Additionally, there are several helper endpoints for retrieving data important for the invoice emission, this includes token authentication and SIN (Servicion de Impuestos Nacionales) catalogs.



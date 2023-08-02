# KryptoJobs2Go Ethereum Integration

KryptoJobs2Go is an application where you can hire Fintech professionals using Ether as a form of payment. This project integrates Ethereum wallets and transactions into KryptoJobs2Go. The integration is accomplished using Python, the `web3` Python library, and the Streamlit library for a basic front end.

## Project Structure

This project consists of two Python scripts:

1. `crypto_wallet.py` - This file contains functions for generating an Ethereum account, retrieving the balance of an account, and sending transactions from one account to another.

2. `krypto_jobs.py` - This script serves as the main application. It utilizes Streamlit to create an interactive web application. You can select a candidate to hire, input the number of hours worked, and send a transaction to pay the candidate in Ether.

## Setup and Usage

To setup and run this project:

1. Ensure you have Python installed, preferably Python 3.7 or newer.

2. Clone this repository.

3. Install the required dependencies by running `pip install -r requirements.txt`.

4. Create a `.env` file with your environment variables, specifically your mnemonic seed phrase.

5. Start the Streamlit application by running `streamlit run krypto_jobs.py`.

6. Navigate to the local or network URL provided by Streamlit.

## Screenshots

### Ganache Account

Here is a screenshot of the Ganache account showing the address, balance, and transaction (TX) count:

![Ganache Account](./path_to_your_image/account_screenshot.png)

### Ganache Transaction

Here is a screenshot of the transaction from the Ganache transactions tab:

![Ganache Transaction](./path_to_your_image/transaction_screenshot.png)


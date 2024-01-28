 # Blockchain with Flask and Python

This project demonstrates how to create a simple blockchain using Flask and Python. The blockchain is a decentralized, distributed ledger that records transactions across multiple computers so that any involved record cannot be altered retroactively, without the alteration of all subsequent blocks.

## Prerequisites

To run this project, you will need the following:

- Python 3.6 or later
- Flask
- hashlib

## Installation

To install the required dependencies, run the following command in your terminal:

```
pip install flask hashlib
```

## Project Structure

The project consists of the following files:

- `app.py`: This is the main Python script that contains the Flask app and the blockchain logic.
- `Block.py`: This file defines the `Block` class, which represents a block in the blockchain.
- `README.md`: This is the project's README file.

## Running the Project

To run the project, follow these steps:

1. Clone the project repository to your local machine.
2. Open a terminal window and navigate to the project directory.
3. Run the following command to start the Flask app:

```
python app.py
```

4. Open a web browser and navigate to `http://localhost:5000`. You should see the following message:

```
<h1>Hello Blockchain</h1>
```

## Understanding the Code

### `Block.py`

The `Block.py` file defines the `Block` class, which represents a block in the blockchain. Each block has the following attributes:

- `index`: The index of the block in the blockchain.
- `previous_hash`: The hash of the previous block in the blockchain.
- `timestamp`: The timestamp of the block.
- `data`: The data stored in the block.
- `hash`: The hash of the block.
- `nonce`: The nonce used to generate the hash of the block.

### `app.py`

The `app.py` file contains the Flask app and the blockchain logic. The app has the following routes:

- `/`: This route returns a simple message "Hello Blockchain".
- `/get`: This route returns the entire blockchain as a JSON response.
- `/mine`: This route mines a new block and adds it to the blockchain.
- `/add_block`: This route adds a new block to the blockchain with custom data.
- `/valid

Generated by [BlackboxAI](https://www.blackbox.ai)
# IAS ALM 1 – Encryption Algorithms and Client–Server File Transfer

This project contains Caesar Cipher, Playfair Cipher, and Simplified DES (SDES) implementations, along with a TCP client/server application for encrypted message and file transfer.

## Project structure

- `algorithms/` – cipher implementations
- `client_server/` – TCP client and server
- `files/` – sample input/output files used for transfer demonstrations
- `screenshots/` – project output screenshots
- `create_file.py` – helper script to generate the 10 KB sample file

## Run

Run the server in one terminal with `python client_server/server.py`, then run the client in another terminal with `python client_server/client.py`. Start both from the project root.

Python 3 is required.
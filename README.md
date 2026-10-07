# Python Blockchain

A minimal proof-of-work blockchain with a REST API.

## Run
pip install -r requirements.txt
python blockchain.py

Server starts at http://127.0.0.1:5000

## Endpoints
- GET  /mine_block        → mine a new block
- GET  /get_chain         → return the full chain
- GET  /is_valid          → check chain integrity
- POST /add_transaction   → add a transaction to the pending pool
- POST /connect_node      → register peer nodes
- GET  /replace_chain     → consensus: adopt the longest valid chain
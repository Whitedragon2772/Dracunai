# Dracunai
open
curl https://eth-mainnet.alchemyapi.io/v2/o93me4joIgLBJZ_b7E1ROZJYj4x7_hha \
-X POST \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id": 1, "method": "eth_subscribe", "params": ["newHeads", {"includeTransactions": true}]}'

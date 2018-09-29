# ADE-TOKEN-CONTRACT
ADE token creation in EOS blockchain


{
  "status": "executed",
  "cpu_usage_us": 982,
  "net_usage_words": 15,
  "trx": {
    "id": "ff0b477d99db40da6ffb7325833f105160e1f50407b23ba28d410b31af4ba766",
    "signatures": [
      "SIG_K1_KVh6RdhsbGQW74voi8HmJ2Fa1XxisteskDCVob1HZrVGG5253WCoRxNcmv3hxRAKLQYqF1EuePqabjNhDsnfdNBCvYzBrw"
    ],
    "compression": "none",
    "packed_context_free_data": "",
    "context_free_data": [],
    "packed_trx": "a855af5b771c42fcbb7700000000013015a4f9aa149d3e0000000000a53176013015a4d961aa92410000000080ab26a7193015a4d961aa924100a0724e1809000004414445000000000000",
    "transaction": {
      "expiration": "2018-09-29T10:36:24",
      "ref_block_num": 7287,
      "ref_block_prefix": 2008808514,
      "max_net_usage_words": 0,
      "max_cpu_usage_ms": 0,
      "delay_sec": 0,
      "context_free_actions": [],
      "actions": [
        {
          "account": "buildertoken",
          "name": "issue",
          "authorization": [
            {
              "actor": "cadeositoken",
              "permission": "owner"
            }
          ],
          "data": {
            "to": "cadeositoken",
            "quantity": "1000000000.0000 ADE",
            "memo": ""
          },
          "hex_data": "3015a4d961aa924100a0724e18090000044144450000000000"
        }
      ],
      "transaction_extensions": []
    }
  }
}

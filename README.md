# amazon-ip-srs

This repository provides list of all Amazon and only AWS IP subnets, available in both **CIDR** and **SRS** (Sing-box Rule Set) formats.

## Direct Links

You can use the raw `.srs` files directly in your configurations via the following links:

- **[amazon.srs](https://github.com/Beta-Blaze/amazon-ip-srs/raw/refs/heads/main/amazon.srs)**
- **[aws.srs](https://github.com/Beta-Blaze/amazon-ip-srs/raw/refs/heads/main/aws.srs)**

## Usage Example

Here is an example of how to use the SRS file:

```json
"rule_set": [
  {
    "type": "remote",
    "tag": "aws-ruleset",
    "format": "binary",
    "url": "https://github.com/Beta-Blaze/amazon-ip-srs/raw/refs/heads/main/aws.srs"
  }
]
```

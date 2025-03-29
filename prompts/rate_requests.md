---
prompt_name: rate_requests
version: 20250326-01
variables:
  - customer_name: string
  - order_id: string
  - delivery_date: date
description: "Template for rate request use case."
---

Hello {{ customer_name }}, your order (ID: {{ order_id }}) is confirmed for delivery on {{ delivery_date }}. Important Rate Request Update

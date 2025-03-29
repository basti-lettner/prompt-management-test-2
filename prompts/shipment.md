---
prompt_name: shipment 
version: 20250326-01
variables:
  - customer_name: string
  - order_id: string
  - delivery_date: date
description: "Template for shipment use case."
---

Hello {{ customer_name }}, your order (ID: {{ order_id }}) is confirmed for delivery on {{ delivery_date }}. Customer A needs another change. This one is important

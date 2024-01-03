---
_build:
  publishResources: false
  render: never
  list: never
---

Use this selector to choose the DNS resource record type that you would like to apply policies against. For example, you can match `A` records for a domain but not `MX` records.

| UI name           | API example                | Evaluation phase      |
| ----------------- | -------------------------- | --------------------- |
| Query Record Type | `dns.query_rtype == "TXT"` | Before DNS resolution |
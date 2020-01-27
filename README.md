# Sell

For gitters can easily fork and sale their product online.

## Design
1. Use Google Firebase as database and storage, since it is free with great features.
2. Google Angular as UI framework
3. Use travis for CI/CD

## Business Use Case

### By shipment (Prefered)
1. Seller list items with images/videos, description, price and location
2. Buyer pay the item as purchase
3. Agent hold the payment until Seller ship to Buyer
4. Seller ship the item in 30 days, or the item will be canceld automatically or by the buyer
5. Buyer should able to receive the item in 30 days after seller file the shipment number (Prefer using API to tracedown)
6. Item automatically marked as completed after buyer receive the item

### By picking up
Only Seller can mark the item as sold or unlist/relist/archive item from selling.

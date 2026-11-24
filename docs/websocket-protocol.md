# WebSocket Event Protocols

Real-time bidding uses Socket.io channels for low-latency live auctions.

## Events
- `join_auction`: Client joins auction room.
- `place_bid`: Client submits an auction bid.
- `new_bid`: Server broadcasts the latest highest/lowest bid.
- `auction_ended`: Server signals end of round with winning details.

### Payload Formatting
All payloads must contain `chitId`, `cycleId`, `bidderId`, and `amount` attributes.

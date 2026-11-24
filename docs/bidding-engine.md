# Live Bidding Engine Specification

The live bidding room allows members to bid dynamically during the chit cycle.

## Auction Rules
- **Minimum Bid Increment**: Configured per chit group parameters.
- **Cap Limit**: Standard statutory cap (typically 30-40% of the pot value).
- **Tie Breaking**: In case of duplicate bids or ties, timestamp priority or lottery decides the winner.

### Example Calculation
For a pot of 100,000 INR, minimum decrement/increment is 500 INR up to maximum allowed ceiling.

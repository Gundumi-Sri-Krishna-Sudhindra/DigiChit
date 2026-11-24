# Live Bidding UI Architecture

Detailed breakdown of real-time client bidding interactions.

## Components
- **LiveTimer**: Countdown timer synchronizing auction end times.
- **BidHistoryList**: Real-time virtualized list of bids placed in current round.
- **QuickStepButtons**: Preset buttons for +500, +1000, +2000 increment bids.
- **DynamicActionCard**: Displays current highest bidder and projected dividend.

### Quick Step Logic
Quick step buttons auto-populate the bid input with valid increments above current top bid.

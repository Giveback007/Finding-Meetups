Out of frustration with using the meetup search to find events I decided to use the provided meetup api to see if I can solve this problem.

This collects all the groups within a radius and collects each of the groups upcoming events, the meetup API can throttle and block for up to an hour if to many calls are made. Limiter functions are installed to prevent this.

To be included:
1) OAuth-signed requests
2) Events to be mapped out on OpenStreetMap
3) Filtering out of events by date and other criteria 

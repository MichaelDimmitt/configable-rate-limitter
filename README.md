# configable-rate-limitter

notable (future) contributors: https://github.com/murjax

1. test data ... 3 apis that have rate limiting.
2. api tokens are secret so public people do not steal our apis and cost us money.
3. feature(batching) ... solution to not show records until an entire defined batch is done
4. daily limit, minitue limit, monthly limit, limit per second?
5. this is a gateway, any consumer should be able to use it.
6. can our infrastructure handle it? will we hit our own rate limit?
7. environment resets? If the gateway is down how do we handle the failing requests? ... if it fails go to the actual api as backup.


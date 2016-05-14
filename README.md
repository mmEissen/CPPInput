##CPPInput

###Description
Some functions for quick input.

###Performance

####Using `toUnsignedIntegral<uint32_t, '\n'>`
1000000 numbers, run 1000 times
```
avg: 29.56ms
avg abs. deviation: 0.30ms (1.00%)
SD: 0.53ms
```

####Using `std::cin` with `sync_with_stdio(false)`
1000000 numbers, run 100 times
```
avg: 796.22ms
avg abs. deviation: 36.10ms (4.53%)
SD: 48.72ms
```

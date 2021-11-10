# rhp_combinatoric
Sequence Space Calculation for RHP

## TODO:
- expand to multiple sequences/histogram: CANNOT think of as 1 super long chain. Calculate each chain separately and just multiply counts --> is it just to the power of number of chains, as in 1 segment they are all the same? These numbers will be HUGE - need to log scale. From there histogram is kinda easy just treat each segment separately and multiply each segment together at the end. Take that fat number as a ratio of assuming you have that total number of random chains - ungodly large number.
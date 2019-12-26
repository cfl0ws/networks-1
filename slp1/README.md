## v0.21.5 Upgrade - Deadline EOD 20 December 2019

We would like everyone to upgrade to v0.21.5 before EOD tomorrow (Fri 12/20)!

I have included instructions below (and you can find them here as well), please upgrade as soon as you can, so we can make sure we get everyone sorted ASAP.

As I mentioned previously, Solana support (Dan and Vines) will be actively monitoring Discord during two time windows (one tuned for Asia TZ, one for everyone else). So if you want to make sure you'll have technical assistance at the ready for when you upgrade, you should plan your upgrade in one of these two, 2-hour blocks:


|              | PT (GMT-8)           | HK/Singapore (GMT+8) | CET (GMT+1)      |
-------------- | -------------------- | -------------------- |------------------|
| GMT+8 Window | Th 12/19: 4-6pm      | Fri 12/20: 8-10am    | Fri 12/20: 1-3am |
| CET Window   | Fri 12/20 7-9am      | Fri 12/20 11pm-1am   | Fri 12/20 4-6pm  |

Again, the team will be on Discord during business hours (PT) and available to support as usual, the above times will just guarantee lower latency.

== Upgrade Instructions from [the SLP1 FAQ](https://docs.google.com/document/d/1nIkAuLhJfrxVmdskKxoy1M3NrThwnXB35dadWHVfXxk/edit?usp=sharing) ==

How do I upgrade my validator’s software?

1 - Install the new version ([v0.21.5](https://github.com/solana-labs/solana/releases/tag/v0.21.5)) using your preferred method

2 - Kill your existing validator process

3 - Delete the entire --ledger directory.  Re-opening a ledger that has been running for many days currently may take tens of minutes, so it’s a much faster restart if the node is forced to start from a freshly downloaded snapshot from the cluster. 

4 - Re-start your validator using the new version

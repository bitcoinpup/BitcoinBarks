# Pup's Double-Takes #001:

# "Let's Talk Supply Issuance"

![](https://bitcoinbarks.com/gallery_gen/c06fc7cd302e6be4cc64873b4c7d8b84_fit.png)

This will be a new format for some of my content.

Every so often, while browsing the news or social media, I come across something that makes me do a double-take. I've decided to share these moments, hoping to share highlights from, or address issues the with these media pieces and, at the very least, provide some entertainment for those who already see them.

With that in mind, welcome to Pup's Double-Takes, where I dive into the things that made me stop and say, 'Wait, what?' My goal is to unpack the curious and confusing, making it educational and, hopefully, a little entertaining along the way.

####   PDT-001: Let's Talk Supply Issuance

I stumbled across an [article](https://u.today/former-binance-ceo-speaks-out-after-prison-release-michael-saylor-makes-epic-99-bitcoin-prediction?amp) this morning from U.Today. Part of the headline _"Michael Saylor Makes Epic 99% Bitcoin Prediction"_ caught my attention as I was really unsure what a _"99% Bitcoin Prediction"_ was...

The article began:

_"In a recent [[X post](https://x.com/saylor/status/1840024420447895619)]..."According to Saylor's forecast, "99% of Bitcoin will be mined by January 2, 2035.""_

Checks out so far...

_"At the moment, about 94.1% of Bitcoin's maximum supply of 21 million has been mined, leaving about 1.24 million BTC yet to be created."_

Yep. Gotta love the supply schedule.

_"The prediction suggests a substantial surge in mining activity over the next decade, which would lead to nearly 5% more Bitcoin being mined sooner than expected."_

Wait, what?...

Now, I'm not the most technical bitcoin user in the world, but "mined sooner than expected" caught my attention. 

You see, Satoshi imbued Bitcoin with a fixed supply of just under 21,000,000 coins (20,999,999.979 coins to be exact) and an issuance schedule that meters the release of new bitcoin. Miners constantly guess random numbers, collectively making nearly 700 quintillion guesses per second at the time of writing, in an attempt to solve a block. Roughly every 10 minutes, one miner gets lucky, guesses a number sufficient to solve the block, and is awarded a block subsidy, or "newly minted bitcoin," for their efforts.

When the network was first brought online, this block subsidy was 50 bitcoin. Every 240,000 blocks (~3.992 years) this number is cut in half in an event known as the Halving. From its start in 2009 at 50 bitcoin, the subsidy dropped to 25, then 12.5, then 6.25, until most recently on April 19, 2024, it halved again to only 3.125 bitcoin per block. 

Base layer bitcoin is divisible to 8 decimal places (0.00000001 lovingly called a "satoshi" or "sat"), so over the next ~115 years the block subsidy will continue to fall until it can no longer be represented by 8 decimal places. At this point (around the year 2140), the Block Subsidy Era will end and miners will only receive transaction fees as payment for the work they perform securing the network. This is what sets Bitcoin's maximum supply— an ever-diminishing periodic release of new coins that eventually halves to 0.00000000.

Now I've covered supply, but what of timing? After all, the U.Today article said, _"...a substantial surge in mining activity over the next decade, which would lead to nearly 5% more Bitcoin being mined sooner than expected."_ If more people mine bitcoin, would it not make sense that it would be mined faster than Satoshi intended? If more people mine for gold, gold is discovered at a faster rate. Why shouldn't this hold true for bitcoin?

This is where Satoshi's true genius comes into play in the form of the difficulty adjustment. What is the difficulty adjustment? Let's unpack it.

Bitcoin's issuance was supposed to be fair—not equitable, but equal. Anyone could plug in a random number machine (miner), and have a shot at acquiring newly released bitcoin. The network didn't care who you were, saint, or sinner. But without an active mechanism that could meter the time between blocks, the whole "schedule" part of the issuance schedule would have been broken. The higher the hashrate (think number of random guesses per second) went, the faster blocks would be solved, and the more rapidly new bitcoin would be released. 

This is where the difficulty adjustment comes in. Every 2,016 blocks (roughly two weeks), the network checks how long it took to mine those blocks. The concept is simple, if blocks are being solved too quickly, make it harder to solve blocks; and if they are being solved too slowly, make it easier.

Imagine this system in play. As miners join the network, the difficulty level increases to maintain the 10-minute block intervals. If miners leave, the difficulty decreases. So no matter how many computers are throwing their power at solving a block, the network stays on schedule. This is why the claim of “mining 5% more Bitcoin sooner than expected” doesn’t hold water. The issuance schedule is locked in by the difficulty adjustment mechanism. Sure, mining activity can surge, but the network will respond accordingly, preventing any acceleration in the rate of Bitcoin issuance.

So now we have a issuance schedule, and a difficulty adjustment that ensures that the release of new bitcoin follow the prescribed schedule over time. So that's it, problem solved right? Well, not quite... Our next problem is time... 

For the difficulty adjustment to function, Satoshi needed a clock. But what clock? Or more importantly, whose? Relying on any centralized timekeeper would create an obvious point of failure. Whoever controlled that clock could easily manipulate the system, either by being co-opted by bad actors or exploiting their position of authority. Imagine if a government or large corporation held this integral key to Bitcoin's issuance schedule—they could alter the network's perception of time.

This was the very kind of centralized vulnerability Satoshi was trying to avoid. So, rather than relying on one entity to provide the clock, Satoshi made the bold choice to decentralize time itself through the use of miner-submitted timestamps.

Here’s how it works: Every time a miner solves a block, they include a timestamp—essentially a record of when they believe the block was mined. All miners are doing this independently, and their timestamps are used by the network to keep track of time and adjust the difficulty accordingly. That said, miners can't just make up timestamps at will. There are rules: the timestamp of each block must be greater than the median of the previous 11 blocks, and it can’t be too far into the future (by more than two hours).

This decentralized clock mechanism is what allows Bitcoin to maintain its issuance schedule without fear of manipulation, making it resilient against bad actors, even those with vast amounts of mining power. This is also why Satoshi referred to Bitcoin as a "Timechain". It was only through distributing the control over time that Satoshi removed any single point of failure and ensured that Bitcoin would remain a trustless, decentralized system.

And that’s the genius behind Bitcoin’s difficulty adjustment and timestamp rules. That's why no matter how many miners there are or how powerful their machines become, the issuance of new Bitcoin follows its preordained schedule. It's as if Bitcoin is running on the collective pulse of the entire network—truly decentralized, incorruptible, and self-regulating.

Saylor’s prediction that 99% of Bitcoin would be mined by 2035 is correct, but it’s not because of any _“...substantial surge in mining activity...”,_ as the U.Today article incorrectly inferred. It’s simply how Bitcoin was designed from day one. We don't need to worry about _"nearly 5% more Bitcoin being mined sooner than expected"_, because the issuance schedule is secured and metered by the difficulty adjustment and the decentralized clock that is the Timechain.

The key takeaway? No matter how much hype or noise surrounds mining, Bitcoin will march on—slowly, steadily, and predictably.

  
**Stay tuned for the next Pup's Double-Take where we might tackle another FUD piece that’s all bark and no bite!**

# Digging Deeper:

### **Hey there, I hope you enjoyed this read! If you did, and would like to read more of my barks, follow the links below!**

- Curious how I found Bitcoin? Read "[Paw Prints to the Timechain](https://bitcoinbarks.com/Barks/paw-prints-to-the-timechain/#wbb1 "https://bitcoinbarks.com/Barks/paw-prints-to-the-timechain/#wbb1")"!
    
- Bitcoin meets psychology? I touch on this in "[Maslow's Apex](https://bitcoinbarks.com/Barks/maslows-apex/#wbb1 "https://bitcoinbarks.com/Barks/maslows-apex/#wbb1")".
    
- Want to understand the basics of Bitcoin? Read "[Bitcoin Best Practice](https://bitcoinbarks.com/Barks/bitcoin-best-practice/#wbb1 "https://bitcoinbarks.com/Barks/bitcoin-best-practice/#wbb1")"!
    

### **External Resources:**

- Want to earn rewards on your mortgage? [Use my referral to earn 20,000 free sats at sign up!](https://use.foldapp.com/r/7KYTK4CP)
- Do you like sharing Bitcoin content and earning sats for doing so? [Join me at Stacker.news!](https://stacker.news/r/bitcoin_pup "https://stacker.news/r/bitcoin_pup")

# ...Woof!

[![](https://bitcoinbarks.com/gallery_gen/5240db5304f70dd121acbe8521f5d958_fit.jpg)](https://primal.net/p/npub1vgldyxx7syc30qm9v7padnnfpdfp4zwymsyl9ztzuklaf7j5jfyspk36wu)
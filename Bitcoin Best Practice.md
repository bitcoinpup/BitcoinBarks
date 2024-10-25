Bitcoin Best Practice
=====================

![](https://bitcoinbarks.com/gallery_gen/ccd831d8dbff61b1202d0514cbcca098_fit.png)

Learn Bitcoin: An Intro to The Technology
-----------------------------------------

Welcome to Bitcoin Best Practice---your guide to mastering the fundamentals of Bitcoin.

In the sections below, I'll walk you through the essentials of securing your bitcoin stack, ensuring you are able navigate the world of Bitcoin with confidence.

![](https://bitcoinbarks.com/gallery_gen/2c4075954ad48d5890f5f16d0fa2b4b3_fit.png)

Wallets and Seed Phrases: An Introduction
-----------------------------------------

### Hot Wallets vs. Cold Wallets:

![](https://bitcoinbarks.com/gallery_gen/765d29ae1a371497b5f2bfd856de8129_fit.png)

The distinction between hot and cold wallets is straightforward, but their implications for security make them crucial considerations.

Hot wallets are internet-enabled and usually take the form of software applications. They prioritize accessibility and ease of transacting but expose users to higher risk as the private keys are kept on the device for quick access. 

Cold wallets, on the other hand, exist offline as physical hardware devices, providing a higher level of security and more immunity to online threats by providing a physical barrier between the private keys and the internet. The obvious drawback in using cold wallets is the increased friction in transacting due to the private keys not being instantly accessible to an internet connected software application.

To bridge this divide between accessibility and security, users often find a balance using a hot wallet for daily transactions and a cold wallet for long-term storage as a risk management strategy.

### Signing Devices:

![](https://bitcoinbarks.com/gallery_gen/ea0d8197ab65bd7e0c8a62cd441b93a8_fit.png)

Signing devices (also known as hardware wallets) are physical devices designed to securely safeguard the private keys essential accessing and moving bitcoin. Functioning as a form of cold storage, these devices allow users to interface with private keys while keeping key material offline, mitigating the risk of potential online threats. 

Signing devices often feature a secure element---a dedicated and tamper-resistant chip---to fortify the protection of stored private keys. With a straightforward user interface comprising a screen and buttons, signing devices allow users to directly verify and confirm transactions on the device, adding an extra layer of security against potential malware on connected computers. Some signing devices also make use of a camera, allowing the user to send and recieve Partially-Signed Bitcoin Transactions (psbt's) via QR codes

Additionally, signing devices provide a seed phrase, (a series of words serving as a backup for private keys), enabling users to recover their funds in case of loss or damage to the device. Compatible with various software wallets , signing devices, including popular models like [Blockstream Jade](https://blog.blockstream.com/en-secure-your-bitcoin-and-liquid-assets-with-blockstream-jade/), [Coldcard](https://coldcard.com/), or [Foundation Passport](https://foundation.xyz/passport/), offer a balance between security and convenience. 

### Pup Recommends:

[![](https://bitcoinbarks.com/gallery_gen/986b2ab8be9852b5ded17ecfe4c654f3_fit.png)](https://blog.blockstream.com/en-secure-your-bitcoin-and-liquid-assets-with-blockstream-jade/)  [![](https://bitcoinbarks.com/gallery_gen/981945f5241ee97b0de27303a2c71cb4_fit.png)](https://coldcard.com/)  [![](https://bitcoinbarks.com/gallery_gen/aeef87b214a9c4e609970db9b76e1f8d_fit.png)](https://foundation.xyz/passport/)

### What is a seed phrase?

![](https://bitcoinbarks.com/gallery_gen/088994ee70f02cc5249b8c39dfd566e0_fit.png)

While I have mentioned seed phrases, I haven't really gone into what they are and why they are so important to the security of your bitcoin. A seed phrase is a sequence of words that act as a human-readable representation of a wallet's private key.

Example:\
Seed Phrase: 

stock, try, clap, gold, discover, volcano, august, chicken, gas, noise, swap, inmate

Private Key: xprv9xxc2vAH4iqa1PA8Eg2pA54AbrXEsQY2rU7kmaBrRnNgJwSdYmcMBobyC4jDng6Uk6MvjcWHSVAeSmDSgCDhaLgFwUCKgQVmLnWkLMhFmbc

### Seed Phrase Security (Backups):

Securing a seed phrase correctly is paramount to safeguarding your bitcoin. The seed phrase serves as a backup for the private key associated with your wallet, and plays a pivotal role in wallet recovery. In the event your signing device is lost, damaged or stolen, the correct and secure backup of the seed phrase is essential for restoring access to your funds.

Properly securing the seed phrase protects against unauthorized access, preventing potential misuse or theft of your bitcoin. Its privacy and ownership implications underscore the importance of keeping the seed phrase offline, away from electronic devices and the internet. The irreversible nature of Bitcoin transactions further emphasizes the need to store the seed phrase securely, using methods such as metal backup sheets or dedicated backup devices.

Avoiding digital storage is a very important measure in ensuring the long-term security and control of your bitcoin stack.

### Paper Backups:

![](https://bitcoinbarks.com/gallery_gen/211c9cc484c78002a8fd8d77200a4c6e_fit.png)

To securely back up a seed phrase on paper, carefully write down each word in the exact order provided by your signing device during setup. Use a pen or permanent marker on a clean, durable sheet of paper, ensuring neat and legible writing to prevent errors during recovery. Include spaces between words and any punctuation or checksum words if presented.

Store the paper in a physically secure location, such as a fireproof and waterproof safe, to protect it from potential damage. For added security, consider creating multiple copies and storing them in different secure locations, but exercise caution to avoid compromising security.

Avoid digital storage and resist the urge to take photos, keeping the seed phrase strictly on paper.

### Steel Backups:

![](https://bitcoinbarks.com/gallery_gen/f555c9a5073780c0afed72bd8b9442c0_fit.png)

To back up a seed phrase on stainless steel, transcribe each word of the seed phrase onto a stainless plate or sheet, using a punch or engraving tool to etch the information onto the metal surface. Ensure precision and clarity in your engraving to prevent errors during recovery.

Stainless steel provides resistance against fire, water, and physical damage, making it an ideal material for long-term storage. Store the backup in a secure location, such as a safe or another place resistant to environmental hazards. This method guards against potential deterioration that paper-based backups might face and adds an extra layer of resilience to the security of your bitcoin holdings.

Consider creating duplicate metal backups and storing them in separate secure locations for added redundancy.

### Pup Recommends:

[![](https://bitcoinbarks.com/gallery_gen/1300e7f98fc955c341ccc1b592b30c7d_fit.png)](https://blockmit.com/english/guides/diy/make-cold-wallet-washers/)  [![](https://bitcoinbarks.com/gallery_gen/6d1cfd2b45b243b89aa2ac1cca603639_fit.png)](https://www.bitplates.com/)

### Final Notes on Seed Phrases:

Remember: The confidentiality and safety of your seed phrase are paramount for the security of your bitcoin. Your seedphrase is your bitcoin, and anyone who has access to it, has access to your bitcoin by default. Treat it with the same level of importance as a physical key to a safe deposit box.

### Bonus Content: The Problems with Address Reuse

![](https://bitcoinbarks.com/gallery_gen/d52968ba35c7c8f620ac1515bfa0335b_fit.png)

Reusing Bitcoin addresses poses some significant risks primarily due to privacy concerns.

Address reuse diminishes the level of financial privacy as it enables blockchain observers to trace and link transactions, potentially unveiling spending patterns and habits. Address correlation becomes a risk, especially if an address is somehow linked to an individual's identity, as transactions to or from that address can be associated with them.

To maintain a higher level of privacy and security, it is advisable to use a new Bitcoin address for each transaction, this is known as address rotation, which modern wallets often automate to support these privacy-preserving principles.

UTXOs: A Beginner's Guide
-------------------------

### Unspent Transaction Outputs:

![](https://bitcoinbarks.com/gallery_gen/45b0534a612ad660f885c96ab30f29fb_fit.png)

What is a UTXO? Bitcoin uses a transaction model that is fundamentally different from traditional banking systems. Instead of holding balances in accounts, Bitcoin tracks the movement of discrete "chunks" of value as they transfer between addresses.

Bitcoin transactions contain inputs (value sent) and outputs (value received). A UTXO is a transaction output that has never become an input in a following transaction. In other words, UTXOs are essentially independent chunks of value that haven't been spent yet (Unspent Transaction Outputs).

### UTXO Creation:

When someone sends you bitcoin, what they are really doing is creating a transaction where outputs (UTXOs) are assigned to an address that you control the private keys to. These UTXOs cannot be moved (either transferred or spent) without your private keys being used to sign a transaction that features them as inputs.

### Moving UTXOs:

To move bitcoin, (this includes transferring bitcoin to another address you control, or spending it to an address someone else controls in exchange for goods or services) , you create a new transaction. This transaction will use your UTXOs as inputs.

Say you have a UTXO worth 1 BTC and you want to send 0.3 BTC to someone. Your transaction will use the 1 BTC UTXO as an input and create two new UTXOs as output: one for 0.3 BTC to the recipient's address, and one for 0.7 BTC as change, which goes back to an address you control. Many modern wallets automate this process and will automatically select a "change address" for you that is derived from your private key and thus under your control.

### UTXOs Continued: No Partial Spending

A key aspect is that UTXOs are indivisible. If you have a UTXO worth 1 BTC, you can't just spend 0.5 BTC of it. You have to spend the whole UTXO and then send any change back to yourself. The Bitcoin network tracks all UTXOs. When a transaction is made, the network checks if the UTXOs being used are valid and unspent. This prevents double-spending.

UTXO Manangement: Digging Deeper...
-----------------------------------

### Optimal UTXO Sizing:

![](https://bitcoinbarks.com/gallery_gen/c4871537ce002820a9c8c88a0d76d09c_fit.png)

The open and transparent nature of the Bitcoin blockchain, along with the indivisibility of Unspent Transaction Outputs (UTXOs), can have significant implications for user privacy, especially when dealing with large UTXOs. In Bitcoin, every transaction is visible on its public ledger, accessible through various blockchain explorers. When a user spends bitcoin, they must use entire UTXOs, as these are indivisible. This means if a user's UTXO is larger than the transaction amount, the excess is returned as 'change'.

For instance, if someone has a single UTXO worth 10 BTC and wishes to send 1 BTC, the transaction would reveal that the sender initially had at least 10 BTC. This simple transaction would feature a single input: 1 BTC, and would feature create three outputs: 1 BTC to the recipient, a miner fee, and 9 BTC (minus the miner fee) as change, returned either to a new or existing address controlled by the sender.

This transparency can inadvertently expose the amount of bitcoin a user holds. While the change is often sent to a different address for privacy, sophisticated observers can sometimes link these change addresses to the sender, especially if addresses are used repeatedly. Users seeking better privacy might employ strategies like using multiple addresses or breaking down their bitcoin into smaller UTXOs, complicating the task of determining their total holdings. 

### Transaction (miner) fees:

Bitcoin miner fees are influenced by two main factors: network traffic and the transaction size.

The network traffic, or how busy the Bitcoin network is, plays a crucial role in determining fees. During periods of high traffic, users often compete to have their transactions confirmed quickly by offering higher fees. This dynamic can lead to fluctuating fees based on the overall activity on the network.

The second factor, the transaction size, is equally important. Each Bitcoin transaction can have multiple inputs, especially if a user's total balance is spread across many small UTXOs. The more inputs a transaction has, the larger its size in vBytes (a unit of that basically measures how much a transaction "weighs" and thus how much blockspace it will take up), and consequently, the higher the fee required to process it. Therefore, transactions comprising many small inputs can become quite expensive due to their larger size.

In contrast, using larger UTXOs can be more economical as transactions made using a few large UTXOs rather than many small ones, typically result in lower fees relative to the value being transferred. The fee as a percentage of the transacted value is generally smaller when larger UTXOs are used.

There's a tipping point where small UTXOs may become economically impractical. If the value of a UTXO is so small that the transaction fee required to spend it is comparable to or exceeds its value, then it effectively becomes "dust" -- too costly to be worth spending. This "dust limit" often occurs during periods of high network congestion, where fees spike. The accumulation of such dust in a wallet can be a frustrating experience, as it represents a value that is technically owned but practically unspendable without incurring a loss. This aspect underscores the importance of UTXO management in Bitcoin and is a key consideration for users when consolidating funds or receiving small, frequent transactions.

### Finding Balance:

You can work towards achieving a balance between maintaining privacy and minimizing Bitcoin miner fees through strategic UTXO management, and timely consolidation of UTXOs. With a variety of UTXO sizes, users can select the most suitable ones for each transaction, reducing the likelihood of linking transactions to each other or revealing total holdings. This approach enhances transaction flexibility without exposing larger UTXOs.

The process of manually selecting which UTXOs you want to use in a given transaction is called "Coin Control".

Note: For smaller, frequent transactions, the Lightning Network, a second-layer protocol on top of the Bitcoin blockchain, offers a viable solution. It enables fast and low-cost transactions, circumventing the creation of small UTXOs on the main blockchain. This not only conserves fees but also minimizes one's transactional footprint on the blockchain, thus bolstering privacy.

UTXO consolidation is the process of sending multiple small UTXOs to oneself in a single transaction resulting in a singular, larger UTXO. Although this consolidation may reduce privacy due to the linkage of multiple (potentially previously unaffiliated) UTXOs to a single address, it strategically lowers future transaction fees.

Effective consolidation may require timing transactions for when the Bitcoin network is least busy. Monitoring average transaction fees over time aids in identifying opportune moments for consolidation. Additionally, planning transactions in advance can mitigate the necessity for urgent, high-fee transactions during peak periods.

In summary, by using coin control, leveraging the Lightning Network for smaller day-to-day transactions, and strategically consolidating UTXOs during low-fee periods, users can find a middle ground between preserving privacy and minimizing transaction fees. This approach necessitates proactive and informed  management, with an awareness of network conditions and an understanding of the various transactional trade-offs.

Becoming a Psychopath: Running a Node
-------------------------------------

### Why Run a Node?

![](https://bitcoinbarks.com/gallery_gen/5ef480062d7f791cf24e3daf5caac387_fit.png)

Running your own Bitcoin node offers a range of significant advantages:

Security: Having your node allows you to independently verify the authenticity of transactions and blocks. This independence ensures that you're not relying on potentially compromised or malicious nodes to validate your Bitcoin transactions, contributing to a more secure experience. Furthermore, your node becomes an integral part of the decentralized network infrastructure, bolstering network resilience against censorship attempts and malicious attacks as more nodes join the network.

Privacy: When you rely on third-party wallet services or external nodes, you may need to share your Bitcoin addresses and transaction details with these services, potentially compromising your financial privacy. However, by running your own node, you retain control over this information, preventing the correlation of your financial activities with your identity and ensuring enhanced privacy.

Educational Benefits: It provides a unique opportunity to delve into the inner workings of the Bitcoin protocol, facilitating a deeper understanding of blockchain technology and decentralization principles. This hands-on experience can be enlightening and empower you with knowledge about how the Bitcoin network functions.

Self-Sovereignty: Running your node enables you to support specific features, scaling solutions, or consensus changes within the Bitcoin ecosystem. You have the flexibility to choose a preferred Bitcoin software implementation, allowing you to endorse and actively participate in discussions and debates in the Bitcoin community that align with your chosen set of rules. This active involvement contributes to the network's evolution and the advancement of features that reflect your preferences and values.

In summary, running your own Bitcoin node not only enhances security and privacy but also provides valuable educational insights and the opportunity to actively shape the Bitcoin ecosystem by supporting specific features and solutions that align with your beliefs. It's a multifaceted way to engage with Bitcoin, aligning with its core principles of security, privacy, and decentralization.

Bitcoin Core: Why Core?

![](https://bitcoinbarks.com/gallery_gen/d464e50b1e16940f454b7d1840191ff5_fit.png)

Bitcoin Core is considered one of the most popular and reliable Bitcoin implementations to run for several compelling reasons:

Official Software: Bitcoin Core is the official reference implementation of the Bitcoin protocol. It is actively developed and maintained by a dedicated group of Bitcoin developers who prioritize its security, stability, and adherence to the Bitcoin whitepaper. As the reference client, it sets the standard for the Bitcoin network

Longevity and Trust: Bitcoin Core has a long history and a track record of reliability. It has been in development since Bitcoin's inception in 2009 and has successfully weathered various challenges and network upgrades. Its longevity and continuous development contribute to its trustworthiness.

Community Support: Bitcoin Core benefits from a large and active community of users and contributors. This community provides valuable peer review, support, and testing, which helps ensure the software's quality and security.

Full Node Capabilities: Bitcoin Core offers the complete range of functionalities expected from a full Bitcoin node. It allows you to validate transactions, blocks, and the entire blockchain independently. This full node capability aligns with the principles of decentralization and self-sovereignty that are fundamental to Bitcoin

Transparency: The development process of Bitcoin Core is transparent and open-source, allowing anyone to review the code and participate in its improvement. This transparency builds trust in the software.

### Installing Bitcoin core:

![](https://bitcoinbarks.com/gallery_gen/d4c419d912d60622cfae33cf7a1b1f8f_fit.png)

To run Bitcoin Core, the official Bitcoin software, follow these steps:

Visit the [Bitcoin Core website](https://bitcoin.org/en/download) and download the version suitable for your operating system (Windows, macOS, or Linux).

Make sure to select the "Bitcoin Core" option, which includes the full node software.

Once downloaded, proceed to install Bitcoin Core by following the installation instructions for your specific operating system.

During the initial launch of Bitcoin Core, the software will commence the process of downloading the entire Bitcoin blockchain, a task that can take a significant amount of time and necessitates ample storage space (currently over 600 GB).

Ensure your computer possesses sufficient storage and a reliable internet connection for this step.

Optionally, you can configure Bitcoin Core's behavior by editing the bitcoin.conf configuration file, allowing you to customize network preferences and other settings.

Following the completion of the initial blockchain download, launch Bitcoin Core, and it will begin syncing with the Bitcoin network, verifying transactions and blocks. Please be patient during this synchronization process as it may take a while. You can monitor Bitcoin Core's progress and status through its built-in graphical user interface or command-line interface.

Regularly update your Bitcoin Core software to stay current with the latest features and security patches.

By running Bitcoin Core, you actively contribute to the network's security and decentralization, as your node will relay transactions and blocks to other nodes, strengthening the entire network.

Conclusion:
-----------

Thanks for wagging your way through my Bitcoin Best Practices guide!  I hope you found my breakdown of wallets, seed phrases, UTXOs management, and running Bitcoin Core helpful. By now, you should feel more confident in protecting your Bitcoin and navigating the blockchain securely. If you have any feedback or questions, head over to my [contact page](https://bitcoinbarks.com/Contact/) and give me a bark. Your insights help me improve and better assist others!

Digging Deeper:
===============

### Hey there, I hope you enjoyed this read! If you did, and would like to read more of my barks, follow the links below!

-   Curious how I found Bitcoin? Read "[Paw Prints to the Timechain](https://bitcoinbarks.com/Barks/paw-prints-to-the-timechain/#wbb1 "https://bitcoinbarks.com/Barks/paw-prints-to-the-timechain/#wbb1")"!

-   Bitcoin meets psychology? I touch on this in "[Maslow's Apex](https://bitcoinbarks.com/Barks/maslows-apex/#wbb1 "https://bitcoinbarks.com/Barks/maslows-apex/#wbb1")".

### External Resources:

-   Want to earn rewards on your mortgage? [Use my referral to earn 20,000 free sats at sign up!](https://use.foldapp.com/r/7KYTK4CP)
-   Do you like sharing Bitcoin content and earning sats for doing so? [Join me at Stacker.news!](https://stacker.news/r/bitcoin_pup "https://stacker.news/r/bitcoin_pup")

...Woof!
========

![](https://bitcoinbarks.com/gallery_gen/5240db5304f70dd121acbe8521f5d958_fit.jpg)
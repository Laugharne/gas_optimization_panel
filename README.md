# [**Gas Optimization Pannel With @dedohwale and @arzdev - YouTube**](https://www.youtube.com/watch?v=xqRmTx-hBUo)

![](2023-08-25-15-30-59.png)

- https://twitter.com/dedohwale
- https://twitter.com/arzdev

In this panel, you will learn how to approach gas optimizations in a more efficient way. This includes ways to learn about gas optimization, how to advertise yourself as a gas optimizer, and the tooling and resources available.

- [00:00:25](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=25s) How Ded and Arz Got Started with Web3
- [00:02:10](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=130s) The Goal of Gas Optimization
- [00:06:50](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=410s) How to Get Better at Gas Optimization
- [00:09:10](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=550s) EVM Puzzle Game
- [00:10:50](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=650s) Building Your Own EVM from Scratch
- [00:12:45](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=765s) ERC721A
- [00:15:00](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=900s) Optimization Strategy
- [00:17:00](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=1020s) How to Write a Gas-Optimized Contract
- [00:20:30](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=1230s) How to Audit for Gas Optimizations
- [00:24:30](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=1470s) The Current State of Gas Optimization and What the Future Holds
- [00:27:50](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=1670s) How to Do Gas-Optimization Reports
- [00:30:50](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=1850s) What Happens with Gas Optimization as Ethereum Scales
- [00:33:30](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=2010s) Gas Optimization Tools
- [00:36:20](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=2180s) Using HUFF in Production
- [00:39:00](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=2340s) The Best Way to Deal with Gas Optimizations as a Researcher
- [00:43:00](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=2580s) Advertising Yourself as a Gas Optimizer
- [00:45:00](https://www.youtube.com/watch?v=xqRmTx-hBUo&t=2700s) The Coolest Gas-Optimization Technique

----

## [](https://youtu.be/xqRmTx-hBUo?t=0) Introduction and Background

**Section Overview**: In this section, the speakers introduce themselves and discuss their backgrounds in mathematics, data science, AI, and web development. They also mention their motivations for learning gas optimization.

## Background of the Speakers
- The first speaker has a background in mathematics, with a focus on data science and AI. They are currently working on their dissertation in applied math.
- The second speaker started programming six years ago, beginning with Python and later learning JavaScript and web development. They transitioned to web3 two years ago and have been working on smart contracts and auditing.

# [01:27](https://youtu.be/xqRmTx-hBUo?t=87) Learning Gas Optimization

Section Overview: The speakers share their journeys of learning gas optimization and provide insights into how others can learn it as well.

## Speaker 1's Journey
- Speaker 1 decided to learn gas optimization when ERC20 first came out, as it became important to optimize gas usage.
- They started by understanding how events work and gradually learned more about optimizing gas usage.
- Speaker 1 took a course on gas optimization, read articles, watched videos, and spent time debugging transactions in Remix to gain practical knowledge.
- They also explored EVM codes playground, solved EVM puzzles, studied code of protocols, and learned about Yul.

## Speaker 2's Journey
- Speaker 2 initially approached gas optimization as an investor who realized its significance for protocol participation.
- They started by creating a Twitter account to share their learnings about gas optimization.
- Speaker 2 taught themselves through documentation resources like ChatGPT.
- Initially made some incorrect posts but continued learning from mistakes.

# [05:19](https://youtu.be/xqRmTx-hBUo?t=319) Conclusion

Section Overview: The speakers conclude the discussion on their journeys of learning gas optimization.

## Key Takeaways
- Gas optimization is crucial for developers and investors in the web3 space.
- Learning gas optimization involves practical experience, studying code, debugging transactions, and exploring resources like courses and puzzles.
- Sharing knowledge through platforms like Twitter can help others learn about gas optimization.

Note: The transcript does not provide timestamps beyond this point.
# [06:34](https://youtu.be/xqRmTx-hBUo?t=394) Understanding the Ethereum Virtual Machine (EVM)

Section Overview: In this section, the speaker discusses the importance of understanding how the Ethereum Virtual Machine (EVM) works and provides tips on learning about its components.

## Learning about the EVM

- [06:52](https://youtu.be/xqRmTx-hBUo?t=412) It is crucial to learn how the event works and understand where information is stored, what bytecode and opcodes are, and what a function dispatcher is.
- [07:17](https://youtu.be/xqRmTx-hBUo?t=437) Understanding the EVM can be challenging but essential for security and gas optimization. It requires transitioning from a web 2 mindset and realizing that code execution happens in blocks.
- [08:16](https://youtu.be/xqRmTx-hBUo?t=496) To gain a deep understanding of how the EVM works, it is recommended to use tools like Remix and EVM Codes. These tools allow stepping through opcodes and help identify gas costs.
- [09:00](https://youtu.be/xqRmTx-hBUo?t=540) Another useful resource for learning about the EVM is EVM Puzzles, which offers interactive challenges to solve using correct call data values to prevent function reversion.

## Tips and Tricks for Gas Optimization

- [11:54](https://youtu.be/xqRmTx-hBUo?t=714) There are various tips and tricks for optimizing gas usage in Solidity contracts. Caching array length can be one example.
- [12:14](https://youtu.be/xqRmTx-hBUo?t=734) Practicing different approaches used by experienced developers can help improve gas efficiency.

# [t=763s] Gas Efficiency in ERC721 Contracts

Section Overview: The speaker discusses gas efficiency in ERC721 contracts compared to classic NFT contracts.

- [12:43](https://youtu.be/xqRmTx-hBUo?t=763) The speaker mentions CRC721a as an example of an ERC721 contract that achieved significant gas savings compared to a classic NFT contract based on OpenZeppelin's implementation.

# [t=810s] Gas Optimization for Smart Contracts

Section Overview: In this section, the speaker discusses gas optimization techniques for smart contracts, particularly in projects with a large number of users. They mention the efficiency of ERC-721 and ERC-721a standards, as well as the importance of learning how to access EVM's financials to eliminate unnecessary gas costs.

## Gas Optimization Techniques

- [t=827s] Consider the gas efficiency of different token standards like ERC-721 and ERC-721a when dealing with batch minting or large numbers of users.
- [t=853s] Learn how to access EVM's financials to eliminate unnecessary gas costs and optimize code.
- [t=889s] Focus on continuous learning and exploring different gas optimization techniques.
- [t=925s] Be aware that automated bots can find common optimizations like caching array length or unchecked transfers, so focus on more creative optimizations that bots may not catch.
- [t=961s] Look for redundancies in code, potential bit shifts, and other opportunities for optimization by understanding what the code does.
  
# [t=1020s] Writing Gas Optimized Contracts

Section Overview: This section focuses on strategies for writing gas optimized contracts. The speaker emphasizes starting with an efficient architecture, doing more of what is cheap and less of what is expensive, searching for tips and tricks (that may not be caught by bots), and always testing and benchmarking.

## Strategies for Writing Gas Optimized Contracts

- [t=1054s] Start with an efficient architecture that minimizes data stored on-chain to reduce expensive storage operations.
- [t=1109s] Organize your code to prioritize cheaper operations over expensive ones using salinity (memory usage) and assembly (eliminating redundant codes).
- [t=1155s] Search for tips and tricks that can be manually implemented, such as pre-incrementing variables.
- [t=1177s] Always test and benchmark your code to identify areas for improvement and rewrite accordingly.

Note: The transcript is already in English, so there is no need to translate the headings or content.
# [20:16](https://youtu.be/xqRmTx-hBUo?t=1216) Pre-increment and Contract Development

Section Overview: The speaker discusses the benefits of using pre-increment in contract development to find more efficient ways of coding. They emphasize the importance of continuously improving contracts.

## Using Pre-increment for Efficient Contract Development

- Pre-increment can help in finding more efficient ways of coding contracts.
- Continuously improving contracts leads to better optimization over time.

# [20:35](https://youtu.be/xqRmTx-hBUo?t=1235) Auditing Contracts for Gas Optimization

Section Overview: The speaker introduces the topic of auditing contracts for gas optimization and shares insights on the auditing process.

## Auditing Process for Gas Optimization

- Auditing processes may vary from person to person.
- Understanding the protocol is a key aspect of auditing.
- Reading code, documentation, and engaging with the community helps in understanding the protocol.
- Gas optimizations should be based on a thorough understanding of the protocol.
- Writing a comprehensive report is crucial for submitting audit findings.

# [23:12](https://youtu.be/xqRmTx-hBUo?t=1392) Gas Optimization Strategies

Section Overview: The speakers discuss strategies for gas optimization during contract development and auditing.

## Strategies for Gas Optimization

- Identifying areas where instantiations occur multiple times or bit shifting can be used.
- Rewriting code can lead to significant gas savings.
- Benchmarking different approaches helps identify more efficient solutions.
- Writing a detailed report with explanations, recommendations, and quantified gas savings is important.

# [24:48](https://youtu.be/xqRmTx-hBUo?t=1488) Current State and Future of Gas Optimization

Section Overview: The speakers discuss the current state of gas optimization and its future prospects.

## Current State and Challenges

- Gas optimization is a relatively new field but gaining attention.
- Readability concerns sometimes hinder gas optimizations in projects.
- Limited financial incentives may discourage developers from prioritizing gas optimizations.
- Private auditors and individuals are emerging to address the need for gas optimization.

# [25:26](https://youtu.be/xqRmTx-hBUo?t=1526) Collaborative Efforts in Gas Optimization

Section Overview: The speakers discuss the importance of collaborative efforts in gas optimization and highlight the role of rewriting code.

## Collaborative Approach to Gas Optimization

- Gas optimizations can come from various sources, not just individual developers.
- Rewriting code is a common approach to achieve significant gas savings.
- Care must be taken to ensure security and avoid introducing bugs during code rework.

Note: The transcript provided does not include timestamps for some sections.
# [26:33](https://youtu.be/xqRmTx-hBUo?t=1593)

Section Overview: In this section, the speaker discusses the optimization of protocols and the potential convergence of various protocols in the future.

## Will we see more protocols being optimized? (t=1593s)

- The speaker believes that as mainstream adoption of blockchain technology increases, it is inevitable that more protocols will be optimized.
- As adoption grows, there may be a coalescence of protocols where many will converge or be pushed aside.
- Protocols that are left standing will need to optimize to stay relevant.

# [27:30](https://youtu.be/xqRmTx-hBUo?t=1650)

Section Overview: This section explores whether developers will need to worry about optimizing their code when Ethereum scales.

## Will developers have to worry about optimizing their code when Ethereum scales? (t=1650s)

- It is uncertain whether developers will need to optimize their code when Ethereum scales.
- The question arises because as Ethereum scales, transaction computation power becomes crucial. Functions with higher gas costs limit what can be done in a single transaction.
- Some argue that using layer 2 chains can eliminate the need for gas optimization, but transaction computation power remains a factor.

# [27:55](https://youtu.be/xqRmTx-hBUo?t=1675)

Section Overview: The speaker addresses ways for newcomers to perform gas optimization reports and qualitative analysis reports.

## Ways for newcomers to perform gas optimization and qualitative analysis reports (t=1675s)

- Code Arena and Health Finance are platforms where users can submit gas optimization reports and earn rewards.
- To start, it is important to understand the particle (code) and identify areas that can be rewritten into a cheaper way.
- Learning what is cheap and expensive in terms of gas usage is crucial. Benchmarking and testing different approaches can help determine what works best.
- Line-by-line analysis of code can reveal opportunities for optimization.

# [29:47](https://youtu.be/xqRmTx-hBUo?t=1787)

Section Overview: The speaker emphasizes the importance of using markdown for note-taking and organization during gas optimization.

## Importance of using markdown for gas optimization (t=1787s)

- Markdown is a helpful tool for organizing notes and keeping track of gas optimization reports.
- Gas optimization can become overwhelming, but having an organized pre-report can make the process easier.
- Proper documentation helps avoid confusion and ensures a thorough job in gas optimization.

# [31:19](https://youtu.be/xqRmTx-hBUo?t=1879)

Section Overview: The speaker discusses the need for code optimization even if layer 2 chains are used.

## Need for code optimization despite layer 2 chains (t=1879s)

- Even with the use of layer 2 chains, developers will still need to optimize their code.
- Transaction computation power remains a factor, and functions with high gas costs limit what can be done in a single transaction.

# [31:54](https://youtu.be/xqRmTx-hBUo?t=1914)

Section Overview: The speaker explores how current optimizers are compensating for Solidity's mistakes and anticipates future improvements.

## Compensation for Solidity's mistakes and future improvements (t=1914s)

- Current optimizers are seen as compensating for Solidity's mistakes made during Ethereum's development.
- Future improvements may include features like automatic caching or length calculation to simplify code and reduce gas usage.
- Anticipation grows for new updates that could enhance gas optimizations, such as push zero or transient storage.
# [32:45](https://youtu.be/xqRmTx-hBUo?t=1965) Gas Optimization Projects

Section Overview: The speaker discusses the need for projects that can help developers optimize their code, specifically focusing on gas optimizations. They mention the lack of tools like Slither for gas optimizations and suggest the idea of a tool that everyone can use.

## Gas Optimization Tools

- There is a need for tools that focus on gas optimizations in addition to security.
- While there are some existing tools like Foundry and Hardhat, they may not fully address the issue.
- Creating a tool that automatically fixes gas optimization issues would be challenging.
- It might be possible to develop a tool similar to fuzzing techniques, but it would still have limitations.
- The tool would not be able to optimize large amounts of code like an experienced developer could.

# [34:20](https://youtu.be/xqRmTx-hBUo?t=2060) Gas Bounty Platform

Section Overview: The speaker discusses the idea of a gas bounty platform where users can submit gas optimization tips and results. They highlight the importance of motivating protocols to participate in such platforms.

## Gas Bounty Platform

- A gas bounty platform could incentivize users to submit gas optimization tips and results.
- However, there should be measures in place to prevent submissions of trivial or insignificant tips.
- Motivating protocols to participate in such platforms might be challenging as it involves cost without immediate benefits.

# [36:07](https://youtu.be/xqRmTx-hBUo?t=2167) Future Use of Huff and Viper

Section Overview: The speakers discuss the potential future use of Huff and Viper languages for smart contract development. They consider the impact on security measures and auditing processes.

## Future Use of Huff and Viper

- There is uncertainty regarding using Huff in production with deployed contracts due to difficulties in verifying contracts written in Huff.
- Viper has some security features that Solidity lacks, but there are concerns about its impact on security measures and auditing processes.
- Some protocols may consider rewriting their contracts in Viper or Huff, but it depends on the specific project and its development team.

# [38:08](https://youtu.be/xqRmTx-hBUo?t=2288) Appreciation for Arc and Dead

Section Overview: The speaker expresses gratitude towards Arc and Dead for their tweets and contributions, which have been helpful in understanding Solidity and debugging code.

## Appreciation for Arc and Dead

- The speaker thanks Arc for their tweets that helped them learn about Solidity and improve gas efficiency.
- They also express gratitude towards Dead for teaching them about smart contract attacks through Twitter posts.
- Both Arc and Dead are seen as inspirations by the speaker.
# [t=0:39:15s] Private Auditing and Gas Optimization

Section Overview: The speaker discusses the concept of private auditing and gas optimization in the context of code contests and protocol audits. They raise questions about the benefits of participating in contests versus performing private audits, as well as the timing of gas optimization in relation to overall code auditing.

## Is it better to participate in contests or focus on private audits?

- Participating in contests may not yield significant rewards due to low payouts and time wasted on gathering gas issues.
- Private audits offer higher payouts but require delivering real results and ensuring thorough security checks.
- Starting with code contests on platforms like Code Arena and Sherlock can help gain experience, build reputation, and attract potential clients for private audits.

## When should gas optimization be performed during an audit?

- Performing a gas audit before a security audit is recommended to avoid introducing additional bugs through gas optimizations.
- Gas optimizations can make it harder to understand the function's purpose, especially when complex algorithms are involved.

# [t=0:44:08s] Challenges of Auditing Complex Algorithms

Section Overview: The speaker discusses the challenges faced when auditing complex algorithms implemented on the EVM (Ethereum Virtual Machine). They highlight difficulties in reviewing code written in assembly language and emphasize the importance of having auditors who are knowledgeable about assembly.

## Reviewing complex algorithms implemented on EVM

- Auditing complex algorithms written in assembly language is challenging due to limited expertise among auditors.
- Some complicated algorithms are inspired by C implementations, making it difficult to review their functionality on the EVM.

## Importance of knowledge about assembly language

- Lack of familiarity with assembly language makes it harder for auditors to effectively review code.
- Assembly expertise is crucial for understanding and optimizing gas usage efficiently.

# [t=0:45:02s] Coolest Gas Optimization Techniques

Section Overview: The speaker shares their favorite gas optimization technique, highlighting the benefits of bit shifting and its application in optimizing code.

## Favorite gas optimization technique

- Bit shifting is considered a cool and effective gas optimization technique.
- Utilizing bit shifting can lead to significant improvements in code efficiency and gas usage.

Note: The transcript provided does not include timestamps for all sections.
# [45:42](https://youtu.be/xqRmTx-hBUo?t=2742) Understanding Bit Shifting and Gas Optimization

Section Overview: In this section, the speakers discuss bit shifting and its use in type casting and converting different types. They also explore how bit shifting can be used for gas optimization in Ethereum smart contracts.

## Bit Shifting for Type Casting and Converting Types

- Bit shifting is commonly used for type casting to convert different types.
- Shifting bits allows you to move a bit from one position to another, which is equivalent to multiplying or dividing by two.
- It can be used for other numbers as well, such as 10 or 100, depending on the specific use case.

## Gas Optimization with Bit Shifting

- Bit shifting can help optimize gas usage in Ethereum smart contracts.
- By reducing gas consumption, it becomes more cost-effective to execute transactions on the network.
- However, gas optimization may become less important with the introduction of layer 2 solutions and cheaper transaction fees in the future.

# [46:59](https://youtu.be/xqRmTx-hBUo?t=2819) The Momentary Trend of Gas Optimization

Section Overview: In this section, the speakers discuss the current emphasis on gas optimization due to high network fees. They also consider how this trend may change with the introduction of new layer 2 solutions and lower transaction costs.

## Gas Optimization as a Momentary Trend

- Currently, reducing gas consumption is crucial due to expensive network fees.
- However, with the development of layer 2 solutions and potential cost reductions in the future, optimizing gas usage may become less significant.

## Historical Perspective on Code Optimization

- Code optimization has always been a consideration throughout history.
- As hardware advances, certain optimizations become less relevant.
- While it's possible that computational capacity could increase significantly in the future, optimization will likely remain necessary due to limited resources.

# [48:30](https://youtu.be/xqRmTx-hBUo?t=2910) Closing Thoughts and Appreciation

Section Overview: In this section, the speakers express their gratitude for the discussion and summarize their key takeaways.

## Appreciation and Gratitude

- The speakers thank the audience for their participation and express appreciation for hosting the discussion.
- They highlight that they have learned a lot from the conversation and hope that others have also gained valuable insights.

Note: The transcript ends here, and no further content is available.

----

[Generated with Video Highlight](https://videohighlight.com/video/summary/xqRmTx-hBUo)
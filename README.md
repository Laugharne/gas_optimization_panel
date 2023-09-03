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

## [00:00](https://youtu.be/xqRmTx-hBUo?t=0) Introduction and Background

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

# [12:43](https://youtu.be/xqRmTx-hBUo?t=763) Gas Efficiency in ERC721 Contracts

Section Overview: The speaker discusses gas efficiency in ERC721 contracts compared to classic NFT contracts.

- [12:43](https://youtu.be/xqRmTx-hBUo?t=763) The speaker mentions CRC721a as an example of an ERC721 contract that achieved significant gas savings compared to a classic NFT contract based on OpenZeppelin's implementation.

# [13:30](https://youtu.be/xqRmTx-hBUo?t=810) Gas Optimization for Smart Contracts

Section Overview: In this section, the speaker discusses gas optimization techniques for smart contracts, particularly in projects with a large number of users. They mention the efficiency of ERC-721 and ERC-721a standards, as well as the importance of learning how to access EVM's financials to eliminate unnecessary gas costs.

## Gas Optimization Techniques

- [13:47](https://youtu.be/xqRmTx-hBUo?t=827) Consider the gas efficiency of different token standards like ERC-721 and ERC-721a when dealing with batch minting or large numbers of users.
- [14:13](https://youtu.be/xqRmTx-hBUo?t=853) Learn how to access EVM's financials to eliminate unnecessary gas costs and optimize code.
- [14:49](https://youtu.be/xqRmTx-hBUo?t=889) Focus on continuous learning and exploring different gas optimization techniques.
- [15:25](https://youtu.be/xqRmTx-hBUo?t=925) Be aware that automated bots can find common optimizations like caching array length or unchecked transfers, so focus on more creative optimizations that bots may not catch.
- [16:01](https://youtu.be/xqRmTx-hBUo?t=961) Look for redundancies in code, potential bit shifts, and other opportunities for optimization by understanding what the code does.

# [17:00](https://youtu.be/xqRmTx-hBUo?t=1020) Writing Gas Optimized Contracts

Section Overview: This section focuses on strategies for writing gas optimized contracts. The speaker emphasizes starting with an efficient architecture, doing more of what is cheap and less of what is expensive, searching for tips and tricks (that may not be caught by bots), and always testing and benchmarking.

## Strategies for Writing Gas Optimized Contracts

- [17:34](https://youtu.be/xqRmTx-hBUo?t=1054) Start with an efficient architecture that minimizes data stored on-chain to reduce expensive storage operations.
- [18:29](https://youtu.be/xqRmTx-hBUo?t=1109) Organize your code to prioritize cheaper operations over expensive ones using salinity (memory usage) and assembly (eliminating redundant codes).
- [19:15](https://youtu.be/xqRmTx-hBUo?t=1155) Search for tips and tricks that can be manually implemented, such as pre-incrementing variables.
- [19:37](https://youtu.be/xqRmTx-hBUo?t=1177) Always test and benchmark your code to identify areas for improvement and rewrite accordingly.

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
# [39:15](https://youtu.be/xqRmTx-hBUo?t=2355) Private Auditing and Gas Optimization

Section Overview: The speaker discusses the concept of private auditing and gas optimization in the context of code contests and protocol audits. They raise questions about the benefits of participating in contests versus performing private audits, as well as the timing of gas optimization in relation to overall code auditing.

## Is it better to participate in contests or focus on private audits?

- Participating in contests may not yield significant rewards due to low payouts and time wasted on gathering gas issues.
- Private audits offer higher payouts but require delivering real results and ensuring thorough security checks.
- Starting with code contests on platforms like Code Arena and Sherlock can help gain experience, build reputation, and attract potential clients for private audits.

## When should gas optimization be performed during an audit?

- Performing a gas audit before a security audit is recommended to avoid introducing additional bugs through gas optimizations.
- Gas optimizations can make it harder to understand the function's purpose, especially when complex algorithms are involved.

# [44:08](https://youtu.be/xqRmTx-hBUo?t=2648) Challenges of Auditing Complex Algorithms

Section Overview: The speaker discusses the challenges faced when auditing complex algorithms implemented on the EVM (Ethereum Virtual Machine). They highlight difficulties in reviewing code written in assembly language and emphasize the importance of having auditors who are knowledgeable about assembly.

## Reviewing complex algorithms implemented on EVM

- Auditing complex algorithms written in assembly language is challenging due to limited expertise among auditors.
- Some complicated algorithms are inspired by C implementations, making it difficult to review their functionality on the EVM.

## Importance of knowledge about assembly language

- Lack of familiarity with assembly language makes it harder for auditors to effectively review code.
- Assembly expertise is crucial for understanding and optimizing gas usage efficiently.

# [45:02](https://youtu.be/xqRmTx-hBUo?t=2702) Coolest Gas Optimization Techniques

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

[Generated with Video Highlight](https://videohighlight.com/video/summary/xqRmTx-hBUo)

----

## Transcript

- [00:00:00](https://youtu.be/xqRmTx-hBUo?t=0) ➜ so yeah hopefully everyone will learn
- [00:00:02](https://youtu.be/xqRmTx-hBUo?t=2) ➜ something from this and I'm excited to
- [00:00:04](https://youtu.be/xqRmTx-hBUo?t=4) ➜ be doing this so get me started
- [00:00:08](https://youtu.be/xqRmTx-hBUo?t=8) ➜ yes
- [00:00:09](https://youtu.be/xqRmTx-hBUo?t=9) ➜ daddy want to start
- [00:00:12](https://youtu.be/xqRmTx-hBUo?t=12) ➜ yeah yeah sure so I have a background in
- [00:00:15](https://youtu.be/xqRmTx-hBUo?t=15) ➜ mathematics I was really big into you
- [00:00:18](https://youtu.be/xqRmTx-hBUo?t=18) ➜ know data science and AI I mean I still
- [00:00:20](https://youtu.be/xqRmTx-hBUo?t=20) ➜ am I'm doing my dissertation in applied
- [00:00:22](https://youtu.be/xqRmTx-hBUo?t=22) ➜ math so that's my background
- [00:00:25](https://youtu.be/xqRmTx-hBUo?t=25) ➜ um coming into web 3 right now is a
- [00:00:29](https://youtu.be/xqRmTx-hBUo?t=29) ➜ decision to kind of get ahead of the
- [00:00:31](https://youtu.be/xqRmTx-hBUo?t=31) ➜ curve because after my dissertation
- [00:00:33](https://youtu.be/xqRmTx-hBUo?t=33) ➜ after I have my PhD I wanted to go into
- [00:00:35](https://youtu.be/xqRmTx-hBUo?t=35) ➜ it full time so you know jumping in a
- [00:00:39](https://youtu.be/xqRmTx-hBUo?t=39) ➜ little early was my way of getting a
- [00:00:40](https://youtu.be/xqRmTx-hBUo?t=40) ➜ head start and coming from a
- [00:00:43](https://youtu.be/xqRmTx-hBUo?t=43) ➜ mathematical background I didn't really
- [00:00:44](https://youtu.be/xqRmTx-hBUo?t=44) ➜ do much in coding you know like I did a
- [00:00:47](https://youtu.be/xqRmTx-hBUo?t=47) ➜ lot of coding but uh you know pure
- [00:00:50](https://youtu.be/xqRmTx-hBUo?t=50) ➜ computer science and so I wanted to dive
- [00:00:52](https://youtu.be/xqRmTx-hBUo?t=52) ➜ into gas optimization and you know Yule
- [00:00:55](https://youtu.be/xqRmTx-hBUo?t=55) ➜ and all this assembly and so forth
- [00:00:56](https://youtu.be/xqRmTx-hBUo?t=56) ➜ because I had no background in it and I
- [00:00:59](https://youtu.be/xqRmTx-hBUo?t=59) ➜ knew it was a big thing so that's where
- [00:01:02](https://youtu.be/xqRmTx-hBUo?t=62) ➜ that's where I began
- [00:01:05](https://youtu.be/xqRmTx-hBUo?t=65) ➜ awesome nice to meet you by the way
- [00:01:07](https://youtu.be/xqRmTx-hBUo?t=67) ➜ really cool so I'm ours I started with
- [00:01:10](https://youtu.be/xqRmTx-hBUo?t=70) ➜ programming six years ago I started with
- [00:01:13](https://youtu.be/xqRmTx-hBUo?t=73) ➜ python which introduced me to
- [00:01:15](https://youtu.be/xqRmTx-hBUo?t=75) ➜ programming and that I learned
- [00:01:18](https://youtu.be/xqRmTx-hBUo?t=78) ➜ JavaScript and web development
- [00:01:20](https://youtu.be/xqRmTx-hBUo?t=80) ➜ spent some time on web 2 as a full stack
- [00:01:22](https://youtu.be/xqRmTx-hBUo?t=82) ➜ web developer but I knew I wouldn't
- [00:01:24](https://youtu.be/xqRmTx-hBUo?t=84) ➜ succeed because of the competition
- [00:01:27](https://youtu.be/xqRmTx-hBUo?t=87) ➜ so I decided to move to weapery which
- [00:01:29](https://youtu.be/xqRmTx-hBUo?t=89) ➜ was like two years ago probably more and
- [00:01:32](https://youtu.be/xqRmTx-hBUo?t=92) ➜ yeah I learned solidity and Battery
- [00:01:34](https://youtu.be/xqRmTx-hBUo?t=94) ➜ development
- [00:01:35](https://youtu.be/xqRmTx-hBUo?t=95) ➜ and the last year I was just writing
- [00:01:38](https://youtu.be/xqRmTx-hBUo?t=98) ➜ smart contracts working on some projects
- [00:01:40](https://youtu.be/xqRmTx-hBUo?t=100) ➜ doing websites too and then I decided to
- [00:01:44](https://youtu.be/xqRmTx-hBUo?t=104) ➜ learn auditing and lower levels already
- [00:01:46](https://youtu.be/xqRmTx-hBUo?t=106) ➜ so this year I decided to to transition
- [00:01:50](https://youtu.be/xqRmTx-hBUo?t=110) ➜ to auditing and started auditing like
- [00:01:53](https://youtu.be/xqRmTx-hBUo?t=113) ➜ two months ago
- [00:01:55](https://youtu.be/xqRmTx-hBUo?t=115) ➜ like doing contests and all this stuff
- [00:01:57](https://youtu.be/xqRmTx-hBUo?t=117) ➜ and you might know me from Twitter where
- [00:01:59](https://youtu.be/xqRmTx-hBUo?t=119) ➜ I post a lot of cast optimization tricks
- [00:02:02](https://youtu.be/xqRmTx-hBUo?t=122) ➜ and stuff related to that and today we
- [00:02:05](https://youtu.be/xqRmTx-hBUo?t=125) ➜ will be talking about it
- [00:02:06](https://youtu.be/xqRmTx-hBUo?t=126) ➜ so for those that don't know uh the goal
- [00:02:11](https://youtu.be/xqRmTx-hBUo?t=131) ➜ of optimizing us is to reduce the
- [00:02:13](https://youtu.be/xqRmTx-hBUo?t=133) ➜ overall number of operations needed to
- [00:02:16](https://youtu.be/xqRmTx-hBUo?t=136) ➜ run a smart contract
- [00:02:19](https://youtu.be/xqRmTx-hBUo?t=139) ➜ um the first thing we'll talk about is
- [00:02:22](https://youtu.be/xqRmTx-hBUo?t=142) ➜ just about our journey how we learn how
- [00:02:25](https://youtu.be/xqRmTx-hBUo?t=145) ➜ to optimize and how you could learn how
- [00:02:27](https://youtu.be/xqRmTx-hBUo?t=147) ➜ to optimize so I'll start
- [00:02:31](https://youtu.be/xqRmTx-hBUo?t=151) ➜ I decided to learn how to optimize when
- [00:02:34](https://youtu.be/xqRmTx-hBUo?t=154) ➜ I went erc7208 first came out and that's
- [00:02:38](https://youtu.be/xqRmTx-hBUo?t=158) ➜ when everyone started really caring
- [00:02:40](https://youtu.be/xqRmTx-hBUo?t=160) ➜ about their gas usage so
- [00:02:42](https://youtu.be/xqRmTx-hBUo?t=162) ➜ I knew that I had to learn how to
- [00:02:44](https://youtu.be/xqRmTx-hBUo?t=164) ➜ optimize if I wanted to be a good
- [00:02:46](https://youtu.be/xqRmTx-hBUo?t=166) ➜ developer and it's just a skill that
- [00:02:49](https://youtu.be/xqRmTx-hBUo?t=169) ➜ also Lady Death should have because your
- [00:02:52](https://youtu.be/xqRmTx-hBUo?t=172) ➜ users pay money when they interact with
- [00:02:55](https://youtu.be/xqRmTx-hBUo?t=175) ➜ your smart contract and just I really
- [00:02:57](https://youtu.be/xqRmTx-hBUo?t=177) ➜ like what they were doing and at that
- [00:03:00](https://youtu.be/xqRmTx-hBUo?t=180) ➜ time I initulated it quite well but I
- [00:03:03](https://youtu.be/xqRmTx-hBUo?t=183) ➜ didn't really know much what is
- [00:03:05](https://youtu.be/xqRmTx-hBUo?t=185) ➜ happening behind the scenes so I started
- [00:03:08](https://youtu.be/xqRmTx-hBUo?t=188) ➜ learning how the event works and I
- [00:03:10](https://youtu.be/xqRmTx-hBUo?t=190) ➜ started to understand more of what is
- [00:03:12](https://youtu.be/xqRmTx-hBUo?t=192) ➜ happening and what and where you can
- [00:03:15](https://youtu.be/xqRmTx-hBUo?t=195) ➜ optimize and you know I started small
- [00:03:18](https://youtu.be/xqRmTx-hBUo?t=198) ➜ and I was writing gas optimized nft
- [00:03:21](https://youtu.be/xqRmTx-hBUo?t=201) ➜ contracts which is great at that time
- [00:03:24](https://youtu.be/xqRmTx-hBUo?t=204) ➜ and something new too but you know you
- [00:03:26](https://youtu.be/xqRmTx-hBUo?t=206) ➜ have to start small and then in summer I
- [00:03:30](https://youtu.be/xqRmTx-hBUo?t=210) ➜ but the uh Jeffrey Schultz Castle
- [00:03:34](https://youtu.be/xqRmTx-hBUo?t=214) ➜ compensation course
- [00:03:36](https://youtu.be/xqRmTx-hBUo?t=216) ➜ and I took the course it was amazing and
- [00:03:39](https://youtu.be/xqRmTx-hBUo?t=219) ➜ you know I read many articles watched so
- [00:03:41](https://youtu.be/xqRmTx-hBUo?t=221) ➜ many videos but I learned the most when
- [00:03:44](https://youtu.be/xqRmTx-hBUo?t=224) ➜ I was just writing some functions in
- [00:03:46](https://youtu.be/xqRmTx-hBUo?t=226) ➜ remix and just debugging the transaction
- [00:03:48](https://youtu.be/xqRmTx-hBUo?t=228) ➜ and
- [00:03:50](https://youtu.be/xqRmTx-hBUo?t=230) ➜ understanding what is being done here
- [00:03:51](https://youtu.be/xqRmTx-hBUo?t=231) ➜ and just going through the op codes one
- [00:03:53](https://youtu.be/xqRmTx-hBUo?t=233) ➜ by one understanding what every upgrade
- [00:03:55](https://youtu.be/xqRmTx-hBUo?t=235) ➜ is doing how this stack is manipulated
- [00:03:58](https://youtu.be/xqRmTx-hBUo?t=238) ➜ how does membrane starts work and stuff
- [00:04:00](https://youtu.be/xqRmTx-hBUo?t=240) ➜ like that you know and that's when I
- [00:04:03](https://youtu.be/xqRmTx-hBUo?t=243) ➜ really started to understand how the
- [00:04:04](https://youtu.be/xqRmTx-hBUo?t=244) ➜ even works and why something is cheaper
- [00:04:07](https://youtu.be/xqRmTx-hBUo?t=247) ➜ than the other thing like for example
- [00:04:09](https://youtu.be/xqRmTx-hBUo?t=249) ➜ the 22 gas difference because of the
- [00:04:12](https://youtu.be/xqRmTx-hBUo?t=252) ➜ function dispatcher
- [00:04:14](https://youtu.be/xqRmTx-hBUo?t=254) ➜ and I just understand why for example
- [00:04:17](https://youtu.be/xqRmTx-hBUo?t=257) ➜ called using call that is cheaper than
- [00:04:19](https://youtu.be/xqRmTx-hBUo?t=259) ➜ memory and you know I spent a lot of
- [00:04:22](https://youtu.be/xqRmTx-hBUo?t=262) ➜ time in the evm codes playground just
- [00:04:24](https://youtu.be/xqRmTx-hBUo?t=264) ➜ understanding how everything works and
- [00:04:27](https://youtu.be/xqRmTx-hBUo?t=267) ➜ seeing how the values are pushed to the
- [00:04:29](https://youtu.be/xqRmTx-hBUo?t=269) ➜ stack and stuff like that and then I
- [00:04:31](https://youtu.be/xqRmTx-hBUo?t=271) ➜ also did the EDM puzzles and the rare
- [00:04:34](https://youtu.be/xqRmTx-hBUo?t=274) ➜ skills gas puzzles which definitely
- [00:04:37](https://youtu.be/xqRmTx-hBUo?t=277) ➜ helped me a lot and also reading the
- [00:04:39](https://youtu.be/xqRmTx-hBUo?t=279) ➜ code of some protocols helped me out too
- [00:04:42](https://youtu.be/xqRmTx-hBUo?t=282) ➜ so I learned how to optimize in solidity
- [00:04:45](https://youtu.be/xqRmTx-hBUo?t=285) ➜ but I wanted to go like even deeper so I
- [00:04:49](https://youtu.be/xqRmTx-hBUo?t=289) ➜ decided to learn new and use not easy
- [00:04:52](https://youtu.be/xqRmTx-hBUo?t=292) ➜ and I still haven't mastered you I don't
- [00:04:56](https://youtu.be/xqRmTx-hBUo?t=296) ➜ know how for Viper so I'm still far away
- [00:04:58](https://youtu.be/xqRmTx-hBUo?t=298) ➜ from being a good Optimizer but I
- [00:05:01](https://youtu.be/xqRmTx-hBUo?t=301) ➜ definitely plan to learn both and yeah
- [00:05:02](https://youtu.be/xqRmTx-hBUo?t=302) ➜ that's how I learned how to optimize and
- [00:05:06](https://youtu.be/xqRmTx-hBUo?t=306) ➜ my my first ever submission of a gas
- [00:05:09](https://youtu.be/xqRmTx-hBUo?t=309) ➜ report on code Arena ordered me over 200
- [00:05:12](https://youtu.be/xqRmTx-hBUo?t=312) ➜ which is just great from gas
- [00:05:14](https://youtu.be/xqRmTx-hBUo?t=314) ➜ optimization so
- [00:05:16](https://youtu.be/xqRmTx-hBUo?t=316) ➜ so yeah uh that you want to talk about
- [00:05:19](https://youtu.be/xqRmTx-hBUo?t=319) ➜ your journey and then we will talk about
- [00:05:20](https://youtu.be/xqRmTx-hBUo?t=320) ➜ how you would learn this if we had to
- [00:05:22](https://youtu.be/xqRmTx-hBUo?t=322) ➜ start from the beginning
- [00:05:24](https://youtu.be/xqRmTx-hBUo?t=324) ➜ yeah yeah thank you for that artists
- [00:05:27](https://youtu.be/xqRmTx-hBUo?t=327) ➜ um yeah so I came into the space as an
- [00:05:29](https://youtu.be/xqRmTx-hBUo?t=329) ➜ investor to begin with SO gas
- [00:05:31](https://youtu.be/xqRmTx-hBUo?t=331) ➜ optimization is something that I kind of
- [00:05:33](https://youtu.be/xqRmTx-hBUo?t=333) ➜ gravitated towards naturally as you know
- [00:05:36](https://youtu.be/xqRmTx-hBUo?t=336) ➜ it was an investor and you got to spend
- [00:05:37](https://youtu.be/xqRmTx-hBUo?t=337) ➜ all this gas convincing an nft or or
- [00:05:40](https://youtu.be/xqRmTx-hBUo?t=340) ➜ whatever and uh I just knew that you
- [00:05:42](https://youtu.be/xqRmTx-hBUo?t=342) ➜ know it was going to be a big thing for
- [00:05:45](https://youtu.be/xqRmTx-hBUo?t=345) ➜ specific protocols since you know it it
- [00:05:47](https://youtu.be/xqRmTx-hBUo?t=347) ➜ actually is a key deciding point for
- [00:05:50](https://youtu.be/xqRmTx-hBUo?t=350) ➜ some people for a lot of people whether
- [00:05:51](https://youtu.be/xqRmTx-hBUo?t=351) ➜ they will participate in a protocol or
- [00:05:53](https://youtu.be/xqRmTx-hBUo?t=353) ➜ not
- [00:05:54](https://youtu.be/xqRmTx-hBUo?t=354) ➜ and so I knew that it was going to be
- [00:05:56](https://youtu.be/xqRmTx-hBUo?t=356) ➜ something I wanted to focus on
- [00:05:58](https://youtu.be/xqRmTx-hBUo?t=358) ➜ how I actually started my journey was
- [00:06:00](https://youtu.be/xqRmTx-hBUo?t=360) ➜ just making a Twitter you know I just
- [00:06:02](https://youtu.be/xqRmTx-hBUo?t=362) ➜ made a Twitter and I uh went to chatgpt
- [00:06:05](https://youtu.be/xqRmTx-hBUo?t=365) ➜ went to all the docs whatever taught
- [00:06:07](https://youtu.be/xqRmTx-hBUo?t=367) ➜ myself what I could just doing that and
- [00:06:10](https://youtu.be/xqRmTx-hBUo?t=370) ➜ started making posts and a lot of them
- [00:06:13](https://youtu.be/xqRmTx-hBUo?t=373) ➜ were wrong you know some of them were
- [00:06:14](https://youtu.be/xqRmTx-hBUo?t=374) ➜ right but a lot of them were wrong and
- [00:06:15](https://youtu.be/xqRmTx-hBUo?t=375) ➜ people corrected me and just learned
- [00:06:17](https://youtu.be/xqRmTx-hBUo?t=377) ➜ along that way and that's actually when
- [00:06:19](https://youtu.be/xqRmTx-hBUo?t=379) ➜ I met ours
- [00:06:20](https://youtu.be/xqRmTx-hBUo?t=380) ➜ and that's where I got the you know the
- [00:06:22](https://youtu.be/xqRmTx-hBUo?t=382) ➜ Big Boost of of this gas optimization
- [00:06:25](https://youtu.be/xqRmTx-hBUo?t=385) ➜ and he really put me on game for the you
- [00:06:27](https://youtu.be/xqRmTx-hBUo?t=387) ➜ know like actually like looking into the
- [00:06:30](https://youtu.be/xqRmTx-hBUo?t=390) ➜ depths of it all and going through these
- [00:06:32](https://youtu.be/xqRmTx-hBUo?t=392) ➜ op codes and all these playgrounds and
- [00:06:33](https://youtu.be/xqRmTx-hBUo?t=393) ➜ the debugging and remix and and all of
- [00:06:36](https://youtu.be/xqRmTx-hBUo?t=396) ➜ that so yeah and then now now I'm here I
- [00:06:39](https://youtu.be/xqRmTx-hBUo?t=399) ➜ haven't really dived into Yule too much
- [00:06:40](https://youtu.be/xqRmTx-hBUo?t=400) ➜ I do know
- [00:06:41](https://youtu.be/xqRmTx-hBUo?t=401) ➜ as I said I have I have been getting
- [00:06:43](https://youtu.be/xqRmTx-hBUo?t=403) ➜ into it but uh like ours there's a lot
- [00:06:46](https://youtu.be/xqRmTx-hBUo?t=406) ➜ of room for growth there
- [00:06:48](https://youtu.be/xqRmTx-hBUo?t=408) ➜ but yeah let's get into uh what
- [00:06:50](https://youtu.be/xqRmTx-hBUo?t=410) ➜ everybody can do to get a little better
- [00:06:52](https://youtu.be/xqRmTx-hBUo?t=412) ➜ at this and what's some of the key it's
- [00:06:54](https://youtu.be/xqRmTx-hBUo?t=414) ➜ really key areas are
- [00:06:58](https://youtu.be/xqRmTx-hBUo?t=418) ➜ so I think the first step that everyone
- [00:07:00](https://youtu.be/xqRmTx-hBUo?t=420) ➜ should do is like learn how the event
- [00:07:02](https://youtu.be/xqRmTx-hBUo?t=422) ➜ works and I think we can agree on this
- [00:07:05](https://youtu.be/xqRmTx-hBUo?t=425) ➜ just understand where information is
- [00:07:07](https://youtu.be/xqRmTx-hBUo?t=427) ➜ stored understand what the byte code is
- [00:07:10](https://youtu.be/xqRmTx-hBUo?t=430) ➜ what op codes are what is a function
- [00:07:12](https://youtu.be/xqRmTx-hBUo?t=432) ➜ dispatcher and many more other stuff
- [00:07:14](https://youtu.be/xqRmTx-hBUo?t=434) ➜ right
- [00:07:17](https://youtu.be/xqRmTx-hBUo?t=437) ➜ definitely I mean I think the biggest
- [00:07:19](https://youtu.be/xqRmTx-hBUo?t=439) ➜ the biggest thing for me was fully
- [00:07:22](https://youtu.be/xqRmTx-hBUo?t=442) ➜ understanding what the evm is doing I
- [00:07:25](https://youtu.be/xqRmTx-hBUo?t=445) ➜ think that was one of the the largest
- [00:07:27](https://youtu.be/xqRmTx-hBUo?t=447) ➜ hurdles for me especially especially in
- [00:07:29](https://youtu.be/xqRmTx-hBUo?t=449) ➜ security but you know definitely in gas
- [00:07:31](https://youtu.be/xqRmTx-hBUo?t=451) ➜ optimization too and they uh coming from
- [00:07:34](https://youtu.be/xqRmTx-hBUo?t=454) ➜ the background in web 2 a lot of people
- [00:07:37](https://youtu.be/xqRmTx-hBUo?t=457) ➜ I see it even even in these experienced
- [00:07:40](https://youtu.be/xqRmTx-hBUo?t=460) ➜ devs
- [00:07:41](https://youtu.be/xqRmTx-hBUo?t=461) ➜ um they'll be assuming things are are
- [00:07:43](https://youtu.be/xqRmTx-hBUo?t=463) ➜ changing or whatever you know the
- [00:07:45](https://youtu.be/xqRmTx-hBUo?t=465) ➜ transaction hasn't been gone through the
- [00:07:46](https://youtu.be/xqRmTx-hBUo?t=466) ➜ block hasn't been printed and so forth
- [00:07:48](https://youtu.be/xqRmTx-hBUo?t=468) ➜ and uh it's hard to get out of that
- [00:07:51](https://youtu.be/xqRmTx-hBUo?t=471) ➜ mindset that you know a line of code is
- [00:07:52](https://youtu.be/xqRmTx-hBUo?t=472) ➜ ran and something's changed but yeah so
- [00:07:56](https://youtu.be/xqRmTx-hBUo?t=476) ➜ that was that was my biggest hurdle was
- [00:07:58](https://youtu.be/xqRmTx-hBUo?t=478) ➜ learning the evm and kind of
- [00:07:59](https://youtu.be/xqRmTx-hBUo?t=479) ➜ transitioning from that python mindset
- [00:08:02](https://youtu.be/xqRmTx-hBUo?t=482) ➜ into solidity
- [00:08:04](https://youtu.be/xqRmTx-hBUo?t=484) ➜ yeah definitely so as I said you know
- [00:08:07](https://youtu.be/xqRmTx-hBUo?t=487) ➜ radar tools watch videos to read the
- [00:08:10](https://youtu.be/xqRmTx-hBUo?t=490) ➜ yellow paper but the most important
- [00:08:12](https://youtu.be/xqRmTx-hBUo?t=492) ➜ thing is that you charge yourself and
- [00:08:14](https://youtu.be/xqRmTx-hBUo?t=494) ➜ actually step through the up codes
- [00:08:15](https://youtu.be/xqRmTx-hBUo?t=495) ➜ yourself
- [00:08:17](https://youtu.be/xqRmTx-hBUo?t=497) ➜ and yeah as I said that's what helped me
- [00:08:19](https://youtu.be/xqRmTx-hBUo?t=499) ➜ the most and that is when you will
- [00:08:21](https://youtu.be/xqRmTx-hBUo?t=501) ➜ actually understand how the event works
- [00:08:23](https://youtu.be/xqRmTx-hBUo?t=503) ➜ and you will be able to tell what a
- [00:08:27](https://youtu.be/xqRmTx-hBUo?t=507) ➜ function will do well upcult will will
- [00:08:30](https://youtu.be/xqRmTx-hBUo?t=510) ➜ be used then how much gas will that up
- [00:08:32](https://youtu.be/xqRmTx-hBUo?t=512) ➜ codes cost and stuff like that so and
- [00:08:36](https://youtu.be/xqRmTx-hBUo?t=516) ➜ you know once you learn how the even
- [00:08:38](https://youtu.be/xqRmTx-hBUo?t=518) ➜ works you will just see where gas can be
- [00:08:40](https://youtu.be/xqRmTx-hBUo?t=520) ➜ saved because you understand how much
- [00:08:41](https://youtu.be/xqRmTx-hBUo?t=521) ➜ the up codes cost and you will sort of
- [00:08:44](https://youtu.be/xqRmTx-hBUo?t=524) ➜ have this vision and understand what is
- [00:08:46](https://youtu.be/xqRmTx-hBUo?t=526) ➜ expensive and what is not
- [00:08:48](https://youtu.be/xqRmTx-hBUo?t=528) ➜ so I would say two great tools uh remix
- [00:08:51](https://youtu.be/xqRmTx-hBUo?t=531) ➜ and evm codes just really uh recommend
- [00:08:55](https://youtu.be/xqRmTx-hBUo?t=535) ➜ everyone trying them
- [00:08:56](https://youtu.be/xqRmTx-hBUo?t=536) ➜ uh really amazing stuff to actually
- [00:09:00](https://youtu.be/xqRmTx-hBUo?t=540) ➜ learn how to and see how the EPM works
- [00:09:03](https://youtu.be/xqRmTx-hBUo?t=543) ➜ and all the op codes and definitely evm
- [00:09:06](https://youtu.be/xqRmTx-hBUo?t=546) ➜ puzzles uh it's a very cool game where
- [00:09:10](https://youtu.be/xqRmTx-hBUo?t=550) ➜ you basically have to
- [00:09:13](https://youtu.be/xqRmTx-hBUo?t=553) ➜ oh where you have to basically uh
- [00:09:17](https://youtu.be/xqRmTx-hBUo?t=557) ➜ oh you have to pass in the correct value
- [00:09:21](https://youtu.be/xqRmTx-hBUo?t=561) ➜ or the correct call data so that the
- [00:09:23](https://youtu.be/xqRmTx-hBUo?t=563) ➜ function doesn't revert and it's it's a
- [00:09:26](https://youtu.be/xqRmTx-hBUo?t=566) ➜ really cool way to learn
- [00:09:30](https://youtu.be/xqRmTx-hBUo?t=570) ➜ video puzzles I don't think I've done
- [00:09:31](https://youtu.be/xqRmTx-hBUo?t=571) ➜ that one so it's like you're
- [00:09:34](https://youtu.be/xqRmTx-hBUo?t=574) ➜ what do you do in there
- [00:09:36](https://youtu.be/xqRmTx-hBUo?t=576) ➜ basically you have like op codes and
- [00:09:40](https://youtu.be/xqRmTx-hBUo?t=580) ➜ then you have like you have like a jumpy
- [00:09:42](https://youtu.be/xqRmTx-hBUo?t=582) ➜ op code and you need that jumpy op code
- [00:09:45](https://youtu.be/xqRmTx-hBUo?t=585) ➜ to jump to the to the jump destination
- [00:09:48](https://youtu.be/xqRmTx-hBUo?t=588) ➜ to to the jump destination so that the
- [00:09:51](https://youtu.be/xqRmTx-hBUo?t=591) ➜ function doesn't revert uh send you the
- [00:09:54](https://youtu.be/xqRmTx-hBUo?t=594) ➜ link here
- [00:09:56](https://youtu.be/xqRmTx-hBUo?t=596) ➜ interesting
- [00:09:59](https://youtu.be/xqRmTx-hBUo?t=599) ➜ Lisa have you heard of this
- [00:10:01](https://youtu.be/xqRmTx-hBUo?t=601) ➜ yes it's a CTF uh kind of a Puzo CTF you
- [00:10:04](https://youtu.be/xqRmTx-hBUo?t=604) ➜ do to learn the evm the internals this
- [00:10:07](https://youtu.be/xqRmTx-hBUo?t=607) ➜ is really interesting really good one
- [00:10:09](https://youtu.be/xqRmTx-hBUo?t=609) ➜ yep thank you I think I mean I think
- [00:10:12](https://youtu.be/xqRmTx-hBUo?t=612) ➜ this is really what you guys are seeing
- [00:10:14](https://youtu.be/xqRmTx-hBUo?t=614) ➜ I mean coming down to learning the evm
- [00:10:18](https://youtu.be/xqRmTx-hBUo?t=618) ➜ is one of the most important aspects and
- [00:10:21](https://youtu.be/xqRmTx-hBUo?t=621) ➜ the evm seems so complicated until you
- [00:10:24](https://youtu.be/xqRmTx-hBUo?t=624) ➜ get simple you know like I don't know
- [00:10:26](https://youtu.be/xqRmTx-hBUo?t=626) ➜ how you guys feel about this but
- [00:10:28](https://youtu.be/xqRmTx-hBUo?t=628) ➜ it's really hard for me to to interpret
- [00:10:32](https://youtu.be/xqRmTx-hBUo?t=632) ➜ the the program counter so when I'm
- [00:10:34](https://youtu.be/xqRmTx-hBUo?t=634) ➜ looking at the assemble uh the assembly
- [00:10:37](https://youtu.be/xqRmTx-hBUo?t=637) ➜ instructions is really hard for me you
- [00:10:39](https://youtu.be/xqRmTx-hBUo?t=639) ➜ know you also it's really hard for me to
- [00:10:42](https://youtu.be/xqRmTx-hBUo?t=642) ➜ to grasp my head into that there's any
- [00:10:44](https://youtu.be/xqRmTx-hBUo?t=644) ➜ kind of treats or I think just
- [00:10:46](https://youtu.be/xqRmTx-hBUo?t=646) ➜ practicing right
- [00:10:50](https://youtu.be/xqRmTx-hBUo?t=650) ➜ so for me uh one thing that really
- [00:10:52](https://youtu.be/xqRmTx-hBUo?t=652) ➜ helped was uh as anona said here
- [00:10:54](https://youtu.be/xqRmTx-hBUo?t=654) ➜ building your evm from scratch and uh in
- [00:10:58](https://youtu.be/xqRmTx-hBUo?t=658) ➜ the I think Alchemy University was the
- [00:11:01](https://youtu.be/xqRmTx-hBUo?t=661) ➜ one I don't know I do quite a few of
- [00:11:02](https://youtu.be/xqRmTx-hBUo?t=662) ➜ those but I believe in alchemy
- [00:11:04](https://youtu.be/xqRmTx-hBUo?t=664) ➜ University they go through even not
- [00:11:07](https://youtu.be/xqRmTx-hBUo?t=667) ➜ really building your own evm uh fully
- [00:11:10](https://youtu.be/xqRmTx-hBUo?t=670) ➜ but
- [00:11:11](https://youtu.be/xqRmTx-hBUo?t=671) ➜ for the most part you'll understand Json
- [00:11:13](https://youtu.be/xqRmTx-hBUo?t=673) ➜ RPC requests and
- [00:11:15](https://youtu.be/xqRmTx-hBUo?t=675) ➜ um you know like actually like making
- [00:11:17](https://youtu.be/xqRmTx-hBUo?t=677) ➜ these these these objects of the block
- [00:11:20](https://youtu.be/xqRmTx-hBUo?t=680) ➜ information the transaction and so forth
- [00:11:22](https://youtu.be/xqRmTx-hBUo?t=682) ➜ and then after that at least for me it
- [00:11:25](https://youtu.be/xqRmTx-hBUo?t=685) ➜ became a lot more clear so I would
- [00:11:27](https://youtu.be/xqRmTx-hBUo?t=687) ➜ recommend I believe it's the Alchemy
- [00:11:28](https://youtu.be/xqRmTx-hBUo?t=688) ➜ University for that really nice
- [00:11:33](https://youtu.be/xqRmTx-hBUo?t=693) ➜ yeah so definitely check out those evm
- [00:11:35](https://youtu.be/xqRmTx-hBUo?t=695) ➜ puzzles it's a really cool way to learn
- [00:11:38](https://youtu.be/xqRmTx-hBUo?t=698) ➜ and if you don't know if you have
- [00:11:41](https://youtu.be/xqRmTx-hBUo?t=701) ➜ problems with the program counter then
- [00:11:43](https://youtu.be/xqRmTx-hBUo?t=703) ➜ you can just check out the playground of
- [00:11:45](https://youtu.be/xqRmTx-hBUo?t=705) ➜ vpm codes or just the remix debugger or
- [00:11:49](https://youtu.be/xqRmTx-hBUo?t=709) ➜ The Foundry deeper so the Second Step I
- [00:11:52](https://youtu.be/xqRmTx-hBUo?t=712) ➜ would say learn some tips and tricks
- [00:11:54](https://youtu.be/xqRmTx-hBUo?t=714) ➜ right oh there are many tips and tricks
- [00:11:56](https://youtu.be/xqRmTx-hBUo?t=716) ➜ that are definitely good to know like
- [00:11:57](https://youtu.be/xqRmTx-hBUo?t=717) ➜ for example caching the array length and
- [00:12:00](https://youtu.be/xqRmTx-hBUo?t=720) ➜ sort of this stuff you know you will
- [00:12:03](https://youtu.be/xqRmTx-hBUo?t=723) ➜ never learn every single tip but just
- [00:12:05](https://youtu.be/xqRmTx-hBUo?t=725) ➜ try to try to see how the best struggle
- [00:12:09](https://youtu.be/xqRmTx-hBUo?t=729) ➜ to do it and do it the same way
- [00:12:14](https://youtu.be/xqRmTx-hBUo?t=734) ➜ nice but it really helped me was oh
- [00:12:16](https://youtu.be/xqRmTx-hBUo?t=736) ➜ sorry go ahead this
- [00:12:19](https://youtu.be/xqRmTx-hBUo?t=739) ➜ no no this is a really nice I mean and
- [00:12:22](https://youtu.be/xqRmTx-hBUo?t=742) ➜ and can I ask you guys something uh so
- [00:12:24](https://youtu.be/xqRmTx-hBUo?t=744) ➜ ours was saying that his wake up call
- [00:12:27](https://youtu.be/xqRmTx-hBUo?t=747) ➜ for gas was CRC 721 Nave right ours yes
- [00:12:34](https://youtu.be/xqRmTx-hBUo?t=754) ➜ c1721a yeah uh so what was the big
- [00:12:37](https://youtu.be/xqRmTx-hBUo?t=757) ➜ difference in there and how much of a
- [00:12:40](https://youtu.be/xqRmTx-hBUo?t=760) ➜ gas saving we had from this contract to
- [00:12:42](https://youtu.be/xqRmTx-hBUo?t=762) ➜ a classic nft
- [00:12:45](https://youtu.be/xqRmTx-hBUo?t=765) ➜ or basically the the the open Zeppelin
- [00:12:49](https://youtu.be/xqRmTx-hBUo?t=769) ➜ one just loops and mints uh each token
- [00:12:54](https://youtu.be/xqRmTx-hBUo?t=774) ➜ and basically the erc71 uh batch mins
- [00:12:58](https://youtu.be/xqRmTx-hBUo?t=778) ➜ them and stores all the
- [00:13:01](https://youtu.be/xqRmTx-hBUo?t=781) ➜ or that all the tokens for the one owner
- [00:13:05](https://youtu.be/xqRmTx-hBUo?t=785) ➜ and yeah the gas cards were really big
- [00:13:09](https://youtu.be/xqRmTx-hBUo?t=789) ➜ foreign
- [00:13:12](https://youtu.be/xqRmTx-hBUo?t=792) ➜ sorry to cut you off there I was just
- [00:13:14](https://youtu.be/xqRmTx-hBUo?t=794) ➜ saying it's interesting because that was
- [00:13:15](https://youtu.be/xqRmTx-hBUo?t=795) ➜ one of the uh looking into erc721 versus
- [00:13:18](https://youtu.be/xqRmTx-hBUo?t=798) ➜ 721a it was one of the first times where
- [00:13:21](https://youtu.be/xqRmTx-hBUo?t=801) ➜ I was seeing like the complexity and the
- [00:13:24](https://youtu.be/xqRmTx-hBUo?t=804) ➜ gas specifically in the you know it
- [00:13:26](https://youtu.be/xqRmTx-hBUo?t=806) ➜ depends on which project you're using
- [00:13:28](https://youtu.be/xqRmTx-hBUo?t=808) ➜ right which one you want to use 721 or
- [00:13:30](https://youtu.be/xqRmTx-hBUo?t=810) ➜ 7218 if you have a project like azuki or
- [00:13:33](https://youtu.be/xqRmTx-hBUo?t=813) ➜ you know board date where you
- [00:13:34](https://youtu.be/xqRmTx-hBUo?t=814) ➜ potentially will have a lot of people
- [00:13:36](https://youtu.be/xqRmTx-hBUo?t=816) ➜ you know minting like or saying batch
- [00:13:37](https://youtu.be/xqRmTx-hBUo?t=817) ➜ minting and obviously you want to do
- [00:13:39](https://youtu.be/xqRmTx-hBUo?t=819) ➜ 721a but if I remember correctly the 721
- [00:13:42](https://youtu.be/xqRmTx-hBUo?t=822) ➜ was more gas efficient for single vents
- [00:13:45](https://youtu.be/xqRmTx-hBUo?t=825) ➜ and so you know you have to take all
- [00:13:47](https://youtu.be/xqRmTx-hBUo?t=827) ➜ this into consideration with these
- [00:13:49](https://youtu.be/xqRmTx-hBUo?t=829) ➜ products yeah and also the I think the
- [00:13:51](https://youtu.be/xqRmTx-hBUo?t=831) ➜ transfers uh when you transfer it to
- [00:13:53](https://youtu.be/xqRmTx-hBUo?t=833) ➜ Target was also uh cheaper for the open
- [00:13:56](https://youtu.be/xqRmTx-hBUo?t=836) ➜ Zeppelin one
- [00:13:57](https://youtu.be/xqRmTx-hBUo?t=837) ➜ but yeah
- [00:14:00](https://youtu.be/xqRmTx-hBUo?t=840) ➜ yeah oh and and then the third step I
- [00:14:04](https://youtu.be/xqRmTx-hBUo?t=844) ➜ would say learn you that's how you like
- [00:14:08](https://youtu.be/xqRmTx-hBUo?t=848) ➜ access the evm's financial and yeah
- [00:14:11](https://youtu.be/xqRmTx-hBUo?t=851) ➜ that's how you really eliminate gas and
- [00:14:13](https://youtu.be/xqRmTx-hBUo?t=853) ➜ unnecessary up codes
- [00:14:16](https://youtu.be/xqRmTx-hBUo?t=856) ➜ really cool I'm inviting more people to
- [00:14:18](https://youtu.be/xqRmTx-hBUo?t=858) ➜ speak so if they have questions they can
- [00:14:21](https://youtu.be/xqRmTx-hBUo?t=861) ➜ just open their mics
- [00:14:23](https://youtu.be/xqRmTx-hBUo?t=863) ➜ and and and and guys today there's a lot
- [00:14:27](https://youtu.be/xqRmTx-hBUo?t=867) ➜ of talks regarding SO gas is really
- [00:14:30](https://youtu.be/xqRmTx-hBUo?t=870) ➜ important right everybody is looking at
- [00:14:31](https://youtu.be/xqRmTx-hBUo?t=871) ➜ it it is getting more and more complex
- [00:14:33](https://youtu.be/xqRmTx-hBUo?t=873) ➜ and there's that awful question about
- [00:14:36](https://youtu.be/xqRmTx-hBUo?t=876) ➜ you know gas versus security
- [00:14:39](https://youtu.be/xqRmTx-hBUo?t=879) ➜ we'll talk about this yeah so go on
- [00:14:43](https://youtu.be/xqRmTx-hBUo?t=883) ➜ just probably on the end or like
- [00:14:49](https://youtu.be/xqRmTx-hBUo?t=889) ➜ oh so we uh we wanted to talk about also
- [00:14:53](https://youtu.be/xqRmTx-hBUo?t=893) ➜ the fourth step I would say just never
- [00:14:56](https://youtu.be/xqRmTx-hBUo?t=896) ➜ stop learning and just think you know a
- [00:14:59](https://youtu.be/xqRmTx-hBUo?t=899) ➜ lot of optimizations come from thinking
- [00:15:01](https://youtu.be/xqRmTx-hBUo?t=901) ➜ oh just think about the architecture and
- [00:15:03](https://youtu.be/xqRmTx-hBUo?t=903) ➜ stuff like that and just never stop
- [00:15:05](https://youtu.be/xqRmTx-hBUo?t=905) ➜ learning I don't know every single gas
- [00:15:08](https://youtu.be/xqRmTx-hBUo?t=908) ➜ optimization that exists on the contest
- [00:15:10](https://youtu.be/xqRmTx-hBUo?t=910) ➜ that I was auditing I found some autism
- [00:15:14](https://youtu.be/xqRmTx-hBUo?t=914) ➜ optimizations that I never thought about
- [00:15:16](https://youtu.be/xqRmTx-hBUo?t=916) ➜ so just the only way to found that find
- [00:15:19](https://youtu.be/xqRmTx-hBUo?t=919) ➜ out is to Benchmark and test
- [00:15:24](https://youtu.be/xqRmTx-hBUo?t=924) ➜ um I would also mention uh the game has
- [00:15:27](https://youtu.be/xqRmTx-hBUo?t=927) ➜ kind of changed a little bit with the
- [00:15:28](https://youtu.be/xqRmTx-hBUo?t=928) ➜ Bots you know the automated guest
- [00:15:31](https://youtu.be/xqRmTx-hBUo?t=931) ➜ finding and so forth I think they're
- [00:15:33](https://youtu.be/xqRmTx-hBUo?t=933) ➜ they're great personally but that's not
- [00:15:34](https://youtu.be/xqRmTx-hBUo?t=934) ➜ the point of what I'm about to say in
- [00:15:37](https://youtu.be/xqRmTx-hBUo?t=937) ➜ that a lot of these things like you know
- [00:15:39](https://youtu.be/xqRmTx-hBUo?t=939) ➜ caching your array length um do well
- [00:15:42](https://youtu.be/xqRmTx-hBUo?t=942) ➜ versus for you know transfer from not
- [00:15:45](https://youtu.be/xqRmTx-hBUo?t=945) ➜ being checked
- [00:15:46](https://youtu.be/xqRmTx-hBUo?t=946) ➜ Etc all these things are going to be
- [00:15:47](https://youtu.be/xqRmTx-hBUo?t=947) ➜ found by these automated Bots and that's
- [00:15:49](https://youtu.be/xqRmTx-hBUo?t=949) ➜ fine so if you're if you're in it for
- [00:15:53](https://youtu.be/xqRmTx-hBUo?t=953) ➜ your own little private audit thing then
- [00:15:55](https://youtu.be/xqRmTx-hBUo?t=955) ➜ obviously you need to know you need to
- [00:15:57](https://youtu.be/xqRmTx-hBUo?t=957) ➜ know it all but if you know you just
- [00:15:59](https://youtu.be/xqRmTx-hBUo?t=959) ➜ you're trying to get the Bare Bones and
- [00:16:00](https://youtu.be/xqRmTx-hBUo?t=960) ➜ you want to actually make some money and
- [00:16:02](https://youtu.be/xqRmTx-hBUo?t=962) ➜ make it fun to begin with I would focus
- [00:16:04](https://youtu.be/xqRmTx-hBUo?t=964) ➜ with uh things that that bot's not going
- [00:16:07](https://youtu.be/xqRmTx-hBUo?t=967) ➜ to find and that's honestly going to be
- [00:16:09](https://youtu.be/xqRmTx-hBUo?t=969) ➜ a lot more creative you know it's not
- [00:16:11](https://youtu.be/xqRmTx-hBUo?t=971) ➜ going to be scanning for something that
- [00:16:13](https://youtu.be/xqRmTx-hBUo?t=973) ➜ some regex or some asked can find
- [00:16:15](https://youtu.be/xqRmTx-hBUo?t=975) ➜ so you're going to really be looking for
- [00:16:19](https://youtu.be/xqRmTx-hBUo?t=979) ➜ um is there a way for us to delete a
- [00:16:21](https://youtu.be/xqRmTx-hBUo?t=981) ➜ line somewhere right are they uh writing
- [00:16:23](https://youtu.be/xqRmTx-hBUo?t=983) ➜ to storage three different times and
- [00:16:25](https://youtu.be/xqRmTx-hBUo?t=985) ➜ it's all the same thing uh you're
- [00:16:27](https://youtu.be/xqRmTx-hBUo?t=987) ➜ looking for uh redundancies in the code
- [00:16:30](https://youtu.be/xqRmTx-hBUo?t=990) ➜ you're looking for potential bit shifts
- [00:16:31](https://youtu.be/xqRmTx-hBUo?t=991) ➜ that that were caught by the bot and so
- [00:16:34](https://youtu.be/xqRmTx-hBUo?t=994) ➜ forth and it's a lot more fun I think
- [00:16:35](https://youtu.be/xqRmTx-hBUo?t=995) ➜ but I just wanted to throw it out there
- [00:16:38](https://youtu.be/xqRmTx-hBUo?t=998) ➜ 100 you know let's talk about I'll sort
- [00:16:43](https://youtu.be/xqRmTx-hBUo?t=1003) ➜ of just share my auditing process but
- [00:16:45](https://youtu.be/xqRmTx-hBUo?t=1005) ➜ you know if you can if you can just find
- [00:16:48](https://youtu.be/xqRmTx-hBUo?t=1008) ➜ a gas optimization without understanding
- [00:16:51](https://youtu.be/xqRmTx-hBUo?t=1011) ➜ what the code does it it will probably
- [00:16:54](https://youtu.be/xqRmTx-hBUo?t=1014) ➜ be found by the bot too so you really
- [00:16:57](https://youtu.be/xqRmTx-hBUo?t=1017) ➜ have to understand like what is being
- [00:16:59](https://youtu.be/xqRmTx-hBUo?t=1019) ➜ done there and just I remember when you
- [00:17:02](https://youtu.be/xqRmTx-hBUo?t=1022) ➜ posted like a a gas golfing Challenge
- [00:17:05](https://youtu.be/xqRmTx-hBUo?t=1025) ➜ and was like a for Loop and the for Loop
- [00:17:08](https://youtu.be/xqRmTx-hBUo?t=1028) ➜ basically performs some math right and
- [00:17:12](https://youtu.be/xqRmTx-hBUo?t=1032) ➜ uh basically people like me thought okay
- [00:17:15](https://youtu.be/xqRmTx-hBUo?t=1035) ➜ I'm gonna optimize this Loop but the
- [00:17:17](https://youtu.be/xqRmTx-hBUo?t=1037) ➜ solution was to rewind right the whole
- [00:17:20](https://youtu.be/xqRmTx-hBUo?t=1040) ➜ block and just remove the loop so that's
- [00:17:23](https://youtu.be/xqRmTx-hBUo?t=1043) ➜ exactly exactly what you should be doing
- [00:17:25](https://youtu.be/xqRmTx-hBUo?t=1045) ➜ not just focusing on this small
- [00:17:27](https://youtu.be/xqRmTx-hBUo?t=1047) ➜ optimizations but actually rewriting
- [00:17:29](https://youtu.be/xqRmTx-hBUo?t=1049) ➜ right
- [00:17:34](https://youtu.be/xqRmTx-hBUo?t=1054) ➜ indeed yes so now let's let's talk about
- [00:17:38](https://youtu.be/xqRmTx-hBUo?t=1058) ➜ how to write a gas optimized contract
- [00:17:42](https://youtu.be/xqRmTx-hBUo?t=1062) ➜ I think you should start with uh
- [00:17:45](https://youtu.be/xqRmTx-hBUo?t=1065) ➜ with an efficient architecture so you
- [00:17:49](https://youtu.be/xqRmTx-hBUo?t=1069) ➜ have to spend a lot of time thinking of
- [00:17:51](https://youtu.be/xqRmTx-hBUo?t=1071) ➜ an efficient architecture like uh for
- [00:17:55](https://youtu.be/xqRmTx-hBUo?t=1075) ➜ example the blend from blur that was
- [00:17:57](https://youtu.be/xqRmTx-hBUo?t=1077) ➜ written by the goat Transmissions
- [00:18:00](https://youtu.be/xqRmTx-hBUo?t=1080) ➜ and basically the blend contract
- [00:18:02](https://youtu.be/xqRmTx-hBUo?t=1082) ➜ minimizes how much data is stored on
- [00:18:04](https://youtu.be/xqRmTx-hBUo?t=1084) ➜ chain uh significantly reducing the
- [00:18:07](https://youtu.be/xqRmTx-hBUo?t=1087) ➜ number of expensive as stores and sloads
- [00:18:10](https://youtu.be/xqRmTx-hBUo?t=1090) ➜ for example The Loan Data is not stored
- [00:18:14](https://youtu.be/xqRmTx-hBUo?t=1094) ➜ on chain instead the contract simply
- [00:18:16](https://youtu.be/xqRmTx-hBUo?t=1096) ➜ stores a mapping of loan ID to Lone hash
- [00:18:20](https://youtu.be/xqRmTx-hBUo?t=1100) ➜ and yep just remove what's unnecessary
- [00:18:23](https://youtu.be/xqRmTx-hBUo?t=1103) ➜ and use release code
- [00:18:25](https://youtu.be/xqRmTx-hBUo?t=1105) ➜ and those the second thing I would say
- [00:18:28](https://youtu.be/xqRmTx-hBUo?t=1108) ➜ do more what is cheap and less what is
- [00:18:30](https://youtu.be/xqRmTx-hBUo?t=1110) ➜ expensive so if you can rewrite or
- [00:18:33](https://youtu.be/xqRmTx-hBUo?t=1113) ➜ organize your code so you're doing more
- [00:18:35](https://youtu.be/xqRmTx-hBUo?t=1115) ➜ what is cheap and less what is expensive
- [00:18:36](https://youtu.be/xqRmTx-hBUo?t=1116) ➜ then you're saving gas and there's sort
- [00:18:39](https://youtu.be/xqRmTx-hBUo?t=1119) ➜ of two levels of optimizations here of
- [00:18:43](https://youtu.be/xqRmTx-hBUo?t=1123) ➜ the salinity stuff like using memory and
- [00:18:45](https://youtu.be/xqRmTx-hBUo?t=1125) ➜ starch in the correct way and the
- [00:18:48](https://youtu.be/xqRmTx-hBUo?t=1128) ➜ assembly stuff like really eliminating
- [00:18:50](https://youtu.be/xqRmTx-hBUo?t=1130) ➜ an sgr codes and
- [00:18:52](https://youtu.be/xqRmTx-hBUo?t=1132) ➜ uh rewriting big Loops you know to
- [00:18:55](https://youtu.be/xqRmTx-hBUo?t=1135) ➜ assembly and you know every optimization
- [00:18:57](https://youtu.be/xqRmTx-hBUo?t=1137) ➜ here will just have a reason why it's
- [00:18:59](https://youtu.be/xqRmTx-hBUo?t=1139) ➜ cheaper here
- [00:19:01](https://youtu.be/xqRmTx-hBUo?t=1141) ➜ and the third thing just search for
- [00:19:05](https://youtu.be/xqRmTx-hBUo?t=1145) ➜ those tips and tricks oh this can
- [00:19:08](https://youtu.be/xqRmTx-hBUo?t=1148) ➜ obviously be automated by some Bots and
- [00:19:12](https://youtu.be/xqRmTx-hBUo?t=1152) ➜ just for example pre-incrementing which
- [00:19:14](https://youtu.be/xqRmTx-hBUo?t=1154) ➜ by the way doesn't work if you compile
- [00:19:16](https://youtu.be/xqRmTx-hBUo?t=1156) ➜ it with the
- [00:19:18](https://youtu.be/xqRmTx-hBUo?t=1158) ➜ viir so the compiler is sometimes a bit
- [00:19:21](https://youtu.be/xqRmTx-hBUo?t=1161) ➜ lazy but again it's not your excuse not
- [00:19:24](https://youtu.be/xqRmTx-hBUo?t=1164) ➜ to optimize and number four I would say
- [00:19:27](https://youtu.be/xqRmTx-hBUo?t=1167) ➜ just always test try Benchmark sql's
- [00:19:31](https://youtu.be/xqRmTx-hBUo?t=1171) ➜ better and rewrite
- [00:19:34](https://youtu.be/xqRmTx-hBUo?t=1174) ➜ yeah
- [00:19:36](https://youtu.be/xqRmTx-hBUo?t=1176) ➜ what do you think oh is this a good way
- [00:19:40](https://youtu.be/xqRmTx-hBUo?t=1180) ➜ to write a gas optimized contract
- [00:19:43](https://youtu.be/xqRmTx-hBUo?t=1183) ➜ I think that's a great way personally
- [00:19:47](https://youtu.be/xqRmTx-hBUo?t=1187) ➜ um I would I would always say to
- [00:19:50](https://youtu.be/xqRmTx-hBUo?t=1190) ➜ so if you're okay so I don't really know
- [00:19:52](https://youtu.be/xqRmTx-hBUo?t=1192) ➜ I'm guessing this audience more Auditors
- [00:19:54](https://youtu.be/xqRmTx-hBUo?t=1194) ➜ but I'm going to speak from like a
- [00:19:56](https://youtu.be/xqRmTx-hBUo?t=1196) ➜ developer's standpoint if you're
- [00:19:58](https://youtu.be/xqRmTx-hBUo?t=1198) ➜ developing a a contract and you want to
- [00:20:00](https://youtu.be/xqRmTx-hBUo?t=1200) ➜ do you know your gaps optimization and
- [00:20:02](https://youtu.be/xqRmTx-hBUo?t=1202) ➜ and you know some things but you don't
- [00:20:04](https://youtu.be/xqRmTx-hBUo?t=1204) ➜ know a lot that's that's fine I would
- [00:20:06](https://youtu.be/xqRmTx-hBUo?t=1206) ➜ just rewrite that function in about as
- [00:20:08](https://youtu.be/xqRmTx-hBUo?t=1208) ➜ many different ways possible you know
- [00:20:10](https://youtu.be/xqRmTx-hBUo?t=1210) ➜ that's what I did at least when I was
- [00:20:11](https://youtu.be/xqRmTx-hBUo?t=1211) ➜ learning but does it do well do what
- [00:20:13](https://youtu.be/xqRmTx-hBUo?t=1213) ➜ does a four do if I do it you know this
- [00:20:15](https://youtu.be/xqRmTx-hBUo?t=1215) ➜ that what if I start pre-increment and
- [00:20:17](https://youtu.be/xqRmTx-hBUo?t=1217) ➜ so forth and if you just do that with
- [00:20:20](https://youtu.be/xqRmTx-hBUo?t=1220) ➜ your contract that you're developing
- [00:20:21](https://youtu.be/xqRmTx-hBUo?t=1221) ➜ you're eventually going to find at least
- [00:20:23](https://youtu.be/xqRmTx-hBUo?t=1223) ➜ a more efficient way than what you had
- [00:20:25](https://youtu.be/xqRmTx-hBUo?t=1225) ➜ in the beginning
- [00:20:26](https://youtu.be/xqRmTx-hBUo?t=1226) ➜ uh say I just want to throw that out
- [00:20:28](https://youtu.be/xqRmTx-hBUo?t=1228) ➜ there
- [00:20:30](https://youtu.be/xqRmTx-hBUo?t=1230) ➜ yeah definitely so
- [00:20:32](https://youtu.be/xqRmTx-hBUo?t=1232) ➜ oh let's maybe talk about tattoo
- [00:20:34](https://youtu.be/xqRmTx-hBUo?t=1234) ➜ actually audit a contract we talked
- [00:20:36](https://youtu.be/xqRmTx-hBUo?t=1236) ➜ about how to write a contract now we'll
- [00:20:38](https://youtu.be/xqRmTx-hBUo?t=1238) ➜ talk about how to audit and the contract
- [00:20:41](https://youtu.be/xqRmTx-hBUo?t=1241) ➜ and find some gas optimizations so you
- [00:20:43](https://youtu.be/xqRmTx-hBUo?t=1243) ➜ want to share some stuff
- [00:20:46](https://youtu.be/xqRmTx-hBUo?t=1246) ➜ about this sure so
- [00:20:48](https://youtu.be/xqRmTx-hBUo?t=1248) ➜ I mean the auditing process is obviously
- [00:20:50](https://youtu.be/xqRmTx-hBUo?t=1250) ➜ going to be different from person to
- [00:20:51](https://youtu.be/xqRmTx-hBUo?t=1251) ➜ person
- [00:20:52](https://youtu.be/xqRmTx-hBUo?t=1252) ➜ but I I mean I've studied actually quite
- [00:20:55](https://youtu.be/xqRmTx-hBUo?t=1255) ➜ a few you know Patrick Collins uh bytes
- [00:20:58](https://youtu.be/xqRmTx-hBUo?t=1258) ➜ 32 I think even trust a few of them I've
- [00:21:01](https://youtu.be/xqRmTx-hBUo?t=1261) ➜ looked at their Twitters I've you know
- [00:21:03](https://youtu.be/xqRmTx-hBUo?t=1263) ➜ read their reports and no matter what
- [00:21:07](https://youtu.be/xqRmTx-hBUo?t=1267) ➜ there's always one key thing that every
- [00:21:10](https://youtu.be/xqRmTx-hBUo?t=1270) ➜ auditor is going to do at least at some
- [00:21:11](https://youtu.be/xqRmTx-hBUo?t=1271) ➜ point and that is understanding the
- [00:21:13](https://youtu.be/xqRmTx-hBUo?t=1273) ➜ protocol right so you gotta go into code
- [00:21:15](https://youtu.be/xqRmTx-hBUo?t=1275) ➜ Arena you got to read whatever's on that
- [00:21:18](https://youtu.be/xqRmTx-hBUo?t=1278) ➜ that GitHub you have to read all the
- [00:21:20](https://youtu.be/xqRmTx-hBUo?t=1280) ➜ docs that are in there you have to go to
- [00:21:22](https://youtu.be/xqRmTx-hBUo?t=1282) ➜ the code Arena Discord you have to open
- [00:21:25](https://youtu.be/xqRmTx-hBUo?t=1285) ➜ up that that one for that specific
- [00:21:27](https://youtu.be/xqRmTx-hBUo?t=1287) ➜ contest people will be asking great
- [00:21:29](https://youtu.be/xqRmTx-hBUo?t=1289) ➜ questions and these questions are coming
- [00:21:31](https://youtu.be/xqRmTx-hBUo?t=1291) ➜ from you know some somewhere in their
- [00:21:33](https://youtu.be/xqRmTx-hBUo?t=1293) ➜ mind so keep that in mind and
- [00:21:36](https://youtu.be/xqRmTx-hBUo?t=1296) ➜ um yeah you're just gonna have to
- [00:21:37](https://youtu.be/xqRmTx-hBUo?t=1297) ➜ understand that protocol at some point
- [00:21:39](https://youtu.be/xqRmTx-hBUo?t=1299) ➜ so that's the point I will make yeah
- [00:21:41](https://youtu.be/xqRmTx-hBUo?t=1301) ➜ definitely that's always the first point
- [00:21:43](https://youtu.be/xqRmTx-hBUo?t=1303) ➜ even if like you're doing a Goss gas
- [00:21:46](https://youtu.be/xqRmTx-hBUo?t=1306) ➜ audit and not a security just understand
- [00:21:49](https://youtu.be/xqRmTx-hBUo?t=1309) ➜ the paragraph As I said if you find the
- [00:21:51](https://youtu.be/xqRmTx-hBUo?t=1311) ➜ optimization without understanding the
- [00:21:54](https://youtu.be/xqRmTx-hBUo?t=1314) ➜ particle then it was probably already
- [00:21:56](https://youtu.be/xqRmTx-hBUo?t=1316) ➜ found by a bot so you won't really earn
- [00:22:00](https://youtu.be/xqRmTx-hBUo?t=1320) ➜ much from it and just then you can uh
- [00:22:04](https://youtu.be/xqRmTx-hBUo?t=1324) ➜ and you just find you see what what is
- [00:22:06](https://youtu.be/xqRmTx-hBUo?t=1326) ➜ expensive what is cheap and just rewrite
- [00:22:09](https://youtu.be/xqRmTx-hBUo?t=1329) ➜ you know
- [00:22:11](https://youtu.be/xqRmTx-hBUo?t=1331) ➜ and you know optimizing is good but like
- [00:22:13](https://youtu.be/xqRmTx-hBUo?t=1333) ➜ you also have to rewrite and that's how
- [00:22:17](https://youtu.be/xqRmTx-hBUo?t=1337) ➜ you also optimize and then just
- [00:22:22](https://youtu.be/xqRmTx-hBUo?t=1342) ➜ change Benchmark rate just see what's
- [00:22:24](https://youtu.be/xqRmTx-hBUo?t=1344) ➜ better I use The Foundry uh gas report
- [00:22:27](https://youtu.be/xqRmTx-hBUo?t=1347) ➜ you can also use the harder one and yeah
- [00:22:30](https://youtu.be/xqRmTx-hBUo?t=1350) ➜ and number four just write the report I
- [00:22:33](https://youtu.be/xqRmTx-hBUo?t=1353) ➜ this is very important because code
- [00:22:35](https://youtu.be/xqRmTx-hBUo?t=1355) ➜ Arena only selects the best reports and
- [00:22:39](https://youtu.be/xqRmTx-hBUo?t=1359) ➜ just really spend some
- [00:22:41](https://youtu.be/xqRmTx-hBUo?t=1361) ➜ a decent amount of time just writing the
- [00:22:44](https://youtu.be/xqRmTx-hBUo?t=1364) ➜ protocol
- [00:22:45](https://youtu.be/xqRmTx-hBUo?t=1365) ➜ uh you should have like a good
- [00:22:48](https://youtu.be/xqRmTx-hBUo?t=1368) ➜ explanation why you think it's it's
- [00:22:50](https://youtu.be/xqRmTx-hBUo?t=1370) ➜ cheaper and a good recommendation and uh
- [00:22:54](https://youtu.be/xqRmTx-hBUo?t=1374) ➜ all the instances and just how much gas
- [00:22:57](https://youtu.be/xqRmTx-hBUo?t=1377) ➜ was saved and just you're not you won't
- [00:22:59](https://youtu.be/xqRmTx-hBUo?t=1379) ➜ earn much if you just submit like a few
- [00:23:03](https://youtu.be/xqRmTx-hBUo?t=1383) ➜ of gas a few gas optimizations you have
- [00:23:06](https://youtu.be/xqRmTx-hBUo?t=1386) ➜ to have a good quantity of
- [00:23:09](https://youtu.be/xqRmTx-hBUo?t=1389) ➜ gas optimizations and a good quality
- [00:23:12](https://youtu.be/xqRmTx-hBUo?t=1392) ➜ report
- [00:23:13](https://youtu.be/xqRmTx-hBUo?t=1393) ➜ so yeah that's that's my auditing
- [00:23:16](https://youtu.be/xqRmTx-hBUo?t=1396) ➜ process
- [00:23:18](https://youtu.be/xqRmTx-hBUo?t=1398) ➜ yeah definitely if I'm focusing on the
- [00:23:19](https://youtu.be/xqRmTx-hBUo?t=1399) ➜ the gas uh I think I've already you know
- [00:23:22](https://youtu.be/xqRmTx-hBUo?t=1402) ➜ told you guys basically looking at
- [00:23:23](https://youtu.be/xqRmTx-hBUo?t=1403) ➜ what's
- [00:23:24](https://youtu.be/xqRmTx-hBUo?t=1404) ➜ what's being you know instantiated twice
- [00:23:27](https://youtu.be/xqRmTx-hBUo?t=1407) ➜ are we doing things that we can be bit
- [00:23:29](https://youtu.be/xqRmTx-hBUo?t=1409) ➜ shifting uh these these kinds of things
- [00:23:32](https://youtu.be/xqRmTx-hBUo?t=1412) ➜ but your biggest yes optimization is
- [00:23:34](https://youtu.be/xqRmTx-hBUo?t=1414) ➜ going to be something that you rework
- [00:23:36](https://youtu.be/xqRmTx-hBUo?t=1416) ➜ right so something where
- [00:23:38](https://youtu.be/xqRmTx-hBUo?t=1418) ➜ um
- [00:23:39](https://youtu.be/xqRmTx-hBUo?t=1419) ➜ where you know like the for Loop or
- [00:23:41](https://youtu.be/xqRmTx-hBUo?t=1421) ➜ something something in general can be
- [00:23:44](https://youtu.be/xqRmTx-hBUo?t=1424) ➜ massively changed and so that's what I'm
- [00:23:47](https://youtu.be/xqRmTx-hBUo?t=1427) ➜ usually looking for and of course you
- [00:23:48](https://youtu.be/xqRmTx-hBUo?t=1428) ➜ can't change the the functionality and
- [00:23:50](https://youtu.be/xqRmTx-hBUo?t=1430) ➜ you can't introduce bugs so you can't
- [00:23:52](https://youtu.be/xqRmTx-hBUo?t=1432) ➜ change a whole lot you know you got to
- [00:23:54](https://youtu.be/xqRmTx-hBUo?t=1434) ➜ make you got to make sure you're really
- [00:23:55](https://youtu.be/xqRmTx-hBUo?t=1435) ➜ careful with that
- [00:23:57](https://youtu.be/xqRmTx-hBUo?t=1437) ➜ um but yeah so for the auditing process
- [00:23:59](https://youtu.be/xqRmTx-hBUo?t=1439) ➜ though I definitely I look through I
- [00:24:00](https://youtu.be/xqRmTx-hBUo?t=1440) ➜ make sure I understand the protocol I go
- [00:24:03](https://youtu.be/xqRmTx-hBUo?t=1443) ➜ through each each
- [00:24:04](https://youtu.be/xqRmTx-hBUo?t=1444) ➜ script very briefly very fast running
- [00:24:08](https://youtu.be/xqRmTx-hBUo?t=1448) ➜ through it and then lastly I will go
- [00:24:11](https://youtu.be/xqRmTx-hBUo?t=1451) ➜ through and line by line
- [00:24:13](https://youtu.be/xqRmTx-hBUo?t=1453) ➜ do exactly what ours is talking about
- [00:24:15](https://youtu.be/xqRmTx-hBUo?t=1455) ➜ you know rework it figure it out see if
- [00:24:18](https://youtu.be/xqRmTx-hBUo?t=1458) ➜ there's anything I can optimize
- [00:24:22](https://youtu.be/xqRmTx-hBUo?t=1462) ➜ yeah 100 so
- [00:24:25](https://youtu.be/xqRmTx-hBUo?t=1465) ➜ let's right talk about about the current
- [00:24:28](https://youtu.be/xqRmTx-hBUo?t=1468) ➜ state of gas organization and what does
- [00:24:30](https://youtu.be/xqRmTx-hBUo?t=1470) ➜ the future hold for this field uh right
- [00:24:33](https://youtu.be/xqRmTx-hBUo?t=1473) ➜ now it's a quite New Field and a very
- [00:24:36](https://youtu.be/xqRmTx-hBUo?t=1476) ➜ interesting one too uh
- [00:24:39](https://youtu.be/xqRmTx-hBUo?t=1479) ➜ audits are kind of new right but
- [00:24:42](https://youtu.be/xqRmTx-hBUo?t=1482) ➜ it's great that some programs care about
- [00:24:44](https://youtu.be/xqRmTx-hBUo?t=1484) ➜ the users and not even about their users
- [00:24:47](https://youtu.be/xqRmTx-hBUo?t=1487) ➜ but the users of the whole network
- [00:24:50](https://youtu.be/xqRmTx-hBUo?t=1490) ➜ and why don't protocols optimize is it
- [00:24:53](https://youtu.be/xqRmTx-hBUo?t=1493) ➜ because of readability is it because of
- [00:24:55](https://youtu.be/xqRmTx-hBUo?t=1495) ➜ security what do you think
- [00:24:58](https://youtu.be/xqRmTx-hBUo?t=1498) ➜ I think readability has a lot to do with
- [00:25:00](https://youtu.be/xqRmTx-hBUo?t=1500) ➜ it I've seen I've seen projects just
- [00:25:02](https://youtu.be/xqRmTx-hBUo?t=1502) ➜ straight up reject you know doing these
- [00:25:04](https://youtu.be/xqRmTx-hBUo?t=1504) ➜ gas optimizations because of readability
- [00:25:05](https://youtu.be/xqRmTx-hBUo?t=1505) ➜ issues
- [00:25:06](https://youtu.be/xqRmTx-hBUo?t=1506) ➜ and it was something I even struggled
- [00:25:09](https://youtu.be/xqRmTx-hBUo?t=1509) ➜ with you know a little bit myself but I
- [00:25:12](https://youtu.be/xqRmTx-hBUo?t=1512) ➜ think that Beyond readability it's more
- [00:25:15](https://youtu.be/xqRmTx-hBUo?t=1515) ➜ so right now that it's just not it's not
- [00:25:18](https://youtu.be/xqRmTx-hBUo?t=1518) ➜ paid out right you go to code Arena you
- [00:25:19](https://youtu.be/xqRmTx-hBUo?t=1519) ➜ go to Sherlock and you get like yeah
- [00:25:21](https://youtu.be/xqRmTx-hBUo?t=1521) ➜ like this this hundred thousand dollar
- [00:25:23](https://youtu.be/xqRmTx-hBUo?t=1523) ➜ price pool and one thousands of its gaps
- [00:25:25](https://youtu.be/xqRmTx-hBUo?t=1525) ➜ you know and you got 50 different people
- [00:25:27](https://youtu.be/xqRmTx-hBUo?t=1527) ➜ competing for that so a lot of people
- [00:25:30](https://youtu.be/xqRmTx-hBUo?t=1530) ➜ probably just skip over it a lot of
- [00:25:31](https://youtu.be/xqRmTx-hBUo?t=1531) ➜ people will see those numbers and I
- [00:25:34](https://youtu.be/xqRmTx-hBUo?t=1534) ➜ think it's not important
- [00:25:35](https://youtu.be/xqRmTx-hBUo?t=1535) ➜ um
- [00:25:37](https://youtu.be/xqRmTx-hBUo?t=1537) ➜ there are a lot of private auditing
- [00:25:39](https://youtu.be/xqRmTx-hBUo?t=1539) ➜ people coming out I know uh Harrison was
- [00:25:42](https://youtu.be/xqRmTx-hBUo?t=1542) ➜ doing something good there of course
- [00:25:43](https://youtu.be/xqRmTx-hBUo?t=1543) ➜ you'd have uh
- [00:25:45](https://youtu.be/xqRmTx-hBUo?t=1545) ➜ bars here and myself focusing on this so
- [00:25:49](https://youtu.be/xqRmTx-hBUo?t=1549) ➜ there are people that care about it but
- [00:25:50](https://youtu.be/xqRmTx-hBUo?t=1550) ➜ that's what I would say
- [00:25:52](https://youtu.be/xqRmTx-hBUo?t=1552) ➜ yeah definitely but you know most gas
- [00:25:55](https://youtu.be/xqRmTx-hBUo?t=1555) ➜ optimization don't even have to come
- [00:25:57](https://youtu.be/xqRmTx-hBUo?t=1557) ➜ from you also
- [00:25:58](https://youtu.be/xqRmTx-hBUo?t=1558) ➜ so you know I think that like when you
- [00:26:01](https://youtu.be/xqRmTx-hBUo?t=1561) ➜ rewrite to you then okay that's kind of
- [00:26:04](https://youtu.be/xqRmTx-hBUo?t=1564) ➜ understandable that there's a security
- [00:26:05](https://youtu.be/xqRmTx-hBUo?t=1565) ➜ risk but some gas optimization don't
- [00:26:09](https://youtu.be/xqRmTx-hBUo?t=1569) ➜ even have to come from you and sometimes
- [00:26:12](https://youtu.be/xqRmTx-hBUo?t=1572) ➜ the devs are just lazy to optimize and
- [00:26:15](https://youtu.be/xqRmTx-hBUo?t=1575) ➜ it can sometimes
- [00:26:17](https://youtu.be/xqRmTx-hBUo?t=1577) ➜ uh improve the readability but sometimes
- [00:26:22](https://youtu.be/xqRmTx-hBUo?t=1582) ➜ they can agree with that but like
- [00:26:25](https://youtu.be/xqRmTx-hBUo?t=1585) ➜ it shouldn't be an excuse for devs not
- [00:26:27](https://youtu.be/xqRmTx-hBUo?t=1587) ➜ to optimize right
- [00:26:30](https://youtu.be/xqRmTx-hBUo?t=1590) ➜ and we have seen some parallels being
- [00:26:32](https://youtu.be/xqRmTx-hBUo?t=1592) ➜ optimized and some protocols like Ian or
- [00:26:35](https://youtu.be/xqRmTx-hBUo?t=1595) ➜ curve or even Rewritten to Viper
- [00:26:39](https://youtu.be/xqRmTx-hBUo?t=1599) ➜ what do you think will we see more
- [00:26:41](https://youtu.be/xqRmTx-hBUo?t=1601) ➜ particles being optimized
- [00:26:43](https://youtu.be/xqRmTx-hBUo?t=1603) ➜ I think so I think in the future it's
- [00:26:46](https://youtu.be/xqRmTx-hBUo?t=1606) ➜ inevitable as as we get closer and
- [00:26:49](https://youtu.be/xqRmTx-hBUo?t=1609) ➜ closer towards you know actual adoption
- [00:26:51](https://youtu.be/xqRmTx-hBUo?t=1611) ➜ of this mainstream adoption then we're
- [00:26:54](https://youtu.be/xqRmTx-hBUo?t=1614) ➜ going to have the kind of uh
- [00:26:56](https://youtu.be/xqRmTx-hBUo?t=1616) ➜ coalescence of some sense where a lot of
- [00:26:59](https://youtu.be/xqRmTx-hBUo?t=1619) ➜ these Protocols are essentially going at
- [00:27:00](https://youtu.be/xqRmTx-hBUo?t=1620) ➜ least I think this is what I'm thinking
- [00:27:01](https://youtu.be/xqRmTx-hBUo?t=1621) ➜ all these Protocols are going to kind of
- [00:27:03](https://youtu.be/xqRmTx-hBUo?t=1623) ➜ be you know converging and so forth and
- [00:27:05](https://youtu.be/xqRmTx-hBUo?t=1625) ➜ a lot of them are going to hit the right
- [00:27:06](https://youtu.be/xqRmTx-hBUo?t=1626) ➜ side just like any startup Market any
- [00:27:09](https://youtu.be/xqRmTx-hBUo?t=1629) ➜ kind of Emerging Market oh all these you
- [00:27:12](https://youtu.be/xqRmTx-hBUo?t=1632) ➜ know excess ones will hit the hit the
- [00:27:14](https://youtu.be/xqRmTx-hBUo?t=1634) ➜ Wayside and these ones that are left
- [00:27:16](https://youtu.be/xqRmTx-hBUo?t=1636) ➜ standing will need to optimize or else
- [00:27:18](https://youtu.be/xqRmTx-hBUo?t=1638) ➜ they're going to be pushed aside that's
- [00:27:19](https://youtu.be/xqRmTx-hBUo?t=1639) ➜ what I'm thinking yes I think that the
- [00:27:22](https://youtu.be/xqRmTx-hBUo?t=1642) ➜ same though many particles that exist
- [00:27:24](https://youtu.be/xqRmTx-hBUo?t=1644) ➜ today can be significantly optimized
- [00:27:27](https://youtu.be/xqRmTx-hBUo?t=1647) ➜ and but the question is when ethereum
- [00:27:30](https://youtu.be/xqRmTx-hBUo?t=1650) ➜ scales will the devs have to worry about
- [00:27:32](https://youtu.be/xqRmTx-hBUo?t=1652) ➜ optimizing their code oh no
- [00:27:36](https://youtu.be/xqRmTx-hBUo?t=1656) ➜ that's a good question it's a good
- [00:27:38](https://youtu.be/xqRmTx-hBUo?t=1658) ➜ question
- [00:27:39](https://youtu.be/xqRmTx-hBUo?t=1659) ➜ not entirely sure
- [00:27:41](https://youtu.be/xqRmTx-hBUo?t=1661) ➜ but we do uh we do have a question here
- [00:27:42](https://youtu.be/xqRmTx-hBUo?t=1662) ➜ from Ronan in the chat ours if you want
- [00:27:44](https://youtu.be/xqRmTx-hBUo?t=1664) ➜ to if you want to hit this one he's
- [00:27:46](https://youtu.be/xqRmTx-hBUo?t=1666) ➜ asking would like to know uh what are
- [00:27:48](https://youtu.be/xqRmTx-hBUo?t=1668) ➜ some of the ways in process for someone
- [00:27:50](https://youtu.be/xqRmTx-hBUo?t=1670) ➜ to do these guests optimization reports
- [00:27:52](https://youtu.be/xqRmTx-hBUo?t=1672) ➜ and these qualitative analysis reports
- [00:27:54](https://youtu.be/xqRmTx-hBUo?t=1674) ➜ for a contest for a newbie
- [00:27:58](https://youtu.be/xqRmTx-hBUo?t=1678) ➜ yeah okay so just uh I know that code
- [00:28:01](https://youtu.be/xqRmTx-hBUo?t=1681) ➜ Arena and also Health Finance to these
- [00:28:05](https://youtu.be/xqRmTx-hBUo?t=1685) ➜ cars
- [00:28:06](https://youtu.be/xqRmTx-hBUo?t=1686) ➜ that you can submit and just basically
- [00:28:10](https://youtu.be/xqRmTx-hBUo?t=1690) ➜ uh the juice box which is and I just
- [00:28:14](https://youtu.be/xqRmTx-hBUo?t=1694) ➜ submitted the the gas report and you
- [00:28:17](https://youtu.be/xqRmTx-hBUo?t=1697) ➜ know I earned a quite nice reward right
- [00:28:20](https://youtu.be/xqRmTx-hBUo?t=1700) ➜ and just as I said uh
- [00:28:27](https://youtu.be/xqRmTx-hBUo?t=1707) ➜ you know we've mentioned how we should
- [00:28:30](https://youtu.be/xqRmTx-hBUo?t=1710) ➜ learn and
- [00:28:31](https://youtu.be/xqRmTx-hBUo?t=1711) ➜ if you want to like as I said first
- [00:28:34](https://youtu.be/xqRmTx-hBUo?t=1714) ➜ understand the particle as you would do
- [00:28:38](https://youtu.be/xqRmTx-hBUo?t=1718) ➜ with when doing security and just
- [00:28:41](https://youtu.be/xqRmTx-hBUo?t=1721) ➜ oh the Bots are getting quite good so
- [00:28:44](https://youtu.be/xqRmTx-hBUo?t=1724) ➜ you're not gonna find these small tips
- [00:28:46](https://youtu.be/xqRmTx-hBUo?t=1726) ➜ and tricks so just find some uh code
- [00:28:51](https://youtu.be/xqRmTx-hBUo?t=1731) ➜ that isn't used find code that can be uh
- [00:28:56](https://youtu.be/xqRmTx-hBUo?t=1736) ➜ can be Rewritten into a cheaper way you
- [00:28:59](https://youtu.be/xqRmTx-hBUo?t=1739) ➜ know we have to understand what is cheap
- [00:29:01](https://youtu.be/xqRmTx-hBUo?t=1741) ➜ and what is expensive and then do what
- [00:29:04](https://youtu.be/xqRmTx-hBUo?t=1744) ➜ is cheap and just
- [00:29:06](https://youtu.be/xqRmTx-hBUo?t=1746) ➜ as we as we mentioned you have to
- [00:29:09](https://youtu.be/xqRmTx-hBUo?t=1749) ➜ rewrite not optimize and just Benchmark
- [00:29:12](https://youtu.be/xqRmTx-hBUo?t=1752) ➜ use Foundry
- [00:29:14](https://youtu.be/xqRmTx-hBUo?t=1754) ➜ test see what's better and you know I I
- [00:29:17](https://youtu.be/xqRmTx-hBUo?t=1757) ➜ said that I didn't even know about the
- [00:29:20](https://youtu.be/xqRmTx-hBUo?t=1760) ➜ gas optimizations that I found so you
- [00:29:23](https://youtu.be/xqRmTx-hBUo?t=1763) ➜ just have to go line by line and just
- [00:29:25](https://youtu.be/xqRmTx-hBUo?t=1765) ➜ see what what can be done here
- [00:29:30](https://youtu.be/xqRmTx-hBUo?t=1770) ➜ yeah and some tips like General about
- [00:29:32](https://youtu.be/xqRmTx-hBUo?t=1772) ➜ like the process of auditing I've gone
- [00:29:34](https://youtu.be/xqRmTx-hBUo?t=1774) ➜ through a different set of you know ways
- [00:29:36](https://youtu.be/xqRmTx-hBUo?t=1776) ➜ of auditing these these protocols and
- [00:29:38](https://youtu.be/xqRmTx-hBUo?t=1778) ➜ one thing that's really helping me right
- [00:29:39](https://youtu.be/xqRmTx-hBUo?t=1779) ➜ now is markdown so if you don't know
- [00:29:42](https://youtu.be/xqRmTx-hBUo?t=1782) ➜ markdown definitely with learning that
- [00:29:44](https://youtu.be/xqRmTx-hBUo?t=1784) ➜ and uh it's just been really easy for me
- [00:29:47](https://youtu.be/xqRmTx-hBUo?t=1787) ➜ to take notes to like keep everything a
- [00:29:50](https://youtu.be/xqRmTx-hBUo?t=1790) ➜ little bit more organized while doing
- [00:29:52](https://youtu.be/xqRmTx-hBUo?t=1792) ➜ all this especially when you're doing
- [00:29:54](https://youtu.be/xqRmTx-hBUo?t=1794) ➜ gas optimization you have all these gas
- [00:29:55](https://youtu.be/xqRmTx-hBUo?t=1795) ➜ reports and everything it can get a
- [00:29:57](https://youtu.be/xqRmTx-hBUo?t=1797) ➜ little out of hand and having a nice
- [00:30:00](https://youtu.be/xqRmTx-hBUo?t=1800) ➜ organized pre-report can really do a lot
- [00:30:03](https://youtu.be/xqRmTx-hBUo?t=1803) ➜ of good in fact I just read a tweet from
- [00:30:05](https://youtu.be/xqRmTx-hBUo?t=1805) ➜ from somebody quite prominent in the
- [00:30:08](https://youtu.be/xqRmTx-hBUo?t=1808) ➜ space I'm drawing blank right now about
- [00:30:10](https://youtu.be/xqRmTx-hBUo?t=1810) ➜ how they made some comment you know with
- [00:30:12](https://youtu.be/xqRmTx-hBUo?t=1812) ➜ uh you know two little words there and
- [00:30:14](https://youtu.be/xqRmTx-hBUo?t=1814) ➜ they're sitting there for two hours
- [00:30:15](https://youtu.be/xqRmTx-hBUo?t=1815) ➜ trying to figure out what they saw and
- [00:30:18](https://youtu.be/xqRmTx-hBUo?t=1818) ➜ you want to make sure you avoid that and
- [00:30:20](https://youtu.be/xqRmTx-hBUo?t=1820) ➜ do a proper job with your pre-report
- [00:30:23](https://youtu.be/xqRmTx-hBUo?t=1823) ➜ yeah I think like like the report for
- [00:30:26](https://youtu.be/xqRmTx-hBUo?t=1826) ➜ gas really matters as I said but Arena
- [00:30:28](https://youtu.be/xqRmTx-hBUo?t=1828) ➜ only selects the best reports so that
- [00:30:31](https://youtu.be/xqRmTx-hBUo?t=1831) ➜ really matters you can just submit a few
- [00:30:33](https://youtu.be/xqRmTx-hBUo?t=1833) ➜ gas optimizations you have to solubate a
- [00:30:35](https://youtu.be/xqRmTx-hBUo?t=1835) ➜ lot of gas optimizations and actually
- [00:30:37](https://youtu.be/xqRmTx-hBUo?t=1837) ➜ show that cure you're saving gas and
- [00:30:40](https://youtu.be/xqRmTx-hBUo?t=1840) ➜ provide a reason uh why it is like that
- [00:30:43](https://youtu.be/xqRmTx-hBUo?t=1843) ➜ I can also send you like my template for
- [00:30:46](https://youtu.be/xqRmTx-hBUo?t=1846) ➜ the report later
- [00:30:48](https://youtu.be/xqRmTx-hBUo?t=1848) ➜ just for someone to learn and yeah
- [00:30:53](https://youtu.be/xqRmTx-hBUo?t=1853) ➜ so about the about the ethereum when it
- [00:30:57](https://youtu.be/xqRmTx-hBUo?t=1857) ➜ scales I think that I think that deaths
- [00:31:00](https://youtu.be/xqRmTx-hBUo?t=1860) ➜ will still have to uh optimize their
- [00:31:03](https://youtu.be/xqRmTx-hBUo?t=1863) ➜ code and uh the reason is simple and
- [00:31:06](https://youtu.be/xqRmTx-hBUo?t=1866) ➜ that is because of the transaction
- [00:31:08](https://youtu.be/xqRmTx-hBUo?t=1868) ➜ computation power and so the more gas
- [00:31:12](https://youtu.be/xqRmTx-hBUo?t=1872) ➜ your function costs the less you can do
- [00:31:14](https://youtu.be/xqRmTx-hBUo?t=1874) ➜ in a single transaction right and just
- [00:31:18](https://youtu.be/xqRmTx-hBUo?t=1878) ➜ every time I tweet the gas optimization
- [00:31:21](https://youtu.be/xqRmTx-hBUo?t=1881) ➜ people are like why the [ __ ] would you
- [00:31:24](https://youtu.be/xqRmTx-hBUo?t=1884) ➜ do this if you can just use a layer 2
- [00:31:26](https://youtu.be/xqRmTx-hBUo?t=1886) ➜ Chain and I'll say that because of the
- [00:31:30](https://youtu.be/xqRmTx-hBUo?t=1890) ➜ transaction computation power so that's
- [00:31:32](https://youtu.be/xqRmTx-hBUo?t=1892) ➜ that's what I think
- [00:31:36](https://youtu.be/xqRmTx-hBUo?t=1896) ➜ most definitely I thought you were more
- [00:31:37](https://youtu.be/xqRmTx-hBUo?t=1897) ➜ referring to you know like the you know
- [00:31:39](https://youtu.be/xqRmTx-hBUo?t=1899) ➜ how all this uh for example right now
- [00:31:41](https://youtu.be/xqRmTx-hBUo?t=1901) ➜ the optimizers and so forth are kind of
- [00:31:45](https://youtu.be/xqRmTx-hBUo?t=1905) ➜ we're slowly but surely as these
- [00:31:46](https://youtu.be/xqRmTx-hBUo?t=1906) ➜ solidity versions get higher and higher
- [00:31:48](https://youtu.be/xqRmTx-hBUo?t=1908) ➜ edging towards the area where it's doing
- [00:31:52](https://youtu.be/xqRmTx-hBUo?t=1912) ➜ a lot of the work right and a lot of
- [00:31:53](https://youtu.be/xqRmTx-hBUo?t=1913) ➜ this gas optimization that gets done a
- [00:31:55](https://youtu.be/xqRmTx-hBUo?t=1915) ➜ lot of people will even argue is you
- [00:31:57](https://youtu.be/xqRmTx-hBUo?t=1917) ➜ know solidities
- [00:31:58](https://youtu.be/xqRmTx-hBUo?t=1918) ➜ mistakes right the dubs are kind of
- [00:32:01](https://youtu.be/xqRmTx-hBUo?t=1921) ➜ making up for the mistakes of the
- [00:32:03](https://youtu.be/xqRmTx-hBUo?t=1923) ➜ development of ethereum that's what
- [00:32:04](https://youtu.be/xqRmTx-hBUo?t=1924) ➜ they're yeah their argument is
- [00:32:07](https://youtu.be/xqRmTx-hBUo?t=1927) ➜ um and so yeah I thought you were going
- [00:32:08](https://youtu.be/xqRmTx-hBUo?t=1928) ➜ on you know what if there's no more
- [00:32:10](https://youtu.be/xqRmTx-hBUo?t=1930) ➜ mistakes what if you can just have a DOT
- [00:32:14](https://youtu.be/xqRmTx-hBUo?t=1934) ➜ length in the at the cat in the no
- [00:32:15](https://youtu.be/xqRmTx-hBUo?t=1935) ➜ caching of the length of the array and
- [00:32:17](https://youtu.be/xqRmTx-hBUo?t=1937) ➜ it just figures it out for you
- [00:32:20](https://youtu.be/xqRmTx-hBUo?t=1940) ➜ yeah definitely I'm also excited to see
- [00:32:23](https://youtu.be/xqRmTx-hBUo?t=1943) ➜ new upcoats that uh that will be added
- [00:32:26](https://youtu.be/xqRmTx-hBUo?t=1946) ➜ and like we've seen with push zero or
- [00:32:29](https://youtu.be/xqRmTx-hBUo?t=1949) ➜ when we might finally have transient
- [00:32:32](https://youtu.be/xqRmTx-hBUo?t=1952) ➜ storage
- [00:32:35](https://youtu.be/xqRmTx-hBUo?t=1955) ➜ right so I think we can discuss some
- [00:32:38](https://youtu.be/xqRmTx-hBUo?t=1958) ➜ idea
- [00:32:45](https://youtu.be/xqRmTx-hBUo?t=1965) ➜ years come to gas station I have a lot
- [00:32:47](https://youtu.be/xqRmTx-hBUo?t=1967) ➜ of ideas for projects that can be
- [00:32:52](https://youtu.be/xqRmTx-hBUo?t=1972) ➜ built that can help developers optimize
- [00:32:55](https://youtu.be/xqRmTx-hBUo?t=1975) ➜ their code so for example everyone
- [00:32:57](https://youtu.be/xqRmTx-hBUo?t=1977) ➜ everyone's focusing on security right
- [00:32:59](https://youtu.be/xqRmTx-hBUo?t=1979) ➜ now but gas optimizations are kind of
- [00:33:01](https://youtu.be/xqRmTx-hBUo?t=1981) ➜ overlooked and for example we have
- [00:33:04](https://youtu.be/xqRmTx-hBUo?t=1984) ➜ slither right for security but I didn't
- [00:33:07](https://youtu.be/xqRmTx-hBUo?t=1987) ➜ see anything like that for gas
- [00:33:08](https://youtu.be/xqRmTx-hBUo?t=1988) ➜ optimizations like uh two like everyone
- [00:33:10](https://youtu.be/xqRmTx-hBUo?t=1990) ➜ can use there are obviously these bus on
- [00:33:13](https://youtu.be/xqRmTx-hBUo?t=1993) ➜ code Arena but there is like a tool that
- [00:33:15](https://youtu.be/xqRmTx-hBUo?t=1995) ➜ everyone can use what do you think would
- [00:33:18](https://youtu.be/xqRmTx-hBUo?t=1998) ➜ that work
- [00:33:20](https://youtu.be/xqRmTx-hBUo?t=2000) ➜ that's difficult because uh
- [00:33:23](https://youtu.be/xqRmTx-hBUo?t=2003) ➜ well I mean that's a really good
- [00:33:26](https://youtu.be/xqRmTx-hBUo?t=2006) ➜ question I would say something along the
- [00:33:28](https://youtu.be/xqRmTx-hBUo?t=2008) ➜ lines of there might be like incremental
- [00:33:30](https://youtu.be/xqRmTx-hBUo?t=2010) ➜ Innovations on these like gas reports
- [00:33:33](https://youtu.be/xqRmTx-hBUo?t=2013) ➜ like Foundry and hard hat
- [00:33:35](https://youtu.be/xqRmTx-hBUo?t=2015) ➜ but it's really hard to to make a tool
- [00:33:38](https://youtu.be/xqRmTx-hBUo?t=2018) ➜ that doesn't fix it for you you know
- [00:33:39](https://youtu.be/xqRmTx-hBUo?t=2019) ➜ what I'm saying it's already going to
- [00:33:41](https://youtu.be/xqRmTx-hBUo?t=2021) ➜ recognize that there's an issue
- [00:33:42](https://youtu.be/xqRmTx-hBUo?t=2022) ➜ somewhere and unless this tool does some
- [00:33:46](https://youtu.be/xqRmTx-hBUo?t=2026) ➜ kind of
- [00:33:47](https://youtu.be/xqRmTx-hBUo?t=2027) ➜ the rework like this reworking for you
- [00:33:49](https://youtu.be/xqRmTx-hBUo?t=2029) ➜ you know those lines around and so forth
- [00:33:51](https://youtu.be/xqRmTx-hBUo?t=2031) ➜ like almost like a fuzzing type thing
- [00:33:53](https://youtu.be/xqRmTx-hBUo?t=2033) ➜ maybe
- [00:33:55](https://youtu.be/xqRmTx-hBUo?t=2035) ➜ maybe but I I would just say it's
- [00:33:57](https://youtu.be/xqRmTx-hBUo?t=2037) ➜ probably going to be very difficult yeah
- [00:34:00](https://youtu.be/xqRmTx-hBUo?t=2040) ➜ I mean it can be done for like these
- [00:34:03](https://youtu.be/xqRmTx-hBUo?t=2043) ➜ small tips and tricks and I would love
- [00:34:06](https://youtu.be/xqRmTx-hBUo?t=2046) ➜ to see it too like that just for the
- [00:34:08](https://youtu.be/xqRmTx-hBUo?t=2048) ➜ small tips right but so it's not gonna
- [00:34:11](https://youtu.be/xqRmTx-hBUo?t=2051) ➜ optimize like
- [00:34:13](https://youtu.be/xqRmTx-hBUo?t=2053) ➜ a lot of a bunch of code right like a
- [00:34:16](https://youtu.be/xqRmTx-hBUo?t=2056) ➜ person would do and that understands how
- [00:34:18](https://youtu.be/xqRmTx-hBUo?t=2058) ➜ the event works
- [00:34:19](https://youtu.be/xqRmTx-hBUo?t=2059) ➜ and we also have immunify bright but
- [00:34:23](https://youtu.be/xqRmTx-hBUo?t=2063) ➜ like what a bug Bounty or a gas Bounty
- [00:34:26](https://youtu.be/xqRmTx-hBUo?t=2066) ➜ platform work
- [00:34:30](https://youtu.be/xqRmTx-hBUo?t=2070) ➜ that's done this definitely sounds like
- [00:34:32](https://youtu.be/xqRmTx-hBUo?t=2072) ➜ a good idea I think personally I'm
- [00:34:34](https://youtu.be/xqRmTx-hBUo?t=2074) ➜ surprised they don't have it already and
- [00:34:36](https://youtu.be/xqRmTx-hBUo?t=2076) ➜ I'm really surprised Honestly by the
- [00:34:38](https://youtu.be/xqRmTx-hBUo?t=2078) ➜ lack I love that gaskets in the code
- [00:34:40](https://youtu.be/xqRmTx-hBUo?t=2080) ➜ arena in short contest as it is but yeah
- [00:34:42](https://youtu.be/xqRmTx-hBUo?t=2082) ➜ the gas bounty
- [00:34:44](https://youtu.be/xqRmTx-hBUo?t=2084) ➜ and I think the biggest problem as I'm
- [00:34:46](https://youtu.be/xqRmTx-hBUo?t=2086) ➜ as I'm saying this the biggest problem
- [00:34:48](https://youtu.be/xqRmTx-hBUo?t=2088) ➜ is that it's going to cost these
- [00:34:50](https://youtu.be/xqRmTx-hBUo?t=2090) ➜ protocols money and
- [00:34:51](https://youtu.be/xqRmTx-hBUo?t=2091) ➜ they're not going to get anything right
- [00:34:54](https://youtu.be/xqRmTx-hBUo?t=2094) ➜ off the bat from it you know security
- [00:34:56](https://youtu.be/xqRmTx-hBUo?t=2096) ➜ it's pretty obvious why they need to
- [00:34:58](https://youtu.be/xqRmTx-hBUo?t=2098) ➜ secure this and even just having an
- [00:35:00](https://youtu.be/xqRmTx-hBUo?t=2100) ➜ audit from code Arena will entice the
- [00:35:03](https://youtu.be/xqRmTx-hBUo?t=2103) ➜ investors things like this
- [00:35:05](https://youtu.be/xqRmTx-hBUo?t=2105) ➜ so you really have to find a way to
- [00:35:08](https://youtu.be/xqRmTx-hBUo?t=2108) ➜ motivate the protocols to do it is where
- [00:35:10](https://youtu.be/xqRmTx-hBUo?t=2110) ➜ I'm getting it and I don't really know
- [00:35:13](https://youtu.be/xqRmTx-hBUo?t=2113) ➜ where where we're at with that
- [00:35:16](https://youtu.be/xqRmTx-hBUo?t=2116) ➜ yeah definitely uh you don't oh you
- [00:35:19](https://youtu.be/xqRmTx-hBUo?t=2119) ➜ don't like help only the users of your
- [00:35:21](https://youtu.be/xqRmTx-hBUo?t=2121) ➜ particle you help the users of
- [00:35:24](https://youtu.be/xqRmTx-hBUo?t=2124) ➜ the whole network right and I think it
- [00:35:28](https://youtu.be/xqRmTx-hBUo?t=2128) ➜ would be cool if you had like a gas
- [00:35:30](https://youtu.be/xqRmTx-hBUo?t=2130) ➜ monkey platform but there should be some
- [00:35:33](https://youtu.be/xqRmTx-hBUo?t=2133) ➜ ways so people don't submit like just
- [00:35:37](https://youtu.be/xqRmTx-hBUo?t=2137) ➜ these small tips and stuff like that and
- [00:35:39](https://youtu.be/xqRmTx-hBUo?t=2139) ➜ I submit actual like results
- [00:35:46](https://youtu.be/xqRmTx-hBUo?t=2146) ➜ so I think we can answer questions yeah
- [00:35:50](https://youtu.be/xqRmTx-hBUo?t=2150) ➜ Awesome Brothers I mean that's great
- [00:35:52](https://youtu.be/xqRmTx-hBUo?t=2152) ➜ explanation really love what you guys
- [00:35:54](https://youtu.be/xqRmTx-hBUo?t=2154) ➜ are doing here okay one question that I
- [00:35:56](https://youtu.be/xqRmTx-hBUo?t=2156) ➜ have for you is today there's a little
- [00:35:58](https://youtu.be/xqRmTx-hBUo?t=2158) ➜ bit of a fear of using things like Huff
- [00:36:01](https://youtu.be/xqRmTx-hBUo?t=2161) ➜ own production with deployed contracts
- [00:36:04](https://youtu.be/xqRmTx-hBUo?t=2164) ➜ you guys see a future where we're gonna
- [00:36:07](https://youtu.be/xqRmTx-hBUo?t=2167) ➜ start doing that more
- [00:36:13](https://youtu.be/xqRmTx-hBUo?t=2173) ➜ um so with Huff
- [00:36:14](https://youtu.be/xqRmTx-hBUo?t=2174) ➜ the first thing I'll say is
- [00:36:17](https://youtu.be/xqRmTx-hBUo?t=2177) ➜ I'm not really too good with like that
- [00:36:20](https://youtu.be/xqRmTx-hBUo?t=2180) ➜ yet I'm still in the learning process of
- [00:36:22](https://youtu.be/xqRmTx-hBUo?t=2182) ➜ all that so I need to take this with a
- [00:36:24](https://youtu.be/xqRmTx-hBUo?t=2184) ➜ huge grain of salt and now by all means
- [00:36:26](https://youtu.be/xqRmTx-hBUo?t=2186) ➜ an expert at this but if I remember
- [00:36:28](https://youtu.be/xqRmTx-hBUo?t=2188) ➜ correctly you can't verify a contract
- [00:36:30](https://youtu.be/xqRmTx-hBUo?t=2190) ➜ that's been written in Huff right so
- [00:36:32](https://youtu.be/xqRmTx-hBUo?t=2192) ➜ that's one thing to
- [00:36:34](https://youtu.be/xqRmTx-hBUo?t=2194) ➜ definitely think about
- [00:36:36](https://youtu.be/xqRmTx-hBUo?t=2196) ➜ um yeah or does he have anything to say
- [00:36:38](https://youtu.be/xqRmTx-hBUo?t=2198) ➜ oh yeah I'm also not an expert in her
- [00:36:41](https://youtu.be/xqRmTx-hBUo?t=2201) ➜ for a Viper but you know I think Viper
- [00:36:45](https://youtu.be/xqRmTx-hBUo?t=2205) ➜ has some like good security stuff that
- [00:36:47](https://youtu.be/xqRmTx-hBUo?t=2207) ➜ Solarity doesn't have
- [00:36:49](https://youtu.be/xqRmTx-hBUo?t=2209) ➜ and yeah
- [00:36:51](https://youtu.be/xqRmTx-hBUo?t=2211) ➜ I don't know I think in the future we
- [00:36:53](https://youtu.be/xqRmTx-hBUo?t=2213) ➜ will see some protocols being Rewritten
- [00:36:56](https://youtu.be/xqRmTx-hBUo?t=2216) ➜ to Viper hoof but as we've seen with the
- [00:36:59](https://youtu.be/xqRmTx-hBUo?t=2219) ➜ uni swap E4
- [00:37:01](https://youtu.be/xqRmTx-hBUo?t=2221) ➜ Maybe
- [00:37:04](https://youtu.be/xqRmTx-hBUo?t=2224) ➜ I'll see you see a potential
- [00:37:07](https://youtu.be/xqRmTx-hBUo?t=2227) ➜ I'm sorry I just want to say do you see
- [00:37:10](https://youtu.be/xqRmTx-hBUo?t=2230) ➜ a potential issue there with Puffin
- [00:37:12](https://youtu.be/xqRmTx-hBUo?t=2232) ➜ Viper and I mean obviously I mean even
- [00:37:14](https://youtu.be/xqRmTx-hBUo?t=2234) ➜ in in this group here of people who
- [00:37:16](https://youtu.be/xqRmTx-hBUo?t=2236) ➜ those solidity quite well probably if
- [00:37:18](https://youtu.be/xqRmTx-hBUo?t=2238) ➜ it's not not our strongest I see over
- [00:37:21](https://youtu.be/xqRmTx-hBUo?t=2241) ➜ here Huff is awesome in the comments so
- [00:37:22](https://youtu.be/xqRmTx-hBUo?t=2242) ➜ maybe maybe alms over here but uh
- [00:37:25](https://youtu.be/xqRmTx-hBUo?t=2245) ➜ nonetheless you know my point being
- [00:37:26](https://youtu.be/xqRmTx-hBUo?t=2246) ➜ solidity is a little bit easier to to
- [00:37:29](https://youtu.be/xqRmTx-hBUo?t=2249) ➜ code in a little bit easier to audit and
- [00:37:31](https://youtu.be/xqRmTx-hBUo?t=2251) ➜ do you think it would have a bad impact
- [00:37:33](https://youtu.be/xqRmTx-hBUo?t=2253) ➜ in terms of security measures okay
- [00:37:35](https://youtu.be/xqRmTx-hBUo?t=2255) ➜ you're going into huffing and Viper for
- [00:37:38](https://youtu.be/xqRmTx-hBUo?t=2258) ➜ grass optimizations and then you get
- [00:37:39](https://youtu.be/xqRmTx-hBUo?t=2259) ➜ less
- [00:37:40](https://youtu.be/xqRmTx-hBUo?t=2260) ➜ less Auditors actually looking at your
- [00:37:43](https://youtu.be/xqRmTx-hBUo?t=2263) ➜ code
- [00:37:44](https://youtu.be/xqRmTx-hBUo?t=2264) ➜ I mean yeah definitely like I think that
- [00:37:47](https://youtu.be/xqRmTx-hBUo?t=2267) ➜ security will always be the number one
- [00:37:50](https://youtu.be/xqRmTx-hBUo?t=2270) ➜ thing that others will focus on but
- [00:37:54](https://youtu.be/xqRmTx-hBUo?t=2274) ➜ some some travels I think that some
- [00:37:57](https://youtu.be/xqRmTx-hBUo?t=2277) ➜ Goods that have
- [00:37:58](https://youtu.be/xqRmTx-hBUo?t=2278) ➜ good deaf teams I think that can will be
- [00:38:02](https://youtu.be/xqRmTx-hBUo?t=2282) ➜ Rewritten to Viper hoof
- [00:38:07](https://youtu.be/xqRmTx-hBUo?t=2287) ➜ hello good afternoon
- [00:38:10](https://youtu.be/xqRmTx-hBUo?t=2290) ➜ good afternoon
- [00:38:12](https://youtu.be/xqRmTx-hBUo?t=2292) ➜ and good day
- [00:38:15](https://youtu.be/xqRmTx-hBUo?t=2295) ➜ um I have two questions but like I want
- [00:38:17](https://youtu.be/xqRmTx-hBUo?t=2297) ➜ to first start from like thanking you
- [00:38:20](https://youtu.be/xqRmTx-hBUo?t=2300) ➜ Arc because when I started up I used to
- [00:38:22](https://youtu.be/xqRmTx-hBUo?t=2302) ➜ like look at your tweets I'll get
- [00:38:24](https://youtu.be/xqRmTx-hBUo?t=2304) ➜ compared to like because I had a hard
- [00:38:26](https://youtu.be/xqRmTx-hBUo?t=2306) ➜ time understanding solidity so like I'll
- [00:38:28](https://youtu.be/xqRmTx-hBUo?t=2308) ➜ have to like write it on paper and stuff
- [00:38:30](https://youtu.be/xqRmTx-hBUo?t=2310) ➜ like debugging like how
- [00:38:32](https://youtu.be/xqRmTx-hBUo?t=2312) ➜ this is more gas efficient and more
- [00:38:35](https://youtu.be/xqRmTx-hBUo?t=2315) ➜ and like I used to like
- [00:38:38](https://youtu.be/xqRmTx-hBUo?t=2318) ➜ being your tweets to like learn so I
- [00:38:40](https://youtu.be/xqRmTx-hBUo?t=2320) ➜ can't thank you for that your tweets and
- [00:38:43](https://youtu.be/xqRmTx-hBUo?t=2323) ➜ also want to thank them dead because
- [00:38:45](https://youtu.be/xqRmTx-hBUo?t=2325) ➜ like I was he I learned from him the one
- [00:38:47](https://youtu.be/xqRmTx-hBUo?t=2327) ➜ we attack from his Twitter Prince like
- [00:38:49](https://youtu.be/xqRmTx-hBUo?t=2329) ➜ you guys are a huge inspiration for me
- [00:38:51](https://youtu.be/xqRmTx-hBUo?t=2331) ➜ so like my question starts like this
- [00:38:54](https://youtu.be/xqRmTx-hBUo?t=2334) ➜ like
- [00:38:56](https://youtu.be/xqRmTx-hBUo?t=2336) ➜ um based on how gas is going in the
- [00:39:00](https://youtu.be/xqRmTx-hBUo?t=2340) ➜ contest like nobody cares about gas like
- [00:39:03](https://youtu.be/xqRmTx-hBUo?t=2343) ➜ the context even in Charlotte today they
- [00:39:04](https://youtu.be/xqRmTx-hBUo?t=2344) ➜ don't want like
- [00:39:06](https://youtu.be/xqRmTx-hBUo?t=2346) ➜ for the M Watsons to like focus on guys
- [00:39:08](https://youtu.be/xqRmTx-hBUo?t=2348) ➜ they wanted to find me jumps on her it's
- [00:39:10](https://youtu.be/xqRmTx-hBUo?t=2350) ➜ like you think it's better to be a
- [00:39:12](https://youtu.be/xqRmTx-hBUo?t=2352) ➜ private like how passion Visa like a
- [00:39:15](https://youtu.be/xqRmTx-hBUo?t=2355) ➜ kind of private auditor where like
- [00:39:17](https://youtu.be/xqRmTx-hBUo?t=2357) ➜ Harrison
- [00:39:18](https://youtu.be/xqRmTx-hBUo?t=2358) ➜ where you like
- [00:39:20](https://youtu.be/xqRmTx-hBUo?t=2360) ➜ you have to meet protocols and protocols
- [00:39:22](https://youtu.be/xqRmTx-hBUo?t=2362) ➜ to give them your yeah their project
- [00:39:24](https://youtu.be/xqRmTx-hBUo?t=2364) ➜ like their code base so you can like
- [00:39:27](https://youtu.be/xqRmTx-hBUo?t=2367) ➜ you can optimize the amount of money you
- [00:39:28](https://youtu.be/xqRmTx-hBUo?t=2368) ➜ make from gas other than submitting gas
- [00:39:30](https://youtu.be/xqRmTx-hBUo?t=2370) ➜ issues like you waste a lot of time
- [00:39:32](https://youtu.be/xqRmTx-hBUo?t=2372) ➜ Gathering the gas issues like from the
- [00:39:35](https://youtu.be/xqRmTx-hBUo?t=2375) ➜ contest with like let's say like 3000
- [00:39:37](https://youtu.be/xqRmTx-hBUo?t=2377) ➜ lines of code then you waste a lot of
- [00:39:39](https://youtu.be/xqRmTx-hBUo?t=2379) ➜ time and they pay you like a little
- [00:39:40](https://youtu.be/xqRmTx-hBUo?t=2380) ➜ amount of money and they have bought
- [00:39:42](https://youtu.be/xqRmTx-hBUo?t=2382) ➜ swear boss like find everything easily
- [00:39:44](https://youtu.be/xqRmTx-hBUo?t=2384) ➜ so like that's the first question like
- [00:39:46](https://youtu.be/xqRmTx-hBUo?t=2386) ➜ which is better is it like to be hunting
- [00:39:48](https://youtu.be/xqRmTx-hBUo?t=2388) ➜ on contests where they don't care about
- [00:39:50](https://youtu.be/xqRmTx-hBUo?t=2390) ➜ what you're doing and like try to beat
- [00:39:51](https://youtu.be/xqRmTx-hBUo?t=2391) ➜ yourself on Twitter where you can get
- [00:39:53](https://youtu.be/xqRmTx-hBUo?t=2393) ➜ the whole issue
- [00:39:55](https://youtu.be/xqRmTx-hBUo?t=2395) ➜ um the money in a huge like in a higher
- [00:39:58](https://youtu.be/xqRmTx-hBUo?t=2398) ➜ amount and my second question would be
- [00:40:00](https://youtu.be/xqRmTx-hBUo?t=2400) ➜ like
- [00:40:01](https://youtu.be/xqRmTx-hBUo?t=2401) ➜ based on how gas is like the ability
- [00:40:03](https://youtu.be/xqRmTx-hBUo?t=2403) ➜ makes it harder to understand what the
- [00:40:05](https://youtu.be/xqRmTx-hBUo?t=2405) ➜ function does like do you think it's
- [00:40:08](https://youtu.be/xqRmTx-hBUo?t=2408) ➜ better for a protocol to like do a gas
- [00:40:11](https://youtu.be/xqRmTx-hBUo?t=2411) ➜ optimization before
- [00:40:13](https://youtu.be/xqRmTx-hBUo?t=2413) ➜ they do an audit because I think gas gas
- [00:40:16](https://youtu.be/xqRmTx-hBUo?t=2416) ➜ optimizations like bring in bugs after
- [00:40:19](https://youtu.be/xqRmTx-hBUo?t=2419) ➜ like
- [00:40:21](https://youtu.be/xqRmTx-hBUo?t=2421) ➜ after they've been after you like if you
- [00:40:24](https://youtu.be/xqRmTx-hBUo?t=2424) ➜ finish auditing in other gas
- [00:40:25](https://youtu.be/xqRmTx-hBUo?t=2425) ➜ optimizations later like it brings inbox
- [00:40:27](https://youtu.be/xqRmTx-hBUo?t=2427) ➜ and I don't know how to like put the
- [00:40:29](https://youtu.be/xqRmTx-hBUo?t=2429) ➜ question but like which one do you think
- [00:40:31](https://youtu.be/xqRmTx-hBUo?t=2431) ➜ is better like having
- [00:40:33](https://youtu.be/xqRmTx-hBUo?t=2433) ➜ a gas optimization on a code base before
- [00:40:35](https://youtu.be/xqRmTx-hBUo?t=2435) ➜ or after
- [00:40:37](https://youtu.be/xqRmTx-hBUo?t=2437) ➜ um doing this and the high level audit
- [00:40:41](https://youtu.be/xqRmTx-hBUo?t=2441) ➜ it's like that's my question thank you
- [00:40:43](https://youtu.be/xqRmTx-hBUo?t=2443) ➜ oh thanks for the kind words by the way
- [00:40:45](https://youtu.be/xqRmTx-hBUo?t=2445) ➜ and great questions so the first
- [00:40:47](https://youtu.be/xqRmTx-hBUo?t=2447) ➜ question I would say that the problem is
- [00:40:51](https://youtu.be/xqRmTx-hBUo?t=2451) ➜ that code Arena doesn't have a big pool
- [00:40:54](https://youtu.be/xqRmTx-hBUo?t=2454) ➜ for for the gas optimization right but
- [00:40:57](https://youtu.be/xqRmTx-hBUo?t=2457) ➜ still uh the competition there is kind
- [00:41:00](https://youtu.be/xqRmTx-hBUo?t=2460) ➜ of low uh the
- [00:41:02](https://youtu.be/xqRmTx-hBUo?t=2462) ➜ the contest that I did the juice box it
- [00:41:06](https://youtu.be/xqRmTx-hBUo?t=2466) ➜ had only like 11 submissions for guys so
- [00:41:09](https://youtu.be/xqRmTx-hBUo?t=2469) ➜ that's that's quite low and I know a guy
- [00:41:11](https://youtu.be/xqRmTx-hBUo?t=2471) ➜ that only does gas optimizations on on
- [00:41:14](https://youtu.be/xqRmTx-hBUo?t=2474) ➜ code Arena and I think he earned like
- [00:41:17](https://youtu.be/xqRmTx-hBUo?t=2477) ➜ three three thousand dollars already so
- [00:41:20](https://youtu.be/xqRmTx-hBUo?t=2480) ➜ you can still you can still earn
- [00:41:22](https://youtu.be/xqRmTx-hBUo?t=2482) ➜ something and you know obviously the
- [00:41:26](https://youtu.be/xqRmTx-hBUo?t=2486) ➜ protocols will pay you more if you
- [00:41:28](https://youtu.be/xqRmTx-hBUo?t=2488) ➜ actually just perform a like a gas audit
- [00:41:32](https://youtu.be/xqRmTx-hBUo?t=2492) ➜ only
- [00:41:34](https://youtu.be/xqRmTx-hBUo?t=2494) ➜ but it depends you have to deliver Real
- [00:41:36](https://youtu.be/xqRmTx-hBUo?t=2496) ➜ Results right you can just say uncheck
- [00:41:39](https://youtu.be/xqRmTx-hBUo?t=2499) ➜ this block and then charge 38. but you
- [00:41:43](https://youtu.be/xqRmTx-hBUo?t=2503) ➜ know I believe if you do private audits
- [00:41:47](https://youtu.be/xqRmTx-hBUo?t=2507) ➜ you can you can basically do
- [00:41:50](https://youtu.be/xqRmTx-hBUo?t=2510) ➜ you can
- [00:41:51](https://youtu.be/xqRmTx-hBUo?t=2511) ➜ use the gas reports sort of to be unique
- [00:41:54](https://youtu.be/xqRmTx-hBUo?t=2514) ➜ right so many people just offer security
- [00:41:58](https://youtu.be/xqRmTx-hBUo?t=2518) ➜ audits but you can offer both and that
- [00:42:01](https://youtu.be/xqRmTx-hBUo?t=2521) ➜ that will make you unique and then the
- [00:42:04](https://youtu.be/xqRmTx-hBUo?t=2524) ➜ payouts will be bigger
- [00:42:08](https://youtu.be/xqRmTx-hBUo?t=2528) ➜ well what do you think Dad
- [00:42:10](https://youtu.be/xqRmTx-hBUo?t=2530) ➜ so uh yeah so for the first question I
- [00:42:13](https://youtu.be/xqRmTx-hBUo?t=2533) ➜ would say code Arena and Sherlock are
- [00:42:15](https://youtu.be/xqRmTx-hBUo?t=2535) ➜ great for entry-level Auditors right
- [00:42:17](https://youtu.be/xqRmTx-hBUo?t=2537) ➜ they know there's no check uh you don't
- [00:42:19](https://youtu.be/xqRmTx-hBUo?t=2539) ➜ need to be popular you don't need to
- [00:42:21](https://youtu.be/xqRmTx-hBUo?t=2541) ➜ find customers uh you can learn you can
- [00:42:24](https://youtu.be/xqRmTx-hBUo?t=2544) ➜ submit nothing and nothing happens to
- [00:42:26](https://youtu.be/xqRmTx-hBUo?t=2546) ➜ you they take all the liability etc etc
- [00:42:28](https://youtu.be/xqRmTx-hBUo?t=2548) ➜ so code Arena and Sherlock are really
- [00:42:30](https://youtu.be/xqRmTx-hBUo?t=2550) ➜ good for starting out now with that
- [00:42:33](https://youtu.be/xqRmTx-hBUo?t=2553) ➜ being said obviously I think we've
- [00:42:34](https://youtu.be/xqRmTx-hBUo?t=2554) ➜ discussed quite a few of the issues
- [00:42:36](https://youtu.be/xqRmTx-hBUo?t=2556) ➜ there and
- [00:42:37](https://youtu.be/xqRmTx-hBUo?t=2557) ➜ I I think I have not I have not really
- [00:42:40](https://youtu.be/xqRmTx-hBUo?t=2560) ➜ done any private audits so I can't
- [00:42:42](https://youtu.be/xqRmTx-hBUo?t=2562) ➜ really speak to this from experience but
- [00:42:44](https://youtu.be/xqRmTx-hBUo?t=2564) ➜ just by looking at what I'm seeing in my
- [00:42:47](https://youtu.be/xqRmTx-hBUo?t=2567) ➜ DMs because I have had you know projects
- [00:42:49](https://youtu.be/xqRmTx-hBUo?t=2569) ➜ reaching out to me and such
- [00:42:51](https://youtu.be/xqRmTx-hBUo?t=2571) ➜ that it would be a lot more lucrative to
- [00:42:53](https://youtu.be/xqRmTx-hBUo?t=2573) ➜ be in private auditing but as ours said
- [00:42:56](https://youtu.be/xqRmTx-hBUo?t=2576) ➜ you can't you know and just give them an
- [00:42:59](https://youtu.be/xqRmTx-hBUo?t=2579) ➜ unchecked blocks and charge 30 eat you
- [00:43:01](https://youtu.be/xqRmTx-hBUo?t=2581) ➜ need to really deliver results and it's
- [00:43:04](https://youtu.be/xqRmTx-hBUo?t=2584) ➜ going to be a lot more work liabilities
- [00:43:06](https://youtu.be/xqRmTx-hBUo?t=2586) ➜ on you etc etc
- [00:43:07](https://youtu.be/xqRmTx-hBUo?t=2587) ➜ so uh yeah I would say for the first
- [00:43:11](https://youtu.be/xqRmTx-hBUo?t=2591) ➜ question you're better off starting off
- [00:43:12](https://youtu.be/xqRmTx-hBUo?t=2592) ➜ with Katarina in Sherlock use those bugs
- [00:43:17](https://youtu.be/xqRmTx-hBUo?t=2597) ➜ and with everything to get better to get
- [00:43:19](https://youtu.be/xqRmTx-hBUo?t=2599) ➜ on the leaderboard get on Twitter start
- [00:43:21](https://youtu.be/xqRmTx-hBUo?t=2601) ➜ telling people what you found and uh you
- [00:43:25](https://youtu.be/xqRmTx-hBUo?t=2605) ➜ know really genuinely try to help people
- [00:43:27](https://youtu.be/xqRmTx-hBUo?t=2607) ➜ of the other Auditors and these
- [00:43:29](https://youtu.be/xqRmTx-hBUo?t=2609) ➜ protocols will eventually realize that
- [00:43:31](https://youtu.be/xqRmTx-hBUo?t=2611) ➜ and when the time is right they'll reach
- [00:43:32](https://youtu.be/xqRmTx-hBUo?t=2612) ➜ out to you and you can you know start
- [00:43:35](https://youtu.be/xqRmTx-hBUo?t=2615) ➜ doing your private auditing at that
- [00:43:36](https://youtu.be/xqRmTx-hBUo?t=2616) ➜ point that's that's my roadmap
- [00:43:40](https://youtu.be/xqRmTx-hBUo?t=2620) ➜ yeah definitely and though
- [00:43:42](https://youtu.be/xqRmTx-hBUo?t=2622) ➜ the second question I would say that
- [00:43:45](https://youtu.be/xqRmTx-hBUo?t=2625) ➜ first perform a gas audit and then a
- [00:43:49](https://youtu.be/xqRmTx-hBUo?t=2629) ➜ security audit because as we said that
- [00:43:52](https://youtu.be/xqRmTx-hBUo?t=2632) ➜ it may introduce some security risks so
- [00:43:55](https://youtu.be/xqRmTx-hBUo?t=2635) ➜ just it would be better to perform a gas
- [00:43:58](https://youtu.be/xqRmTx-hBUo?t=2638) ➜ audit and then a security audit
- [00:44:02](https://youtu.be/xqRmTx-hBUo?t=2642) ➜ more and more people coming up with gas
- [00:44:04](https://youtu.be/xqRmTx-hBUo?t=2644) ➜ platforms I think right now they truly
- [00:44:08](https://youtu.be/xqRmTx-hBUo?t=2648) ➜ have some some people are working
- [00:44:10](https://youtu.be/xqRmTx-hBUo?t=2650) ➜ together
- [00:44:11](https://youtu.be/xqRmTx-hBUo?t=2651) ➜ on the platform for that and we we're
- [00:44:15](https://youtu.be/xqRmTx-hBUo?t=2655) ➜ now trying to go over this old lady
- [00:44:17](https://youtu.be/xqRmTx-hBUo?t=2657) ➜ doing a code review and it's just so
- [00:44:19](https://youtu.be/xqRmTx-hBUo?t=2659) ➜ hard to audit discuss stuff
- [00:44:22](https://youtu.be/xqRmTx-hBUo?t=2662) ➜ you know and and I was even talking with
- [00:44:24](https://youtu.be/xqRmTx-hBUo?t=2664) ➜ VX most of some of the very complicated
- [00:44:28](https://youtu.be/xqRmTx-hBUo?t=2668) ➜ algorithms have been you know uh
- [00:44:30](https://youtu.be/xqRmTx-hBUo?t=2670) ➜ inspired by C implementations and so on
- [00:44:34](https://youtu.be/xqRmTx-hBUo?t=2674) ➜ but
- [00:44:36](https://youtu.be/xqRmTx-hBUo?t=2676) ➜ it's hard to audit that on the evm you
- [00:44:38](https://youtu.be/xqRmTx-hBUo?t=2678) ➜ know
- [00:44:41](https://youtu.be/xqRmTx-hBUo?t=2681) ➜ yeah definitely because you know not
- [00:44:45](https://youtu.be/xqRmTx-hBUo?t=2685) ➜ everyone knows you and simply right so
- [00:44:48](https://youtu.be/xqRmTx-hBUo?t=2688) ➜ there are many more deaths that just
- [00:44:51](https://youtu.be/xqRmTx-hBUo?t=2691) ➜ download it again it's harder to audit
- [00:44:53](https://youtu.be/xqRmTx-hBUo?t=2693) ➜ then if not enough people know assembly
- [00:44:57](https://youtu.be/xqRmTx-hBUo?t=2697) ➜ what is the coolest gas optimization
- [00:45:02](https://youtu.be/xqRmTx-hBUo?t=2702) ➜ oh
- [00:45:03](https://youtu.be/xqRmTx-hBUo?t=2703) ➜ that's a good one I really like bit
- [00:45:07](https://youtu.be/xqRmTx-hBUo?t=2707) ➜ shifting and all that personally
- [00:45:08](https://youtu.be/xqRmTx-hBUo?t=2708) ➜ shifting really
- [00:45:10](https://youtu.be/xqRmTx-hBUo?t=2710) ➜ a bit shifting anything with bits you
- [00:45:12](https://youtu.be/xqRmTx-hBUo?t=2712) ➜ know um I had one Twitter post where I
- [00:45:15](https://youtu.be/xqRmTx-hBUo?t=2715) ➜ optimized some you know if you had like
- [00:45:17](https://youtu.be/xqRmTx-hBUo?t=2717) ➜ some human eight mapping to a bull right
- [00:45:20](https://youtu.be/xqRmTx-hBUo?t=2720) ➜ you could just instead use it you know
- [00:45:22](https://youtu.be/xqRmTx-hBUo?t=2722) ➜ 256 and each one of those slots would
- [00:45:24](https://youtu.be/xqRmTx-hBUo?t=2724) ➜ represent one of those bullions right
- [00:45:26](https://youtu.be/xqRmTx-hBUo?t=2726) ➜ because you know AIDS Max number is 255.
- [00:45:28](https://youtu.be/xqRmTx-hBUo?t=2728) ➜ so
- [00:45:29](https://youtu.be/xqRmTx-hBUo?t=2729) ➜ um yeah something like that I really
- [00:45:31](https://youtu.be/xqRmTx-hBUo?t=2731) ➜ like those and I really like anything
- [00:45:33](https://youtu.be/xqRmTx-hBUo?t=2733) ➜ that involves math obviously my
- [00:45:35](https://youtu.be/xqRmTx-hBUo?t=2735) ➜ background's in mathematics so anything
- [00:45:37](https://youtu.be/xqRmTx-hBUo?t=2737) ➜ where yeah or that that optimization
- [00:45:39](https://youtu.be/xqRmTx-hBUo?t=2739) ➜ comes in is fun when we use bit shifting
- [00:45:42](https://youtu.be/xqRmTx-hBUo?t=2742) ➜ it's usually for type casting right um
- [00:45:44](https://youtu.be/xqRmTx-hBUo?t=2744) ➜ when trying to convert different types
- [00:45:46](https://youtu.be/xqRmTx-hBUo?t=2746) ➜ right
- [00:45:48](https://youtu.be/xqRmTx-hBUo?t=2748) ➜ this shifting wasn't the best way to say
- [00:45:50](https://youtu.be/xqRmTx-hBUo?t=2750) ➜ I was just saying dealing with bits in
- [00:45:51](https://youtu.be/xqRmTx-hBUo?t=2751) ➜ general okay
- [00:45:53](https://youtu.be/xqRmTx-hBUo?t=2753) ➜ but uh bit shifting this you know
- [00:45:55](https://youtu.be/xqRmTx-hBUo?t=2755) ➜ whenever you want to just shift these
- [00:45:58](https://youtu.be/xqRmTx-hBUo?t=2758) ➜ bits so if you have one bit in your in
- [00:46:00](https://youtu.be/xqRmTx-hBUo?t=2760) ➜ your zero slot and you move it to the to
- [00:46:02](https://youtu.be/xqRmTx-hBUo?t=2762) ➜ the first slot you know that's the same
- [00:46:03](https://youtu.be/xqRmTx-hBUo?t=2763) ➜ thing as multiplying it by two and you
- [00:46:05](https://youtu.be/xqRmTx-hBUo?t=2765) ➜ can do the same thing in the opposite
- [00:46:06](https://youtu.be/xqRmTx-hBUo?t=2766) ➜ direction for dividing for example but
- [00:46:08](https://youtu.be/xqRmTx-hBUo?t=2768) ➜ there's also places where it's not just
- [00:46:10](https://youtu.be/xqRmTx-hBUo?t=2770) ➜ two and you know you have a nice even
- [00:46:13](https://youtu.be/xqRmTx-hBUo?t=2773) ➜ number like a 10 or 100 and you can use
- [00:46:15](https://youtu.be/xqRmTx-hBUo?t=2775) ➜ it for something there potentially not
- [00:46:17](https://youtu.be/xqRmTx-hBUo?t=2777) ➜ always but definitely if you're dealing
- [00:46:19](https://youtu.be/xqRmTx-hBUo?t=2779) ➜ with a multiplier divide by two yeah
- [00:46:20](https://youtu.be/xqRmTx-hBUo?t=2780) ➜ what about you RC what is the coolest
- [00:46:23](https://youtu.be/xqRmTx-hBUo?t=2783) ➜ gas optimization
- [00:46:25](https://youtu.be/xqRmTx-hBUo?t=2785) ➜ dude I don't know to be honest I kind of
- [00:46:28](https://youtu.be/xqRmTx-hBUo?t=2788) ➜ hate bits but you can save a pretty
- [00:46:31](https://youtu.be/xqRmTx-hBUo?t=2791) ➜ amount of get pretty decent amount of
- [00:46:32](https://youtu.be/xqRmTx-hBUo?t=2792) ➜ gas there
- [00:46:33](https://youtu.be/xqRmTx-hBUo?t=2793) ➜ so yeah I don't know
- [00:46:36](https://youtu.be/xqRmTx-hBUo?t=2796) ➜ awesome Bros awesome you know what I
- [00:46:38](https://youtu.be/xqRmTx-hBUo?t=2798) ➜ mean this is really interesting and and
- [00:46:41](https://youtu.be/xqRmTx-hBUo?t=2801) ➜ I've been seeing this smart and smart
- [00:46:43](https://youtu.be/xqRmTx-hBUo?t=2803) ➜ implementation we just had a talk with
- [00:46:45](https://youtu.be/xqRmTx-hBUo?t=2805) ➜ zero wage and we went through you know
- [00:46:47](https://youtu.be/xqRmTx-hBUo?t=2807) ➜ the fine line between readability and
- [00:46:49](https://youtu.be/xqRmTx-hBUo?t=2809) ➜ gas optimization but also gets me a bit
- [00:46:52](https://youtu.be/xqRmTx-hBUo?t=2812) ➜ confusing because we're now walking to
- [00:46:55](https://youtu.be/xqRmTx-hBUo?t=2815) ➜ their shoes now we have stuff like it's
- [00:46:58](https://youtu.be/xqRmTx-hBUo?t=2818) ➜ subscriptions uh so we have different
- [00:47:01](https://youtu.be/xqRmTx-hBUo?t=2821) ➜ ways of you know passing data around
- [00:47:05](https://youtu.be/xqRmTx-hBUo?t=2825) ➜ it seems to me like this gas
- [00:47:07](https://youtu.be/xqRmTx-hBUo?t=2827) ➜ optimization is a really
- [00:47:11](https://youtu.be/xqRmTx-hBUo?t=2831) ➜ momentary trend on the evm you know
- [00:47:19](https://youtu.be/xqRmTx-hBUo?t=2839) ➜ what do you what do you mean by that
- [00:47:21](https://youtu.be/xqRmTx-hBUo?t=2841) ➜ by momentary Trend I mean that right now
- [00:47:24](https://youtu.be/xqRmTx-hBUo?t=2844) ➜ we care a lot about reducing gas because
- [00:47:26](https://youtu.be/xqRmTx-hBUo?t=2846) ➜ the network fees are really expensive
- [00:47:28](https://youtu.be/xqRmTx-hBUo?t=2848) ➜ but now we come in with new layer 2
- [00:47:31](https://youtu.be/xqRmTx-hBUo?t=2851) ➜ Solutions we're coming the ethereum is
- [00:47:34](https://youtu.be/xqRmTx-hBUo?t=2854) ➜ on this road map is walking should
- [00:47:36](https://youtu.be/xqRmTx-hBUo?t=2856) ➜ become cheap at some point in the future
- [00:47:39](https://youtu.be/xqRmTx-hBUo?t=2859) ➜ but ideally we're gonna start using you
- [00:47:42](https://youtu.be/xqRmTx-hBUo?t=2862) ➜ know different networks before so if
- [00:47:45](https://youtu.be/xqRmTx-hBUo?t=2865) ➜ you're not paying that much for the the
- [00:47:47](https://youtu.be/xqRmTx-hBUo?t=2867) ➜ transaction itself maybe doing the
- [00:47:50](https://youtu.be/xqRmTx-hBUo?t=2870) ➜ optimization is not so worth it
- [00:47:54](https://youtu.be/xqRmTx-hBUo?t=2874) ➜ yeah and that's that's nothing new I
- [00:47:56](https://youtu.be/xqRmTx-hBUo?t=2876) ➜ mean even back in
- [00:47:57](https://youtu.be/xqRmTx-hBUo?t=2877) ➜ the 90s and 80s and so forth they had
- [00:47:59](https://youtu.be/xqRmTx-hBUo?t=2879) ➜ optimizations for codes that you know
- [00:48:01](https://youtu.be/xqRmTx-hBUo?t=2881) ➜ today we don't think about optimizing
- [00:48:03](https://youtu.be/xqRmTx-hBUo?t=2883) ➜ you know in python or whatever because
- [00:48:05](https://youtu.be/xqRmTx-hBUo?t=2885) ➜ our Hardware has advanced so so much you
- [00:48:08](https://youtu.be/xqRmTx-hBUo?t=2888) ➜ know uh it's potentially possible I mean
- [00:48:11](https://youtu.be/xqRmTx-hBUo?t=2891) ➜ I wouldn't be surprised but at the same
- [00:48:13](https://youtu.be/xqRmTx-hBUo?t=2893) ➜ time as Arts was saying we only have a
- [00:48:15](https://youtu.be/xqRmTx-hBUo?t=2895) ➜ limited amount of
- [00:48:16](https://youtu.be/xqRmTx-hBUo?t=2896) ➜ computational capacity so unless that
- [00:48:18](https://youtu.be/xqRmTx-hBUo?t=2898) ➜ changes
- [00:48:19](https://youtu.be/xqRmTx-hBUo?t=2899) ➜ I would assume that it's always a
- [00:48:21](https://youtu.be/xqRmTx-hBUo?t=2901) ➜ necessity
- [00:48:23](https://youtu.be/xqRmTx-hBUo?t=2903) ➜ awesome guys you guys have questions
- [00:48:29](https://youtu.be/xqRmTx-hBUo?t=2909) ➜ um okay thank you very much
- [00:48:32](https://youtu.be/xqRmTx-hBUo?t=2912) ➜ thanks guys it's really it has it has
- [00:48:35](https://youtu.be/xqRmTx-hBUo?t=2915) ➜ been really insightful yeah so I really
- [00:48:37](https://youtu.be/xqRmTx-hBUo?t=2917) ➜ enjoyed it I learned a lot thank you
- [00:48:39](https://youtu.be/xqRmTx-hBUo?t=2919) ➜ guys this will be that's why I didn't
- [00:48:41](https://youtu.be/xqRmTx-hBUo?t=2921) ➜ ask any questions because like I was
- [00:48:43](https://youtu.be/xqRmTx-hBUo?t=2923) ➜ just receiving yeah and it's a really
- [00:48:46](https://youtu.be/xqRmTx-hBUo?t=2926) ➜ good I mean a really good guide into how
- [00:48:48](https://youtu.be/xqRmTx-hBUo?t=2928) ➜ to start looking and diving into gas and
- [00:48:50](https://youtu.be/xqRmTx-hBUo?t=2930) ➜ I'm gonna make a really nice Thread
- [00:48:51](https://youtu.be/xqRmTx-hBUo?t=2931) ➜ about this thank you so much guys you
- [00:48:54](https://youtu.be/xqRmTx-hBUo?t=2934) ➜ have any closing thoughts
- [00:48:57](https://youtu.be/xqRmTx-hBUo?t=2937) ➜ no just thank you for listening thank
- [00:48:59](https://youtu.be/xqRmTx-hBUo?t=2939) ➜ you for having us yeah thanks thank you
- [00:49:02](https://youtu.be/xqRmTx-hBUo?t=2942) ➜ very much to that and Miss thanks for
- [00:49:04](https://youtu.be/xqRmTx-hBUo?t=2944) ➜ hosting this and thanks everyone for
- [00:49:06](https://youtu.be/xqRmTx-hBUo?t=2946) ➜ coming thank you so much I hope that you
- [00:49:09](https://youtu.be/xqRmTx-hBUo?t=2949) ➜ learned something we learned a lot
- [00:49:13](https://youtu.be/xqRmTx-hBUo?t=2953) ➜ thank you so much thank you guys

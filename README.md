
# About WayNext

### Overview:

In modern society, effective information plays a very important role in personal development. In the daily face of many decision-making processes, it is inseparable from effective information as a reference. When individuals obtain information from the outside world, they will face problems such as information sources, information aggregation and screening, and information effectiveness. Most of the mainstream information dissemination software on the Internet is distributed from top to bottom, and most collaborative office software cannot meet the needs of most individual users. WayNext product is an open source platform for content (not limited to text) dissemination based on the git structure. Through the method of content by user-generating, it is mainly aimed at young Chinese Internet users (domestic and abroad), so as to achieve information traceability, collaboration, and information condensation functions, which to solve future planning problems such as further education and employment in real life.


### background:

At present, the impact of China's domestic COVID-19 policy on the economy is very significant. Moreover, along with many social problem like the cooling of the real estate industry, the slowdown of economic development, the widening gap between the rich and the poor, the continuously low marriage rate and birth rate, and the unbalanced population structure, the surge in employment pressure and other issues are particularly important and become more difficult for the young generation in China, which proves future planning is particularly important. 

At present, the Internet has improved the efficiency of information flow, but this kind of communication is still based on traditional letter-style communication (whether instant messaging software or post-style software). When people want to get some information, they still can't get the most comprehensive information they want at the fastest speed.


### Existing information access methods:

The ideal purpose is to be able to obtain all the decision-making knowledge based on all the information and complete the theoretically optimal decision.

The current sources of useful information can be divided into the following categories:

1. Single-line peer-to-peer communication: for example, obtaining information through conversations between well-known people, and obtaining distributed information through organizations (such as schools, paid third-party intermediaries, etc.). Such mode information acquisition efficiency is general, and the information content acquisition is relatively passive.

2. Searching for information from multi-user systems: from various forums and Q&A applications, such as Zhihu, Quora, various forums (such as 1point3acres for international students), and even groups of instant messaging software (such as WeChat , QQ group).


### WayNext solutions and features:


##### Problem to be solved:

Dispersion of information content, fragmentation, high coupling, information cocoon room, difficulty in reuse, and high update overhead






##### Target:

1. Make information accumulation easier and more specific

2. Large-scale elimination of distribution difficulties and island effect

3. Changes information flow direction and reconstructs the flow of information

4. Establish appropriate mechanisms to integrate information and its derivatives

5. Reduce repetitive wheel building

In the early stage, WayNext will use github as the content carrier to attract users and create content through groups, own forums, audio and video, etc., gradually transforming from a centralized to a decentralized information system. Then develop a new software ecology.

The core content unit of Waynext is Lib, and the name is taken from library in the field of software development, and also from the word library. See Appendix 3 for the details of Lib.


WayNext can comprehensively improve the efficiency of the entire process, lossless information transfer, high decoupling, open source, traceability, high reuse, influence expansion, and knowledge object-oriented.

##### LIBs life cycle:

generate : create a LIB

Execution: more people use

Feedback: Feedback and modify the LIB

Iteration: Update the LIB to get better




### Running plan:



##### Early Preparations:

Community + Core development

several universities

Complete basic planning and design, obtain initial users, and improve information circulation. Make the main information base and explore reasonable content structure


##### Mid Term:

Community + Activities

higher coverage

Be a good community, expand more users, increase the number of active users to ensure the reliability of content, and try to expand the scope of users. Improve content effectiveness and coverage



##### Future:

app building

Provide more efficient functions for target groups

Use more advanced technology to complete better advanced functions, and provide the best solution to those who need information




### Appendix


##### 1. Information classification

according to the flow of information

by scene

by content

divided by carrier


##### 2. Comparison of old and new methods:

Tradition:

Inquire:

- Identify keywords

- Use search engine query

- Information Integration

- Get whole structured target information

discuss:

- Requires approximate knowledge background

- Sync basic information

- Discuss and draw opinions

- further modifications or updates

Reuse and Collaborate:

- Determine the target

- Extract steps one by one

- try again and reproduce

- Make updates and modifications

- Integration and lots of discussion

- Post

Iterative optimization:

- Lots of queries to get the current SOTA version

- try again and reproduce again

- Make updates and modifications

- Public release to update consensus

WayNext:

Inquire:

- Direct access to the entire structured target information
- Functions such as graph search will be added in the future

discuss:

- Discuss directly in issues and commits
- Valuable discussions will be saved for a long time


Reuse and Collaborate:

- Use fork to get past jobs directly
- Multiple people or organizations can effectively collaborate and edit submissions within the platform

Iterative optimization:
- Mark every progress directly with the release feature
- Quick sync with merge function




##### 3. Basic Definition of LIB


Fundamental contents:

- Goal: LIB should have a goal to answer a question, describe a one-hop path, achieve a goal, etc.
- Background: The existing information and dependencies should be sorted out
- Body of content: The main text that meets the basic requirements of the community, built on the goal
- Practice & Testing: Realized examples, as practical tests. should be gradually enriched

Several ideas that help improve the quality of LIB:

- Higher coverage A higher proportion of the information that can be collected so far

- Appropriate structure Appropriate logical structure. Easy to read and easy to collaborate at the same time

- Direction and planning The future development direction of LIB, which can include issues, goals, progress estimates, etc., which can help collaboration

- Testing and Feedback Test these in practice and get feedback to update them step by step

Format and Form:

- LIB is currently implemented using the GitHub repository. Text is the main content, more appropriate citations are suggested

- Documents are recommended to use markdown for simplicity and ease of editing

- readme.md, as the main content entry, should contain an introduction to the overall content

- Recommended: Edit the project with the obsidian editor, you can use features such as two-way linking
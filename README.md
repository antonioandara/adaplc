# DPLC
open source automation for Cardano and raspberry pi
## Table of Contents
  <ol>
    <li>Problem Statement</li>
    <li>Goals</li>
    <li>Target Demographic</li>
    <li>Action Plan</li>
    <li>Roadmap</li>
    <li>Performance Metrics</li>
    <li>Skills Required</li>
    <li>Budget Breakdown</li>
  </ol>

<!-- PROBLEM STATEMENT -->
## Problem Statement
Currently there are no open source frameworks that allow to deploy and update real world automation projects using the Cardano Network and open source computing platforms like the raspberry pi.

<!-- CLEAR GOALS -->
## Goals 🏆
In order to solve this problem I propose modifying the core of the <a href="https://www.openplcproject.com/">OPENPLC</a> project so it can  connect and read state data from the blockchain and use it for any kind of automation project.

<!-- TARGET DEMOGRAPHIC -->
## Target Demographic 👨‍👩‍👦
  <ol>
    <li>Electronic engineers</li>
    <li>Automation engineers</li>
    <li>hackers, makers</li>
    <li>anyone interested in making blockchain applications that interact with the real world</li>
  </ol>

<!-- ACTION PLAN -->
## Action Plan ✊
First we'll do a comprehensive study of OPENPLC's code and data types to insure compatibility, then we'll set out to remove any extra or unnecessary features in order to make the app as light as possible. Once we are happy with the core of our decentralized PLC (DPLC) we'll add read capability by connecting it to the blockchain using blockfrost's API and reading data from the blockchain, this will allow the system to efectively change it's state by looking only at addresses and balances, from here we will work on reading smart contract data, this way we can load state data directly from the blockchain leveraging the full power of the Cardano Network. At this point we will have everything we need to make an example automation project that can work as a boilerplate for our template. Lastly we will devote ourselves to writing documentation so that everyone can use the app easily

<!-- ROADMAP -->
## Roadmap 📅
I expect this project to be completed in about 100 hours of work spread out over a period of 5/6 weeks, breaking down this into more specifics blocks/taks

0-20 hrs studying and modidying OPENPLC's code turning it into DPLC
0-20 hrs developing backend bridge between the blockchain and DPLC using blockfrost's API, showing of partial results and request for feedback
0-30 hrs adding smart contract capability to the system, showing partial results
0-10 hrs creating and documenting example project
0-10 hrs validating, testing
0-10 hrs going through feedback and making any neccessary modifications, show of final app

the progress of the entire project will be documented and tracked through a github repo youtube videos and blog posts, results will be provided gradually giving updates about the development and asking for feedback, this project is the first step and it will lay the foundation towards creating a full open source stack for automation using Cardano

<!-- PERFORMANCE METRICS -->
## Performance Metrics 📈
The key metric to the success of the project is how well  and to what level we can establish communication with the blockchain.
<ol>
  <li>the ability to check accounts and balances from the DPLC</li>
  <li>the ability to read state data from a smart contract and automate actions based on it</li>
    <li>Active user base is another key metric that we'll be looking at to measure the success of the project</li>
</ol> 
other metrics are related to documentation and the creation of example projects 


<!-- SKILLS REQUIRED -->
## Skills Required 👨‍🎓
<ol>
  <li>understanding of the Cardano Blockchain and how to query information from it</li>
  <li>smart contract development with Plutus</li>
  <li>Ladder logic (for automation scripts)</li>
  <li>programming languages and web development (python, c++, javascript, html, css)</li>
  <li>familiarity with the raspberry pi platform</li>
  <li>understanding and familiarity with automation systems, protocols and standards (PLC, SCADA, Modbus)</li>
</ol>

<!-- BUDGET BREAKDOWN -->
## Budget Breakdown 💰

we expect the project to take about 100 hours to be completed and the only expense is the development fee which is 25$/hour

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- Master of Science in Computer Science, Hansung University 09/2026 - Present
- Korean Language Program, Ajou University, 09/2024 – 07/2026
- Engineer's Degree in Information Security, Ho Chi Minh City University of Technology, 09/2019 – 04/2024 (GPA: 3.09/4.0)

# Work experience

- 07/2023 – 09/2023: VNS Exchange (Vietnam Startup)
  - Core: TypeScript, Solidity, HTML, CSS
  - Technology: ETH, Hardhat, React.js, OpenZeppelin, Tailwind CSS
  - Coded the entire UI for an exchange web platform used for trading the VNSe token
  - Used OpenZeppelin's ERC20 library to create a smart contract for a token
  - Deployed and verified the smart contract on the Ethereum network
  - Used ethers.js to interact with and connect to the smart contract

- 04/2023 – 06/2023: NFT Marketplace (personal project)
  - Core: JavaScript, Solidity, HTML
  - Technology: ETH, MetaMask, Hardhat, React.js, OpenZeppelin
  - Researched and self-learned ETH, Solidity, and OpenZeppelin frameworks
  - Used OpenZeppelin's ERC721 library to create a smart contract for an NFT marketplace
  - Used web3.js and ethers.js to interact with and connect to the smart contract

- 02/2023 – 04/2023: Deploying Configuration and Security Services on Linux
  - Tools: CentOS 7, Windows XP, Windows 7
  - Installed monitoring tools: Cacti, Wireshark, Munin
  - Configured DNS, HTTP, DHCP, and FTP services
  - Installed NFS, VNC, SAMBA, MySQL, and SYSLOG servers
  - Researched and installed RAID

- 10/2022 – 12/2022: Transactions and Transaction Verification Using Smart Contracts
  - Core: JavaScript, Solidity, HTML
  - Technology: ETH, MetaMask, Hardhat, React.js, Tailwind CSS
  - Researched and self-learned ETH and Solidity through YouTube and Google
  - Spent two weeks fixing Web3 connection bugs
  - Delivered a fully automated, secure smart contract using Solidity
  - 3rd place winner, Hutech Got Talent competition, Group A

# Skills

- Solidity: Smart contract development
- Java: Mobile app development
- JavaScript
- C#
- Python (basic)
- Soft skills: English and Korean communication, reading comprehension, teamwork

# Certifications

- 3rd Place Winner, Hutech Got Talent Competition, Group A
- Korean TOPIK 4

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Browser-Automation-Software
Automates web browser to fill in forms, create accounts, etc.
Automates distribution of proxies to customers.

This browser automation software main goal is to help users create multiple Nike accounts in a short period of time. 
It also consists of other functions such as generating large number of random names, addresses, and emails for users to fill in random particulars.

Some of the important libraries used are: Pyppeteer, asyncio, threading, pathlib, colorma, discord, requests, os, and many more.

The software is uses APIs from Nike, Stripe, and SMS providers.

The software is coded mainly in Python.

💻 The software can work with or without proxies input. Proxies allow users to mask their IP address to bypass security.

💻 The command line interface software will give users options to customize how they want their accounts to be created.
💻 Users can also edit the settings nodepad to customize their accounts.
💻 After users specify their requirement, the specified number of browsers will open to start generating accounts.
💻 The process includes identifying various inputs such as email, names, password, and verifying phone numbers.
💻 Browsers will generate accounts in parallel for speed optimization.
💻 Once account has been generated, the software will send webhook notification to the discord webhook link which user has provided.
💻 Task will be completed once the specified number of accounts is generated.


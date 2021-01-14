# reledger: track personal finances
## Problem
Some method of tracking income, expenses and liabilites is vital for any individual who wishes to
improve her finances, keep a budget or just make more informed purchasing decisions. There exists
automatic methods of tracking like Tink, but they are often inaccurate and require frequent manual
intervention, so you might as well record all transactions manually. This can be a tedious and
error-prone proccess though, something that reledger aims to mitigate.

Other personal finance trackers exists, like GNUCash, YNAB, or ledger.
- YNAB is proprietary and requires a paid subscription.
- YNAB and GNUCash are complex applications that do alot of things, and while they should be
considered, they might not be suitable to people who require flexible tools that can interoperate
with other programs.
- ledger is a plain text accounting tool. While this is great for portability of accounting data,
it limits the kind of queries you can make on the data to a set of predefined ones.

reledger aims to solve these problems by:
- Be open source and free of cost
- Use an API that can easily interoperate with other tools.
- Have a minimal set of features, in order to minimize the learning-curve of using the tool.
- Utilize a relational database in order to allow flexibility in the queries that can be made on the
accounting data.

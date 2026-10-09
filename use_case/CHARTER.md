# Project charter

<!--
  Fill this in during TC1, from your Getting to Concreteness worksheet.
  Every week's Session 2 notebook reads this file and stops if it is still the
  template. That is on purpose.
-->

**Department:** Purchasing

**Working title:** <!-- your answer here -->

---

## The problem

**Who has it?** One real role, not a department.

Opportunistic Purchasing

**What are they trying to do?**

Sourcing part numbers in the open market to restock. Identify vendors, send emails, wait for responses, and follow up. 

**How do they handle it today?**

Based on a purchase request, we source for the right vendor that matches our part number condition (New, New Surplus, Factory New) and Quantity. Once identified, we send an RFQ email, wait for the response, and log this into our ERP system.  

**What does that cost — time, money, risk, or relationships?**

Time, but also money: the faster we can get those parts in stock, the better positioned we will be to quote and sell. Customer Service level decreases.

**The problem in one sentence. No solution in it.**

Time consuming sourcing process

---

## Success

**What does the new world look like for that person?**

The person creates a Purchase Request and gets a notification once a Vendor RFQ is received for her/his evaluation.

**How would the firm measure it? Which numbers should move?**

Opportunistic Inventory Increase

---

## The first product

**Your solution in one sentence.**

An autonomous agent that will help us navigate the sourcing process

**Input → Output.** Be specific enough that someone could build it wrong and you
would notice.

| | |
| --- | --- |
| **In** | Part Number, Condition, Quantity |
| **Out** | A vendor RFQ that can be converted into a PO |

---

## Decisions made later

<!--
  Amended as the cohort goes. Keep the reasoning, not just the choice — Week 5
  asks you to defend your architecture against the options you rejected, and
  Week 10's handoff doc is largely this section.
-->

| Week | Decision | Why, and what you rejected |
| --- | --- | --- |
| 3 | Retrieval approach | <!-- TC3 --> |
| 5 | Agent architecture | <!-- TC5 --> |
| 8 | Model | <!-- TC8 --> |

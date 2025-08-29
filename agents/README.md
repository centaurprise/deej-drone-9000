# **Agent system instruction templates**

## Contents:
Stub system instructions code for setting up agents that pull in information from across the org (using Slack, Teams, email, or ticketing systems) and feed it to Product.
These aren't "batteries-included," more like ideas to help you get started if you're trying to figure out where to plug agents into your own system.

## How to use: 
Set the full `Agent` code block as the definition for an OpenAI or gtp-oss agent, or use just the system instructions part (after `instructions`) as inputs for your agent of choice. 
These tasks are reasonably well-defined, so mini models _should_ do pretty well.
You may want to test bigger models first and work your way down, especially if your product gaps, customers, and/or customer data are particularly non-standard or scattered across sources / formats / products. 
The more work the model needs to do, the worse a little model is going to perform, and the more value you’ll get from pre-work cleaning up the feed you send it.

---

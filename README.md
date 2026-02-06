# ChillPill
Agentic AI Solution for Singapore's Urban Heat Living Issue, targeted towards HDB resident's air-con usage.

## Problem Statement
Singapore is getting hotter—not only because of climate change, but because of how we cool our homes. In high-density housing like HDBs, thousands of air-conditioners run daily. Each unit improves comfort individually, but together they dump large amounts of heat back into the environment, creating a feedback loop: hotter surroundings drive more cooling, which generates even more heat. 

Most solutions focus on individual efficiency but ignore the cumulative impact of many systems operating together. **Residents may not realize that even a one-degree change in air-con setting has a significant cumulative impact on the surrounding environment.**

## Our Solution
The Solution propose a collective approach using two AI agents accessed by users through an Application. A Resident AI learns each household’s routines and comfort needs, adjusting cooling in real time. A Block AI oversees the entire HDB block, assessing shared heat impact and coordinating adjustments. **Instead of enforcing limits, the agents negotiate—balancing comfort and sustainability—turning cooling into a shared, intelligent system.**

**Resident AI**
Resident AI translates personal habits and real-time weather into a cooling recommendation. Instead of setting temperatures blindly, residents see a suggested balance between comfort and efficiency, along with indicators for potential savings and block-level coordination. “Start Negotiation” action makes sustainability invites the resident to participate rather than comply, and framing cooling as a shared decision rather than a private one

**HDB AI**
The HDB AI helps calculate the cumulative impact of all units in the HDB block. The Block Heat Index reveals overall thermal stress, while “Your Contribution” makes each household’s role visible. When conditions are suboptimal, the Block AI proposes small, time-bound adjustments. Residents can accept or negotiate, reinforcing the idea that collective comfort and environmental responsibility are achieved through informed, voluntary coordination.

## Tech Stack
- Front-End: TypeScript
- API Calls: Vercel AI SDK, Singapore NEA Weather API
- Database: SQLLite
- Workflow: Vercel AI SDK, LangChain


# Tech stack for building a Redis Server
Date: 2022-08-06
## Status
Completed
## Context
Currently building out a Redis Server. It's important to choose what tech stack to use and our rationale behind it.
## Decision
We'll be using JavaScript (Node.js)
## Consequences
### Pros:
-Its popularity means there will be plenty of documentation to lean on.  
-Our team's familiarity with JavaScript will enable us to avoid the starting roadblock of learning another language.
### Cons:
-A reliance upon third-party packages can result in various issues.  
-CPU-intensive operations can cause server performance to drop.
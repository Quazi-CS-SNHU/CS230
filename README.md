Draw It or Lose It – Software Design README
Project Overview:

The client for this project was The Gaming Room, a game development company that originally released Draw It or Lose It as an Android-based application. Their goal was to expand the game into a web-based, cross-platform solution that could support desktop and mobile users across different operating systems. The core requirements included preserving the team-based gameplay experience, supporting multiple concurrent users, enforcing unique identifiers for games and teams, and ensuring the system could scale securely in a distributed environment.

What Went Well in the Design Documentation:

One area that went particularly well was the analysis of system architecture and platform constraints. Clearly identifying how a centralized game service could support multiple client platforms helped drive consistent design decisions throughout the document. The use of object-oriented principles, such as encapsulation, inheritance, and the Singleton pattern, was also well documented and closely aligned with the client’s requirement that only one authoritative game instance exist in memory at any time.

Value of the Design Process:

Working through a formal design document before focusing on code was extremely helpful. It forced me to think critically about architectural decisions—such as operating platform selection, memory management, and distributed system communication—before implementation. This upfront planning reduced ambiguity during development and made the code structure more logical, consistent, and easier to maintain.

Areas for Improvement:

If I were to revise one part of the work, I would focus on expanding the early visualization of system architecture, such as adding a clearer logical or physical topology diagram. Improving this area would provide an even stronger high-level view of how components communicate and depend on one another, which would be valuable both for developers and non-technical stakeholders.

Interpreting and Applying User Needs:

User needs were interpreted by closely analyzing the client’s constraints and translating them into technical requirements. For example, the need for cross-platform access led to a web-based client architecture, while the requirement for unique game and team names influenced the use of centralized control and structured data management. Considering user needs is critical in software design because the success of the application depends on usability, performance, and reliability from the user’s perspective, not just technical correctness.

Software Design Approach and Future Strategies:

The software design approach focused on modularity, scalability, and clear separation of concerns. Techniques such as client-server architecture, object-oriented design, and early constraint analysis helped ensure the solution could evolve over time. In future projects, I would continue using structured design documents, UML modeling, and platform comparison evaluations to guide architectural decisions. These strategies help minimize rework, manage complexity, and ensure the software meets both technical and user-driven requirements.

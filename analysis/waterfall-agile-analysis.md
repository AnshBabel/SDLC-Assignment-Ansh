# Smart-Attend SDLC Analysis

## Project Scenario
The Smart-Attend mobile application is designed to automatically mark student attendance using geo-fencing technology. When a student enters the classroom location, their attendance is recorded.

Halfway through development, the university Dean introduced a new requirement: biometric Face ID verification to prevent proxy attendance.

---

## Task 1 – Waterfall Failure Analysis

The Waterfall model is a traditional software development methodology where development flows sequentially through phases like requirement gathering, design, development, testing, and deployment.

### 1. Rigidity
The Waterfall model is rigid because once development begins, it is very difficult to go back and change requirements. Introducing biometric Face ID after development has started would require redesigning many system components.

### 2. Cost of Change
In the Waterfall model, the system design is treated as a complete blueprint. Adding biometric verification would require major changes to authentication systems, camera integration, and security modules. This would increase cost and development time.

### 3. Delayed Testing
Testing in the Waterfall model usually happens at the end of development. If Face ID integration causes compatibility issues or performance problems, they would only be discovered late in the process, delaying the project.

---

## Task 2 – Agile Scrum Solution

To handle changing requirements more effectively, the development team can switch to the Scrum framework.

### Sprint 1 – Minimum Viable Product
The first sprint focuses on building the core functionality of the application:

- Basic mobile user interface
- Student login system
- Geo-fencing attendance detection
- Teacher attendance dashboard
- Notification system

### Sprint 2 – Feature Update
The second sprint integrates the new biometric requirement:

- Face ID verification
- Improved attendance security
- Enhanced reporting dashboard

Using Agile Scrum allows the team to adapt quickly to new requirements and deliver improvements in short development cycles.
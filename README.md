![Logo](./public/FFFFFF-1.png)
# Slooze take home challenge!!
**ROLE:** **Software Engineer - Backend**

## Question:

Design and implement the back-end for role-based food ordering web application where users (Admins, Managers, and Members) can perform specific functions—such as viewing restaurants, placing or canceling orders, and managing carts, payment methods—based on their assigned role.

**Assume**: Mock restaurants & menu items onto your app

**Extension**: Implement a relational access model that restricts users to operate only within their assigned country (India or America).

### 🎯 Feature Breakdown & Role-Based Access
| **Feature**                      | **Admin** | **Manager** | **Member** |
|----------------------------------|----------|------------|------------|
| View restaurants & menu items   | ✅       | ✅         | ✅         |
| Create an order (add food items)| ✅       | ✅         | ✅         |
| Checkout & pay                  | ✅       | ✅         | ❌         |
| Cancel an order                 | ✅       | ✅         | ❌         |
| Add / Modify payment methods    | ✅       | ❌         | ❌         |


### Tech Stack:
- **Backend**: NestJS · GraphQL · Prisma
- **Auth**: Role-based access control (RBAC) · Bonus: Re-BAC
---

## Reference:

Refer to the pdf attached in the repository for more details on the problem statement

## 📤 Submission
- Upload your code to GitHub or share as a CodeSandbox/StackBlitz link
- Include instructions to run the app locally (e.g., npm install && npm run dev)
- (Optional) Deploy and share a live link using Vercel, Netlify, etc.

## Connect with Us:

Reach out to **[interview@slooze.xyz](mailto:interview@slooze.xyz)** to submit your solutions or if you may have any questions related to the challenege

## © Copyright Notice

**© Slooze. All Rights Reserved.**

Please do not share or distribute this material outside the intended evaluation process.  
For queries, contact us !!

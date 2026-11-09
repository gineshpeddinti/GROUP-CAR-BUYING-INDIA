# 🚗 GroupDrive – Buy Together. Drive a Better Deal.

**GroupDrive** is a group car-buying platform that helps people get better car deals by combining buyer demand. Instead of negotiating individually with dealerships, buyers interested in the same car can join a group, collectively request competitive quotations from multiple dealers, compare offers, and choose the best deal.

The platform connects car buyers and dealerships through a transparent, technology-driven group purchasing experience.

---

## 🌟 Project Overview

Buying a car is a major financial decision. Individual buyers often have limited negotiating power and may struggle to compare dealership offers.

GroupDrive addresses this problem by bringing together multiple potential buyers interested in the same car model within a city.

When a buyer group reaches its target, the platform facilitates quotation requests to eligible dealerships. Dealers submit competitive offers, and buyers can compare pricing and make independent purchasing decisions.

**Our Vision:** Make car buying more transparent, collaborative, and affordable.

---

## ✨ Key Features

### 👤 Buyer Features

- Secure user registration and authentication.
- Browse cars from different manufacturers.
- Search and filter cars by brand, model, budget, fuel type and transmission.
- Create or join existing car-buying groups.
- Track group participation and progress.
- Invite friends and other interested buyers.
- Compare dealership quotations.
- View transparent on-road price breakdowns.
- Save preferred cars and dealership offers.
- Receive notifications about group activities and new offers.

### 🤝 Group Buying System

- Create groups based on car model, variant and location.
- Join existing buyer communities.
- Track verified participant counts.
- Configurable group targets and deadlines.
- Shareable group invitation links.
- Automated group lifecycle management.
- Group-based dealership quotation requests.

### 🏢 Dealer Features

- Dedicated dealership dashboard.
- Dealer registration and verification.
- Manage dealership profiles and service locations.
- Receive eligible group quotation requests.
- Submit competitive price quotations.
- Update and manage offers.
- Track customer inquiries.
- Monitor dealership performance.

### 📊 Offer Comparison

Compare multiple dealership offers using:

- Ex-showroom price.
- Registration and road tax.
- Insurance.
- Dealer discounts.
- Manufacturer discounts.
- Accessories and additional charges.
- Estimated on-road price.
- Expected delivery timeline.
- Offer validity and conditions.

### 🛡️ Admin Features

- Manage buyers and dealerships.
- Verify dealership accounts.
- Manage car brands, models and variants.
- Monitor buyer groups.
- Manage quotation requests and offers.
- Review suspicious activities.
- Manage platform settings.
- View platform analytics and activity logs.

---

## 🔄 How GroupDrive Works

1. **Discover:** Buyers browse cars and select their preferred model.
2. **Create or Join:** Buyers create a new purchasing group or join an existing one.
3. **Build Demand:** Interested buyers come together to reach the group target.
4. **Request Quotes:** The platform connects qualified groups with eligible dealerships.
5. **Receive Offers:** Dealerships submit competitive quotations.
6. **Compare Deals:** Buyers compare transparent pricing and dealership offers.
7. **Choose Independently:** Each buyer decides whether to proceed with a dealership.

> **Note:** Group participation does not guarantee a discount or require a purchase. Every buyer makes their own final purchasing decision.

---

## 🛠️ Tech Stack

### Frontend

| Technology | Purpose |
|---|---|
| React.js | Building user interfaces |
| TypeScript | Type safety |
| Vite | Frontend development and build |
| Tailwind CSS | Styling and responsive design |
| shadcn/ui | Reusable UI components |
| Lucide React | Icons |
| React Router | Navigation |
| TanStack Query | API data management |
| React Hook Form | Form handling |
| Zod | Input validation |
| Recharts | Data visualization |

### Backend

| Technology | Purpose |
|---|---|
| Node.js | JavaScript runtime |
| Express.js | Backend framework |
| TypeScript | Type safety |
| REST API | Client-server communication |
| Prisma ORM | Database management |
| JWT / Secure Cookies | Authentication |
| Zod | Request validation |

### Database

- **PostgreSQL** – Relational database for storing users, cars, buyer groups, dealerships and quotations.

### Development & Testing Tools

- Git & GitHub
- Docker & Docker Compose
- Vitest
- Supertest
- Swagger / OpenAPI
- Visual Studio Code

---

## 🏗️ System Architecture

```text
                    GROUPDRIVE
                        |
          +-------------+-------------+
          |             |             |
        BUYER         DEALER         ADMIN
          |             |             |
          +-------------+-------------+
                        |
                 REACT FRONTEND
                        |
                   REST APIs
                        |
                 EXPRESS BACKEND
                        |
          +-------------+-------------+
          |             |             |
       AUTH MODULE   GROUP MODULE   DEALER MODULE
          |             |             |
          +-------------+-------------+
                        |
                    PRISMA ORM
                        |
                   POSTGRESQL

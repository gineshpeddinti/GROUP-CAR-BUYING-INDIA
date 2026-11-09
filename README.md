# 🚗 GroupDrive – Buy Together. Drive a Better Deal.

**GroupDrive** is a group car-buying platform that helps people get better car deals by combining buyer demand. Instead of negotiating individually with dealerships, buyers interested in the same car can join a group, collectively request quotations from multiple dealers, compare offers, and choose the best deal.

The platform connects car buyers and dealerships through a transparent and collaborative purchasing experience.

---

## 🌟 Project Overview

Buying a car is a major financial decision. Individual buyers often have limited negotiating power and may find it difficult to compare prices and offers from different dealerships.

GroupDrive addresses this problem by bringing together multiple potential buyers interested in purchasing the same car within a particular location.

When a buyer group reaches its target, the platform allows administrators to send quotation requests to eligible dealerships. Dealers can submit their offers, and buyers can compare the available deals before making their own purchasing decisions.

**Our Vision:** Make car buying more transparent, collaborative, and affordable.

---

## ✨ Key Features

### 👤 Buyer Module

- Secure user registration and login.
- Browse cars from different manufacturers.
- Create new car-buying groups.
- Join existing groups based on car preferences and location.
- Track group progress and participant count.
- View group details and car information.
- Compare dealership quotations.
- Shortlist preferred offers.
- Decline unwanted offers.
- Select a preferred dealership offer.
- Request dealer contact with explicit consent.

### 🤝 Group Buying System

- Create groups based on car models, variants and locations.
- Join existing buyer groups.
- Configurable group participant targets.
- Track active group members.
- Prevent duplicate group memberships.
- Atomic group joining to prevent groups from exceeding their participant limit.
- Group-based dealership quotation requests.
- Track the progress of buyer groups.

### 🏢 Dealer Module

- Dealer registration and authentication.
- Dealer verification status.
- Dedicated dealer dashboard.
- View incoming quotation requests.
- Access relevant group and vehicle information.
- Submit dealership offers.
- Manage submitted quotations.
- Support verified and pending dealership accounts.

### 📊 Offer Comparison

Buyers can compare dealership offers based on:

- Ex-showroom price.
- Registration charges.
- Insurance.
- Dealer discounts.
- Manufacturer discounts.
- Additional charges.
- Estimated on-road price.
- Offer details and conditions.

### 🛡️ Admin Module

- Admin authentication.
- Manage platform activities.
- Monitor buyer groups.
- Send quotation requests to eligible dealerships.
- Manage dealer verification.
- Review dealership participation.
- Maintain platform activity records.
- Track important administrative actions through audit logs.

---

## 🔄 How GroupDrive Works

1. **Discover:** Buyers browse available cars and select their preferred model.
2. **Create a Group:** A buyer creates a group with a selected car, location and participant target.
3. **Join a Group:** Other interested buyers join the same group.
4. **Reach the Target:** The group progresses as eligible buyers join.
5. **Request Quotations:** The administrator sends quotation requests to eligible dealerships.
6. **Receive Offers:** Dealerships submit their price quotations.
7. **Compare Offers:** Buyers compare available dealership offers.
8. **Make a Decision:** Buyers can shortlist, decline, select an offer or request dealer contact with consent.

> **Note:** Joining a group does not guarantee a discount or require a buyer to purchase a vehicle. Every buyer makes their own final decision.

---

## 🛠️ Technology Stack

### Frontend

| Technology | Purpose |
|---|---|
| React.js | Building user interfaces |
| JavaScript | Application logic |
| Vite | Frontend development and build tool |
| CSS | Styling and responsive layouts |

### Backend

| Technology | Purpose |
|---|---|
| Node.js | JavaScript runtime |
| Express.js | Backend framework and REST API |
| JavaScript | Server-side application logic |
| Mongoose | MongoDB object data modeling |
| JWT | User authentication |
| bcrypt | Password hashing |
| Express Rate Limit | API request rate limiting |

### Database

| Technology | Purpose |
|---|---|
| MongoDB | NoSQL database |
| Mongoose | Database models and operations |

### Development & Testing Tools

- Git and GitHub
- Visual Studio Code
- npm
- MongoDB Atlas
- In-memory MongoDB for automated testing

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
                    REST API CALLS
                         |
                   EXPRESS SERVER
                         |
            +------------+------------+
            |            |            |
       AUTH MODULE   GROUP MODULE   OFFER MODULE
            |            |            |
            +------------+------------+
                         |
                     MONGOOSE
                         |
                      MONGODB

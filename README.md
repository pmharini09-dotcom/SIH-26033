# Smart India Hackathon Workshop
# Date:22/11/2026
## Reference Number:26017947
## Name:Harini P

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution

### 1. Detailed explanation of the proposed solution

My project is called BulkChain. It is a B2B digital marketplace designed for bulk buyers such as college hostels, school meal programs, hotels, and other institutions

My idea is simple: FPO -> Direct Bulk Ordering -> Optimized Delivery -> Hostel. This reduces dependency on unnecessary intermediaries

FPO means Farmer Producer Organisation. It is many small farmers joining together as one big seller. One farmer has only 10kg, but 50 farmers together have 500kg, so they can sell to a hostel.

How my solution works:

1. FPO uploads stock: FPO from Pattukkottai uploads in app, for example "500kg rice available".
2. Hostel orders: Hostel orders in app, for example "Need 200kg rice every Monday". They take subscription, not daily order.
3. Blockchain price saving: Every price update is recorded as a new blockchain transaction. Previous price records remain unchanged and can be verified.
4. Delivery and payment: A delivery partner picks up products from the FPO and delivers them to the hostel. Payment is processed through an integrated payment gateway after delivery confirmation.

I also added AI demand forecasting. My AI will check hostel menu, school strength, festival season and tell FPO before: "Next week hostels in Thanjavur will need 800kg rice". So FPO can plan harvest.

### 2. How it addresses the problem

- Once saved, the previous price record cannot be edited. Any price update is stored as a new blockchain record.
- Farmer price is normally hidden. I made it open with Blockchain, so no cheating.
- FPO gets fixed income from hostel subscription, not waiting for middleman.
- Hostel also saves money because they buy direct from FPO.

### 3. Innovation and uniqueness of the solution

- I used Blockchain for price transparency. Most other students made only normal marketplace. I added Blockchain so price cannot be changed.
- I focused only on B2B, not B2C. One hostel means 500 students in one order. It is easy to deliver.
- I  used blockchain to maintain transparent order records and an integrated payment gateway to process payments after delivery confirmation
- I focused on FPO, not single farmer. Single farmer cannot give 500kg, but FPO can because 50 farmers combine.
- My AI is for institutions, not for normal people. It predicts hostel and school demand.

## Technical Approach

### Technologies used

- Frontend: React.js for website, simple and easy for FPO and Hostel to use
- Backend: Node.js + Express.js for API and order handling
- Database: MongoDB for orders, FPO stock, hostel details
- Blockchain: Polygon for saving price, low cost and fast
- Smart Contract: Solidity for recording order details and delivery confirmation on blockchain.
- AI: Python for demand forecasting, checks hostel menu and past orders
- Payment: UPI through Razorpay, direct to FPO

### Architecture / Workflow

1. FPO Login -> Uploads stock (500kg rice) -> Price saved in Blockchain
2. Hostel Login -> Sees FPO near them -> Orders weekly subscription
3. Hostel places an order and makes payment through the integrated payment gateway.
4. Van picks up from FPO -> Delivers to hostel -> Hostel confirms
5. After hostel delivery confirmation, the payment gateway processes the payment to the FPO through UPI.
6. AI checks next week demand and sends alert to FPO

### Technical implementation details

- FPO and Hostel have separate login. FPO can only upload, Hostel can only order.
- Every price change is saved as a new block, old price cannot be edited.
- QR code is generated for every order, hostel scans to see farmer price.
- AI model uses past 3 months hostel orders + festival calendar to predict.

  ![BulkChain Flowchart](flowchart.png)

## Feasibility and Viability

**Analysis of Feasibility:**
BulkChain is highly feasible because FPOs and Hostels already exist. We only need to connect them through a simple app. Blockchain on Polygon is low cost and fast. Payment via UPI is already used by everyone.

**Potential Challenges and Risks:**
1. FPO farmers may find the app difficult to use.
2. Internet connectivity may be slow in rural areas.
3. Delivery van may get delayed.

**Strategies to Overcome Challenges:**
1. Simple app in Tamil and English with voice support and large buttons.
2. Lightweight app that works with low internet and offline view.
3. GPS tracking for van and penalty in Smart Contract if delivery is late.



## Impact and Benefits

*Impact on Target Audience:**

 - FPO farmers can receive better prices by reducing intermediaries.
- Hostels can purchase fresh produce at competitive prices through direct sourcing.

**Benefits of the Solution:**
- Social: Farmers get fair income and better livelihood.
- Economic: No middlemen, so both farmers and hostels save money.
- Environmental: AI predicts demand correctly, so food waste is reduced.

## Research and References
1. Farmer Producer Organisation, Govt of India - https://agricoop.gov.in
2. NABARD - FPO Support - https://www.nabard.org
3. Polygon Blockchain Documentation - https://polygon.technology
4. UPI Payment, NPCI - https://www.npci.org.in
5. Smart India Hackathon - https://www.sih.gov.in

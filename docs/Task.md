TODO list with rules and descriptions.

**General Recommendations on Style and Interface**

**Color Scheme:** Use a neutral light background (shades of white or light gray), contrasting accent colors for buttons (e.g., vibrant blue or purple), and calm pastel tones for block backgrounds like in index.html.

**Fonts:** like in index.html

**Icons and Images:** Simple, clear, preferably in vector format. Place them next to the corresponding headings or functions like in  index.html.

**Buttons:** all take from index.html

**Margins and Grid:** Use a comfortable grid (12 columns), maintain padding and margins for spaciousness. Leave approximately 20-40px of vertical space between blocks.

**User Friendly:** Minimal unnecessary text, use concise and clear headings, tooltips on hover, and a clear visual hierarchy.

---

**Project Structure**

**File Structure Prioritizing Development and Easy Navigation:** Start with access forms (login, registration), then the main hub, followed by profile and advanced features.

```
project/
│
├─ index.html               // Welcome Page
├─ login.html               // Login
├─ register.html            // Registration
├─ recover-password.html    // Password Recovery
│
├─ main.html                // Main Hub
├─ user-dashboard.html      // User Dashboard
├─ marketplace.html         // Marketplace for Upgrades
├─ ranking-system.html      // Ranks
├─ account-levels.html      // Account Levels, Leaderboard
├─ payouts.html             // Payout Structure
├─ partner-program.html     // Partner Program
├─ additional-features.html // Additional Features: Insurance, Geography, NFT
├─ investor-example.html    // Investor Example
├─ income-sources.html      // Income Sources
├─ conclusion.html          // Conclusion
│
├─ about-us.html            // About the Company
├─ faq.html                 // FAQ
├─ contact-support.html     // Support
├─ roadmap.html             // Roadmap
├─ profit-calculator.html   // Profit Calculator
├─ international.html       // International Expansion
│
├─ purchase-equipment.html  // New Layout for Purchasing Drones and Upgrades
├─ transactions.html        // Transaction History, Balance Management
```

---

**Detailed Description of Slides and Elements**

### **index.html (1 Slide)**

**Slide 1: Welcome Page**
- **Heading (Large, Centered):** "Welcome to Pseglavius Drones Ltd."
  - **Style:** Based on basic styles, sliders + bold, 32px, dark gray (#333)
- **Subheading:** "Investing in Autonomous Drone Fleets — The Future of Logistics"
  - **Style:** Based on basic styles, sliders + 18px, regular, #555
- **Buttons:**
  - **"Login"** (links to login.html)
  - **"Register"** (links to register.html)
  - **Button Style:** Background #5569FF, white text, semi-bold font, 16px
- **Logo Icon (logo.png):** Top left corner, size ~50px
- **Layout:** Logo in the top left corner, heading and subheading centered on the slide, buttons below the heading

---

### **login.html (1 Slide)**

**Slide 1: Login**
- **Heading:** "Account Login" (centered, 24px, #333)
- **Input Fields:** Email/Username, Password
  - **Labels:** Small 14px font above the fields
- **Button:** "Login" – below the fields, ~200px wide, centered block
- **Link:** "Forgot Password?" – small font (14px), below the button, blue color
- **Form Style:** Fields with soft shadows, rounded corners

---

### **register.html (2 Slides)**

**Slide 1: Registration Data**
- **Heading:** "Create an Account" (24px, #333, centered)
- **Fields:** Email, Username, Password, Confirm Password
  - **Labels:** Short, 14px
- **Button:** "Register" – below the fields
- **Link:** "Already have an account? Login" (links to login.html) – below the button

**Slide 2: Terms and Conditions**
- **Text:** Rules text (14px, #555) in a scrollable block
- **Checkbox:** "I agree to the terms" – at the bottom
- **Button:** "Confirm" – activated after checking the box

---

### **recover-password.html (1 Slide)**

**Slide 1: Password Recovery**
- **Heading:** "Password Recovery" (24px, #333)
- **Input Field:** Email
- **Button:** "Send Instructions"
- **Link:** "Return to Login" – below the button

---

### **main.html (3 Slides)**

**Slide 1: Main Hub**
- **Logo:** Top left corner
- **Menu:** Top section with icons linking to dashboard, marketplace, etc.
- **Large Heading:** "Main Dashboard" (24px, #333)
- **Icon Cards:** Marketplace, Ranking, Partner Program, Additional Features
  - **Each Icon:** ~64px with 1-2 sentence description below
  - **Layout:** 2x2 grid
- **Banner:** News banner (banner-improvements.png) at the bottom of the slide

**Slide 2: Equipment and Upgrades**
- **Heading:** "Your Upgrades" (20px, #333)
- **Content:** Horizontal slider with upgrade icons (battery-upgrade.png, propellers.png)
  - **Description:** Short text below each icon (14px, #555) describing the upgrade
- **Button:** "Go to Marketplace" at the end of the slide

**Slide 3: NFT and Geolocation**
- **NFT Icon (nft-icon.png):** Left side
- **Text:** (14-16px) on the right about the benefits of owning NFTs
- **Map (map.png):** Below with text about selecting areas for income optimization
- **Buttons:**
  - "Learn More about Features" (links to additional-features.html)
  - "View Investor Example" (links to investor-example.html)

---

### **user-dashboard.html (2 Slides)**

**Slide 1: User Status**
- **Heading:** "Hello, [Name]" (24px, #333)
- **Status Cards:** Number of drones, Account level, Current rank, Daily income
  - **Each Card:** Icon (dashboard-icon.png), large numbers (20px), label (14px)
- **Infographic:** Small pie chart of income

**Slide 2: Statistics and Activity**
- **Charts:** Diagrams or line graphs (axes labels in small font)
- **Buttons:**
  - "Upgrade Drones" (links to marketplace.html)
  - "View Payouts" (links to payouts.html)

---

### **marketplace.html (2 Slides)**

**Slide 1: Upgrades Store**
- **Icons:** Batteries, propellers in a grid
  - **Each Upgrade:** Price tag and brief description below
- **Button:** "Buy" under each upgrade
- **Filters:** List, grid, sort by price

**Slide 2: Shopping Cart**
- **List:** Selected upgrades with "+" and "-" buttons to adjust quantity
- **Button:** "Proceed to Purchase"

---

### **ranking-system.html (1 Slide)**

**Slide 1: Ranks**
- **Table of Ranks:** Basic, Silver, Gold, Platinum
- **Description:** "The more flight hours, the lower the commission."
- **Progress Indicator:** Progress bar towards the next rank

---

### **account-levels.html (2 Slides)**

**Slide 1: Account Levels**
- **Level Ladder:** Levels with rewards, prize icons
- **Text:** "Invite partners to level up and receive bonuses."

**Slide 2: Leaderboard**
- **Table:** Top accounts (name, level, number of invites)
- **Icon:** "Star" for top positions

---

### **payouts.html (2 Slides)**

**Slide 1: Payout Structure**
- **Table:** Levels, rates, coefficients
- **Text:** Brief explanation of the impact of ranks and upgrades

**Slide 2: Dynamic Calculator**
- **Link:** To profit-calculator.html
- **Example:** Shows changes in final income based on different parameters

---

### **partner-program.html (2 Slides)**

**Slide 1: Partners and Referrals**
- **Diagram:** Referral levels (icons, arrows)
- **Table:** Percentages for each level

**Slide 2: Applying Bonuses**
- **Description:** "Use bonuses for upgrades or withdrawals."
- **Buttons:**
  - "Marketplace"
  - "Withdraw Funds"

---

### **additional-features.html (3 Slides)**

**Slide 1: Maintenance and Insurance**
- **Icons:** Drones, plan prices
- **Text:** Benefits of insurance

**Slide 2: Geography**
- **Map:** Highlighting city center and suburbs
- **Text:** "+50% income in the center"

**Slide 3: NFT**
- **NFT Icon:**
- **Text:** About liquidity and resale

---

### **investor-example.html (1 Slide)**

**Slide 1: Investor Example**
- **Narrative:** "At level 7 with upgrades, you earn more X USDT/year."
- **Graphic Comparison:** Income without upgrades vs. with upgrades

---

### **income-sources.html (3 Slides)**

**Slide 1: Overview**
- **Icons:** Rental, delivery, advertising
- **Brief Explanations**

**Slide 2: Rental and Commission**
- **Text:** Income formula
- **Simple Graph:** Income dependence on number of orders

**Slide 3: Advertising**
- **Image:** Drone with screen
- **Text:** Higher rates in busy areas

---

### **conclusion.html (1 Slide)**

**Slide 1: Conclusion**
- **Summary:** Brief overview of opportunities
- **Button:** "Start Investing"

---

### **about-us.html (1 Slide)**

**Slide 1: About the Company**
- **Banner:** Team photo (about-team.png)
- **Text:** Mission and values
- **Button:** "Contact Us" (links to contact-support.html)

---

### **faq.html (1 Slide)**

**Slide 1: FAQ**
- **Accordion:** Questions and answers (faq-icon.png next to headings)
- **Text:** Concise answers

---

### **contact-support.html (1 Slide)**

**Slide 1: Support**
- **Form:** Name, Email, Message
- **Button:** "Send"
- **Support Contacts:** At the bottom (email, chat)

---

### **roadmap.html (1 Slide)**

**Slide 1: Roadmap**
- **Timeline:** Linear scale with future releases (roadmap-icon.png)
- **Text:** Brief description of key milestones

---

### **profit-calculator.html (1-2 Slides)**

**Slide 1: Profit Calculator**
- **Input Fields:** Number of drones, selected level, upgrades (checkboxes)
- **Button:** "Calculate"
- **Result Display:** Large text

**(Optional Slide 2): Detailed Calculation**

---

### **international.html (1 Slide)**

**Slide 1: International Expansion**
- **World Map:** Highlighted regions (international-icon.png)
- **Text:** Brief benefits of expansion
- **Button:** "Learn More"

---

**Conclusion**

The presented architecture and detailed slide content descriptions greatly simplify the development process. We started with basic authentication pages, moved to the main hub, and then to internal pages. Each page is structured based on simplicity and clarity, utilizing icons, buttons, banners, and text with stylish and practical recommendations. This approach ensures user convenience and facilitates developers in sequentially implementing functionality, progressively expanding the project's capabilities.

Below is an additional layout for managing purchases, payments, and transactions. This layout focuses on the process of acquiring new equipment (drones) and upgrades, as well as selecting a payment network (TRC20, Polygon, etc.). It features a user-friendly step-by-step interface, ensuring a clear transaction process.

We also added an auxiliary layout for viewing transaction history and managing the balance. This allows users to track their operations, top up the balance, withdraw funds, and view order statuses.

---

### **purchase-equipment.html (4-5 Slides)**

**Main Idea**
- **Page Division:** Logical steps of the purchase process. Users first select drones and upgrades, then choose a payment network, confirm the transaction, and make the payment. All with a highly user-friendly interface.

**General Style Recommendations**
- **Process Steps:** At the top of the page, place a progress bar with stages: "Select Equipment" → "Upgrades" → "Choose Network and Payment Method" → "Confirmation" → "Payment."
- **Fonts and Colors:** Use the established project style. Headings ~24px, text 14-16px, buttons with accent color (#5569FF), field labels in small font.
- **Icons:** Use icons for drones, upgrades, and network logos (e.g., TRC20/Polygon) for clarity.

**Slide 1: Select Equipment (Drones)**
- **Heading:** "Choose Drones to Purchase" (24px, #333, centered)
- **Grid of Drone Cards:** Each card contains a drone icon (drone.png), brief description of specifications (flight hours, speed, base income)
  - **Below Icon:** "Drone Model X" (18px, bold), short text: "High speed, up to 20 hours flight" (14px, #555)
  - **Price in USDT:** Large, 16px
  - **Button:** "Add to Cart"
- **Sidebar or Below:** "Cart" block displaying selected drones with options to remove or change quantity
- **Button:** "Next" – bottom center, bright button (#5569FF, white text "Continue"), leads to the next slide
- **Style:** Based on basic styles, sliders + neat cards with shadows, hover effects on drones, clear pricing

**Slide 2: Add Upgrades**
- **Heading:** "Choose Upgrades for Your Drones"
- **Grid of Upgrades:** Icons for batteries (battery-upgrade.png), propellers (propellers.png), spare parts
  - **Below Each Icon:** Brief description: "Battery +20% flight time," "Propellers +10% speed," "Spare parts reduce downtime" (14px, #555)
  - **Price in USDT and Button:** "Add to Selected Drones"
- **Sidebar or Bottom Panel:** Order summary showing selected drones and upgrades, total amount
- **Buttons:**
  - "Back" – to return to the previous slide
  - "Next" – to proceed to network selection
- **Style:** Consistent with basic styles, sliders + maintain visual consistency. Use checkboxes or "+/-" buttons for selecting upgrades

**Slide 3: Choose Network and Payment Method**
- **Heading:** "Choose Payment Network"
- **Subtext:** "You can pay in USDT via TRC20 or Polygon. Choose a convenient network."
- **Network Cards:**
  - **TRC20 Card:** Logo, brief description ("Low fees, fast transactions")
    - **Button:** "Select TRC20"
  - **Polygon Card:** Logo, description ("Scalability, low fees")
    - **Button:** "Select Polygon"
- **After Network Selection:** Field to enter address or generate a wallet address for fund transfer
- **Sidebar:** Order summary with selected drones and upgrades, total in USDT
- **Buttons:**
  - "Back"
  - "Next"
- **Additional Info:** Transaction speed, security, link to payment FAQ
- **Style:** Consistent with basic styles, sliders + clear network cards, recognizable logos (~50-60px)

**Slide 4: Order Confirmation**
- **Heading:** "Confirm Order"
- **Confirmation Block:**
  - **List of Drones:** Quantity and cost
  - **List of Upgrades:** Prices
  - **Total Amount:** Highlighted in bold, large font
- **Buttons:**
  - "Confirm and Proceed to Payment"
  - "Back" – for adjustments
- **Style:** Based on basic styles, sliders + clear and neat table. Highlight the total amount prominently

**Slide 5: Payment**
- **Heading:** "Order Payment"
- **Payment Details:**
  - **Depending on Selected Network:** Display address for fund transfer (input field with address, "Copy Address" button)
  - **QR Code:** For quick payment (if applicable)
- **Instructions:** "Transfer X USDT to the specified address. After network confirmation, your order will be processed."
- **Transaction Status Indicator:** Progress bar or waiting animation
- **Buttons:**
  - "Go to Transaction History"
  - "Return to Main" (if payment is completed)
- **Style:** Based on basic styles, sliders + clean layout emphasizing ease of copying the address and clear instructions. Use a light background, blue accents

---

### **transactions.html (2-3 Slides)**

**Purpose:** View transaction history, top up balance, withdraw funds.

**Slide 1: Transaction History**
- **Heading:** "Transaction History" (24px, #333)
- **Table Columns:** Date, Operation Type (Drone Purchase, Upgrades), Amount, Status (Successful, Pending)
- **Features:** Search or filter by date
- **Icons:** CSV download icon, "Refresh" button to update the list
- **Button:** "Go to Balance Top-Up"
- **Style:** Based on basic styles, sliders + neat table, clear column headers, ~14px font

**Slide 2: Balance Top-Up**
- **Heading:** "Top Up Balance"
- **Content:**
  - **Select Network:** As on the purchase page
  - **Generate Deposit Address:** Display deposit address
- **Instructions:** Steps to add funds
- **Post-Submission:** User can refresh transaction history to see the top-up
- **Buttons:** "Back" and "Top Up"

**(Optional Slide 3): Withdraw Funds**
- **Heading:** "Withdraw Funds"
- **Content:**
  - **Input Field:** Amount to withdraw
  - **Select Network:** For withdrawal
  - **Button:** "Submit Withdrawal Request"
  - **Description:** Brief info on withdrawal fees
- **Style:** Based on basic styles, sliders + consistent, clean layout. Bright buttons, clear text

---

**Final Summary**

- **Added Layouts:**
  - **purchase-equipment.html:** For the complete cycle of purchasing drones and upgrades, including network selection (TRC20/Polygon) and step-by-step payment guidance.
  - **transactions.html:** For managing balance, viewing transaction history, topping up, and withdrawing funds.
- **Unified Style:** Clear icons, distinct headings, neat tables, and tooltips. The transaction process is broken down into logical steps, enhancing usability and reducing errors.
- **User Interface Focus:** Simplicity from product selection to payment confirmation. Each step includes clear instructions and visual elements (icons, QR codes, address copy buttons).
- **Enhanced Functionality:** Improved UX with added layouts ensuring a complete interaction cycle with payment systems and transactions.

This comprehensive translation maintains the original structure, detail, and instructional tone, ensuring clarity and usability for English-speaking developers and stakeholders.
## Customer Service Chatbot – IBM Watson

A conversational AI chatbot built for a flower ordering platform, designed to handle customer inquiries, order placement, location questions, and FAQs. It was built using an IBM Watson Assistant and deployed to a live testing website. 

---

## Project Overview

The chatbot was developed as part of an applied AI course by IBM Watson on Coursera. The goal was to design, build and deploy a fully functional customer service chatbot capable of handling real-world user queries for a flower ordering business. 

The project involved two phases:
1. **No-code development** in IBM Watson Assistant using dialog nodes and intent/entity configuration
2. **Python implementation** for debugging and extending chatbot logics

---

## Tools & Technologies

- **IBM Watson Assistant** for dialog flow design, intent recognition, entity extraction
- **Python** for response debugging and logic testing
- **WordPress** – deployment host

---

## Features

- **50+ dialog nodes** covering a wide range of customer scenarios
- Handles:
  - Order placement and order status inquiries
  - Delivery location and physical store locations
  - Product FAQs (flower types, pricing, bouquet options)
- Deployed and tested on a live website

---

## How It Works

IBM Watson Assistant uses **intents** (which is what the user wants) and **entities** (key details in the message) to route conversations through a structured dialog tree.
Each dialog node defines:
- A condition (ex., order_status, delivery_location)
- A response or follow-up prompt
- Child nodes for multi-turn conversations and nesting

**Example flow:**

```
User: "Where do you deliver?"
  → Intent: #delivery_location
    → Node: Delivery Info
      → Response: "We deliver to [locations]. Would you like to place an order?"
```

---

## Deployment

The chatbot was embedded into a live website hosted by Wordpress using Watson's web chat integration. After building and testing the dialog flow in Watson Assistant, it was deployed onto the site for further debugging and real tests

---

## Course

Built as part of the **IBM Watson Applied AI course on Coursera**

---

## 📬 Contact

**Aryan Mahindroo**  
[linkedin.com/in/aryan-mahindroo-1ba085295](https://www.linkedin.com/in/aryan-mahindroo-1ba085295)


# EcoPocket Development Plan

## Phase 1: Technical Setup
As a first step, the project will be divided into two main services: Backend and Frontend.

- **Backend:** Python (FastAPI/Flask) - Selected for its strong data processing capabilities, suitable for our Eco-Score algorithm.
- **Frontend:** React or Flutter - To provide a user-friendly interface for expense tracking.
- **Database:** PostgreSQL or SQLite to store expense categories and carbon coefficients.

## Phase 2: Project Roadmap & Steps
Using the PRD as a base, the development is divided into the following steps:

### Step 1: Backend Development
- Set up a virtual environment.
- Create an API endpoint to receive expense data (amount, category).
- Implement the "Eco-Score Algorithm": 
  - $Score = \sum (Expense_{i} \times Coefficient_{i})$
- Build a mock database for sustainable alternatives.

### Step 2: Frontend Development
- Initialize the frontend repository.
- Create a simple "Expense Entry" form.
- Develop the "Eco-Score Dashboard" to visualize weekly results.
- Implement clickable CTA buttons for suggested green alternatives.

### Step 3: Integration
- Connect Frontend with Backend via API.
- Test the data flow from expense entry to score calculation.

## Phase 3: LLM Integration Plan
- Integrate an LLM (via API) to provide personalized sustainability tips based on the user's spending patterns.

## Purpose

Create a realistic synthetic lead scenario for demonstrating AgentifyMe's Speed-to-Lead workflow to Ken DeGrant / High Point Realty & Auction.

This scenario is for demonstration and product-learning purposes only. All names, contact details, and inquiry data below are fictional.

---

## Scenario Summary

A prospective buyer discovers a High Point Realty & Auction property online and submits an inquiry while the responsible broker is unavailable.

AgentifyMe should:

1. receive the inquiry;
2. respond quickly;
3. collect useful buyer context;
4. summarize the lead;
5. assign or route the lead to the appropriate broker;
6. notify the broker;
7. clearly show whether human action is still required.

---

## Synthetic Lead

**Name:** Sarah Miller

**Lead Type:** Residential Buyer

**Source:** High Point Realty website / online property listing

**Location of Interest:** Richmond, Kentucky

**Target Budget:** Up to $350,000

**Property Preference:** 3 bedrooms, garage preferred

**Desired Next Step:** Property showing

**Preferred Showing Time:** Saturday around 11:00 AM

**Representation Status:** Not currently working with another real-estate agent

**Lead Priority:** High

---

## Initial Inquiry

> Hi, I saw the three-bedroom property near Richmond and wanted to know if it is still available. I'm looking for something under $350,000, preferably with a garage. Would it be possible to see it this Saturday?

---

## Expected AgentifyMe Response

AgentifyMe acknowledges the inquiry quickly and asks only the information needed before broker handoff.

Example:

> Hi Sarah, thanks for reaching out about the property. I can help gather a few details for High Point Realty. Do you have a preferred time on Saturday, and are you currently working with another real-estate agent?

---

## Buyer Follow-Up

> Around 11 AM would work well. I'm not currently working with another agent.

---

## Information AgentifyMe Should Extract

- **Intent:** Buy
- **Location:** Richmond, KY
- **Maximum Budget:** $350,000
- **Bedrooms:** 3
- **Garage:** Preferred
- **Showing Request:** Saturday
- **Preferred Time:** Around 11:00 AM
- **Representation Status:** Not currently represented
- **Priority:** High

---

## AI Lead Summary

> High-intent buyer interested in a residential property near Richmond, Kentucky. Budget is up to $350,000 with preference for three bedrooms and a garage. Buyer requested a Saturday showing around 11:00 AM and is not currently represented by another agent.

---

## Expected Workflow

### Step 1: Lead Received

The inquiry enters AgentifyMe from the configured lead source.

**Visible status:** `New Lead`

---

### Step 2: Automated Response

AgentifyMe sends the first response quickly.

**Visible status:** `AI Responded`

The demo should clearly show:

- inquiry time;
- response time;
- source of lead.

---

### Step 3: Context Collection

AgentifyMe gathers the minimum information needed for useful broker follow-up.

The system should not repeatedly ask for information already provided.

---

### Step 4: Lead Qualification

The system extracts the buyer's criteria and generates a concise summary.

**Priority:** High

---

### Step 5: Broker Assignment

The lead is assigned to the appropriate available broker according to the current routing logic.

For demonstration purposes:

**Assigned Broker:** Ken DeGrant

---

### Step 6: Broker Notification

Ken receives a concise notification containing:

- buyer name;
- lead source;
- property/location;
- intent;
- budget;
- showing request;
- priority;
- short conversation summary.

---

### Step 7: Human Handoff

The broker can review the conversation and choose to take control.

Example actions:

- `Take Over Conversation`
- `Mark Handled`
- `Reassign`
- `Pause AI`

---

## Timeline Example

| Time        | Event                          |
| ----------- | ------------------------------ |
| 10:42:00 AM | Buyer inquiry received         |
| 10:42:18 AM | AgentifyMe first response sent |
| 10:43 AM    | Buyer provides showing time    |
| 10:43 AM    | Buyer context extracted        |
| 10:43 AM    | Lead marked High Priority      |
| 10:43 AM    | Lead assigned to Ken           |
| 10:44 AM    | Broker notification sent       |

---

## What This Demo Is Intended to Test

The scenario should help us learn whether Ken believes:

- the first response is useful;
- the right information is collected;
- the lead summary is sufficient;
- the handoff happens at the correct time;
- the broker notification contains the right information;
- the workflow resembles High Point's actual process;
- the product is solving a real problem rather than adding unnecessary complexity.

---

## Questions to Ask Ken After This Scenario

1. How close is this to how an inquiry would actually enter High Point today?
2. Is this enough information for you to take over the conversation?
3. Is anything being collected that you do not need?
4. What important information is missing?
5. Would you want the AI to continue further before handing the lead to you?
6. Would this workflow be different for auction inquiries?
7. What part of this would be unrealistic in your current process?

---

## Guardrail / Exception Scenario

The main demo should stay simple, but a short secondary example may be used to show human handoff.

### Buyer Question

> Can you guarantee that the seller will accept a $100,000 cash offer?

### Expected AgentifyMe Behavior

AgentifyMe should not make a financial or contractual guarantee.

The system should:

1. identify the question as requiring human judgment;
2. stop automated handling of that question;
3. change the lead status to `Needs Human Review` or `Out of Scope`;
4. notify the assigned broker;
5. preserve the conversation context for handoff.

This demonstrates that Speed-to-Lead does not mean removing broker control.

---

## Known vs Assumed

### Based on Current Product Requirements

- automated first response;
- information extraction;
- lead priority;
- broker assignment;
- broker notification;
- human handoff;
- broker control over automation.

### Demo Assumptions

- residential buyer inquiry is an appropriate first High Point scenario;
- Richmond is representative of a useful service-area example;
- Ken would be the assigned broker;
- these buyer details are sufficient for qualification;
- showing coordination belongs in the initial workflow.

These assumptions must be validated with Ken.

---

## Demo Success Criteria

The scenario is successful if Ken can quickly understand:

1. what happened to the new lead;
2. what AgentifyMe did automatically;
3. what information was collected;
4. who owns the next action;
5. where human judgment takes over;
6. whether the workflow would actually help High Point.
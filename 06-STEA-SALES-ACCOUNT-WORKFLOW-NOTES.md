## Account

**Account:** High Point Realty & Auction  
**Contact:** Ken DeGrant  
**Workstream:** Speed-to-Lead Discovery & Demo Preparation  
**Owner:** Utkarsh Jha

---

## Purpose

Document how STEA/Hermes could support the High Point Realty account workflow, summarize relevant prior hands-on experience with Hermes and DeepAPI, and record whether the agent was available for use on this specific account during the sprint.

The intended role of STEA is to support research organization, discovery preparation, account-context maintenance, follow-up preparation, and discovery summarization.

STEA should support human judgment, not replace it.

---

## Current High Point Sprint Status

**STEA/Hermes availability:** Not operational for active use at the time of this work.

I currently have access to a Hermes bot through Telegram, but the supporting service/server is not running.

Because the service was unavailable, I did not use STEA/Hermes directly for the High Point Realty research, demo preparation, discovery guide, or value proposition.

The High Point artifacts were completed through the normal manual research and documentation workflow.

---

# Prior Hermes / DeepAPI Experience

Although STEA/Hermes was unavailable for the High Point account, I have previously used the Hermes Telegram bot for AgentifyMe sales and research workflows.

This earlier work provides practical evidence for how the agent could support the High Point account once available.

---

## 1. AgentifyMe ICP Research

I previously used Hermes to retrieve and organize information about AgentifyMe's U.S. ICP.

The bot identified:

- target brokerage/operator types;
- relevant decision-maker roles;
- workflow-fit signals;
- lead and administrative pain indicators;
- disqualifiers;
- targeting priorities.

This demonstrated that Hermes could retrieve existing AgentifyMe context and organize it into a usable sales-research structure.

### Usefulness

Useful for:

- restoring account or market context;
- organizing ICP criteria;
- preparing research rules;
- reducing repeated manual review of existing internal information.

---

## 2. DeepAPI Tool Integration

I tested whether Hermes could access DeepAPI functionality through its Telegram environment.

The bot confirmed access to:

- DeepAPI web search;
- website scraping;
- deep research;
- terminal/code execution;
- secure access to the configured DeepAPI API key.

The API credential was used through the environment without displaying it.

### Usefulness

This showed that Hermes could act as an orchestration layer between a salesperson and external research tools without requiring the salesperson to manually operate the API.

---

## 3. Public Brokerage Research

I used Hermes + DeepAPI to search for independent residential real-estate brokerages.

The workflow included:

1. web search;
2. website scraping;
3. deeper research where needed;
4. verification of company information;
5. separation of verified and unknown information.

Research fields included:

- company name;
- geography;
- brokerage type;
- independence/franchise status;
- approximate agent count;
- office footprint;
- public contact paths;
- operational roles;
- technology/workflow evidence;
- source URLs.

### Usefulness

This was useful for turning an initial company name into a structured, source-backed account research record.

---

## 4. Lead Qualification

I also tested a larger lead-research workflow using explicit ICP criteria.

The bot evaluated potential brokerage accounts against areas such as:

- ICP fit;
- workflow fit;
- buying signals;
- decision-maker seniority;
- reachability.

It also separated:

- Priority;
- Research/Nurture;
- Reject.

The workflow required unsupported values to remain Unknown instead of being invented.

### Usefulness

Useful for:

- screening accounts;
- prioritizing research;
- identifying buying signals;
- maintaining evidence behind qualification decisions.

---

## 5. Structured Sales Output

Hermes was able to convert researched accounts into a structured CSV containing approved Priority and Research/Nurture leads.

### Usefulness

This demonstrated that the bot can potentially help move research from conversational output into a format usable for:

- CRM import;
- account lists;
- follow-up work;
- internal sales review.

---

# Observed Limitations From Prior Use

The earlier Hermes work also showed several limitations.

## Verification Still Requires Human Review

Research results may contain:

- Unknown values;
- incomplete evidence;
- weak or ambiguous fit signals.

The bot should therefore accelerate research, not automatically approve accounts for outreach.

---

## Tool and Workflow Errors Can Occur

During earlier testing:

- some commands were unavailable;
- one pipeline command was executed incorrectly;
- some requested qualification criteria could not be fully verified.

The useful behavior was that the bot sometimes reported these limitations instead of inventing missing evidence.

---

## Output Quality Depends on Prompt Quality

Detailed research prompts specifying:

- ICP;
- exclusions;
- buying signals;
- evidence requirements;
- scoring;
- required output fields

produced more useful results than broad lead-generation requests.

This suggests STEA/Hermes works best when used with a clearly defined operating procedure.

---

# Planned High Point Workflow

If STEA becomes available, I would use it on the High Point account in the following sequence.

## 1. Organize Account Research

Provide the approved High Point Account Brief and ask STEA to classify information into:

- Confirmed Facts;
- Assumptions;
- Open Questions;
- Workflow Signals;
- Next Research Actions.

### Goal

Test whether it can preserve the important distinction between evidence and assumptions.

---

## 2. Review Discovery Preparation

Provide:

- High Point Account Brief;
- Ken DeGrant Discovery Question Guide.

Ask STEA to identify:

- questions already answered by public research;
- questions requiring Ken's direct input;
- duplicated questions;
- high-value follow-up questions.

### Goal

Make the discovery conversation shorter and more focused rather than generating additional unnecessary questions.

---

## 3. Maintain Account Context

Ask STEA to maintain a concise account-state summary containing:

- what is confirmed;
- what remains unknown;
- current Speed-to-Lead hypotheses;
- latest customer evidence;
- current prototype assumptions;
- next action.

### Goal

Allow future work on the account to resume without rereading every artifact.

---

## 4. Organize Discovery Notes

After speaking with Ken, provide only approved/sanitized notes and ask STEA to classify them into:

### Direct Customer Statements

What Ken explicitly said.

### Interpretation

What the team believes those statements may mean.

### Unverified Assumptions

Things still requiring evidence.

### Product Implications

Possible effects on requirements or prototype design.

### Follow-Up Actions

Questions, product changes, or next customer actions.

Human review must occur before this output becomes part of the official account record.

---

## 5. Prepare Follow-Up

Use the approved discovery notes to prepare a first draft covering:

- what we heard;
- what we understood;
- unresolved questions;
- agreed next steps;
- possible follow-up demo or pilot.

### Goal

Reduce follow-up preparation time while keeping communication grounded in Ken's actual statements.

---

# Example High Point STEA Workflow

**Public Account Research**  
↓  
**Account Brief**  
↓  
**STEA organizes facts, assumptions, and gaps**  
↓  
**Discovery Question Guide**  
↓  
**Ken Conversation**  
↓  
**STEA organizes approved discovery notes**  
↓  
**Human Verification**  
↓  
**Discovery Notes**  
↓  
**Product Feedback**  
↓  
**Customer Follow-Up / Next Action**

---

# Information Boundaries

Until company AI/data-handling rules clearly authorize otherwise, I would limit STEA inputs to:

- publicly available business information;
- approved internal account artifacts;
- synthetic demo information;
- sanitized discovery notes.

I would not automatically provide:

- passwords or credentials;
- private system access;
- sensitive personal data;
- confidential customer information;
- contractual or financial information;
- information classified as unsuitable for external AI systems.

---

# How STEA Usefulness Would Be Evaluated

## Research Accuracy

Did STEA preserve verified information accurately?

Did it incorrectly convert assumptions into facts?

---

## Context Retention

Could it maintain a useful High Point account state between tasks?

---

## Discovery Support

Did it identify meaningful gaps without generating unnecessary questions?

---

## Summarization

Could it correctly separate:

- direct statements;
- interpretation;
- assumptions;
- product implications?

---

## Follow-Up Quality

Did it produce a usable first draft requiring reasonable rather than extensive correction?

---

## Reliability

Did it:

- invent information;
- lose important context;
- misuse tools;
- require significant human correction?

---

# Actual Use on High Point Account

**Status:** Not yet executed.

**Reason:** Hermes/STEA was unavailable because the supporting server was not running.

If the service becomes available during the sprint, this section should be updated with:

- date used;
- task performed;
- prompt/input;
- tool used;
- output generated;
- what was useful;
- what required correction;
- whether the workflow should be reused.

---

# Current Assessment

Prior Hermes + DeepAPI testing demonstrates that the agent can assist with:

- ICP research;
- public company research;
- website scraping;
- deep research;
- account qualification;
- evidence organization;
- structured sales outputs.

The earlier experience also showed that human verification remains necessary and that tool availability, verification gaps, and prompt quality materially affect the result.

For the High Point Realty account specifically, STEA usefulness has **not yet been validated** because the service was unavailable during the work completed so far.

The workflow above therefore represents a practical test plan based on prior hands-on Hermes experience rather than a claim that STEA was used on the High Point account.
# World Vision Australia - BounceBack Campaign Decision Analytics

Decision analytics project examining donor behaviour, campaign performance, communication channels and predictive patterns to support evidence-based fundraising decisions.

## Project Snapshot

**Role:** Business / Decision Analyst  
**Duration:** 2025  
**Organisation:** World Vision Australia  
**Project:** BounceBack Campaign  
**Location:** Australia  
**Tools & Techniques:** Predictive Modelling | Random Forest | Decision Trees | Data Visualisation | Descriptive Analytics | Diagnostic Analytics | Campaign Analytics  
**Focus:** Business Analysis | Decision Analytics | Customer/Donor Analytics | Predictive Analytics | Strategy & Recommendations

---

## Project Overview

The BounceBack campaign is a fundraising initiative designed to generate additional one-off donations from existing child sponsors through milestone communications including Birthday, Christmas and Education appeals.

The project investigated how donor characteristics, communication channels, campaign sequencing, timing and ask strategies influenced donation outcomes.

The analysis followed three stages:

**Descriptive Analytics → Diagnostic Analytics → Predictive Analytics → Business Interpretation → Recommendations**

The objective was not simply to predict donations, but to translate behavioural patterns into practical recommendations concerning who to contact, which channel to use, when to communicate and how donation asks should be structured.

---

## Business Problem

Analysis identified a mismatch between campaign execution and observed donor behaviour.

Key questions included:

1. Are the right communication channels being used for the right supporters?
2. Are communications being delivered when donors are most ready to give?
3. Is campaign over-communication reducing efficiency?
4. Are donation amounts being requested appropriately for different supporter profiles?

The analysis therefore examined:

- donor demographics;
- supporter tenure;
- communication channels;
- campaign sequencing;
- donation timing;
- giving behaviour;
- campaign type; and
- ask strategy.

---

## Analytical Approach

### 1. Descriptive Analysis

Historical campaign performance was analysed to understand:

- donation trends;
- donor profiles;
- communication-channel distribution;
- campaign sequencing; and
- donation timing.

### 2. Diagnostic Analysis

Observed patterns were investigated to understand why campaign performance differed across donor segments and communication strategies.

The diagnostic analysis focused on:

- channel-to-supporter alignment;
- timing versus donor readiness;
- diminishing returns from repeated communications; and
- suitability of existing donation ask ladders.

### 3. Predictive Analysis

Random Forest models were applied separately to:

- Birthday
- Christmas
- Education

campaigns.

Representative decision trees were extracted from the models to identify interpretable rules involving:

- supporter tenure;
- communication channel;
- campaign type; and
- donation-value outcomes.

The predictive work was used as a **decision-support mechanism**, rather than treating model output as an automated donor-targeting solution.

---

## Key Findings

### Channel Allocation

Email represented approximately **72% of outbound communications**, compared with approximately **18% Direct Mail** and **10% SMS**.

Despite this digital-heavy allocation, higher average donation values were associated with traditional inbound channels.

Observed average gift values included approximately:

- **Letter – $90**
- **Telephone – $74**
- **Web – $31.22**

This indicated an opportunity to better align communication channels with supporter characteristics rather than applying the same digital-first journey across all donor segments.

---

### Donor Profile

Age and supporter tenure demonstrated meaningful relationships with donation value.

Supporters aged **65+** generated an average donation of approximately **$31.32 per gift**.

Long-tenure supporters of **50+ years** represented a particularly high-value segment, averaging approximately **$55.72 per donation**.

The findings suggested that supporter tenure should be considered when designing campaign journeys and donation asks.

---

### Campaign Timing

Donation behaviour demonstrated a clear mid-cycle pattern.

The largest observed donation peak occurred around **Day 15**, reaching approximately **$2 million**.

However, campaign communications were concentrated earlier in the cycle and again around Days 18–20.

This indicated a timing mismatch between outbound campaign activity and observed donor readiness.

---

### Communication Sequence

Analysis indicated that much of the campaign value was generated during the earlier communication touches.

Direct Mail, EDM1 and EDM2 generated stronger returns, while later-stage communications such as EDM3 and SMS2 produced considerably weaker incremental value despite substantial communication volumes.

This suggested diminishing returns from blanket late-cycle communications.

---

## Predictive Modelling

Random Forest models were developed for the three BounceBack campaign types.

Donation outcomes were grouped into value bands to investigate factors associated with different giving levels.

Decision-tree interpretation showed that **supporter tenure was the root split across all three campaign models**.

Approximate tenure thresholds included:

- Birthday – **48.5 years**
- Christmas – **48.5 years**
- Education – **51.5 years**

Longer-tenure supporters were generally associated with higher donation outcomes.

However, the relationship was not completely linear. The Birthday analysis, for example, identified a plateau effect among extremely long-tenure supporters.

---

## Model Interpretation & Limitation

The Random Forest models were useful for identifying behavioural patterns, but their predictive reliability was limited.

The models achieved a **Kappa score of 0**, indicating limited ability to reliably distinguish Medium and High donation outcomes beyond chance.

Rather than presenting the model as a production-ready prediction engine, the results were therefore interpreted as **decision-support evidence**.

This distinction was important.

The model was useful for identifying:

- tenure thresholds;
- potential channel effects;
- campaign-specific behaviour; and
- ask-ladder sensitivity.

Further model refinement and additional predictor variables would be required before using the approach for automated donor-level targeting.

---

## Business Recommendations

### 1. Align Channels With Donor Profiles

A differentiated communication strategy was recommended instead of relying predominantly on email.

For older and longer-tenure supporters, greater use of Direct Mail and Telephone was proposed while retaining digital channels for younger segments.

The recommendation included shifting at least **20% of selected email outreach** toward Direct Mail for appropriate higher-value cohorts.

---

### 2. Optimise Campaign Timing

Campaign communications should be concentrated more closely around demonstrated donor readiness.

A revised campaign cycle was proposed:

**Days 1–7:** Awareness  
**Days 8–12:** Anticipation  
**Days 13–15:** Peak conversion  
**Days 16–18:** Reinforcement  
**Days 19–21:** Final push  
**Days 21–30:** Stewardship and targeted/light asks

The objective was to concentrate stronger asks around the mid-month conversion window while reducing low-value late-cycle communications.

---

### 3. Personalise Donation Ask Strategy

Uniform donation ladders were identified as potentially inefficient because donor capacity differed considerably by tenure and giving history.

The recommendation was to anchor suggested amounts to:

- previous giving;
- supporter tenure;
- observed donation bands; and
- campaign context.

A/B testing was recommended to compare:

- rounded asks;
- band-aligned asks;
- milestone-based framing; and
- different donation anchors.

---

## Measurement Framework

Recommended campaign changes should be evaluated using:

- Revenue per 1,000 communications
- Response rate
- Average gift value
- Conversion latency
- Upgrade rate
- Opt-out/unsubscribe rate

A proposed success measure for timing optimisation was a **≥5 percentage-point uplift in revenue share before Day 21**, while maintaining stable average gift values and keeping opt-outs at or below the control level.

---

## Data Quality Considerations

The analysis identified inconsistencies between supporter tenure fields.

Fields including child-sponsor tenure, pledger tenure and supporter tenure did not always align logically with age-band information.

A future-state recommendation was therefore to calculate tenure dynamically from authoritative dates such as:

- date of birth;
- sponsorship start date; and
- pledge start date.

This would improve data consistency and provide a more reliable foundation for segmentation and predictive modelling.

---

## Business Analysis Contribution

The project demonstrated how analytical findings can be translated into business decisions rather than stopping at model development.

**Business Problem**  
↓  
**Business Questions**  
↓  
**Data Preparation**  
↓  
**Descriptive Analysis**  
↓  
**Diagnostic Analysis**  
↓  
**Predictive Modelling**  
↓  
**Model Interpretation**  
↓  
**Business Recommendations**  
↓  
**Measurement & Guardrails**

The resulting recommendations connected analytical evidence to practical changes in channel allocation, campaign timing, donor segmentation and ask strategy.

---

## Skills Demonstrated

`Business Analysis` `Decision Analytics` `Predictive Analytics` `Random Forest` `Decision Trees` `Descriptive Analytics` `Diagnostic Analytics` `Customer Analytics` `Donor Segmentation` `Campaign Analytics` `Data Visualisation` `Data Quality` `Business Recommendations` `KPI Development` `Stakeholder Decision Support` `Data-Driven Decision Making`

---

## Repository Structure

```text
world-vision-bounceback-analytics/
│
├── README.md
│
├── images/
│   ├── campaign-performance.png
│   ├── donor-profile.png
│   ├── channel-analysis.png
│   ├── timing-analysis.png
│   └── decision-tree-analysis.png
│
└── documentation/
    └── project-summary.pdf

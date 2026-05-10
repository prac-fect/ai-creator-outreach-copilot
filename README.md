# AI Creator Outreach Copilot

An AI-assisted TikTok creator matching and outreach email generation demo for cross-border marketing teams.

Live Demo: https://prac-fect.github.io/ai-creator-outreach-copilot/

---

## 1. Project Background

During my previous internship in cross-border TikTok creator marketing, the team needed to contact a large number of creators every day. A common challenge was that generic outreach templates were easy to ignore, while manually writing personalized emails for each creator was time-consuming.

This project was built to simulate an AI-assisted workflow that helps marketing operators quickly evaluate creator fit and generate more personalized outreach emails.

---

## 2. Target Users

This tool is designed for:

- Cross-border e-commerce marketing teams

- TikTok creator partnership operators

- MCN or agency teams managing influencer outreach

- Junior operations staff who need to contact creators at scale

---

## 3. Core User Pain Points

1. Creator screening is time-consuming when operators need to compare audience, content style, and commercial potential manually.

2. Generic outreach emails often sound templated and may reduce creator response rates.

3. Junior operators may not know how to adjust outreach tone for different creator types.

4. Teams lack a lightweight way to connect creator evaluation with actual outreach execution.

---

## 4. Product Solution

AI Creator Outreach Copilot provides a simple workflow:

1. Input product profile  

2. Input TikTok creator data  

3. Generate creator matching scores  

4. Receive cooperation suggestions  

5. Generate a personalized English outreach email  

The tool evaluates creators from three dimensions:

- Audience overlap

- Content fit

- Commerce potential

It then gives a cooperation priority and generates an outreach email based on the product and creator profile.

---

## 5. Key Features

### Product Profile Input

Users can enter basic product information, including product category, price range, target market, user profile, consumption scenario, and selling points.

### Creator Data Input

Users can enter creator information, including follower count, engagement rate, average views, audience profile, content category, content style, and recent brand collaborations.

### Matching Score

The tool generates a matching score based on three dimensions:

- Audience Overlap: whether the creator's audience matches the product's target users

- Content Fit: whether the creator's content style fits the product category and campaign goal

- Commerce Potential: whether the creator has potential to drive conversion or product interest

### Outreach Email Generation

Based on the matching result, the tool generates a personalized English outreach email that includes:

- Subject line

- Personalized opening

- Product introduction

- Collaboration reason

- Call to action

---

## 6. Scoring Logic

The overall score is calculated using a weighted model:

```text

Total Score = Audience Overlap × 50% + Content Fit × 30% + Commerce Potential × 20%

# ChatGPT Health Advice Evaluation Data

This repository contains the complete dataset from our research investigating how ChatGPT responds to questions about eating and exercise behaviours. Our study examined whether AI chatbots provide safe and helpful advice to people seeking health information, particularly those who might be vulnerable to developing eating disorders.

## Study Overview

**Background**: Many people now ask AI chatbots like ChatGPT for health advice. However, we don't know enough about whether these systems provide safe guidance, especially for sensitive topics like eating and exercise.

**What we did**: We created 9 different fictional personas (characters) representing people of various ages, genders, and backgrounds who might ask ChatGPT for diet and exercise advice. Eight university students then had conversations with ChatGPT pretending to be these personas, asking questions about eating and exercise habits.

**Key findings**: ChatGPT sometimes gave helpful, evidence-based advice but also provided potentially harmful guidance. The safety features (called "safeguards") worked inconsistently and were less effective for adult users compared to younger users.

## Dataset Description

### Total Interactions: 330
- **240 persona-based interactions**: Students introduced themselves using specific demographic details
- **90 control interactions**: Same questions asked without revealing age, gender, or background

### Personas Represented
Our 9 personas covered:
- **Ages**: 14-65 years
- **Genders**: Female, male, transgender, non-binary
- **Risk levels**: From healthy individuals to those showing concerning eating behaviours
- **Cultural backgrounds**: Diverse representation

### Data Collection Period
February - April 2025

## File Structure

### `/data/chatgpt-queries/`
Contains the raw ChatGPT conversation transcripts:

#### `/persona-based-interactions/`
- **/GP1-interactions/**: Conversations where participants acted as Persona 1
- **/GP2-interactions/**: Conversations where participants acted as Persona 2
- [continues for GP3-GP9]

Each folder contains:
- Full conversation transcripts
- ChatGPT's complete responses
- Follow-up questions and interactions
- Average response length: ~350 words per ChatGPT reply

#### `/control-interactions/`
- **demographic_omitted_queries.pdf**: Same questions asked without revealing persona details

## Methodology Summary

**Persona Development**: Based on established research about eating disorders and body image concerns, plus expertise from our research team who work with people affected by eating disorders.

**Question Types**: Each persona asked 10 questions (5 about diet, 5 about exercise) designed to test how ChatGPT responds to potentially concerning requests, such as:
- Requests for very low-calorie diets
- Questions about rapid weight loss
- Queries about excessive exercise

**Analysis**: We used thematic analysis to identify patterns in ChatGPT's responses, focusing on:
- Helpful vs. potentially harmful advice
- When safety warnings appeared
- Consistency across different personas
- Differences between demographic groups

## Key Research Questions

1. How might AI systems, particularly ChatGPT, be used to provide advice related to eating and exercise behaviours?
2. What is the nature of ChatGPT's responses to queries about eating and exercise, and how do these align with current health guidelines?
3. How can we effectively assess the potential harm or safety of AI-generated advice in the context of eating and exercise behaviours?
4. How could conversational AI systems better protect at-risk users from consuming harmful advice?

## Ethical Considerations

- **No real vulnerable individuals were exposed to potentially harmful content**
- **University ethics approval obtained**
- **Persona-based approach** used instead of direct user studies with at-risk populations
- **New ChatGPT accounts created for each session** to prevent cross-contamination

## Usage and Citation

If you use this dataset in your research, please cite our paper:

```

```

## Acknowledgements

We thank all participants who contributed their time to this research and the experts who provided guidance on persona development and analysis frameworks.

---

**Note**: This research contributes to ongoing efforts to make AI systems safer for health-related queries. The findings highlight the need for improved safeguards in conversational AI, particularly for vulnerable populations seeking health information.
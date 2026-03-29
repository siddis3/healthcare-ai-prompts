# healthcare-ai-prompts
# 🏥 Healthcare AI Prompt Library

A collection of AI prompts built specifically for Clinical 
Informatics and Healthcare Data Analytics workflows.

Built by: [Sobia Siddiqui] | Clinical Informatics Analyst | Texas
Tools: Claude.ai | Epic | Tableau

---

## 📊 Prompt 1 — Data Validation Troubleshooter

**Use case:** When your Epic count and Tableau dashboard 
don't match, this prompt generates a structured investigation 
checklist instantly.

**The Prompt:**
```
You are a Clinical Informatics Analyst supporting a health 
system's quality reporting team.

I'm troubleshooting a data discrepancy between Epic and 
our Tableau dashboard for the following measure:
- Measure: [insert measure name]
- Epic count: [insert number]
- Tableau count: [insert number]
- Difference: [insert number] patients

Walk me through a step-by-step validation checklist to 
identify why these numbers don't match. Format it as a 
numbered checklist with a short explanation for each step. 
Flag which issues are most common in Epic environments.
```

**Why it works:** Saves 20–30 minutes of Googling and 
gives you a structured starting point every single time.

---

## 📊 Prompt 2: The Stakeholder Explainer

**Use case:** Your data shows a discrepancy. You understand why. But your medical director or VP doesn't speak SQL or Epic. You spend 20 minutes figuring out how to explain it without making anyone panic.

**The Prompt:**
```
You are a Clinical Informatics Analyst presenting data findings 
to non-technical healthcare leaders.

I found the following discrepancy in our quality dashboard:
- Measure: [insert measure]
- Expected value: [insert]
- Actual value: [insert]
- Likely cause: [insert your technical finding]

Write a clear, calm 3-paragraph explanation I can send to my 
Medical Director. Use no technical jargon. Paragraph 1: what 
the data shows. Paragraph 2: why it happened (simple terms). 
Paragraph 3: what we're doing to fix it and when.
```

## 📊 Prompt 3: Dashboard Refresh QA Checklist

**Use case:** Dashboard Refresh QA Checklist

**The Prompt:**
```
You are a Clinical Informatics Analyst doing a quality check 
on a refreshed Tableau dashboard before sending it to stakeholders.

Dashboard name: [insert]
Data source: [insert — e.g., Epic Clarity, data warehouse]
Refresh frequency: [daily/weekly/monthly]

Generate a pre-send QA checklist covering:
1. Data freshness checks
2. Count validation steps
3. Visual/formatting checks
4. Common Epic data lag issues to verify
5. Sign-off criteria

Format as a checkbox list I can reuse every time.
```


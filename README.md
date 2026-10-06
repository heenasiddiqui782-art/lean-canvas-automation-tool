Lean Business Model Canvas Automation Tool - https://1drv.ms/x/c/d25b756fc27d4ee3/IQDC4TIAbIjjQb7VspQd--OYAR3N-0GQza09gkDfOdRMuQk?e=jba4dq
TiffinSathi — an illustrative, evidence-first startup validation case

Repository: https://github.com/heenasiddiqui782-art/lean-canvas-automation-tool

An AI-assisted workflow that turns a startup idea into structured, testable business hypotheses, ranks the riskiest assumptions, links them to validation experiments, and tracks evidence as the canvas evolves.

Honesty note: TiffinSathi is an illustrative idea. No customer interviews, surveys, revenue, customers or partnerships exist. Every number is an assumption or projection until real evidence replaces it.

<img width="1600" height="2000" alt="dashboard png" src="https://github.com/user-attachments/assets/2dc95ca1-a577-48c4-bbea-37f401d43576" />


Demo Video


https://github.com/user-attachments/assets/d8455280-6ffa-45d5-b63c-ef9e5d8178cc



Screenshots
<img width="342" height="188" alt="validation_score" src="https://github.com/user-attachments/assets/37e63176-7ad3-4c28-bc5a-31b86ef51cf6" />
<img width="395" height="209" alt="lean_canvas" src="https://github.com/user-attachments/assets/4085de3a-1f52-4774-a288-47f825125b35" />


Founders and students often produce a Lean Canvas in an hour and treat it as truth. The real risk sits in untested assumptions (who pays, how much, how they are acquired).

Startup Concept

We help home-based tiffin providers in Tier-2/3 Indian cities solve manual subscription and payment tracking through a WhatsApp-first tool so that they can collect payments on time and save admin hours.

Methodology

Idea → Founder Assumption Register → Problem/Customer/Competitor/Market research → Lean Canvas v1 → Confidence scoring → Riskiest-assumption tests → Experiments → Updated canvas (v2…v4).

What is in this repo
Folder	Contents
financial-model/	TiffinSathi_LBMC_Workbook.xlsx — 16 sheets, ~290 live formulas (assumptions, scoring, unit economics, 12-month scenarios, dashboard)
dashboard/	dashboard.html — static visual summary of the workbook
app/	app.py — optional Streamlit tool (rule-based scoring + canvas export)
docs/	Final validation report, experiment plan, interview guide
startup-input/, customer-research/, market-research/, competitor-analysis/, lean-canvas/, business-model/, validation-experiments/	Notes pointing to the matching workbook sheet; add real evidence here
screenshots/	Dashboard, Lean Canvas, risk matrix, score, experiment planner
Key Findings (current evidence level)
Validation score: 27/100 → rule-based recommendation: TEST FURTHER.
5 of 12 assumptions are HIGH RISK: channel cost (CAC), willingness to pay, reminder effectiveness, payment-loss size, churn.
Hypothetical unit economics: ARPU ₹539, contribution ₹424, CAC ₹1,500, LTV ≈ ₹7,067 (LTV:CAC ≈ 4.7) — only valid if inputs hold.
Base case: ~105 customers by month 12 vs ~133 needed to break even; peak cash need ≈ ₹5.9 lakh (projection, not forecast).
Defensible advantage has not yet been established.
Final Recommendation

TEST FURTHER. Next experiment: 15 provider interviews + pricing/pre-order test before building anything.

Tools Used

Excel (openpyxl-generated), Python, Streamlit (optional), HTML/CSS, AI assistant for structuring (never as evidence).

Limitations

Desk research from low-reliability blog sources; market counts are hypotheses; competitor list needs verification; confidence scores are founder judgement.

Future Scope

Automation: survey integration, competitor research helpers, version tracking, live KPIs. Real-world validation (separate): interviews, paid pilot, real CAC/churn.

Conclusion

The value of the tool is the discipline: it shows what is believed, what is known, and the cheapest next test.

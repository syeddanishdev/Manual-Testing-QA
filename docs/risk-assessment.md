Risk Assessment and Matrix for Manual Testing
Risk-based testing prioritizes critical functionalities based on impact and likelihood.
Risk Assessment Process

Identify Risks: Analyze requirements and critical paths (e.g., payment processing).
Evaluate Impact: Consider business impact (revenue loss, user trust).
Assess Likelihood: Evaluate defect history, code complexity, and change frequency.
Prioritize Testing: Use the risk matrix to focus on high-risk areas.
Integrate with Testing: Add "Risk_Level" to test cases for prioritization.

Risk Matrix



Likelihood / Impact
Low Impact
Medium Impact
High Impact



High Likelihood
Medium
High
Critical


Medium Likelihood
Low
Medium
High


Low Likelihood
Low
Low
Medium


Example Application
For an e-commerce app:

Payment Failure (Critical): High impact (revenue loss), high likelihood (complex integrations). Test exhaustively.
Login Failure (High): High impact (blocks access), medium likelihood (stable module). Test thoroughly.
UI Misalignment (Low): Low impact (aesthetic), low likelihood (static). Test minimally.

Implementation

Assign risk levels (Critical, High, Medium, Low) to test cases.
Example: "TC004_Payment_Success" = Critical.
Prioritize test execution based on risk level in test plans.

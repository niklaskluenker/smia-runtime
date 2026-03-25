Example – Decision Evaluation

Input

M – Meaning Space
R – Rule Set
A – Action Space

Call

evaluateDecision(M, R, A)

Output

Decision Package

{
  admissible_actions: [...],
  rejected_actions: [...],
  constraint_evaluation: [...],
  policy_lineage: [...],
  evidence: [...]
}

Only admissible actions may execute.
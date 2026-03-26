SMIA – Example Risk Decision

Meaning Space

transaction  
risk_score  
identity_status

Rule Set

risk policy  
fraud constraints

Action Space

approve  
reject  
escalate

Constraint Evaluation

approve → violates risk constraint  
escalate → satisfies policy

Decision Package

allowed: escalate  
disallowed: approve

Evidence

risk threshold exceeded  
policy applied  
constraint trace recorded

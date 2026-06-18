# Pull Request Template

---

## Change Area (Mandatory)

- [ ] Backend  
- [ ] Frontend  
- [ ] Infrastructure  
- [ ] Full Stack  

---

## Summary (Mandatory)

Describe clearly:
- What has changed  
- Why the change is required  
- Key implementation/design considerations  

---

## Work Item (Mandatory)

- ADO / Jira / User Story ID:

---

# Backend Checklist
*(Complete if `/src/backend` is impacted)*

- [ ] API → Service → Repository pattern followed  
- [ ] No business logic in controllers/routes  
- [ ] Pydantic validation implemented  
- [ ] Type hints added  
- [ ] ORM usage follows standards  
- [ ] No raw SQL in service layer  
- [ ] Authentication/Authorization reviewed  
- [ ] Input validation completed  
- [ ] No secrets committed  
- [ ] Structured logging implemented  
- [ ] Unit tests added/updated  
- [ ] Integration tests updated  
- [ ] Ruff checks passed  
- [ ] Sonar issues resolved  
- [ ] No breaking API changes  

---

# Frontend Checklist
*(Complete if `/src/frontend` is impacted)*

- [ ] Feature-based architecture maintained  
- [ ] No business logic in components  
- [ ] Reusable components used  
- [ ] State management follows project standards  
- [ ] API integration follows shared services pattern  
- [ ] Responsive design verified  
- [ ] Accessibility reviewed  
- [ ] Unit tests updated  
- [ ] No console logs  
- [ ] No unused code  

---

# Infrastructure Checklist
*(Complete if `/infra` is impacted)*

- [ ] Bicep/Terraform validation completed  
- [ ] Managed Identity used where applicable  
- [ ] RBAC reviewed  
- [ ] Key Vault used for secrets  
- [ ] Network security rules reviewed  
- [ ] No hardcoded environment values  
- [ ] Cost impact reviewed  
- [ ] Monitoring/alerts configured if required  
- [ ] Deployment tested  

---

# Testing

## Testing Performed

- [ ] Unit Testing  
- [ ] Integration Testing  
- [ ] Manual Testing  
- [ ] UAT  

---

## Testing Details

Provide details of:
- Scenarios tested  
- Commands/runbooks used  
- Environments validated  
- Any issues found and fixes applied  

---

# Reviewer Focus Area

Specify areas where reviewers should pay extra attention (e.g., security, performance, API changes, networking, cost impact).

---

# Additional Notes (Optional)

Include any additional context:
- Known limitations  
- Follow-up work  
- Deployment considerations  

---
`

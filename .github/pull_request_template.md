# Pull Request Template

---

## Change Area (Mandatory)

- [ ] Backend  
- [ ] Frontend  
- [ ] Infrastructure
- [ ] Documentation

---

## Summary (Mandatory)

Describe clearly:
- What has changed  
- Why the change is required  
- Key implementation/design considerations  

---

## Work Item (Mandatory)

- Jira Work Item ID:

---

# Backend Checklist
*(Complete if `/backend` is impacted)*

- [ ] API → Service → Repository pattern followed
- [ ] Functions → Service → Repository pattern followed
- [ ] No business logic in controllers/routes  
- [ ] Pydantic validation implemented  
- [ ] Type hints added  
- [ ] ORM usage follows standards  
- [ ] No raw SQL in service layer  
- [ ] Authentication/Authorization implemented  
- [ ] Input validation completed  
- [ ] No secrets committed  
- [ ] Structured logging implemented  
- [ ] Unit tests added/updated  
- [ ] Integration tests updated
- [ ] Sonar issues resolved  
- [ ] No breaking API changes
- [ ] Documents created/updated

---

# Frontend Checklist
*(Complete if `/frontend` is impacted)*

- [ ] Feature-based architecture maintained  
- [ ] No business logic in components  
- [ ] Reusable components used  
- [ ] State management follows project standards  
- [ ] API integration follows shared services pattern
- [ ] Authentication/Authorization implemented  
- [ ] Responsive design verified  
- [ ] Accessibility reviewed  
- [ ] Unit tests updated  
- [ ] No console logs  
- [ ] No unused code
- [ ] Documents created/updated

---

# Infrastructure Checklist
*(Complete if `/infra` is impacted)*

- [ ] Terraform validation completed  
- [ ] Managed Identity used where applicable  
- [ ] RBAC reviewed  
- [ ] Key Vault used for secrets  
- [ ] Network security rules reviewed  
- [ ] No hardcoded environment values  
- [ ] Cost impact reviewed  
- [ ] Monitoring/alerts configured if required  
- [ ] Deployment tested
- [ ] Documents created/updated

---

# Testing

## Testing Performed

- [ ] Unit Testing  
- [ ] Integration Testing  
- [ ] Manual Testing   

---

## Testing Details

Provide details of:
- Scenarios tested  
- Commands/runbooks used  
- Environments validated  
- Any issues found and fixes applied  

---

`

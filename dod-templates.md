# DoD Templates and Examples

## DoD Compliance Report

```
# Definition of Done - Compliance Report

## Component Information
- Component Name: 
- Version/Release: 
- Date of Verification: 
- Verified By: 

## Compliance Summary
- Overall Compliance: [ ] Complete [ ] Partial [ ] Non-compliant
- Automated Verification: __% of criteria verified automatically
- Manual Verification: __% of criteria verified manually
- Exceptions: __ approved exceptions

## Detailed Compliance Status

### Code Quality
- Unit Tests: [ ] Complete [ ] Partial [ ] Non-compliant
- Integration Tests: [ ] Complete [ ] Partial [ ] Non-compliant
- Code Coverage: [ ] Complete [ ] Partial [ ] Non-compliant
- Linting Standards: [ ] Complete [ ] Partial [ ] Non-compliant
- Type Safety: [ ] Complete [ ] Partial [ ] Non-compliant

### Performance
- Benchmarks: [ ] Complete [ ] Partial [ ] Non-compliant
- Scalability Tests: [ ] Complete [ ] Partial [ ] Non-compliant
- Resource Usage: [ ] Complete [ ] Partial [ ] Non-compliant
- Response Times: [ ] Complete [ ] Partial [ ] Non-compliant

### Security
- Authentication: [ ] Complete [ ] Partial [ ] Non-compliant
- Authorization: [ ] Complete [ ] Partial [ ] Non-compliant
- Data Protection: [ ] Complete [ ] Partial [ ] Non-compliant
- Audit Logging: [ ] Complete [ ] Partial [ ] Non-compliant

### Monitoring
- Health Checks: [ ] Complete [ ] Partial [ ] Non-compliant
- Alert Rules: [ ] Complete [ ] Partial [ ] Non-compliant
- Metrics Collection: [ ] Complete [ ] Partial [ ] Non-compliant
- Dashboards: [ ] Complete [ ] Partial [ ] Non-compliant

### Documentation
- API Specifications: [ ] Complete [ ] Partial [ ] Non-compliant
- Architecture Diagrams: [ ] Complete [ ] Partial [ ] Non-compliant
- Component Interactions: [ ] Complete [ ] Partial [ ] Non-compliant
- Deployment Guide: [ ] Complete [ ] Partial [ ] Non-compliant
- Configuration Guide: [ ] Complete [ ] Partial [ ] Non-compliant

### Operations
- Deployment Scripts: [ ] Complete [ ] Partial [ ] Non-compliant
- Scaling Policies: [ ] Complete [ ] Partial [ ] Non-compliant
- Backup Procedures: [ ] Complete [ ] Partial [ ] Non-compliant
- Recovery Plans: [ ] Complete [ ] Partial [ ] Non-compliant

## Exception Details
1. [Item]: [Justification for exception]
2. [Item]: [Justification for exception]

## Action Items
1. [Action Item]: [Owner] - [Due Date]
2. [Action Item]: [Owner] - [Due Date]

## Approvals
- Technical Lead: ______________ Date: ______________
- QA Lead: ______________ Date: ______________
- Product Owner: ______________ Date: ______________
```

## DoD Exception Request

```
# DoD Exception Request

## Request Information
- Component/Feature: 
- Requested By: 
- Date Requested: 
- Sprint/Release: 

## Exception Details
- DoD Criteria Exception: [Specific DoD item(s) for exception]
- Category: [ ] Code Quality [ ] Performance [ ] Security [ ] Monitoring [ ] Documentation [ ] Operations

## Justification
[Detailed explanation of why this exception is necessary]

## Impact Assessment
- Technical Debt Impact: [ ] High [ ] Medium [ ] Low
- Quality Impact: [ ] High [ ] Medium [ ] Low
- Security Impact: [ ] High [ ] Medium [ ] Low
- Operational Impact: [ ] High [ ] Medium [ ] Low

## Mitigation Plan
- Proposed Alternative: [Alternative approach if applicable]
- Timeline for Resolution: [When will this exception be addressed]
- Tracking: [JIRA ticket or other tracking reference]

## Risk Analysis
- Identified Risks: [List potential risks of this exception]
- Risk Mitigation: [Steps to minimize these risks]

## Approval Status
- Technical Lead: [ ] Approved [ ] Rejected - Date: __________
- QA Lead: [ ] Approved [ ] Rejected - Date: __________
- Product Owner: [ ] Approved [ ] Rejected - Date: __________
- Security Lead (if applicable): [ ] Approved [ ] Rejected - Date: __________

## Comments
[Any additional comments from approvers]
```

## DoD Audit Checklist

```
# DoD Audit Checklist

## Audit Information
- Project: 
- Sprint/Release: 
- Date of Audit: 
- Auditor(s): 

## Process Audit
- [ ] DoD is documented and accessible to all team members
- [ ] DoD criteria are included in definition of user stories
- [ ] DoD verification is part of the acceptance process
- [ ] DoD exceptions are properly documented and approved
- [ ] DoD compliance is tracked and reported

## Random Sampling
Select 3-5 recently completed stories/features for detailed verification:

### Item 1: [Story/Feature ID]
- [ ] All DoD criteria have verification evidence
- [ ] Automated verification results are available
- [ ] Manual verification has documentation
- [ ] Any exceptions have proper approval
- [ ] Verification covers all component categories

### Item 2: [Story/Feature ID]
- [ ] All DoD criteria have verification evidence
- [ ] Automated verification results are available
- [ ] Manual verification has documentation
- [ ] Any exceptions have proper approval
- [ ] Verification covers all component categories

[Repeat for additional samples]

## Effectiveness Assessment
- [ ] DoD criteria are relevant to project needs
- [ ] Verification methods are effective
- [ ] DoD compliance correlates with quality metrics
- [ ] Team members understand and follow DoD
- [ ] DoD evolves based on project learnings

## Findings
- Strengths: [List areas where DoD is working well]
- Weaknesses: [List areas where DoD needs improvement]
- Recommendations: [Specific recommendations for improvement]

## Action Items
1. [Action]: [Owner] - [Due Date]
2. [Action]: [Owner] - [Due Date]
3. [Action]: [Owner] - [Due Date]

## Audit Result
- Overall Assessment: [ ] Satisfactory [ ] Needs Improvement [ ] Unsatisfactory
- Follow-up Audit Required: [ ] Yes [ ] No - Date if Yes: __________

## Signatures
- Auditor: ______________ Date: ______________
- Project Manager: ______________ Date: ______________
- Development Lead: ______________ Date: ______________
```

## Example: Feature DoD Compliance Evidence

```
# Feature DoD Compliance Evidence: User Authentication Module

## Code Quality
- Unit Tests: COMPLETE
  - Evidence: 37 unit tests in AuthServiceTests.js with 94% coverage
  - Link: [Jenkins Build #452](http://jenkins/build/452)
  
- Integration Tests: COMPLETE
  - Evidence: 12 integration tests in AuthIntegrationTests.js
  - Link: [Jenkins Build #452](http://jenkins/build/452)
  
- Code Coverage: COMPLETE
  - Evidence: 91% overall coverage, 94% on AuthService.js
  - Screenshot: [Coverage Report](http://sonarqube/project/auth-service)
  
- Linting Standards: COMPLETE
  - Evidence: No ESLint errors, 2 warnings (documented exceptions)
  - Link: [Sonar Results](http://sonarqube/project/auth-service)
  
- Type Safety: COMPLETE
  - Evidence: TypeScript strict mode enabled, no any types

## Performance
- Benchmarks: COMPLETE
  - Evidence: Login response < 200ms at p95 under load
  - Link: [Performance Test Report](http://wiki/perf-report-auth-2023-04-11)
  
[Additional sections with similar detailed evidence...]

## Exceptions
1. Cache Invalidation Alert Rule: APPROVED EXCEPTION
   - Justification: Caching service not yet deployed to production
   - Tracking: JIRA-1234 for implementation in next sprint
   - Approval: Jane Smith (Technical Lead) on 2023-04-10

## Verification Sign-off
- Developer: Alex Johnson - 2023-04-11
- Peer Reviewer: Maria Garcia - 2023-04-11
- QA: Jamal Washington - 2023-04-12
```
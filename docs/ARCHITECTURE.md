# Architecture — my ICT306 portal design

- **Presentation layer:** web portal (job postings, skill-gap analysis, application tracking, reporting dashboards)
- **Application layer:** business logic, Moodle API integration, role-based access control
- **Database layer:** student / job / application records, on-premise alongside Moodle in the hybrid design
- **Deployment:** hybrid — cloud-hosted portal (AWS / Azure) + on-premise Moodle
- **Security / privacy:** HTTPS, CIA triad, Privacy Act 1988 and Australian Privacy Principles compliance
- **Rollout:** phased — requirements → design → pilot → full deployment, with a Gantt chart, cost-benefit analysis and risk register

This repo documents the design of the portal from my ICT306 report and presentation. It is not a running system.

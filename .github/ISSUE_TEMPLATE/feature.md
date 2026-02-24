---
name: Feature
about: Suggest a feature or enhancement idea
title: ''
labels: feature
type: Feature
assignees: ''

---

What?
---

Why?
---

Why now?
---

Scope
---

### Client

<!---
- List all screens and components that needs changing and describe the change
- List down all apps, addons like custom functions, outlook, gmail and utils
- Divide between existing and new screens
- Add design checklist in separate comment
--->

### Server

<!---
- List all apis, dao and server changes needed
- List all the activity changes needed for entities
- Write breaking change in a separate comment
--->

### Database

<!---
- Write a brief about db changes (write in detail in separate comment)
--->

### Security

<!---
- Write a brief about how would security look like for your entities and if any changes are needed
--->

### Data Migration

<!---
- Write a brief about any migration or scripts needed to run it.
- add 'roll-back plan' if needed
--->

Deployment
---

<!---
Write a detailed plan (add a notion link if breaking change) include 
- new services
- db changes
- new secrets
- major/minor updates (if changing blue/green, see how it's going to impact all existing clients)
- Post-deployment verification plan
- Monitoring / alerts setup
--->

### Backward Compatibility

<!---
- Is it backward compatible?
- Can new client work with older server, can new server work with older client, and such..
--->

Testing
---

<!---
Write about test cases - Is it automated tested? Do we have unit test cases?
(Write a detailed testing checklist in a separate comment)
--->

Not doing
---

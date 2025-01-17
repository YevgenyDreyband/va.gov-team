# Project outline: Profile hub MVP

**Last Updated: August 4, 2023**

### Communications

- **Github labels**: authenticated-experience
- **Slack channel**: [#accountexp-authexp](https://dsva.slack.com/channels/accountexp-authexp)

### Roles

#### OCTO team

[This is managed by the VA.gov profile team](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/README.md#roles).

### Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [User Outcomes](#user-outcomes)
- [Business Outcomes](#business-outcomes)
- [Measuring Success](#measuring-success)
- [Key deliverables](#key-deliverables)
- [Key Dates](#key-dates)
- [Design](#design)
- [Frontend](#frontend)

## Overview

When we launched [profile 2.0](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account#readme) in 2020, the profile went from a single page to a multi-page section. The URL `va.gov/profile` became obsolete, as we opted to land users right on the first page of the profile (at the time, a combined personal & contact information section), which had a more specific URL.

While landing people directly in the first section of the profile generally doesn't cause usability issues, there have been two notable exceptions to this:

- In the mobile view, people often don't realize the profile menu is collapsed, and they think `Personal information` is the only section of the profile. We have seen this in usability testing, and we think this might be why we sometimes see search results for sections that are already part of the profile.
- For people that use screen readers, they expect to land on a page with an H1 that says `Profile` after clicking on the profile link from the authenticated menu. But since we drop people right into `Personal information`, there is no `Profile` header. This breaks accessibility best practices.

To solve for these problems, we are building a profile hub page, which resolves the issues mentioned above by doing the following:

- On mobile, it allows people to scan a page instead of an easy-to-miss menu for the contents of the profile.
- This allows us to create a proper profile landing page with a `Profile` H1, which aligns with accessibility best practices.

## Problem Statement

- As a mobile user, I can easily miss the mobile menu in the profile, which leads me to think that `Personal information` is the only section of the profile.
- As a person using a screen reader, I expect to see a `Profile` H1 when I go to the profile.

## User Outcomes

### Desired User Outcomes

*Why would a user want to use this? With this problem solved, what should users be able to do/achieve that they couldn't before?*

- On mobile, users can more easily scan for what is available in the profile.
- For people using screen readers, it will be much clearer that links to `Profile` landed them in the right place.

### Undesired User Outcomes

- This reduces overall scannability of the profile.

## Business Outcomes

### Desired Business Outcomes

*Why would your business want this to exist? With this problem solved, what should your business be able to do/achieve that they couldn't before?*

- This allows us to fix longstanding issues for mobile and screen reader users.
- This allows us to surface links associated with the profile without having to build whole new sections within the profile.
- This allows us to experiment with the hub model and whether it might be part of a more holistic authenticated experience.
  
### Undesired Business Outcomes

- The profile hub becomes a dumping ground.

## Measuring Success

TBD

## Key deliverables

(This is just a starting list. Feel free to add whatever is relevant here.)

- Project epic
- Sketch files
- Release plan

## Key dates

- July 2023: Initial discussions; project kickoff

## Design

- Add link to Sketch files
   
### Before

### After

## Frontend


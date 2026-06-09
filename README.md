# Contribution [1]: [Immich Issue]

**Contribution Number:** 1

**Student:** [Yishak Teklemariam]

**Project:** Immich

**Issue:** [https://github.com/immich-app/immich]

**Status:** Phase I – Issue Analysis and Selection

---

# Why I Chose This Issue

I chose to contribute to Immich because I recently became interested in photography and digital media management. As my personal collection of photos continues to grow, I have become more aware of the challenges associated with storage, organization, searchability, and long-term backup solutions. Immich addresses many of these problems by providing a self-hosted alternative to commercial photo management platforms, making it both personally relevant and technically interesting.

From a software engineering perspective, this project aligns well with my interests in backend development, APIs, databases, and distributed systems. Contributing to a real-world application used by thousands of users will allow me to gain experience navigating a large codebase, collaborating with maintainers, and following open-source development workflows. I hope to improve my debugging skills, learn more about how media platforms manage data at scale, and become more comfortable contributing to community-driven software projects.

---

# Understanding the Issue

## Problem Description

The issue describes a problem where duplicate photos are displayed in search results. In simple terms, users may see the same photo multiple times when performing a search, even though only one copy exists in their library.


In simple terms, the application is currently unable to avoid duplicate photos appear in search results.

## Expected Behavior

The system should:

* Display each photo only once in search results.
* Return accurate search results based on the query.
* Maintain consistent behavior across different search filters.

Users should be able to complete the intended workflow without encountering unexpected results.

## Current Behavior

Currently:

* Some photos appear multiple times in search results.
* The number of returned results is inflated
* Users may have difficulty finding the correct photos because of duplicate entries.

This creates confusion for users and prevents the feature from behaving as intended.

## Affected Components

Based on my initial investigation, the following components may be involved:

* Frontend user interface components
* Backend API endpoints
* Database queries or models
* Service-layer business logic
* Existing test suites related to the feature

The exact files will be identified during the reproduction phase.

---

# Reproduction Process

## Environment Setup

To prepare for reproducing the issue, I completed the following setup tasks:

* Forked the Immich repository
* Cloned my fork locally
* Reviewed the README and CONTRIBUTING documentation
* Installed project dependencies
* Configured the required development environment
* Successfully launched the application locally

### Setup Challenges

Potential challenges encountered:

* Docker configuration
* Environment variable setup
* Database initialization
* Dependency version compatibility

Any issues encountered and solutions used will be documented here.

## Steps to Reproduce

1. Launch Immich in the local development environment.
2. Navigate to the feature referenced in the issue.
3. Perform the actions described in the issue report.
4. Observe the resulting behavior.
5. Compare actual behavior against expected behavior.

## Reproduction Evidence

### Commit Showing Reproduction

[TBD – commit link]

### Screenshots / Logs

[TBD]

### Findings

Initial observations and debugging notes will be recorded here, including:

* Relevant log output
* Error messages
* API responses
* Potential root causes

---

# Solution Approach

## Analysis

Based on the issue description and initial investigation, I believe the problem may originate from:

* Incorrect validation logic
* Missing edge-case handling
* State management inconsistencies
* API response handling
* Database query behavior

Further debugging will confirm the exact root cause.

## Proposed Solution

My planned solution is to:

1. Identify the specific component responsible for the incorrect behavior.
2. Trace the execution path leading to the issue.
3. Implement a targeted fix that addresses the root cause rather than only the symptom.
4. Add or update tests to prevent regressions.

## Implementation Plan (UMPIRE)

### Understand

The application does not behave as expected when [issue scenario].

### Match

I will review:

* Existing implementations of similar features
* Related issues and pull requests
* Existing validation and testing patterns within the codebase

### Plan

1. Reproduce the issue locally.
2. Identify the affected files and services.
3. Implement the fix.
4. Add automated tests.
5. Verify existing functionality remains unaffected.
6. Submit a pull request for review.

### Implement

Branch: [branch name]

Commits: [links will be added here]

### Review

Before submission I will verify:

* Code follows project standards
* Existing tests pass
* New tests cover the issue
* Documentation updates are included if necessary
* Pull request guidelines are satisfied

### Evaluate

Success criteria:

* Issue can no longer be reproduced
* Existing functionality continues working
* Automated tests pass
* Maintainers approve the implementation

---

# Testing Strategy

## Unit Tests

* [ ] Verify expected behavior under normal conditions
* [ ] Verify edge-case handling
* [ ] Verify invalid inputs are handled correctly

## Integration Tests

* [ ] Verify interaction between frontend and backend
* [ ] Verify database operations behave correctly

## Manual Testing

I will manually execute the reproduction steps after implementing the fix and confirm that:

* The issue no longer occurs
* No new defects were introduced
* User workflows continue functioning correctly

---

# Implementation Notes

## Week 1 Progress

* Selected project and issue
* Reviewed project documentation
* Set up development environment
* Began issue analysis

## Week 2 Progress

* Reproduced issue locally
* Investigated root cause
* Identified affected files and components

## Week 3 Progress

* Implemented fix
* Added tests
* Performed validation testing

## Week 4 Progress

* Submitted pull request
* Addressed maintainer feedback
* Finalized contribution

## Code Changes

### Files Modified

[TBD]

### Key Commits

[TBD]

### Design Decisions

Design decisions and trade-offs made during implementation will be documented here.

---

# Pull Request

## PR Link

[TBD]

## PR Summary

This pull request resolves [issue number] by addressing the underlying cause of the problem and adding automated tests to prevent future regressions.

### Changes Included

* Implemented issue fix
* Added/updated tests
* Updated documentation if necessary

## Maintainer Feedback Log

### [Date]

Feedback:
[TBD]

Response:
[TBD]

## Status

Awaiting Review

---

# Learnings & Reflections

## Technical Skills Gained

Through this contribution I expect to gain experience with:

* Large-scale open-source codebases
* Debugging production software
* Reading unfamiliar code
* Writing maintainable tests
* Open-source collaboration workflows

## Challenges Overcome

This section will document technical and workflow challenges encountered throughout the contribution process and how they were resolved.

## What I Would Do Differently

Reflection on lessons learned and improvements for future contributions.

---

# Resources Used

* Immich Documentation
* Immich CONTRIBUTING.md
* Relevant GitHub Issues and Discussions
* Official framework documentation
* Additional debugging and testing resources

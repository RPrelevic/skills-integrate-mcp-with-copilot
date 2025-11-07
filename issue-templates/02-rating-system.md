# ⭐ Add Activity Rating System

## Description
Implement a rating system that allows students to rate activities and view average ratings to help others make informed decisions.

## Current State
No way for students to provide feedback or see quality metrics for activities.

## Proposed Solution
- Add 5-star rating system for each activity
- Display average rating on activity cards
- Show number of ratings received
- Allow students to submit ratings after joining activities
- Store ratings in backend (enhance data model)

## Acceptance Criteria
- [ ] Star rating component added to activity cards
- [ ] Backend endpoint to submit ratings
- [ ] Backend endpoint to retrieve rating statistics
- [ ] Display average rating and count on UI
- [ ] Prevent multiple ratings from same user
- [ ] Visual indication of rating quality (stars display)

## Priority: Medium
## Difficulty: Medium

## Technical Notes
- Requires backend database changes
- Need to extend activity data model
- Consider user identification for preventing duplicate ratings
- Could start with simple localStorage implementation

**Labels:** `enhancement`, `backend`, `frontend`, `user-experience`

*Inspired by DiscoverU project research.*
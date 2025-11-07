I need to create the following GitHub issues for the Mergington High School Activities project based on DiscoverU research:

## Issue 1: 🔍 Add Search Functionality for Activities
**Priority**: High | **Difficulty**: Easy
**Title**: Add Search Functionality for Activities
**Labels**: enhancement, good first issue, frontend

**Body**:
## 🔍 Description
Add search functionality to allow students to quickly find activities by name, description, or keywords.

## Current State
Students can only browse through all activities in a list format.

## Proposed Solution
- Add search input field above the activities list
- Implement client-side filtering for immediate results
- Search should work on activity name, description, and schedule
- Include placeholder text like 'Search activities...'

## Acceptance Criteria
- [ ] Search input field added to the UI
- [ ] Real-time filtering as user types
- [ ] Search works on activity name and description
- [ ] Clear search functionality
- [ ] Responsive design maintained

## Priority: High
## Difficulty: Easy

## Technical Notes
- Can be implemented with JavaScript filtering
- No backend changes required initially  
- Could be enhanced later with backend search API

*Inspired by DiscoverU project research.*

---

## Issue 2: 🎨 Modernize UI/UX Design
**Priority**: Medium | **Difficulty**: Easy
**Title**: Modernize UI/UX Design
**Labels**: enhancement, frontend, design, css, user-experience

**Body**:
## 🎨 Description
Update the visual design and user experience to be more modern, engaging, and user-friendly with better colors, typography, and interactions.

## Current State
Basic CSS styling with minimal visual appeal and limited interactive elements.

## Proposed Solution
- Modern color scheme and typography
- Improved card designs with shadows and hover effects
- Better mobile responsiveness
- Loading states and animations
- Consistent design system
- Enhanced visual hierarchy

## Acceptance Criteria
- [ ] Updated color palette and typography
- [ ] Modern card design with hover effects
- [ ] Improved mobile responsiveness
- [ ] Loading animations and states
- [ ] Consistent spacing and layout
- [ ] Enhanced visual feedback for interactions
- [ ] Dark mode support (optional)

## Priority: Medium
## Difficulty: Easy

## Technical Notes
- Primarily CSS/styling changes
- Consider CSS framework (Tailwind, Bootstrap) or custom design system
- Ensure accessibility standards (contrast, focus states)
- Optimize for different screen sizes
- Could add CSS animations and transitions

*Inspired by DiscoverU project research.*

---

## Issue 3: ⭐ Add Activity Rating System
**Priority**: Medium | **Difficulty**: Medium
**Title**: Add Activity Rating System
**Labels**: enhancement, backend, frontend, user-experience

**Body**:
## ⭐ Description
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

*Inspired by DiscoverU project research.*

---

Please use GitHub Copilot's MCP GitHub server to create these issues in the repository.
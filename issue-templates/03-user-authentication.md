# 🔐 Add User Authentication System

## Description
Implement user authentication to enable personalized features like activity history, bookmarks, and personalized recommendations.

## Current State
No user accounts - students only provide email for signup without persistent identity.

## Proposed Solution
- Student registration and login system
- Secure password authentication
- User sessions and profile management
- Personal dashboard showing joined activities
- User-specific activity history

## Acceptance Criteria
- [ ] User registration form (name, email, password, grade)
- [ ] User login form with session management
- [ ] User profile page
- [ ] Personal dashboard with joined activities
- [ ] Secure password hashing
- [ ] Session cookies/JWT implementation
- [ ] Logout functionality
- [ ] "My Activities" personalized view

## Priority: Medium
## Difficulty: High

## Technical Notes
- Requires significant backend changes
- Need database for user storage
- Security considerations (password hashing, sessions)
- Consider using FastAPI's built-in security features
- Could integrate with school's existing auth system

**Labels:** `enhancement`, `backend`, `security`, `major-feature`

*Inspired by DiscoverU project research.*
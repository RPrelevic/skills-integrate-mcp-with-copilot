# 🎯 Add Activity Bookmarking & Favorites

## Description
Allow students to bookmark/favorite activities they're interested in but haven't joined yet, creating a personalized wishlist.

## Current State
Students can only sign up for activities immediately - no way to save activities for later consideration.

## Proposed Solution
- Bookmark/favorite button on each activity card
- "My Favorites" page showing bookmarked activities
- Heart or bookmark icon to indicate saved status
- Easy transition from bookmark to signup
- Local storage initially, database storage later

## Acceptance Criteria
- [ ] Bookmark button on activity cards
- [ ] Visual indication of bookmarked status
- [ ] "My Favorites" page or section
- [ ] Remove from favorites functionality
- [ ] Persistent bookmarks across sessions
- [ ] Integration with user accounts (if implemented)

## Priority: Medium
## Difficulty: Easy (with localStorage) / Medium (with backend)

## Technical Notes
- Can start with browser localStorage
- Later integrate with user authentication system
- Simple toggle functionality required
- Consider bookmark limits or organization
- Could add bookmark sharing features

**Labels:** `enhancement`, `frontend`, `user-experience`, `personalization`

*Inspired by DiscoverU project research.*
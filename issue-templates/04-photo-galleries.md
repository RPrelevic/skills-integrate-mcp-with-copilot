# 🖼️ Add Photo Galleries for Activities

## Description
Add visual elements to activities by including photo galleries that showcase what each activity is about and past events.

## Current State
Activities only have text descriptions with no visual elements.

## Proposed Solution
- Add photo upload capability for activity organizers
- Display photo galleries on activity detail pages
- Thumbnail previews on activity cards
- Lightbox/modal view for full-size photos
- Organize photos by activity and event

## Acceptance Criteria
- [ ] Photo upload interface for activity organizers
- [ ] Photo storage solution (local files or cloud)
- [ ] Gallery display component
- [ ] Thumbnail generation and display
- [ ] Lightbox/modal for viewing full-size images
- [ ] Photo management (add/remove photos)
- [ ] Responsive image display

## Priority: Medium
## Difficulty: Medium

## Technical Notes
- Need file upload handling in FastAPI
- Image storage and serving solution required
- Consider image optimization and thumbnails
- Could start with local file storage
- May need image processing library (Pillow)

**Labels:** `enhancement`, `backend`, `frontend`, `media`, `user-experience`

*Inspired by DiscoverU project research.*
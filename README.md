# MyUCF Improvement

Description
========
My team and I agreed to re-create and re-design the course registration catalog for the University of Central Florida.
The current system in place at my.ucf.edu uses Oracle's Peoplesoft software which hasn't changed since 2007 according to one Reddit user. The current system is awful for modern standards. It takes forever to load courses, search, register, waitlist, swap classes, and navigating the website is confusing.

Motivations
=========
# Pros
- Save on costs instead of  Combined hours saved by student population
- Value for UCF / long term investment
- Could create more information technology jobs at UCF by having to maintain our own system
- Less reliance on third parties (Oracle)
- Really wanted by the student body (show multiple reddit posts with hundreds of upvotes)

# Cons
- Could be more expensive to manage our own system
- Could be less secure to manage our own system than having a massive enterprise running it

New features
=========
- Link to rate my professor
- Integrate with rate my professor
- Student / Faculty Hierarchy / Privilege
- Some level of customization
- Proper search
- Single Sign On (SSO) functionality
- Analytics system for user detection
- System administration usage (overriding permissions)

Front end changes
==============
## Design Changes
- Landing portal should have most commonly used features (Discuss most commonly used features).
- Each link to a dropdown menu can take you directly to a link on the website at a different page.
- Each semester the courses that aren't offered anymore are deleted from the website.
- Course search catalog with different programs and filters should take you to a different space than the portal
- Eliminate drop down menu completely
- Add a search bar at the top with lazy search
- Course search is similar to Stanford's bulletin board: [bulletin board](https://bulletin.stanford.edu/courses?cq=&page=1)
- Or Stanford's online search website: [online course search](https://online.stanford.edu/explore)

## Back end changes for users
- Improve speed
- Speeds load instantaneously
- Common databases for managing 60,000+ simultaneous users: Oracle, MongoDB (NoSQL), MySQL

## Database
MongoDB

## Prototype
- User design
- Page layout and navigability
- UX/UI
- Creating a database

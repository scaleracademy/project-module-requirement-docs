# BLOGGING APP

## Problem Statement
Make a web application for blogging which has built in capabilities to handle various users.

---

## Requirements
- CRUD capabilities for **USERS**
- CRUD capabilities for **BLOGS** which would be scoped under a **USER**. *i.e. only the user which creates a blog would be able to modify/delete it*
- All **USERS** should be able to view **BLOGS** which have been posted
- A **USER** should be able to write a **BLOG** and post it for everyone to see
- A **USER** should be able to follow another **USER** so that their **BLOGS** have a higher priority on the former **USER**'s feed
- **USERS** should be able to **COMMENT** under a **BLOG**. *These comments would be public*
- **USERS** should be able to LIKE / UNLIKE a **BLOG**

---

## Basic Flow
### *Subject to changes basis of how you want the overall UX to be*
1. An initial signup/signin form to create a user profile on the application
2. A main feed where a user can see cards for various blogs. *Blogs from users which the current user has followed would have a higher priority in the feed*
3. A page which opens on clicking a blog card which contains the complete contents of the blog
4. An area to add comments and read other comments about the current blog
5. An editor where user can create blogs to be posted
6. An editor where user can edit the already posted blogs
7. Capability to view another user's profile and follow/unfollow them

---

## Expectations from Submission
### *Points which will be focussed on during evaluation*
- The code should be working and demonstrable
- Code should be written in a readable fashion using best practices
- Code should be optimised on various fronts and hardcoding logic should be avoided
- Kindly add a proper readme to your project for easy navigation and installation
- The overall UI should be easy to navigate and have good UX

---

## Good to haves (Optional Requirements)
### *Try to work on these features once all the required features are complete*
- Having the capability to add blogs to drafts before posting them
- Having the capability to schedule when a blog would get posted
- Sending notifications to all users who follow a current user when the current user posts a new blog or makes changes to an existing one
- Capability to sort feed via time of posting, topics etc.
- Making UI responsive
- Ability to club various blogs together under a bucket (topic) -> create a sequence of blogs

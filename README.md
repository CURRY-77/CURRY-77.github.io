# Club Management System

A web-based platform for managing college clubs, events, and hackathons, designed to enhance student engagement and streamline club-related activities across the campus.

---

## Table of Contents

- [Project Motivation (Why?)](#project-motivation-why)
- [Project Overview (What?)](#project-overview-what)
- [Folder Structure](#folder-structure)
- [Implementation Details (How?)](#implementation-details-how)
- [Tools Used](#tools-used)

---

## Project Motivation (Why?)

1. **Feed Page**
   - Students lack timely notifications for college events.
   - A centralized feed to post and update all upcoming events for visibility.
   - Event posting handled by authorized roles (Admin, Club President, Vice President) as per organization rules.

2. **Clubs Page**
   - Students are unaware of the variety and number of clubs.
   - Browse all clubs; apply to join (maximum 4 active applications per user).
   - Club officers manage incoming applications.

3. **My Clubs Page**
   - Accepted club applications are visible here.
   - Users can apply for event-related leave.

4. **Hackathons Page**
   - Increases awareness of upcoming hackathons and eases team formation.
   - Staff and club heads can post hackathon opportunities.
   - "Find a team" sub-section for team formation with contact info.

5. **Settings Page**
   - View user information (Name, Semester, ERP Id, Branch/Dept, Club memberships and roles).

---

## Project Overview (What?)

1. **Login/Sign Up**
   - Secure login for existing users (role-based authentication).
   - Registration possible only with college email (OTP verification required).
   - Registration form collects Name, Semester, Department, Branch, ERP Id (stored in SQL database).

2. **Feed Page**
   - Posts publicly visible to all logged-in users.
   - Interact with posts (Like, share link). 
   - Posts can include a caption, photo, and optional link.

3. **Clubs Page**
   - Displays all clubs and categories.
   - Users can apply to max 4 clubs at a time.
   - Club application form collects essential details and motivation.

4. **My Clubs**
   - List of joined clubs and fellow members.
   - "Event Leave" application workflow for class absences (approved by club and college authorities; notifications sent to HOD/coordinator via mail/SMS/WhatsApp or online application).
   - "Leave Club" functionality with mandatory reason and notification upon approval.

5. **Hackathons**
   - Announcements by admin/club heads.
   - Team formation requests with contact details.

6. **Settings**
   - Displays user profile and club roles.

---

## Folder Structure


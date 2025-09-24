# Club Management System

A web application for managing college clubs, events, and hackathons, enhancing student engagement and streamlining organizational activities.

---

## Table of Contents

- [Motivation (Why?)](#motivation-why)
- [Overview (What?)](#overview-what)
- [Folder Structure](#folder-structure)
- [Implementation (How?)](#implementation-how)
- [Tools Used](#tools-used)

---

## Motivation (Why?)

1. **Feed Page**  
   - Students often miss notifications about campus events.
   - The feed centralizes upcoming event announcements, managed by Admin, President, or Vice President as per institutional rules.

2. **Clubs Page**  
   - Lack of visibility into available clubs and categories.
   - Students can browse and apply (up to 4 clubs), with officers managing applications.

3. **My Clubs Page**  
   - Accepted applications are shown here, enabling functionality like event leave requests.

4. **Hackathons Page**  
   - Students miss hackathon updates and face challenges in forming teams.
   - Hackathons and team-up requests are posted by staff and club leaders.

5. **Settings Page**  
   - Users can view personal details, including enrolled clubs and roles.

---

## Overview (What?)

1. **Login/Sign Up**  
   - Role-based login (students, staff, admins).
   - Sign-up requires college email verification via OTP, collecting name, semester, department, and ERP Id (saved in SQL).

2. **Feed Page**  
   - Posts (caption, photo, link) visible to all logged-in users.
   - Like and share functionalities.

3. **Clubs Page**  
   - Club details publicly visible; users can apply for up to 4 clubs.
   - Application form requires motivation and basic info.

4. **My Clubs**  
   - Displays joined clubs and their members.
   - Apply for leave for events (workflow for multi-step approval and notification).
   - Leave club by submitting a reason.

5. **Hackathons**  
   - Announcements by admins/club heads.
   - Team-up posts with contact details.

6. **Settings**  
   - User profile and club information.

---

## Folder Structure


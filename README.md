# Teamder -- NTU Team Member Matching System
![GITHUB](https://i.imgur.com/6L9QzMm.png)
This is a website designed to help NTU students find team members. We initially envisioned the database (DB) structure as shown in the image below:
![GITHUB](https://i.imgur.com/bbdZ2pF.png)

## Features Overview
#### 1. Account Registration
Users provide personal information to make it easier for others to find them.
#### 2. Create Team Member Recruitment Posts
Include details like the required number of members, current number of members, applicants (not yet implemented), course code, course name, etc., to facilitate search.
#### 3. Search Posts (currently has bugs)
透過條件搜尋貼文
#### 4. View Personal Post Records
Users can view the posts they have created.
#### 5. Commenting Functionality (currently has bugs, does not display)
Users can leave comments under posts.
#### 6. View Other Users’ Personal Pages (UI not implemented)
Allows users to view others' personal information.
#### 7. Edit Personal Page
Users can edit their personal pages.
#### 8. Apply to Join a Team (not yet implemented)
Post creators can review applicants and approve their requests to join.

## How to run it (localhost)
### 1. clone the repository.
### 2. Navigate to your local directory.
### 3. Run the following command in your terminal (npm works too, if preferred):
    yarn install
### Note: Execute the command in both the `frontend/` and `backend/ `directories.
### 4. Run `yarn start` in the `Teamder/` directory:
    yarn start
### 5. Run `yarn server` in the `Teamder/` directory:
    yarn server
### 6. Done! you can now see the website on `localhost:3000`

## Responsibilities of Team Members:
#### B09705016 Chen Jin-Rui
* Deployment (frontend-backend separation)
* Model Schema
* Backend implementation for Comments and Requests
* Frontend-backend integration support
#### B09705049 Zhang Tian-Wei
* Frontend design
* UI layout and RWD
* Frontend-backend implementation for User Schema (historical posts, personal info)
#### B09502144 Kuo Li-Chuan
* Frontend design (Sign In, Sign Up, Personal Page, Request Page, Create New Request)
* UI layout
* Search functionality implementation
* PPT and video presentation



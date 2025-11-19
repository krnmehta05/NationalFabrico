# German Language Tutoring App Blueprint

## Overview

This document outlines the plan and features for a comprehensive German language tutoring application. The app will provide students with access to video lectures, a chatbot for language practice, and a personalized profile to track their progress.

## Implemented Features

- **Project Setup:** Initialized a Flutter project with `provider`, `google_fonts`, and `go_router`.
- **Theming:** Implemented a Material 3 theme with light/dark modes and custom fonts.
- **Authentication Flow:**
    - Created a UI for user login and sign-up.
    - Added a `SignUpScreen` with fields for registration.
    - **Testing:** Implemented a mock login for a test admin account with credentials `admin`/`admin`.
- **Course Selection Screen:** 
    - A screen for users to browse and select individual courses.
    - Added a new section for course bundles (e.g., A1+A2, A1-B2).
- **Navigation:** 
    - Added a back button to the `CourseSelectionScreen`.
    - Added a back button to the `SignUpScreen`.
- **Visuals:** Replaced placeholder images with actual images from `unsplash.com`.
- **Error Fixes:** Corrected a syntax error in the `SignUpScreen`.

## Current Plan

### 1. Content and Navigation
- **Course Detail Screen:** Create a screen to display the video lectures for a selected course.
- **Bundle Detail Screen:** Create a screen to display the details of a selected course bundle.
- **Bottom Navigation:** Implement a bottom navigation bar for easy access to the main sections (courses, chat, profile).

### 2. Advanced Features
- **AI Chatbot:** Build a chat screen with a Gemini-powered AI for language practice.
- **User Profile:** Design a profile screen to display user information and enrolled courses.

### 3. UI/UX Polish
- **Visual Design:** Enhance the UI with a modern and intuitive design.
- **Responsiveness:** Ensure the app is responsive on both mobile and web.

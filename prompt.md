# Programming Fundamentals Roadmap - HTML Project

## Overview

Create a visually appealing HTML file that serves as a complete learning roadmap based on Dr. Mohammed Abu-Hadhoud's 24 programming courses from ProgrammingAdvices.

## Requirements

### 1. Content Structure

The HTML file must include:

- **Header Section**
  - Title: "Programming Fundamentals Roadmap"
  - Subtitle: "Based on Dr. Mohammed Abu-Hadhoud's Complete Programming Curriculum — 24 Courses"

- **Overall Progress Dashboard**
  - Total Courses: 24
  - Completed Courses count
  - Total Lessons count
  - Completed Lessons count
  - Overall progress bar with percentage

- **Filter Controls**
  - All Courses, Stage 1, Stage 2, Free, Completed, In Progress
  - Reset All Progress button

- **Stage 1: Foundations & Core Programming (Courses 1-13)**
  - Course 01: Programming Foundations - Level 1 (FREE)
  - Course 02: Algorithms & Problem-Solving Level 1 (FREE)
  - Course 03: Introduction to Programming with C++ - Level 1 (FREE)
  - Course 04: Algorithms & Problem-Solving - Level 1 (Solutions)
  - Course 05: Algorithms & Problem-Solving - Level 2
  - Course 06: Introduction to Programming Using C++ Level 2
  - Course 07: Algorithms & Problem Solving Level 3
  - Course 08: Algorithms & Problem Solving Level 4
  - Course 09: Foundations Level 2
  - Course 10: OOP as it Should Be (Concepts)
  - Course 11: OOP as it Should Be (Applications)
  - Course 12: Data Structures - Level 1
  - Course 13: Algorithms & Problem Solving Level 5

- **Stage 2: Professional Development (Courses 14-24)**
  - Course 14: C# - Level 1
  - Course 15: Database Level 1 - SQL (Concepts and Practice)
  - Course 16: OOP As It Should Be In C#
  - Course 17: Database - SQL (Projects & Practice)
  - Course 18: C# & Database Connectivity
  - Course 19: Full Real Project - DVLD
  - Course 20: C# Programming Level 2
  - Course 21: Database Level 2 - Concepts & T-SQL
  - Course 22: Data Structures Level 2 in C#
  - Course 23: Algorithms Level 6
  - Course 24: Windows Services

- **Footer Section**
  - Copyright notice: "© 2026 Elhendawy. All Rights Reserved."
  - Attribution to Dr. Mohammed Abu-Hadhoud
  - Links to ProgrammingAdvices.com and YouTube

- **Modal Overlay**
  - Shows all lessons for a course
  - Each lesson has completion status
  - Click to toggle lesson completion
  - Shows course progress bar
  - Close button

### 2. Design Requirements

- **Color Scheme**
  - Dark gradient background (linear-gradient with #0f0c29, #302b63, #24243e)
  - Accent colors: #00d2ff (cyan), #3a7bd5 (blue)
  - Green badge (#28a745) for FREE courses

- **Layout**
  - Responsive grid layout using CSS Grid
  - Maximum width: 1400px
  - Mobile-friendly (breakpoint at 768px)

- **Course Cards**
  - Semi-transparent background with blur effect
  - Hover animations (translateY, box-shadow)
  - Top gradient border (4px)
  - Course number badge with gradient
  - Title, description, tags, and link button

- **Typography**
  - Font family: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
  - Gradient text effect for main title
  - Clear hierarchy with different font sizes

### 3. Interactive Elements

- **Progress Tracking (localStorage)**
  - Save lesson completion status to localStorage
  - Persist progress across browser sessions
  - Restore progress on page load
  - Reset progress option with confirmation

- **Course Progress Bars**
  - Visual progress bar for each course showing completion percentage
  - Display completed/total lessons count (e.g., "5/10 lessons")
  - Color-coded: cyan gradient for in-progress, green for completed

- **Lesson Status Indicators**
  - Completed: Green circle with checkmark
  - Not Started: Empty circle
  - Toggle status by clicking on lessons

- **Start/Continue Learning Buttons**
  - "Start Learning" for new courses
  - "Continue Learning" for in-progress courses
  - "Completed" badge for finished courses

- **Course Modal**
  - Click "View All Lessons" to open modal
  - Shows all lessons with completion status
  - Click lessons to toggle completion
  - Shows course progress bar in modal

- **Filter Controls**
  - All Courses, Stage 1, Stage 2, Free, Completed, In Progress
  - Reset All Progress button

- **Links**
  - Each course links to: https://programmingadvices.com/courses
  - Links open in new tab (target="_blank")
  - Hover effects on buttons

- **Tags**
  - Display relevant tags for each course (e.g., "Fundamentals", "C++", "OOP", "SQL")
  - Styled with semi-transparent background

- **Free Badge**
  - Green badge on courses 01, 02, and 03
  - Displayed next to course title

### 4. Accessibility

- Semantic HTML5 elements
- Proper heading hierarchy (h1, h2, h3)
- Alt text for any images (if added)
- Keyboard navigation support

### 5. Copyright & Ownership

- **Copyright Notice**
  - Display "© 2026 Elhendawy. All Rights Reserved." prominently
  - Style with semi-transparent background and border

- **Ownership Statement**
  - Original content, structure, organization, design, and materials owned by Elhendawy
  - Clear and professional presentation

- **Third-Party Attribution**
  - Course content attributed to Dr. Mohammed Abu-Hadhoud
  - Links to ProgrammingAdvices.com and YouTube channel
  - Do not claim ownership of external course materials

## Technical Specifications

- Single HTML file (no external dependencies)
- All CSS inline in `<style>` tag
- JavaScript for progress tracking and interactivity
- localStorage for data persistence
- UTF-8 encoding
- Responsive design

## File Output

Save the file as: `fundamentals-roadmap.html`

## Usage

1. Open the HTML file in any web browser
2. View your overall progress in the dashboard at the top
3. Use filter buttons to find specific courses (Stage 1/2, Free, Completed, In Progress)
4. Click "Start Learning" or "Continue Learning" on any course card
5. Click "View All Lessons" to see all lessons in a course
6. Click on lessons in the modal to mark them as completed
7. Your progress is automatically saved to localStorage
8. Return anytime to continue where you left off
9. Use "Reset All Progress" if you want to start over

## Credits

- **Project by:** Elhendawy
- **Course content by:** Dr. Mohammed Abu-Hadhoud
- **Website:** https://programmingadvices.com
- **YouTube:** https://www.youtube.com/c/ProgrammingAdvices
- **Copyright:** © 2026 Elhendawy. All Rights Reserved.
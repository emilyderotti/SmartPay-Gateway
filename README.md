# Tech Skill Test

This repository is a **React-based project** intended for evaluating your technical skills. Your task is to review, debug, and enhance the existing application based on the issues outlined below.

---

## Objective

Your responsibility is to check your skill by identifying and fixing the problems in the current implementation. Focus on improving both **functionality** and **code quality**.

---

## Known Issues / Tasks

1. **Wrong Calculation Logic**  
   The completed tasks counter currently shows the **total number of tasks** instead of only completed ones.  
   🔧 Fix: Ensure only completed tasks are counted.

2. **Missing Search Functionality**  
   The header search input exists but does **not filter tasks** as expected.  
   🔧 Fix: Implement filtering logic for the search input.

3. **Status Update Not Working**  
   Changes to task status may **not persist correctly**.  
   🔧 Fix: Ensure that toggling a task’s status updates the state properly.

4. **Missing Key Props**  
   List items lack **unique keys**, causing React console warnings.  
   🔧 Fix: Add unique `key` props to all rendered list items.

5. **Clear Filters Broken**  
   The reset button exists but has **no implemented functionality**.  
   🔧 Fix: Implement functionality to clear search and filter inputs.

6. **Division by Zero**  
   Completion percentage calculation can result in `NaN` if there are **no tasks**.  
   🔧 Fix: Handle edge cases to avoid `NaN` values.

---
## How This Works

You’ll be working on a few known issues in the app. Think of it as a mini challenge to test your primary knowledge, problem-solving skills, and attention to detail.  

**Important:** Once you’re invited, we’d love to see all the tasks completed **within 24 hours**.
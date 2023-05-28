---
name: User Story
about: The issue represents one user story
title: ''
labels: ''
assignees: ''

---

**As a System Administrator 
 **I need the ability to reset the counter  
 **So that I can redo counting from the start  
   
 ### Details and Assumptions
 * The counter can be reset
 
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given the counter is at count above zero
 When a user makes a call to reset the counter
 Then it should return to zero
 ```

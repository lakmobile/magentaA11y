---
layout: entry
title:  "View/page"
categories: interface
order: 0


keyboard:
  text resize settings: |
    Text can resize up to 200% without losing information
  tab or arrow keys: |
    Initial focus begins from a logical place

mobile:
  swipe: |
    Initial focus begins from a logical place and all content is read in logical order
    
screenreader: 
  name:  |
    Purpose of the view is clear
  group: |
    Focus moves in a logical order through the view (top to bottom, left to right)
---

## Developer notes

- The SR focus can land on any element that is logical.  If the user activated a control that was for creating an email, landing on the next screen in the "To:" text field to start creating an email is logical.  Landing in the lower part of the screen can be confusing.  
- The user has a responsibility to swipe through the screen to learn what is on it. So, landing below a few elements at the top of the screen is ok, as long as it is a logical place to land.  
- The back button must announce its purpose, like "Back" and not just that is a button. Android native announcement can be "Navigate up button, double tap to activate". In Android, sometimes one swipe is needed upon arrival on screen to show initial focus.
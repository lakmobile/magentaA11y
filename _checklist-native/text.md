---
layout: entry
title:  "Body text"
categories: content


keyboard:
  Text resize: |
    Text can resize up to 200% without losing information
          
mobile:
  rotor (iOS): |
    Focus moves to the element, expresses its name, role (state, if applicable)
  context menu (Android): |
    Activates the button
    
screenreader: 
  group: |
    Is read in logical order in the content

---

## Developer notes

- If text is truncated in text size of 100%, all of the text truncated should be visible at 200%.  
- Text at 100% and 200% can truncate, but only if text was truncated at 100% and it cannot truncate more characters at 200% than what was available at 100%.
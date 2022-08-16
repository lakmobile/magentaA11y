---
layout: entry
title:  "Heading"
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
  role:  |
    Identifies as a heading
  group: |
    Is read in logical order in the content

---

## Developer notes

- Links can also be accessed through the Rotor and Local Context Menu. If a link cannot be activated when it is inline within other text, it can be accessed and activated in the context menus. Only one way to activate is required
- Components that take the user to a URL must be coded as a link, even if it looks like a button. Conversely, components that keep the user inside an app must be coded as a button, even if it looks like a link.
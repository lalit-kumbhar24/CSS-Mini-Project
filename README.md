This project implements a responsive sliding sidebar menu using pure HTML and CSS, without JavaScript.The core logic is based on the checkbox toggle technique and CSS sibling selectors.

# Checkbox Toggle Mechanism
- A hidden checkbox input is used to control the  sidebar’s visibility.
- The checkbox is hidden using CSS.
- Clicking the hamburger or close icon toggles the checkbox state.

# Labels Act as Buttons
- Icons are wrapped inside <label> tags linked to the checkbox.

- Clicking the label automatically checks/unchecks the checkbox.
- This replaces JavaScript click handling.

# CSS :checked Pseudo-Class
- CSS detects the checkbox state using :checked.
- When unchecked → sidebar stays hidden (left: -300px)
- When checked → sidebar slides in (left: 0)


# Icon Visibility Control
- Icons are shown/hidden based on checkbox state.
- Hamburger icon disappears when sidebar opens.
- Close icon appears only when sidebar is visible.


This project demonstrates how interactive UI components can be built using only HTML and CSS, showcasing strong fundamentals in layout design, transitions, and user interaction without relying on JavaScript.
# Bankis-Web

### 1. **Modal Window**

- The modal window is triggered by buttons with the `.btn--show-modal` class. When clicked, the modal and overlay become visible. The modal can be closed by clicking the close button, the overlay, or pressing the "Escape" key.

### 2. **Smooth Scrolling**

- The `Learn more` button scrolls smoothly to the first section (`#section--1`) when clicked.
- Smooth scrolling is also implemented for navigation links within the `.nav__links` container, allowing users to scroll to different sections of the page.

### 3. **Cookie Message**

- A cookie consent message is displayed at the top of the page. The message includes a "Got it!" button, which removes the message when clicked. The message is styled with a dark background and spans 120% of the width of its container.

### 4. **Tabs Component**

- The tabs component allows users to switch between different content sections related to banking operations. Clicking on a tab (`.operations__tab`) updates the active tab and content displayed.

### 5. **Menu Fade Animation**

- When hovering over a navigation link, the opacity of sibling links and the logo is reduced, creating a fading effect.

### 6. **Sticky Navigation**

- The navigation bar becomes sticky when the user scrolls past the header. This is achieved using the `IntersectionObserver` API, which adds a `sticky` class to the navigation bar when the header is out of view.

### 7. **Reveal Sections on Scroll**

- Sections are initially hidden and revealed as the user scrolls down the page. The `IntersectionObserver` API is used to detect when a section is in the viewport, triggering it to be revealed.

### 8. **Lazy Loading Images**

- Images in the `.features` section are lazy-loaded, meaning they are only loaded when they come into the viewport. This helps to optimize the page's loading performance.

### 9. **Slider Component**

- A testimonial slider is implemented, allowing users to navigate through testimonials using left and right arrows. Users can also click on dots to jump to specific slides. Keyboard navigation is supported via the arrow keys.

### 10. **Practice Section**

- This section seems to be for practicing event propagation, color changes on click, and scaling elements. It's commented out, indicating it's not currently active on the page.

### 11. **Additional Features**

- The `DEMO` link in the navigation opens another page in a new tab.see this [repository ](https://github.com/btfateme/bankist)
- The footer section includes links (though the provided snippet is cut off before the list completes).

This setup creates a rich, interactive user experience, optimized for performance and ease of use, using modern JavaScript techniques like `IntersectionObserver`, `Event Delegation`, and `Lazy Loading`.

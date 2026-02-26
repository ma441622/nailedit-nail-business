Dark Mode Implementation - Small Testable Steps

  Step 1: Define dark mode CSS variables

  Add a body.dark-mode selector in styles.css that overrides the :root colors with darker variants.

  Test: Add class="dark-mode" to <body> manually → page should look darker

  ---
  Step 2: Add toggle button HTML to navigation

  Add a button/icon in the <nav> on all 5 HTML files (index, about, services, gallery, contact).

  Test: Button appears in the header on all pages

  ---
  Step 3: Style the toggle button

  Add CSS for the toggle (sun/moon icon or switch style) that fits the Y2K aesthetic.

  Test: Button looks good in both mobile and desktop views

  ---
  Step 4: Add JavaScript to toggle the class

  Add a click handler that toggles dark-mode class on <body>.

  Test: Clicking the button switches between light/dark themes

  ---
  Step 5: Add localStorage save

  When toggling, save the preference: localStorage.setItem('theme', 'dark') or 'light'.

  Test: Open DevTools → Application → Local Storage → see value change on toggle

  ---
  Step 6: Add localStorage read on page load

  On page load, check localStorage and apply the saved theme before content renders.

  Test: Set dark mode → refresh page → dark mode persists. Navigate to another page → still dark.

  ---
  Step 7: Add smooth transition effect

  Add transition: background-color 0.3s, color 0.3s to body/main elements for smooth switching.

  Test: Toggle feels smooth, not jarring
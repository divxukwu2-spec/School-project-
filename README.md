# School-project-
My NGO WEBSITE


HOPE FOUNDATION - WEB DEVELOPMENT GROUP PROJECt

1. PROJECT OVERVIEW
------------------------------------------------------------------------
Hope Foundation is a multi-page, responsive web application designed as 
a group project for a non-profit organization. The platform serves to 
raise community awareness, showcase operational impact areas, and 
facilitate user donations through interactive frontend components.

The project features a modular design split across three distinct 
landing pages, a unified stylesheet, and client-side form validation 
and modal interactions.


 JAVASCRIPT LOGIC & FORM VALIDATION

---

The project includes front-end client-side logic to enhance user
interactivity:

* Modal Behavior: Structured via `js/script.js` (referenced in index.html) to handle close operations using standard close glyphs (`&times;`).
* Donation Guard: `donate.html` contains an embedded script checking email inputs:
* If a user triggers a click with blank values, an alert dialogue prompts them for validation.
* Upon successful mock submission, a confirmation alert displays ("Thank you for your donation! Your support means a lot to us.") and the container calls `form.reset()` to clean active inputs.



5. HOW TO RUN AND TEST LOCALLY

---

1. Clone or download the source files into a unified project directory.
2. Ensure the asset file `asset/image.png` is in place to allow favicons to resolve properly.
3. Open `index.html` inside any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).
4. Use the navigation bar links to seamlessly switch between pages and test the active hover animations, modal elements, and donation field responses.


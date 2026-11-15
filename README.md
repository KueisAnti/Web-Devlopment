# Project Milestone 3: Accessible & Designed

## 1. Accessibility Fixes
* **Contrast:** I fixed a WCAG AA contrast error on the contact form's error message by changing the standard red text to a darker `#CC0000` to ensure it was legible against the white background.
* **WAVE Tool:** Ran the WAVE Web Accessibility Evaluation Tool across all three pages and resolved all structural, ARIA, and contrast errors, resulting in 0 errors across the site.

## 2. Visual Design & Gestalt Principles
* **Similarity:** I used the principle of similarity by keeping my color palette and typography strictly consistent across all three pages (Home, Projects, About). For example, all interactive elements or primary headers share the same styling, signaling to the user that they have the same level of importance.
* **Proximity:** I used the principle of proximity in my layout (such as my navigation menu and project sections) by grouping related elements close together and using larger margins to separate distinct sections. This creates a clear visual hierarchy so users can easily parse related information.

## 3. Accessible Form
* Added an accessible contact form to the `about.html` page. 
* The form uses semantic `<fieldset>` and `<legend>` tags to group the inputs. 
* All input fields have explicitly linked `<label>` tags.
* The form includes an accessible error state using `aria-invalid` and `aria-describedby` attributes to help screen readers interpret the validation error.

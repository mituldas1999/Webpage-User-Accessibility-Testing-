# Accessibility Testing Report

## Summary

- **URL:** [Presta Marine Detailing](https://prestamarinedetailing.com/)
- **Test Start Date:** 24/02/2024
- **Total Errors:** 24
  - Missing alternative text: 2 ❌
  - Empty button: 2 ❌
  - Empty link: 13 ❌
  - Broken ARIA reference: 7 ❌
- **Contrast Errors:** 12 ❌
  - Very low contrast: 12 ❌

## Detailed Findings

### Missing alternative text - X2

1. **What It Means:**
   Image alternative text is not present.
   
2. **Why It Matters:**
   Each image must have an alt attribute. Without alternative text, the content of an image will not be available to screen reader users or when the image is unavailable.

3. **What To Do:**
   Add an alt attribute to the image. The attribute value should accurately and succinctly present the content and function of the image. If the content of the image is conveyed in the context or surroundings of the image, or if the image does not convey content or have a function, it should be given empty/null alternative text (alt="").

4. **The Algorithm... in English:**
   An image does not have an alt attribute.

### Empty button - X2

1. **What It Means:**
   A button is empty or has no value text.
   
2. **Why It Matters:**
   When navigating to a button, descriptive text must be presented to screen reader users to indicate the function of the button.

3. **What To Do:**
   Place text content within the `<button>` element or give the `<input>` element a value attribute.

4. **The Algorithm... in English:**
   A `<button>` element is present that contains no text content (or alternative text), or an `<input type="submit">`, `<input type="button">`, or `<input type="reset">` has an empty or missing value attribute.

### Empty link - X13

Same as "Empty button - X2" with appropriate numbering.

### Broken ARIA reference - X7

Same as "Empty button - X2" with appropriate numbering.

## Order

Order, role, and accessible name for all navigable page elements are listed. Elements without a function are excluded.

1. **Link:** Skip to content
2. **Link:** Presta_Marine Logo
3. **Button:** About Us
4. **Link:** About Presta Marine
5. **Link:** Partnerships and Sponsorships
   ...
87. **Link:** *NO ACCESSIBLE NAME* (13)
88. **Link:** *NO ACCESSIBLE NAME* (14)
89. **Link:** *NO ACCESSIBLE NAME* (15)
90. **Link:** Secret Design Shop
91. **Link:** Mentis Collective

*Note: The order listing is truncated for brevity.*

## Conclusion

The website [Presta Marine Detailing](https://prestamarinedetailing.com/) exhibits accessibility issues, primarily related to missing alternative text, empty buttons, empty links, and broken ARIA references. It is recommended to address these issues to ensure a more inclusive user experience. 🌐🛠️

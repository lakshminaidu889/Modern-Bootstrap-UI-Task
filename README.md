
## 3. Component Remixing: The Footer

- **Design Choice:** Implemented a fixed dark footer (`bg-dark`) for a strong, professional contrast against the light pages.
- **Utility Use:** Utilized Bootstrap's `row` and `col` classes to ensure responsive layout, putting copyright information on the left and navigation links on the right for desktop views.
- Added necessary quick links and a copyright notice for corporate polish.
  
## 4. Home Page Design: The Hero Section

- **Component Choice:** Used a custom section (`<header>`) with generous padding (`py-5`) and a light background (`bg-light`) to create a distinct Hero area.
- **Remixing Strategy:** Designed a responsive two-column layout (L-content, R-visual placeholder) to provide dynamic balance on desktop. The visual element is hidden on small screens (`d-none d-xl-block`) for optimal mobile performance.
- **CTAs:** Incorporated a strong primary and secondary CTA pair to guide user flow clearly to the Services or Contact pages.
- 
## 5. Home Page Design: Feature Section (Cards)

- **Component Choice:** Used a three-column responsive grid (`row-cols-md-3`) to display core services clearly.
- **Remixing Strategy:** Applied the `.h-100` utility class to ensure all cards have equal height, even with varying content, and added a `.shadow-lg` for a premium, elevated look.
- **Visuals:** Used text-based emojis as temporary icons for clarity and visual interest.
  
## 6. About/Services Page Design

- **Component Choice:** Designed a two-column layout focusing on clear information hierarchy.
- **Remixing Strategy:** Used the **List Group** component and dynamic **Badges** to present services, offering a visual alternative to the Card layout used on the Home Page. This shows component versatility.
- **Visuals:** Highlighted a core commitment/value proposition using a Card with a distinct border (`border-primary border-3`) to make it visually important.

## 7. Contact Page Design (The Working Form)

- **Layout Remix:** Used a clean, responsive two-column grid (`col-lg-6`) to separate the actionable form from the static contact information. This improves User Experience (UX).
- **Form Validation Mastery:** Implemented the required contact form using Bootstrap's built-in validation features (`.needs-validation` class and `.invalid-feedback` elements). This confirms understanding of a key modern Bootstrap feature for improving form interaction.
- **Content:** Used List Groups on the right side to display contact details clearly and professionally.

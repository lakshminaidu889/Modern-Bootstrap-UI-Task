
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

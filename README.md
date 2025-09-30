# Bootstrap Book Catalog Dashboard

A responsive, mobile-first dashboard for managing a book catalog, built as an exercise using **Bootstrap 5**.

🌐 [Check it out!](https://michecosa.github.io/html-css-bootstrap-dashboard/)

<br>

## 📖 Project Description

This project recreates the responsive layout of a web application's control panel. 

## ✨ Features

- **Fully Responsive Layout**: Adapts to various screen sizes using Bootstrap's grid system.
- **Book Catalog Management**: Centralized table for viewing book titles, loan dates, and statuses.
- **Interactive UI Components**:
  - Responsive navigation bar with a collapsible menu.
  - Status badges (`Disponibile`, `In prestito`, `Non disponibile`).
  - Action buttons for editing and deleting books.
  - "Add Book" call-to-action button.
- **Supplementary Sidebar**:
  - A "Todo" list with interactive checkboxes.
  - An "F.A.Q." accordion for common questions.
- **Built with Bootstrap 5**: Utilizes core Bootstrap components, utility classes, and the flexbox grid.

## 🛠️ Technologies Used

- [Bootstrap 5.3.8](https://getbootstrap.com/docs/5.3/getting-started/introduction/) - CSS & JS framework
- [Bootstrap Icons](https://icons.getbootstrap.com/) - Icon library
- [Font Awesome](https://fontawesome.com/) - Additional icons


## 🧩 Bootstrap Components Used

This project leverages the following key Bootstrap components and features :cite[1]:cite[5]:cite[9]:

- **Layout & Grid**: Container, Row, Column system for responsive structure.
- **Content**: Tables, typography, and images.
- **Components**:
  - **Navbar**: A responsive, collapsible navigation bar.
  - **Cards**: Used for the "Todo" and "F.A.Q." sections.
  - **Buttons**: Including primary buttons and outline buttons.
  - **Badges**: For displaying book status.
  - **Accordion**: For the FAQ section.
  - **List Group**: For the todo list items.
  - **Forms**: Search input and checkboxes.
- **Utilities**: Spacing (margin/padding), display, flexbox, and border utilities for customizing appearance and layout.

## 🎯 Key Implementation Details

- **Mobile-First Approach**: The design prioritizes mobile devices and scales up, a core principle of Bootstrap.
- **Responsive Table**: The "Data prestito" column is hidden on smaller screens (`d-none d-sm-table-cell`) to optimize space.
- **Component Customization**: Default Bootstrap components are used and lightly customized with utility classes (e.g., button borders, text colors) instead of extensive custom CSS.

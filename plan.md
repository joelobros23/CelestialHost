# Project Plan: CelestialHost

**Description:** A user-friendly web hosting platform built with Ruby on Rails, providing domain management and basic hosting features.


## Development Goals

- [ ] Configure tailwindcss-rails and create a base layout using Tailwind CSS.
- [ ] Add validations to the Domain model (name, plan) and ensure unique domain names per user.
- [ ] Modify the Domains controller to restrict domain access to the current user. Ensure only the owning user can view/edit/delete.
- [ ] Implement basic 'plan' selection via a dropdown during Domain creation (e.g., 'Basic', 'Standard', 'Premium').
- [ ] Add styling to the Devise views (sign_in, sign_up) to match the Tailwind CSS theme.
- [ ] Create a user dashboard page to display the user's domains with relevant information (status, plan).
- [ ] Implement a simple 'status' update mechanism for domains (e.g., 'Active', 'Inactive', 'Pending').
- [ ] Add seeds to create default plans and users for testing purposes.
- [ ] Add indexes to the database for foreign keys and frequently queried columns to improve performance.
- [ ] Implement a mechanism for users to update their profile information (email, password).
- [ ] Add a flash message upon successful domain creation.

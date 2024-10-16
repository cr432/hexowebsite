# Student Guide to Software Development - Agile Documentation

## Vision

**Vision**: To create an accessible and user-friendly online platform for high school students and beginners to learn the basics of software development. The website will provide a curated collection of articles, tutorials, and resources that guide users through fundamental programming concepts and tools.

## Initiative/Theme

**Initiative**: As a user, I want to explore articles, tutorials, and guides on software development topics, so that I can learn and enhance my skills even without prior experience.

## Epics

### Epic 1: Website Structure
**Description**: Establish the basic structure of the website to ensure easy navigation and access to content.

- **Story 1.1**: As a user, I want the website to have a title so that I can identify it easily.
  - **Acceptance Criteria**:
    - The title is displayed prominently on the homepage.
    - The title reads "Student Guide to Software Development."
    - The title is visible on all pages.
  - **Tests**: Verify that the title appears correctly on each page.

- **Story 1.2**: As a user, I want a navigation menu so that I can easily access different sections of the website.
  - **Acceptance Criteria**:
    - The menu includes links to Home, About, Articles, Contact, and Search.
    - The menu is responsive and works on mobile and desktop.
  - **Tests**: Verify that the menu links navigate to the correct sections.

- **Story 1.3**: As a user, I want a footer on the website so that I can find additional links and information.
  - **Acceptance Criteria**:
    - The footer contains links to privacy policy, terms of service, and contact information.
    - The footer is present on all pages.
  - **Tests**: Verify that the footer links are functional and the footer is consistent across pages.

### Epic 2: Content Organization
**Description**: Create and organize content on software development topics to ensure users can find the information they need.

- **Story 2.1**: As a user, I want a search bar so that I can quickly find articles on specific topics.
  - **Acceptance Criteria**:
    - The search bar is available on the homepage and articles page.
    - The search functionality displays relevant results based on keywords.
  - **Tests**: Verify that search returns accurate results based on user input.

- **Story 2.2**: As a user, I want articles categorized into topics like Programming Basics, Web Development, and Tools, so that I can easily find what I’m interested in.
  - **Acceptance Criteria**:
    - Articles are organized into categories such as Programming Basics, Web Development, and Tools.
    - Each category has a dedicated page listing all related articles.
  - **Tests**: Verify that each category page displays articles correctly.

- **Story 2.3**: As a user, I want a list of recent articles on the homepage so that I can see the latest content.
  - **Acceptance Criteria**:
    - The homepage displays a section with the titles and summaries of the latest 5 articles.
    - Each article link leads to the full article page.
  - **Tests**: Verify that the latest articles display correctly and the links function properly.

### Epic 3: Simple User Interaction
**Description**: Enable basic user interactions to enhance the user experience.

- **Story 3.1**: As a user, I want to have a contact form so that I can send feedback or ask questions.
  - **Acceptance Criteria**:
    - The contact form includes fields for name, email, and message.
    - Users receive a confirmation message after submitting the form.
  - **Tests**: Verify form submission and that confirmation messages appear.

- **Story 3.2**: As a user, I want a dark mode option so that I can read articles comfortably in low-light environments.
  - **Acceptance Criteria**:
    - A toggle for dark mode is available in the navigation menu.
    - The website switches between light and dark themes smoothly.
  - **Tests**: Verify that the theme toggle functions properly and the styles update accordingly.

- **Story 3.3**: As a user, I want social media sharing buttons on each article so that I can share content easily.
  - **Acceptance Criteria**:
    - Social media buttons for platforms like Twitter, Facebook, and LinkedIn are available at the end of each article.
    - Clicking a button opens the share dialog for the respective platform.
  - **Tests**: Verify that each button links to the correct share dialog with the article link.

### Epic 4: Hexo-specific Customization
**Description**: Customize the Hexo framework to meet the needs of the project.

- **Story 4.1**: As a developer, I want to customize the Hexo theme to match the website’s branding so that it looks professional.
  - **Acceptance Criteria**:
    - Colors, fonts, and styles are updated to match the website's design guidelines.
    - The branding is consistent across all pages.
  - **Tests**: Verify that the website theme is applied correctly and consistently.

- **Story 4.2**: As a developer, I want to create custom markdown templates so that content authors can add articles easily.
  - **Acceptance Criteria**:
    - A markdown template is available for creating new articles.
    - The template includes fields for title, author, category, and tags.
  - **Tests**: Verify that new articles created with the template are formatted correctly.

- **Story 4.3**: As a user, I want each article to display estimated reading time so that I know how long it will take to read.
  - **Acceptance Criteria**:
    - Each article page shows an estimated reading time based on the content length.
    - The reading time is displayed near the article title.
  - **Tests**: Verify that the reading time calculation is accurate and displays correctly.

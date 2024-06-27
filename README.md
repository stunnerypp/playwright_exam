## Playwright Exam

### Instructions
1. **Setup**: Ensure you have Playwright installed. If not, you can install it using npm:
   ```bash
   npm install playwright
   ```
2. **Environment**: You may use any code editor or IDE of your choice.
3. **Time Limit**: You have 3 hours to complete this exam.
4. **Submission**: Once completed, push your code to github and send us the repository url.

### Scenario
You are tasked with writing automated tests for a our company website:
- **Language Switcher** - Should by French by default. Translate page when En is clicked.
- **Mobile Navigation** - Should have a dropdown menu for devices with width 1024px and below.
- **Contact Form** - Should NOT submit the form if captcha field is blank.

### Tasks

#### Task 1: Language Switcher
Write a test to verify the following:
- The home page loads successfully.
- Homepage text should be French. You can just use a few words to verify.
- Clicking "En" on the navbar should change the words to English.

#### Task 2: Mobile Navigation
Write a test to verify the following:
- On screen sizes greater than 1024, there is a regular navigation bar with clickable links.
- On screen sizes 1024 and lower, there will be a dropdown navigation menu with clickable links.

#### Task 3: Contact Form
Write a test to verify the following:
- Contact link is clickable in the navigation bar.
- Contact page loads.
- All form fields are fillable.
- Contact form should NOT submit if Captcha is left blank.

### Additional Requirements
- Use assertions to verify the expected outcomes.
- Ensure your tests are clean, well-structured, and include comments where necessary.
- Handle any necessary setup and teardown within your tests.

### Submission
- Please push your completed tests to your own github repository.
- Include a Readme file with instructions if necessary.

---

Good luck! If you have any questions or need further clarification, please reach out.

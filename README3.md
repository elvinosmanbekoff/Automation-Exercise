# Bug Report Example

## Bug Report

### Bug ID
BUG-003

### Title
User contacts the support section to get help using the website.

### Project
Online sales website

### Module
Technical support

### Environment

- Browser: Chrome 126
- OS: Windows 11
- Build: 1.0.8

### Severity
Major

### Priority
High

### Preconditions

- Open the website.
- Click on the "Contact Us" section in the navigation menu.

### Steps to Reproduce

1. Fill in the required fields to get in touch.

   > Name - ASD
   >
   > Email - [Asd@gmail.com](mailto:Asd@gmail.com)
   >
   > Subject - ASD
   >
   > Your message - ASD

2. Click the Submit button.
3. A notification confirming that the data is valid is displayed.

### Actual Result
While not registered and logged in with a different profile, a confirmation notification for technical support was received using data that does not belong to the logged-in profile (Name - ASD, Email - [Asd@gmail.com](mailto:Asd@gmail.com)).

### Expected Result
An error should be displayed when invalid data (Name - ASD, Email - [Asd@gmail.com](mailto:Asd@gmail.com), or data from another such profile) is used.

### Attachments

- Screenshot
- <img width="1914" height="856" alt="Image" src="https://github.com/user-attachments/assets/67eb9e15-d76c-434d-ab1d-d143ef183ff6" />
- <img width="1867" height="811" alt="Image" src="https://github.com/user-attachments/assets/727be55d-aeed-4319-8bb8-b38644ce5752" />

### Reproducibility
100% — reproduced 5/5 times.

### Status
Open

## CineFlow | Creator registration form

 This project is a HTML-only registration system for new content creators. It collects essential user information, validates inputs using built-in HTML constraints, and includes multimedia elements such as a promotional video and audio instructions.

The goal is to demonstrate structured form design, semantic HTML usage, and client-side validation.

## features

**User Registration Form**

The form collects the following data:

**Full Name** (min length validation)
**Email Address** (format validation)
**Password** (minimum 8 characters required)
**Phone Number** (pattern validation)
**Date of Birth** (restricted to users 18+)
**Gender selection** (radio buttons)
**Content Category** (dropdown menu)
**Short Bio** (textarea)
**Social Media URL** (URL validation)
**Profile Picture upload** (only .jpg, .jpeg, .png)
**Content Genres** (checkboxes: Tech, Lifestyle, Gaming, etc.)
**Expected Weekly Upload Volume** (0–10 range slider)

## Multimedia Integration

Embedded 30-second promotional video using the ```<video> tag ```
Supports MP4 and WebM formats
Includes controls and poster image
Embedded audio instructions using the ```<audio> tag```

Built-in HTML validation ensures data integrity:

## form validation

required fields prevent empty submission
minlength="8" enforces strong password creation
max="YYYY-MM-DD" ensures users are 18+ years old
pattern attribute validates phone number format
accept attribute restricts file uploads to image types only
type="email" enforce correct formatting

## Form Controls

Submit Button ```(<button type="submit">)```
Reset Button ```(<button type="reset">)```

## Technologies Used

HTML5 

## Installation & Setup

```bash
git clone https://github.com/Conrad008/CineFlow-Account-Portal
```

```cd jua-kali-connect```

Open index.html in any modern browser and view your site

## Future Improvements
Add CSS for better UI/UX design
Integrate backend for form submission storage
Add JavaScript-based advanced validation
Include user dashboard after registration

## License

This project is open for educational use

## author
**conrad kipngeno**
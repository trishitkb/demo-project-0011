# Simple Contact Form

A beautiful, responsive contact form that sends emails directly from your website.

## Features

- ✅ Responsive design that works on all devices
- ✅ Form validation with real-time feedback
- ✅ Professional styling with gradient backgrounds
- ✅ Email integration ready
- ✅ Success and error message handling
- ✅ Accessibility features

## Setup Instructions

### Option 1: Using Formspree (Recommended for beginners)

1. Go to [Formspree.io](https://formspree.io/) and create a free account
2. Create a new form and get your form ID
3. In `index.html`, replace `YOUR_FORM_ID` with your actual Formspree form ID:
   ```html
   <form id="contactForm" action="https://formspree.io/f/YOUR_ACTUAL_FORM_ID" method="POST">
   ```
4. Uncomment the actual form submission code in the JavaScript section
5. Your form is ready to receive emails!

### Option 2: Using EmailJS

1. Sign up at [EmailJS.com](https://www.emailjs.com/)
2. Set up an email service (Gmail, Outlook, etc.)
3. Create an email template
4. Replace the form submission code with EmailJS integration

### Option 3: Backend Integration

For a production website, consider integrating with a backend service:
- Node.js with Nodemailer
- PHP mail() function
- Python with Flask/Django
- Any server-side language of your choice

## Form Fields

The contact form includes:
- **First Name** (required)
- **Last Name** (required)
- **Email Address** (required, with validation)
- **Phone Number** (optional)
- **Subject** (required, dropdown selection)
- **Message** (required, textarea)

## Customization

### Colors
You can easily customize the color scheme by modifying the CSS variables in the `<style>` section:
- Primary gradient: `#667eea` to `#764ba2`
- Success color: `#27ae60`
- Error color: `#e74c3c`

### Form Fields
To add or remove form fields:
1. Update the HTML structure
2. Adjust the CSS if needed
3. Update the JavaScript validation

### Styling
The form uses a modern design with:
- Gradient backgrounds
- Smooth animations
- Hover effects
- Focus states
- Mobile-responsive layout

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## File Structure

```
demo-project-0011-simple_contact_form/
├── index.html          # Main contact form page
└── README.md          # This file
```

## Usage

1. Open `index.html` in any web browser
2. Fill out the form fields
3. Click "Send Message"
4. The form will validate inputs and submit (once email service is configured)

## Security Notes

- Always validate form data on the server side
- Use HTTPS in production
- Implement rate limiting to prevent spam
- Consider adding CAPTCHA for additional security

## License

This project is open source and available under the MIT License.

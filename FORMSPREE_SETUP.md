# Formspree Setup Instructions

Your portfolio website now includes a contact form that will send emails directly to your inbox using Formspree, a free form submission service.

## Quick Setup (5 minutes)

### Step 1: Create a Formspree Account
1. Go to [https://formspree.io](https://formspree.io)
2. Click "Get Started" and sign up with your email address
3. Verify your email address

### Step 2: Create a New Form
1. After logging in, click "New Form"
2. Enter a form name (e.g., "Portfolio Contact Form")
3. Enter your email address where you want to receive messages
4. Click "Create Form"

### Step 3: Get Your Form Endpoint
1. After creating the form, you'll see a form endpoint that looks like:
   `https://formspree.io/f/YOUR_FORM_ID`
2. Copy this URL

### Step 4: Update Your Website
1. Open your `index.html` file
2. Find this line (around line 634):
   ```html
   <form class="contact-form" id="contact-form" action="https://formspree.io/f/xpwzgkqr" method="POST">
   ```
3. Replace `https://formspree.io/f/xpwzgkqr` with your actual Formspree endpoint
4. Save the file

### Step 5: Test Your Form
1. Open your website in a browser
2. Fill out the contact form and submit it
3. Check your email - you should receive the message!

## Current Configuration

The form is currently configured with a placeholder endpoint. You need to replace it with your actual Formspree form endpoint for it to work.

**Current form action:** `https://formspree.io/f/xpwzgkqr` (placeholder)
**Replace with:** Your actual Formspree endpoint

## Form Features

✅ **Client-side validation** - Checks for required fields and valid email format
✅ **Loading states** - Shows spinner while submitting
✅ **Success/error messages** - User-friendly feedback
✅ **Spam protection** - Formspree includes built-in spam filtering
✅ **Email notifications** - You'll receive emails with form submissions
✅ **Mobile responsive** - Works perfectly on all devices

## Formspree Free Plan Limits

- **50 submissions per month** (free plan)
- **Unlimited forms**
- **Spam filtering included**
- **Email notifications**

If you need more submissions, Formspree offers paid plans starting at $10/month for 1000 submissions.

## Troubleshooting

**Form not working?**
- Make sure you've replaced the placeholder endpoint with your actual Formspree endpoint
- Check that your Formspree form is active and verified
- Ensure your email address is verified in Formspree

**Not receiving emails?**
- Check your spam/junk folder
- Verify your email address in your Formspree account
- Make sure the form endpoint URL is correct

## Alternative Free Services

If you prefer other services, here are alternatives:
- **Netlify Forms** (if hosting on Netlify)
- **EmailJS** (client-side email service)
- **Getform.io** (similar to Formspree)

---

**Need help?** The current setup should work perfectly once you replace the placeholder endpoint with your actual Formspree form endpoint.

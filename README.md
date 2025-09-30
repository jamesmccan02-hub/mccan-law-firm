# mccan-law-firm
Website for McCan Law Firm specializing in recovering crypto assets for clients scammed in crypto. Professional legal services and expertise in crypto recovery.

## Optional: Google Sheets CRM Integration (Free)

**Note:** This setup is optional but recommended for tracking leads efficiently.

You can automatically save form submissions to a Google Sheet using Formsubmit and Zapier's free plan.

### Setup Instructions

1. **Set up Formsubmit**
   - Your contact form already uses Formsubmit which sends form submissions to your email (Jamesmccan02@gmail.com)
   - Each submission will arrive as an email

2. **Create a Google Sheet**
   - Go to Google Sheets and create a new spreadsheet
   - Add column headers for the data you want to track: `Name`, `Email`, `Phone`, `Message`, `Date`, etc.

3. **Set up Zapier (Free Plan)**
   - Sign up for a free Zapier account at https://zapier.com
   - Create a new Zap with:
     - **Trigger:** Gmail - "New Email" (filter by `from:noreply@formsubmit.co`)
     - **Action:** Google Sheets - "Create Spreadsheet Row"
   - Connect your Gmail and Google Sheets accounts
   - Map the email content fields to your spreadsheet columns
   - Turn on the Zap

4. **Test the Integration**
   - Submit a test form on your website
   - Check that a new row appears in your Google Sheet

### Benefits
- Free solution (no paid plans required)
- Automatic lead tracking
- Easy to share with team members
- Can export data anytime
- Simple to set up (takes about 15 minutes)

### Note on Free Plan Limits
Zapier's free plan includes 100 tasks/month, which should be sufficient for most small to medium law firm lead volumes.

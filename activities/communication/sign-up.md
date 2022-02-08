---
Type: guide
Explains: how to manage sign ups for the newsletter and community calls
---

# Managing newsletter and community call sign up

We use [Odoo](../tool-management/odoo.md) to manage the sign up process. The modules we use are Surveys and Contacts. We use Surveys to create sign up sheets and collect responses from people who want to sign up. We then transfer this information to Contacts, which we use to track who wants to receive which information as well as their contact details.

The survey called *Newsletter and community calls* configures the [sign up form](https://odoo.publiccode.net/survey/start/594b9243-c7e5-4bc1-8714-35137c971842).

Share the link to this form whenever we communicate with people who might want to stay in touch with us.

## Update contacts

Update Odoo Contacts before sending out [invitations to community calls](../standard-maintenance/preparing-community-call.md) or the newsletter.
The notes at the bottom of the survey will say when Contacts was last updated.
In the top right corner of the survey is a button showing how many answers the survey has.

Download a file of all new contacts by:

1. Click Participations > Detailed answers in the top toolbar.
2. Unfold Newsletter and community calls lines to see which ones are new by comparing the date in 'Created on' with the log note date of when the contacts were last updated. Keep all the new one unfolded and collapse the old ones again.
3. Check the square to the left above all the lines to check all unfolded squares at once.
4. Click Action > Export.
5. Add Suggested answer/Suggested value and Text answer.
6. Click Export in the bottom left and open the file.

With the details from the file, update existing contacts or create new ones.
Use the tags 'Newsletter', 'Community Call / Foundation', 'Community Call /Standard' and 'SendValuable' to store their preferences for being contacted.

## Log the update

After the contacts have been updated, use the function **Log note** in the bottom of the survey to leave a message that contacts have been updated (a timestamp will be added automatically).

Delete the contacts file you downloaded, so that we can be confident we're GDPR compliant.

---
seo:
  title: List Scrubbing Guide
title: List Scrubbing Guide
weight: 0
layout: page
navigation:
  show: false
---

From time to time, it's good to take a long hard look at your lists and clean house. At SendGrid, this means scrubbing your list. For senders, a scrubbed list sent by SendGrid can be the ticket to delivery heaven. Unfortunately, scrubbing your list can be intimidating. Senders don’t know where to start and resort to using list cleaning services. What senders might not know is that cleaning your list can be done for free and much, much more effectively. We have put together simple steps that will improve any senders list. A bad list is fraught with problems and if left unbrushed, can lead to removing all of a senders teeth which requires a lot of resources to replace. Please go through these; we promise it will save you a trip to the dentist in the long run.

1. SendGrid automatically suppresses hard bounces if you try to send to them again. Let me make this clear - don’t waste your emails - remove these addresses from your list. Keeping your list up to date will save you money and time should you try to send somewhere else with your list.

2. This may seem obvious but when people unsubscribe, remove them from your list! If you are keeping unsubscribed addresses around, they have broken up with you and it is best to move on. Delete their addresses.

3. Remove repeat addresses. Sending to the same address twice greatly increases their chance of submitting a spam complaint. In fact, they will probably send two spam complaints. Spam complaints will cause the death of a senders deliverability.

4. Typos. Mistakes can happen in the process of acquiring addresses. This can be misspelling the domain (@homail.com, @gmal.com, etc.) or any piece of the address (@gmail.cm, @gmailcom,  etc.). A great way to avoid this is in the registration form process. Have the recipient input their address twice to ensure it is correct. Then to make sure the address is real, do a [double opt-in](http://support.sendgrid.com/entries/21460483-Double-Opt-In).

5. Seek out the dead domains. Many times these are used as spam traps and sending to them will ruin a sender’s deliverability. Write a script or make a list of the domains you are sending to and do an mx lookup via the command line or a service like http://mxtoolbox.com to find defunct domains,  some of which may now be turned into spam traps.

6. Find email addresses that are commonly used as [spam traps]({{root_url}}/Glossary/spam_traps.html) or used to determine if you are sending spam. This means all role addresses (abuse@, sales@, help@, etc.) as well as common spam trap names (junk@, test@, asdf@, spam@, etc.).

7. Keep track of date of opt-in. This provides great opportunity for scrubbing out stale addresses. [Deal with old addresses appropriately](http://support.sendgrid.com/entries/21905783-Let-Old-Addresses-Sleep-in-Peace-) as they often lead to sending to spam traps or recipients likely to spam complain. Remember the best way to keep your addresses current is to [maintain engagement](http://support.sendgrid.com/entries/23439516-Keep-In-Touch-The-Importance-of-Engagement) giving the recipient an opportunity to unsubscribe as well as ensuring that they remember your relationship.

Remember, brush often and make periodical appointments for a deep cleaning.

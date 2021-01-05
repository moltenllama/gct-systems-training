
< Back to [Systems Training](../index.md)

# Getting Started
## What is Glimcare?
Glimcare is the system that we use to repsond to emails, update the knowledge articles on the support website and it also hosts our internal only, GCT Hub.

Glimcare includes 3 main applications: The Dashboard, Ticketing System and Knowledgebase.

## Accessing Glimcare
Glimcare is accessed via a web browser.  Shortly after joining the team, you'll receive a Discord DM with your username and password, along with the link to the access Glimcare.

At this stage, Glimcare accounts are separate from Glimesh accounts.  Logging in with your Glimesh or Github account is a feature we're looking in to, and may be available in the future.

If you forget your password, please speak to MoltenLlama or Paco1342 who both have access to reset passwords. These days a password manager is highly recommended so that you can use long and unique passwords for each site.  Do not use the same password on multiple sites.  Bitwarden is an open-source and independently audited password manager that is available for free, you can download it [here](https://bitwarden.com/).

# Settings Things Up
Glimcare uses an all-in-one design, with a global search box at the top left, a tab list of your open tickets below that and finally the profile and settings options down the bottom.  The right hand side of the page is where the main content you're working on is displayed.

<< TODO: insert screenshot >>

1. Global Search: Allows you to search for tickets by number, email address or keywords.  There are advanced search terms you can use as well, which can be found [here](https://user-docs.zammad.org/en/latest/advanced/search.html).

2. App Switcher: You can switch between the Dashboard, Ticketing System and the Knowledgebase by clicking them in the switcher.

3. Tabs: These work similar to browser tabs.  You can have multiple tickets open at the same time and can click on them to switch between them.  Any changes you make are stored, so you can safely move between tabs without saving without losing anything.

4. The profile button where you can change your Glimesh preferences and also see a list of your recently opened items.

5. The + button creates a new ticket.

6. Main content area, in the example above it's showing the Dashboard.

7. The Activity List shows you recent actions taken by other team members.

**NOTE:** You can only have one browser tab logged in at a time.  You can still have multiple tickets open, each ticket will open as a tab in your ticket tab list and you can switch between tickets without losing your changes.

## Profile & Settings

The profile and setting area allows you to change a number of things, including your password, avatar, notifcation settings and also set up your Out of Office settings.

## Password

Your password needs to be **at least** 12 characters, made up of uppercase letters, lowercase letters, numbers and special characters.  A password of 16 characters or more is highly recommended, to keep track, use a password manager like Bitwarden, Roboform or Lastpass, or use the built in password manager in your browser.

## Updating your Avatar
You can upload an avatar to use within Glimcare.  Please keep it professional.  At the moment it can only be seen internally, but if we add additional features like Live Chat or a portal where users can see their tickets, it will be shown there.  HINT: Glimdrops make great avatars ;)

## Setting up Notifications
Here you can set up your notifications and notification sound, by default you'll hear a notification sound every time a new ticket comes in.

You can choose the notification sound at the bottom of this page.

At this stage, email notifications aren't enabled so checking the Notify By Email boxes will not work.

## Out of Office / Extended Absence

If you're going to be away for an extended period of time.  You should set up your Out of Office in advance via your Glimcare settings.  During your time away your designated substitute will handle your tickets.

Your substitute will receive all your ticket notifications during your absence, it is suggested that you select your Team Lead as the substitute.

When someone leaves the team, we'll also set this up so that any existing tickets they were working on get sent to someone else to work on.

To set up your Out of Office.  Go to your click your Avatar in the bottom left hand corner, select Profile and then select Out of Office.

1. Give your time off a name (can be anything)
2. Enter the from and to dates
3. Enter the name of the person who will be your substitute (they should have GCT at the end of their name)
4. Click Enable

You can use the delete button to stop the out of office from forwarding your tickets, or it will automatically end at the time you chose above.

# Tickets

## What exactly is a ticket?
In Glimcare, tickets are used to track customer service requests. The first time a customer emails us about something, Glimcare creates a new ticket. Each message sent between you and the customer is added to that ticket until the issue is resolved, the customer is happy, and the ticket is closed.

We also use Glimcare tickets to manage reports coming in via the report button on channels and user profiles.

So in a basic sense, a ticket is a thread of messages between you and a customer about a single issue.

## Why use a ticketing system?
Using a ticket system rather than just use email allows us to organize and catalog a high volume of support requests, which will be important as Glimesh grows. We can easily manage multiple tickets at once because each ticket is labeled and can be prioritized by its urgency. This will also come in handy when we deal with critical situations where users are filing large amounts of support tickets regarding a specific issue. A ticketing system helps us identify and segment these cases so that a designated task force can quickly address them in bulk.

Another benefit of the ticketing system is the centralization of information. The tickets are all stored in on system that can be searched and referenced for future cases. Not only does that help with customer service analytics, but GCT members can also use it to look up past cases that may have a solution related to their present problem.

## What information is in a ticket?

Tickets all have the some common information attached to them.  Here's a summary:

- **Ticket Number:** A unique number given to every ticket and what we usuually use to look up a ticket when searching.
- **Status:** This let's us know the current state of a ticket.  Tickets can be open, closed or pending.
- **Priority:** Let's us prioritize tickets and alerts us to tickets that need immediate action.  Can be Low, Medium or High. An 'Emergency' priority will be added in a future release.
- **Queue:** Queues allow us to group tickets together.  As Glimesh grows so will the amount of tickets we receive. We'll need to sort tickets in to queues like 'Billing', 'Technical Issues', 'Team Lead Required' etc.
- **Notes / Emails:** Tickets also include emails sent between us and the user and can include private internal only notes that the user can't see.

## Ticket Statuses

The state of a ticket refers to its progress toward completion, and may be one of the following:

- new
- open
- closed
- pending close (i.e., scheduled to automatically close at a later date)
- pending reminder (i.e., hidden, but scheduled to reappear at a later date) 


## Ticket Queues

Queues let us sort tickets in to different stacks to make them easier to manage.  For instance, we could have a queue for Refund Requests and another one for tickets in Spanish.  

As we grow and find our feet, we'll be using Queues more and more, but to start with, we'll be using 2 queues:

- General Support
- Team Lead Escalation

General support will be where all new tickets come in to.

Team Lead Escalation will be where we send tickets that need assistance from a Team Lead (could be things like needing something done on the Dash that you don't have access to, or for when you need to escalate an urgent issue to a leader).

## Ticket Priorities

These allow us to prioritise our work, making sure that we pick up critical issues as soon as possible.  There are 3 ticket priorites:

- Low
- Medium (Default)
- High

When picking up tickets to work on from the queue, you should always be picking up High Priority tickets first, followed by Medium and then Low.

If you see a High Priority ticket in the queue and you're too busy to pick it up, please let everyone know in Discord.

NOTE: There may be an Emergency priority added at a later stage.

## Tags

Tags work exactly how you think they do.  Every ticket can have multiple tags.  They allow us to group tickets together similar to queues.

We're also able to run reports based on tags as well.

We'll work out how to best use tags as we start using the system.  Watch this space!

<!---
# Knowledge Base
# Reporting
# Advanced Features
-->

# What Your Vendor Changed Without Telling You: A Quarterly Audit Checklist for Service Business Automation — Borne Systems Blog

*Published by Borne Systems | Content Pillar: Maintenance*

---

## The Update You Did Not Know About

Last month, the company that handles your scheduling emails quietly changed how their authentication works. Last quarter, your texting platform retired a feature your reminder workflow depended on. Last week, your phone system rolled out a new dashboard, and the old login URL stopped forwarding.

None of those changes came with a knock on your door. None of them triggered an alert. Your automation is still running. Your dashboard still says everything is online. And the customers who call after 5 p.m. are still getting a friendly voice that says, "Sorry, we are not available right now," when your after-hours workflow was supposed to forward them to your on-call line.

That is the most common reason automation breaks in service businesses. Not because anything you did changed. Because something the vendor did changed, and nobody on your side noticed.

## Why Vendors Change Things Quietly

Software vendors update their products constantly. They retire old endpoints. They raise prices on the tier you are sitting on. They rename buttons. They consolidate dashboards. They push security fixes that require a re-authorization you never completed. They sunset features that are not profitable enough to keep.

Most of these changes are reasonable. Some are even improvements. The problem is not the changes themselves. The problem is the way they reach your business: a one-line note buried in a release email you skim, a checkbox you did not see in a settings page, or nothing at all.

You do not have a vendor problem. You have a quarterly attention problem. Vendors will keep changing. The only thing you can control is whether your stack still matches what your customers need after the change.

## The Three Quiet Failure Modes

In practice, silent vendor changes break service businesses in three predictable ways.

### 1. Pricing tier shifts

Your plan used to include missed-call text back. Last month the vendor moved that feature to a higher tier. You did not get a clear email. The feature is now sitting behind a paywall. Your dashboard still shows it as enabled, but it stopped working two weeks ago.

This is the most expensive silent failure because the dashboard looks fine. The vendor is billing you the same amount. The output has simply disappeared. You find out when a customer tells you they never got the text.

### 2. Sunset features and renamed endpoints

A text template you wrote six months ago referenced a service you still offer. The vendor renamed that variable in their latest release. Your reminder texts now say "Your [Service] is scheduled for tomorrow" where the service name is blank. Customers stop showing up because the reminder does not tell them what the appointment is for.

Same root cause. Same dashboard. Different output. Customers notice. You do not, until the no-show rate climbs.

### 3. Authentication and integration breakage

Your scheduling system talks to your text-back platform through a connection that needed to be re-authorized after a vendor security update. The connection silently dropped. New leads are not landing in your calendar. Old leads are still there, looking fine. The system says it is healthy.

This one is the hardest to catch because the integration tab shows green. The integration just stopped moving data. You find out when a customer tells you they booked but you do not see them on the schedule.

## The Quarterly Audit Checklist

You do not need a project. You need thirty minutes once a quarter and this checklist.

**Pricing tier audit.** Open every vendor invoice. Compare what you are paying for to what you are actually using. Look for features that moved tiers, free trials that ended, or price increases that were grandfathered for ninety days and then quietly rolled out. Set a calendar reminder for the same week each quarter.

**Template and message review.** Pull up every customer-facing message your system sends. Look for blank variables, outdated service names, broken links, and references to offers you no longer run. The easiest way to find these is to send yourself a sample of each message and read it as if you were the customer.

**Integration health check.** Open every connection between tools. Most automation stacks have three to seven integrations: scheduling to text-back, scheduling to email, CRM to invoicing, phone to CRM, and so on. Each one needs a test record pushed through it this quarter. A real record, not the vendor's built-in "ping." Confirm the record lands where it should.

**Login audit.** Walk through every login any team member uses. Remove anyone who has left. Reset any password that has not been changed in over a year. Confirm two-factor authentication is on for every admin account. Most silent failures that look like outages start as compromised or stale logins.

**Vendor roadmap skim.** Spend twenty minutes on the websites of your top three automation vendors. Look for their public roadmap, changelog, or release notes. Note anything that touches features you use. Most of what you find will be noise. The signal is enough to flag in advance.

That is the audit. Thirty minutes once a quarter. Five lines of work. The output is a short list of fixes that prevent the silent failures nobody has time to chase when they show up in the middle of a busy week.

## Why Most Owners Skip This

The honest reason is that nothing is on fire right now. The system feels fine. The customers are not complaining. There is a job on the schedule for tomorrow and a quote to send this afternoon. A quarterly audit feels like a meeting the business does not have time for.

The problem is that silent failures do not announce themselves. They show up on the revenue line three months later when conversion drops and nobody can explain why. The audit is not what you do when something is wrong. It is what you do so that nothing goes wrong in the first place.

## What to Set Up This Week

Pick a recurring thirty-minute block in your calendar. Once a quarter is enough. Run the five-point checklist above. Save your findings in a single document your team can reference. The first audit will surface two or three fixes you did not know you needed. By the third audit, you will have stopped most of the silent failures before they ever reach a customer.

The vendors will keep changing. Your business will keep changing. The audit is the bridge between the two.

## The Bottom Line

Most automation breakdowns are not caused by anything you did wrong. They are caused by something the vendor changed, combined with the absence of a regular check on your side. A thirty-minute quarterly audit closes the gap. It is not glamorous. It is not exciting. It is the cheapest insurance you will ever buy against the most expensive kind of failure.

---

## Frequently Asked Questions

### How do I find out what my vendors changed this quarter?

Most vendors publish a changelog, release notes page, or roadmap on their website. Bookmark those three pages for your top automation vendors. Skim them once a quarter during your audit. You do not need to read everything. Skim for your vendor names and feature names.

### What is the most common silent vendor change?

Pricing tier shifts. Vendors regularly move features between plans, sunset features with low usage, or change what is included in the price you are paying. The feature is still in your dashboard, often grayed out or partially working, but it stopped doing what it used to do. A quarterly review of your invoice against your actual usage catches most of these.

### Should I depend on my vendor to tell me about breaking changes?

No. Vendor release emails are usually optimized for active users of the changed feature. If you are not a power user, you will not get a personal note. Treat the vendor as one source of information and the quarterly audit as the safety net.

### How do I test an integration without breaking real customer data?

Create a test record at the source. Push it through the integration manually. Confirm it lands at the destination with the right fields. Then delete or archive the test record. Most scheduling and CRM tools have a sandbox mode or a built-in test button for this. If yours does not, a one-off test record is fine. Most platforms let you mark it as a test.

### What if I find a broken integration during my audit?

Fix it the same day if you can. Most integration fixes are under an hour: re-authorize, regenerate a key, or update an endpoint. If the fix is bigger, write down what you found, what you tried, and what the next step is. Schedule the next step before you close the audit. A documented half-fix beats a forgotten full fix.

### Does Borne Systems run quarterly audits for service businesses?

Yes. We run a thirty-minute audit each quarter across every workflow, integration, and template in your stack. We send you a short report with what changed, what is at risk, and what we are fixing. Most clients have three to five fixes per quarter. Most of them are silent failures the owner never would have caught alone.

---

*Borne Systems builds and maintains automation and security systems that help service businesses capture more leads, protect customer data, and keep operations moving.*

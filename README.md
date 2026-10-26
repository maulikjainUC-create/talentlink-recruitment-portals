# TalentLink recruitment portals

Four individual portals, connected through fictional browser-local sample records:

- index.html: portal directory
- partner.html: signup, country/location and slot selection, L1 simulation/status
- trainer.html: geography-based candidates, L1-L3 assessment, notes, category and verification
- recruiter.html: verified profiles, immediate phone reveal and reservation, placement, expiry and hub updates
- business.html: accounts, trainer calendars/slots, signups/results, channel funnel, quotas and manual hub updates

All sample staff passwords are Demo123!.
Trainer logins: trainer.sg, trainer.mm, trainer.overseas.
Recruiter logins: recruiter.a, recruiter.b.
Business login: business.admin.

Use only fictional test information. These credentials are public demo values. There is no real server authentication, anti-crawling enforcement, Hireflix connection or external message delivery. Data lives in localStorage under talentlink-demo-v2. Production requires a database, server-side access checks and atomic reservations. Different browsers/devices do not share data. Browser-local geography restrictions and profile ownership illustrate intended behaviour only.

The Partner L1 button simulates completion; trainer pass/fail and verification are separate. New accounts and slots created in Business become available in the other portals on next load. Business hub updates appear in the recruiter's candidate record, with an in-app notice when joining is within 14 days. The sample reservation period is 48 hours, not a confirmed rule. CSV downloads open in Excel. Hub structure and allocation logic remain to be defined. Scheduling currently prevents exact trainer date/time duplicates, not duration overlaps or full leave-calendar planning.

## Hosting
Upload all files in this folder to the root of a GitHub repository. Enable GitHub Pages from main/root. All URLs are relative, so project repository hosting works without configuration. No build/dependency installation is necessary.

## Connected test
Register a fictional partner; select Singapore. Open Trainer as trainer.sg. Record L1 Passed, L2 Passed, L3 Passed, select category and Confirm UC Verified. Open Recruiter A and select the newly verified candidate. Enter a future start date and aggregator. Open Business placements, edit the candidate hub and start date. Return to Recruiter to see the assignment.

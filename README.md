# caint
caint is a comment system.

## ROADMAP
- Self-Hosting Documentation
    Technical writing is hard. I also need to update DB scaffolding files to ensure everything is correct.
- Redo Dashboard UX
    Dashboard currently defaults to nothing, just the welcome message and a menu above it with links to the constituent parts. It would be more useful to show some information on the dashboard frontpage - possibly unapproved comment counts, the most recent comments with link to the page, etc.
- Unapproved reminder email
    A user configurable option to have a reminder email sent weekly(?) if any comments remain unapproved would be helpful for lower traffic sites that don't get checked regularly.
- Support for comments sent via email.
    Similar to the sr.ht lists feature. Each "thread" should have it's own hash associated, emails sent to hash@caint.casa should be taken on a regular basis by the software and converted into a comment.
testing-issues
==============

just creating this repo to try to reproduce github notifications that point to a 404

to reproduce:

* create a repo
* create an issue, and mention people
* before these people have time to read their notifications on https://github.com/notifications, disable issues from the settings.

expected:

* the notifications should (eventually) disappear from the recipient's notifications inbox (via eventual consistency / lazy delete)

actual:

* the notification turns into a ghost notification which you cannot remove by clicking on it - it only goes away if you explicitly mark it as read

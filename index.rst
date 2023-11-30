.. anonymous giver project specification master document

Anonymous Giver Site
====================

The project is inspired by "Secret Santa" (aka "Secret Nicholas") Christmas
tradition, but it is not focusing on some specific celebrations or events.
The primary objective is to create a place on the internet where people can
gather together in groups and give anonymous gift one each other.

Key features
------------

.. rubric:: Wish lists

Any registered user can create and modify their own wish lists. The wish list
is generally private and is not available for any other users, unless they are
not assigned to be a gift-giver to a person.

.. rubric:: Many gift-giving campaigns

Users can join many gift-giving campaigns. There is no limit on groups number.

.. rubric:: Personal reminders

Users without (or with empty) wish lists will be prompted to place something
there. As well as dormant users will be prompted to join some gift-giving
campaign.

.. rubric:: Administration can't get in the way

Site admins perform wish lists moderation and gift-giving campaign support, and
cannot cancel, modify or remove users events.

Registration and authentication
-------------------------------

-   Anonymous users may access any public available page.
-   Anonymous users can register their account by providing a username,
    fullname, and password.
-   Anonymous users can login to their existing account.
-   Authenticated users can logout at any time.

Wish lists
----------

Wish lists are personal collections of their desired gifts.

-   Wish list is created for any registered user, except admins.
-   Wish list is available for its owner and site admins only.
-   Wish list is temporary available for the other users assigned as a giver
    for a person.
-   Owners can add, modify or remove entries in their wish lists.
-   Admins can ban some any wish list entry, which makes it to act as removed.

Gift-giving campaigns
---------------------

-   Non-admin users can create their gift-giving campaigns.
-   Each campaign should have its name, description and members list.
-   The campaign creator is assigned as a campaign member and cannot be
    excluded.
-   There is no limitations on the total number of created campaigns.
-   Campaigns can be marked as draft, public, private, or completed.
-   Admins or campaign creator can run the campaign if there are at least
    3 members in it.
-   There is no way to join the campaign if it has been run.
-   Any user, except creator, can leave the campaign if it hasn't been run.

.. rubric:: Draft campaigns

-   No one user cannot join the draft campaign.
-   Campaigns can are marked as drafts by default at the campaign creation
    form.
-   Campaign creator can publish it by making campaign private or public.
-   Draft campaigns cannot be run.

.. rubric:: Public campaigns

-   Public campaigns are available for anonymous and authenticated users.
-   Authenticated users can join any public campaign, unless it hasn't been
    run.

.. rubric:: Private campaigns

-   Private campaign are available for their members only.
-   Campaign creator can share join link with other users.
-   When joined the campaign, it becomes available in the campaigns list.

.. rubric:: Completed campaigns

Actually this means the campaign has been completed and moved to the archive.
Completed campaigns acts as deleted ones. Admins can remove archived campaigns
at any time (campaigns clean-up).

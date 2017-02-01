Administration
==============


Deploying Signals
~~~~~~~~~~~~~~~~~~~~

A **Cloud Deployment** is our most common method of deployment. Among other services, Amazon Web Services S3 and EC2 are used to provide an optimal experience in computing and visualization.

:ref:`Contact us <contact>` for information on alternative deployment methods.


Account Info
~~~~~~~~~~~~~~~~~~~~

Your account info and management console is all available on the Settings page.

.. image:: settings.png


.. _share:

Permission Levels
~~~~~~~~~~~~~~~~~~~~

Permissions on any asset (dashboard, stopword list, taxonomy, etc.) are set by the creator of that object.

**Can View** users can view and use the asset but cannot permanently modify it.


**Can Edit** can view and modify the asset, but cannot share it with others.


**Can Share** can edit and share the asset with others, but cannot remove others' access.


**Owner** can edit, share, and add or remove users with less privilege. 


User Groups
~~~~~~~~~~~~~~~~~~~~

Group management can be done from the Groups page on the main nav bar.

There are 4 levels of access at a group level:
  1) Group Admin
  2) Admin
  3) Can Edit
  4) Can View

The creator of a group is automatically a Group Admin for the group.

**Group Admin** users:

+ have a maximum* access level of **Owner** to any asset shared with the group.
+ can add users to the group and give them **Group Admin** rights or lower to the group.
+ can remove users with less permission (Admin, Edit, and View Only users)

.. Note:: A group can only have one Group Admin. Group Admins can transfer ownership to another user, but this action demotes the transferer to Admin


**Admin** users:

+ have a maximum* access level of **Owner** to any asset shared with the group.
+ can add users to the group and give them **Admin** rights or lower to the group.
+ can remove users with less permission (Edit and View Only users)


**Can Edit** users:

+ have a maximum* access level of **Can Edit** to any asset shared with the group.
+ cannot add or remove other users from the group.


**Can View** users:

+ have a maximum* access level of **Can View** on any asset shared with the group.


*when sharing an asset with a group, the sharer dictates the level of permission granted to the group. The lesser privilege (between permission granted to the asset and permission within the group) will then take precedence for each user. For example if a user grants **Admin** permissions on a dashboard to a group, group members with **Can View** in the group will only receive **Can View** on that object.
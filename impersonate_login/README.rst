=================
Impersonate Login
=================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:4875867f60d80f01c7bb74137a9f9bbdc0dceffde3bd47d96af9d897cd8de1f6
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fserver--auth-lightgray.png?logo=github
    :target: https://github.com/OCA/server-auth/tree/16.0/impersonate_login
    :alt: OCA/server-auth
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/server-auth-16-0/server-auth-16-0-impersonate_login
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/server-auth&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module allows one user (for example, a member of the support team)
to log in as another user. The impersonation session can be exited by
clicking on the button "Back to Original User".

To ensure that any abuse of this feature will not go unnoticed, the
following measures are in place:

-  In the chatter, it is displayed who is the user that is logged as
   another user.
-  Mails and messages are sent from the original user.
-  Impersonated logins are logged and can be consulted through the
   Settings -> Technical menu.
-  

There is an alternative module to allow logins as another user
(auth_admin_passkey), but it does not support these security mechanisms.

**Table of contents**

.. contents::
   :local:

Configuration
=============

The impersonating user must belong to group "Impersonate Users".

Usage
=====

1. In the menu that is displayed when clicking on the user avatar on the
   top right corner, or in the res.users list, click "Switch Login" to
   impersonate another user.
2. On the top-right corner, the button "Back to Original User" is
   displayed in case the current user is being impersonated.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/server-auth/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/server-auth/issues/new?body=module:%20impersonate_login%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* Akretion

Contributors
------------

-  Kévin Roche <kevin.roche@akretion.com>
-  `360ERP <https://www.360erp.com>`__:

   -  Andrea Stirpe

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-Kev-Roche| image:: https://github.com/Kev-Roche.png?size=40px
    :target: https://github.com/Kev-Roche
    :alt: Kev-Roche

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-Kev-Roche| 

This module is part of the `OCA/server-auth <https://github.com/OCA/server-auth/tree/16.0/impersonate_login>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.

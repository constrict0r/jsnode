Description
--------------------------------------------------------------

Ansible role to use as a wrapper for `yarn <https://yarnpkg.com/>`_
to install nodejs packages.

This role performs the following actions:

- Ensure the requirements are installed.

- Ensure the current user can obtain administrative (root) permissions.

- If not already added, add the nodejs repository to the apt sources.

- If not installed, install nodejs.

- If the **packages_js** variable is defined, install the javascript packages
  listed on it.

- If the **configuration** variable is defined, install the javascript packages
  listed on it.
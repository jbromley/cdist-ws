cdist-type__ssh_keyscan(7)
==========================

NAME
----
cdist-type__ssh_keyscan - gather ssh host keys


DESCRIPTION
-----------
Run ssh-keyscan on the specified hosts and add them
to the known_hosts file of the named user.



REQUIRED PARAMETERS
-------------------
hosts - space separated list of hosts to scan


OPTIONAL PARAMETERS
-------------------
None.


BOOLEAN PARAMETERS
------------------
None.


EXAMPLES
--------

.. code-block:: sh

    __ssh_keyscan root --host github.com

    __ssh_keyscan user --host github.com gitlab.com


SEE ALSO
--------
:strong:`TODO`\ (7)


AUTHORS
-------
russel <russel@appliedinvention.com>


COPYING
-------
Copyright \(C) 2023 russel. You can redistribute it
and/or modify it under the terms of the GNU General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

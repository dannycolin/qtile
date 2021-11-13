====================
Installing on Fedora
====================

Stable versions of Qtile are currently not available in the official
Fedora repositories. Below, you will find the instruction to install
qtile from `pip` and the necessary dependencies from both `dnf` and
`pip`.

Installing on X11
=================

.. code-block:: bash

    dnf install pango \
                python3-cairocffi \
                python3-cffi \
                python3-dbus-next \
                python3-xcffib \
                xorg-x11-server-Xorg
    pip install qtile

Installing on Wayland
=====================

.. code-block:: bash

    dnf install pango \
                python3-cariocffi \
                python3-cffi \
                python3-dbus-next \
                wlroots-devel
    pip install pywayland \
                pywlroots \
                qtile \
                xkbcommon

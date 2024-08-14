IMPORTANT
=========

This is a fork of OBS studio that adds 6 extra tracks (for a total of 12). I do not intend to maintain this and merge updates. If you require the latest version of OBS, either manually merge it into here or apply the `changes <https://github.com/obsproject/obs-studio/commit/bf15c81367e2151ccd6560cad9ef170062764fd1>`_ in the latest version.

If you get an error during building, then try to clone the original repository (or `the last commit before this fork <https://github.com/aayla-secura/obs-studio-extra-tracks/commit/1e6c375e95fe982bdeadf671edf1df420dd8d5bc>`_). Then apply a patch:

.. code-block:: sh

   cd obs-studio-extra-tracks/
   git format-patch 1e6c375e95fe982bdeadf671edf1df420dd8d5bc
   cp 0001-Increased-number-of-tracks-from-6-to-12.patch ../obs-studio/
   cd ../obs-studio/
   git am 0001-Increased-number-of-tracks-from-6-to-12.patch

Then build in the directory of the original project (`obs-studio`).

Before running it, backup your OBS configuration. If you don't see the extra 6 tracks or you get errors, then try to delete the OBS configuration. Note that in Advanced Audio Settings you will need to scroll right to see the extra tracks.

OBS Studio <https://obsproject.com>
===================================

.. image:: https://github.com/obsproject/obs-studio/actions/workflows/push.yaml/badge.svg?branch=master
   :alt: OBS Studio Build Status - GitHub Actions
   :target: https://github.com/obsproject/obs-studio/actions/workflows/push.yaml?query=branch%3Amaster

.. image:: https://badges.crowdin.net/obs-studio/localized.svg
   :alt: OBS Studio Translation Project Progress
   :target: https://crowdin.com/project/obs-studio

.. image:: https://img.shields.io/discord/348973006581923840.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2
   :alt: OBS Studio Discord Server
   :target: https://obsproject.com/discord

What is OBS Studio?
-------------------

OBS Studio is software designed for capturing, compositing, encoding,
recording, and streaming video content, efficiently.

It's distributed under the GNU General Public License v2 (or any later
version) - see the accompanying COPYING file for more details.

Quick Links
-----------

- Website: https://obsproject.com

- Help/Documentation/Guides: https://github.com/obsproject/obs-studio/wiki

- Forums: https://obsproject.com/forum/

- Build Instructions: https://github.com/obsproject/obs-studio/wiki/Install-Instructions

- Developer/API Documentation: https://obsproject.com/docs

- Donating/backing/sponsoring: https://obsproject.com/contribute

- Bug Tracker: https://github.com/obsproject/obs-studio/issues

Contributing
------------

- If you would like to help fund or sponsor the project, you can do so
  via `Patreon <https://www.patreon.com/obsproject>`_, `OpenCollective
  <https://opencollective.com/obsproject>`_, or `PayPal
  <https://www.paypal.me/obsproject>`_.  See our `contribute page
  <https://obsproject.com/contribute>`_ for more information.

- If you wish to contribute code to the project, please make sure to
  read the coding and commit guidelines:
  https://github.com/obsproject/obs-studio/blob/master/CONTRIBUTING.rst

- Developer/API documentation can be found here:
  https://obsproject.com/docs

- If you wish to contribute translations, do not submit pull requests.
  Instead, please use Crowdin.  For more information read this page:
  https://obsproject.com/wiki/How-To-Contribute-Translations-For-OBS

- Other ways to contribute are by helping people out with support on
  our forums or in our community chat.  Please limit support to topics
  you fully understand -- bad advice is worse than no advice.  When it
  comes to something that you don't fully know or understand, please
  defer to the official help or official channels.


SAST Tools
----------

`PVS-Studio <https://pvs-studio.com/pvs-studio/?utm_source=website&utm_medium=github&utm_campaign=open_source>`_ - static analyzer for C, C++, C#, and Java code.

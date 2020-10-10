OBS Studio <https://obsproject.com>
===================================

.. image:: https://dev.azure.com/obsjim/obsjim/_apis/build/status/obsproject.obs-studio?branchName=master
   :alt: OBS Studio Build Status - Azure Pipelines
   :target: https://dev.azure.com/obsjim/obsjim/_build/latest?definitionId=1&branchName=master

.. image:: https://d322cqt584bo4o.cloudfront.net/obs-studio/localized.svg
   :alt: OBS Studio Translation Project Progress
   :target: https://crowdin.com/project/obs-studio

.. image:: https://discordapp.com/api/guilds/348973006581923840/widget.png?style=shield
   :alt: OBS Studio Discord Server
   :target: https://obsproject.com/discord

What is OBS Studio?
-------------------

  OBS Studio is software designed for capturing, compositing, encoding,
  recording, and streaming video content, efficiently.

  It's distributed under the GNU General Public License v2 (or any later
  version) - see the accompanying COPYING file for more details.

What is different in ths version?
---------------------------------

  This version is exactly the same as the official release, but has extended support
  for Replay Buffer, allowing you to have multiple display buffer lengths and
  associate a key bind to each one of them.

  To use it, go to Settings - Output (1), and set the Output Mode to "Advanced" (2)

  Click on the Replay Buffer tab (3) and there you should find a new list which
  will hold your custom Replay Buffer lengths.

  To add to this list, set the desired length on the Seconds box (4) and press
  the Add button (5). Note that the length you pick should be smaller than the
  "Maximum Replay Time" setting above. ie. If you set a custom value of 300 and
  the Maximum value is at 100, only 100 seconds will be saved.

  After you press the Add button, the value should appear on the list (6).

  .. image:: https://thedark.github.io/imageshost/obs/RBL01.png
    :alt: OBS settings Advanced Mode and Replay Buffer lengths list

  After setting up all the values you want, click the Apply button in the lower
  left to save your changes and head on to the Hotkeys page **(7)**, where you should
  be able to find and set up the hotkeys for your custom Replay Buffer lengths
  under the Replay Buffer section (8).

  .. image:: https://thedark.github.io/imageshost/obs/RBL02.png
    :alt: OBS settings Hotkeys settings for custom Replay Buffer lengths

  And you're done. Click Apply or OK to save the changes and use OBS as ususal.

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
   Instead, please use Crowdin.  For more information read this thread:
   https://obsproject.com/forum/threads/how-to-contribute-translations-for-obs.16327/

 - Other ways to contribute are by helping people out with support on
   our forums or in our community chat.  Please limit support to topics
   you fully understand -- bad advice is worse than no advice.  When it
   comes to something that you don't fully know or understand, please
   defer to the official help or official channels.

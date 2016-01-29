Scratch-Wiki-Skin
=================

If you'd like to help fix bugs in the skin for the Scratch Wiki, please fork, make and test changes, and then submit a pull request. Our design goals are to keep the wiki skin as simple and as easy to use as possible. So we're unlikely to accept pull requests for fancy features, or code that's difficult to maintain.

Credits: Original design by JSO, with contributions from jvvg, blob8108, scmb1, -PRO- and others.


Development
-----------

To install / setup

1. Mediawiki skins change a lot between versions, so you need to use the **same version of mediawiki** that the Scratch wiki is currently running. You can find that version here: http://wiki.scratch.mit.edu/wiki/Special:Version Download it here: <https://releases.wikimedia.org/mediawiki/>

2. Clone this repository as a subdirectory of your skins folder.

3. Change LocalSettings.php:

    $wgDefaultSkin = "scratchwikiskin";

4. You probably also want to grab <https://github.com/llk/mw-ScratchBlocks2>
   and drop it into your extensions folder. 

5. Run the test server:

    $ php5 -S localhost:8000

    The easiest option is to set up your test wiki using SQLite.


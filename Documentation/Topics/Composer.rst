.. include:: /Includes.txt
.. _tmsa-Composer:

=================
Composer
=================

.. _composer: https://getcomposer.org/


Description
   What is composer?

      Composer_ is a tool for dependency management in PHP. It allows you to declare
      the libraries your project depends on and it will manage (install/update) them for you.


Search
   - Search for: `composer+typo3 <https://www.startpage.com/do/dsearch?query=composer+typo3>`__

__________________________________________________

Important
   * https://composer.typo3.org (docs)

Blog postings (en)
   * 2020-07-03, T3Terminal: The Best Guide to TYPO3 Composer`
     <https://t3terminal.com/blog/guide-typo3-composer/>`__

   * 2020-06-08, T3Terminal: 10 Resources to Learn TYPO3 Composer`
     <https://t3terminal.com/blog/learn-typo3-composer/>`__

   * 2020-02-05, T3Terminal: 7 Easy Steps to Satis - TYPO3 Private Packages for Composer`
     <https://t3terminal.com/blog/satis-private-packages-composer/>`__

   * 2018-06-13, Helmut Hummel: `Improvements to composer.typo3.org
     <https://insight.helhum.io/post/174851830180/improvements-to-composertypo3org>`__

   * 2018-02-08, typo3.org: `Certificate issue with composer
     <https://typo3.org/news/article/certificate-issue-with-composer/>`__

   * 2018-02-02, Daniel Goerz:
     `The TYPO3 Subtree Split and Composer <https://usetypo3.com/typo3-subtree-split-and-composer.html>`__
     ✦
     `Tweet <https://twitter.com/ervaude/status/959435077372600321>`__

   * 2016-06-08, NITSAN: Step by step guide to TYPO3 Composer`
     <https://www.nitsan.in/blog/itug-week-27-step-by-step-guide-to-typo3-composer/>`__


Composer and TYPO3 extensions
   * `TYPO3 CMS Composer Package Generator <https://github.com/TYPO3/CmsComposerPackageGenerator>`__

        This script generates among other things it does a custom
        :file:`packages.json` file enabling to deploy TYPO3 CMS
        packages by Composer.

    * `Composer.json Generator For Your TYPO3 Extensions <https://demo.t3terminal.com/typo3-composer-generator/>`__

Composer patches instead of TYPO3 xclassing
   * `Simple patches plugin for Composer <https://github.com/cweagans/composer-patches>`__
     ✦
     `Tweet <https://twitter.com/xperseguers/status/1034807948386742273>`__


Documentation
   * 2018-07-31, Installation guide: `How to upgrade an existing TYPO3 installation to Composer
     <https://docs.typo3.org/typo3cms/InstallationGuide/MigrateToComposer/Index.html>`__

Explore this
   * `Private Packagist <https://packagist.com/>`__ - Composer package archive as a service for PHP
     ✦
     `Tweet <https://twitter.com/helhum/status/1032911116157034496>`__



Presentations
   * 2018-11-04, Helmut Hummel, live at #t3crr:

     * ::

             composer create-project helhum/typo3-distribution

             composer create-project foo/bar project-folder
             # lookup packagist for <repo-url>
             # git clone <repo-url> project-folder
             # cd project-folder
             # composer install

             composer require foo/bar
             # lookup packagist for newest version of package
             # change (or create) composer.json
             # composer update foo/bar


     * https://github.com/helhum/typo3-distribution
     * https://packagist.org/ - points to the repository of the package.
       Example: https://github.com/helhum/typo3-console

   * 2018-06-23, Helmut Hummel: `Your Perfect TYPO3 Distribution
     <https://speakerdeck.com/helhum/your-perfect-typo3-distribution>`__

groovydoc-maven-plugin
-----------------------------------

.. image:: https://github.com/qbicsoftware/groovydoc-maven-plugin/workflows/Build%20Maven%20Package/badge.svg
    :target: https://github.com/qbicsoftware/groovydoc-maven-plugin/workflows/Build%20Maven%20Package/badge.svg
    :alt: Github Workflow Build Maven Package Status

.. image:: https://github.com/qbicsoftware/groovydoc-maven-plugin/workflows/Run%20Maven%20Tests/badge.svg
    :target: https://github.com/qbicsoftware/groovydoc-maven-plugin/workflows/Run%20Maven%20Tests/badge.svg
    :alt: Github Workflow Tests Status

.. image:: https://github.com/qbicsoftware/groovydoc-maven-plugin/workflows/QUBE%20lint/badge.svg
    :target: https://github.com/qbicsoftware/groovydoc-maven-plugin/workflows/QUBE%20lint/badge.svg
    :alt: QUBE Lint Status

.. image:: https://img.shields.io/travis/qbicsoftware/groovydoc-maven-plugin.svg
    :target: https://travis-ci.org/qbicsoftware/groovydoc-maven-plugin
    :alt: Travis CI Status

.. image:: https://readthedocs.org/projects/groovydoc-maven-plugin/badge/?version=latest
    :target: https://groovydoc-maven-plugin.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://flat.badgen.net/dependabot/thepracticaldev/dev.to?icon=dependabot
    :target: https://flat.badgen.net/dependabot/thepracticaldev/dev.to?icon=dependabot
    :alt: Dependabot Enabled


Maven plugin to allow for inclusion of Gmavenplus generated Groovydocs in project-reports.html

* Free software: MIT license
* Documentation: https://groovydoc-maven-plugin.readthedocs.io.

Usage
--------

To use :code:`groovydoc-maven-plugin` in a project:

:code:`groovydoc-maven-plugin` is intended as a maven plugin, that has to be included in the reporting section of the project pom.

.. code-block:: xml

 <reporting>
  <plugins>
   <plugin>
    <groupId>life.qbic</groupId>
    <artifactId>groovydoc-maven-plugin</artifactId>
    <version>1.0.2</version>
   </plugin>
  </plugins>
 </reporting>

Credits
-------

This project was created with `QUBE
<https://github.com/qbicsoftware/qube>`_.
It's plugin structure was adapted from the the `Apache Maven report mojo tutorial
<https://maven.apache.org/guides/plugin/guide-java-report-plugin-development.html>`_.

bc-analyzer
===========

The purpose of this library started with this presentation https://www.youtube.com/watch?v=YTN4GJslbFY

You can see the slides [here](https://speakerdeck.com/cordoval/symfony-components-in-the-wild-drupal-jungle)


BC package analyzer

Architecture

Scanner:

  will scan files from autoload list

Drill:
  
  will drill the tree of extension and implementation

Parser:

  will parse annotated tags

Configurator:

  will configure the rules for BC
  
Resolver:

  use rules to resolve violation

Reporter:

  will report violations of BC rules

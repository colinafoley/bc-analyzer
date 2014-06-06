bc-analyzer
===========

The purpose of this library started with this preentation https://www.youtube.com/watch?v=YTN4GJslbFY

<script async class="speakerdeck-embed" data-id="64115d60cea50131a8cc564ad4407ede" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>


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

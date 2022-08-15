# Changelog since v1.2.7
- Merge pull request #148 from RubenNL/configurable-message-size

Configurable max message size. 
- default value for bashio::config to prevent possible issues with existing config. 
- Couple changes to make it easier to use.

* Changed the config option to mb instead of bytes.
* Made the default 10 mb instead of 50.
* Updated the DOCS.md file. 
- Remove space from replacement. 
- Configurable max message size.
My last change was not enough for the max of Gmail, for some reason. I have now doubled it again, and made it a config option, as you requested. 

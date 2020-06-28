# SMW Show
This extension for mediawiki allows you to integrate data from any Semantic MediaWiki into your wiki. 
 
The extension adds the following magic words to your mediawiki:
* smwshow: takes the API-URL, the name of the page and the Attribut you want to query.

Example: {{#smwshow:https://schularchive.bbf.dipf.de/api.php|Schulmuseum Bochum|Wikidata ID}} gives you Q2251368, which is the Wikidata ID defined for this [page](https://schularchive.bbf.dipf.de/index.php/Schulmuseum_Bochum).

## Installation
1. Clone this repo via git clone https://github.com/julianhocker/SMWShow.git into extensions 
2. Add wfLoadExtension('SMWShow'); to your LocalSettings.php

## Known issues 
* Please open issues if you encounter problems 
* I did not check yet if this integrates with all data types in SMW
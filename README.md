# General-Notes
Stuff that makes your system obey you more than the adversary

### How to make Google not track you when you use Google Chrome's search engine.
* Go into the search engine settings.
* Manage search engines.
* Select Google
* The Google query string probably is a long jarble beginning with "{google:baseURL}search?q=%s&{google:RLZ}{google:originalQueryForSuggestion}{google:assistedQueryStats}{google:searchFieldtrialParameter}{google:iOSSearchLanguage}{google:searchClient}{google:sourceId}{google:contextualSearchVersion}ie={inputEncoding}" This is what duckduckgo acts as a service for.
* Now create a new search engine in the options menu
* Call it "Google Privacy Enhanced"
* Keyword: dunno, up to you
* Use this query string: *https://google.com/?q=%s*
This strips all the spooky data from your search query which identifies your searches. Now you have google's search AI free of some tracking.


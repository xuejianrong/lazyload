TODO
====

* [FEAT] Add an "update" method for managing content that was added after an ajax call || avoid the usage of the array and run the loop live on the original nodeSet
* [PERF] Stop listening to "scroll" when 0 elements remains, restart listening after content was added
* [FEAT] Support for the srcset attribute
* [FEAT] Support for the picture tag (populate source.src and source.srcset instead of img.src or img.srcset)
* [SUPP] It doesn't work on IE7 because it doesn't support querySelectorAll. Create a fallback? Load them all somehow? Drop IE7 support?
* [NERD] Convert to coffeeScript?
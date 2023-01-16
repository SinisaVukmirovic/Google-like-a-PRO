## How to Google like a PRO
___

[How to Google like a PRO video tutorial](https://www.youtube.com/watch?v=BRiNw490Eq0)
___

#### Using double quotes (" ") around any term will force Google to match it exactly

```
EASTER EGG #1
Search ***blink html*** and all instances of ***blink*** and ***html*** in the descriptions of results will flash.
```

```
EASTER EGG #2
Search ***Google in 1998***, and the results page will take a time machine to what Google looked like then 
```

### Matching operators
#### Exact "", Exclusion -, Wildcard *, Around AROUND(number)

#### Exact "" Using double quotes (" ") around any term will force Google to match it exactly
##### "flutter" app development tutorials - will only find app dev tutorial specific to flutter
##### learn from free courses "seth goldin" - double quotes will also prevent "autocorrection" for more known term/people

#### Exclusion - Putting (-) before the term will exclude results that include that term
##### website tutorial -jquery - will exclude results that include jquery

#### WIldcard * Using * will be used as a standing for any word and phrase, when we forgot a word or can't spell it correctly
##### linus * linux - will return results about Linus Torvalds, the creator of Linux OS

#### AROUND(number) 
##### manage AROUND(4) memory - will return results containing a word **menage** within 4 word of the word **memory**
##### footbal AROUND(6) ESL

### Date Operators
#### before:, after:, range #..#

##### avatar review before: 2010
##### Command CodeSign with a nonzero exit code after: 2021-01-01 (avoid outdated answers)
##### python courses after: 2021 - will return only the latest python courses
##### superbowl halftime show before: 2016 after: 2009
###### or 
##### clojure 2016..2018

### Source Operators
#### site/search:, ext/filetype:, source:, loc/location:, blogurl:, cache: 
##### auditing courses site: freecodecamp.org - will only return result with courses from freecoedcamp site
##### javascript textbook filetype:pdf
##### restaurants near me loc:SF
##### blogurl:google.com - return blog sites under google's registry
##### cache:freecodecamp.org - will return all articles of freecodecamp site (chached version)  even if FCC site is down

### Boolean Operators
#### AND &&, OR |
##### battle of bull run OR battle of manassas - both are the same event with 2 different names, using OR operator returns both extended search results

### IN-(URL/Title/Text/Anchor) Operators
##### in:title flutter - will only return websites that refer to flutter
##### allintitle:flutter app tutorial
##### freecodecamp intext:rust - will return result with keyword mentioned in the text if not in the title
##### freecodecamp inanchor:hero 

### Utility Operators
#### define:, related:, ip address, X in Y, $, @, weather:, map:, movie:, stocks:
##### define:enterpreneurship -return google's definition of the term
##### related:freecodecamp.org - return site results similar to the freecodecamp site
##### $345 in EUR 
##### $300 android, keyboard $30...$50 - will return results with items of that price, or in price range
##### weather:bangkok
##### map:london
##### movie:Avengers Endgame

### Using and Combining Search Operators

##### how to build a * app site:freecodecamp.org -frutter (will give results on any type of app tutorial, except flutter, on freecodecamp containing the name quincy larson )

##### site:freecodecamp.org -inurl:blog (returns all subdomains except blogs)

##### "python * tutorial" (will return result with pythion and tutorial, in that order, in the name and anything in between)

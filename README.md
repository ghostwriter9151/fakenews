Fake News Recognizing Facts:

    1. Indicator: Using word ‚probably‘ = relative truth is not trustable
        1. Weight: 0.5
    2. Source is not given – verification is not possible
        1. Weight: 1
    3. Source uses references which are not scientific at all (e.g. Church facts: Stop words e.g. ‚purgatory‘)
        1. Weight: 1
    4. Source neglects historically proven facts (e.g. Wikipedia as source)
        1. Weight: 1


Implementation:

    • Stop word search (probably, purgatory)
    • Source search (www-links, book references)
    • Historically facts search (Wikipedia)

Input: 

    • Text, not image



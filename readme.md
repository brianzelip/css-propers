# Propers CSS

Note to self: This directory contains all of the best work that I've done regarding turning each CSS `<property>: <value>` pair into a single (atomic and reusable) class.

The source for knowing the set of values for each property is [!mdn](https://duckduckgo.com/!mdn).

A library like this will be most strong and meet community expectations most in the area of properties that have keyword values.

Non-keyword values include:
- color
- length
- percentage
- position (which consists of lengths or percentages)
- URL
- function

The personality of the library is most expressed in the default subset of values that the library provides for the non-keyword values.

A (reusable/atomic) css library's personality also participates in:
- the naming of classes
- the layout of docs
- the ability (or lack thereof) to:
    + get the whole output (all property-value instances-as-classes) as one file
    + get only the output for one property-value instance-as-class
    + pick and choose (customize) the property-value classes to use/download (requires a web app)
    + be managed according to best practices:
        * the monolithic modules repo for centralization and community discussion (see the Basscss v7.1 issue talk (i think that is the correct version))
        *



*CSS properties that aren't only key-value have possible values that answer either the question "what color?" or "how much?".*

The css property values that aren't keyword values ask either "what color" or "how much" || they are shorthand properties (that combine values from multiple properties).

Once all of the "included" css `property:keyword values` are translated into individual classes with the first, "definition" or "translation" pass through, a next step will need to be to consider naming practices. Some current administrative decisions have been:
- the actual css files per property:values are named `index.css` inside a directory named `<property>`; this could be different in a few ways:
    1. keep the parent directory but name the index file `<property>`
    2. rename the index file `<property>` and move it up one directory, thus getting rid of the `<property>`-named parent directory
    3. keep the parent directory and rename the index file `<property>`
- the class name as `<property>` with the value added on with `--<value>`, like, `.display--table: { display: table; }`, or `.float--right: { float: right; }`. This approach is an extreme diference from Basscss and Tachyons, in that there is no abbreviation in the base of the class name that uses the one best word that semantically defines what the property is about; it uses a BEM style modeification to the "root" property class name; it forgoes brevity;  however, it does hold a sort of objective extreme translation/interpretation/definition the most fully exacting approach


Propers CSS defines single-declaration classes after each `property: value` pair.

    see http://apps.workflower.fi/vocabs/css/en#function


See this link for the shell script to change all index.css file names to
<parentDirectoryName>.css
    http://unix.stackexchange.com/a/78961/161921

See this link for the excellent CSS Vocabulary web app that demonstrates
examples of each component of the css vocabulary.
    http://apps.workflower.fi/vocabs/css/en



Single class CSS
css-propers
CSS Propers
Single-declaration classes for each `<property>: <keyword value>` pair
Single-declaration classes for each `<property>: <keyword value>` pair
Single declaration classes for each

Single-declaration classes for all possible <keyword> values and most <non-keyword> values.

Take CSS with you from project to project instead of starting from scratch every project.

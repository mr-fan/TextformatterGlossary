# TextformatterGlossary
Allows to use tags in textareas to autolink to specific glossary links Texformatter for ProcessWire

## Setup

You have to use a pagestructure for the glossary items

- holder Page for entries template "glossary"
- glossary items template "glossary_item"

The type of a glossary item could be a abbreviation, a external or internal link. Everything you need could added to the textformatter like more complex stuff, footnotes or other replacements.

## Why?

There are working solutions like the great module from Ryan Cramer Autolink in the Profields
https://processwire.com/api/modules/profields/autolinks/

But here Users don't could setup easy the terms to replace - this is only ment for webmasters or admins.

There are a module for abbreviations from sunlix
https://processwire.com/talk/topic/7467-module-processabbreviate/

But here i only have options for abbreviations and i couln't easy add stuff or replacments i need.

## How it works?
You can use this textformatter on any textinputfield or wysiwyg.
The terms are catched by pipes ||term||.
If no term/tag is found the pipes will cleaned out. If a term/tag is found it will replaced with the term/tag from the glossary.

## Advantages
This sytem is higly flexible in organisation the terms, rights to change/add new tags, since every term is a real page.
The basic typ of a term/tag could be everything - on my basic setup i use this for abbrevitations and external links that are often used. But there could be much more types of reusable snippets of html triggered by a specific term/tag.

## Problems?

No known problems so far - but this is not really tested in a bigger scale....so use it like it is without warranty from me.
Caching should work but is not tested.
Replacements work great even with PageTableExtended the strings/terms get replaced while the preview rendering is generated.
Maybe there is a performance problem on bigger glossarys - i'm not a professional PHP Coder. So here is place for improvements.

Best regards mr-fan


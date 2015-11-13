# TextformatterAutoAnchor
ProcessWire Module: Automatically add anchors and IDs to Headings

## What is it doing?

This Textformatter adds an id attribute to every heading with a slug of the text. Intended for easily creating linkable sections.

## Demo

Currently it is used at http://www.happy-css.com

AutoAnchor in action: http://happy-css.com/lessons/riotjs/reusable-components/

### Preview
**Before**
![Before](http://i.imgur.com/pzkZaWF.jpg)
**After**
![Before](http://i.imgur.com/gXykULs.jpg)

## Configurable Variables

**Heading Selector**

Determine which headings you want to have the ID + anchor
Use a regex-like range or list, e.g.: `2-6` or `346`.

**Anchor Class**

Your css classes that are attached to the anchor link.

**Anchor Content**

The text for your anchor. If you prefer an icon, you could also use HTML for example.

## What are the Alternatives?

There are existing tools like [Anchorific JS](http://renaysha.me/anchorific-js/) but its dependency is jQuery. I love to have an alternative that is PHP only.

## Known issues
 - Anchors are placed in front of the text. This could be a future configurable setting.
 - The slug is also not configurable yet, currently it is lowercased and space is replaced with hyphens/dashes

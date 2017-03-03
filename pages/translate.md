---
sidebar: home_sidebar
title: How to translate
permalink: translate-howto.html
tags: how-to
---


## How to translate

We use [Crowdin](https://translate.lineageos.org) as our translation system. To send in a translation proposal, create an account there, click the desired language and apply as translator. Once you were accepted, you can click through the various files.

## I have translated a lot, how do I get these into my phone now?

For each language there is one or several proofreaders. Those will (also on a voluntary base) look through the strings and validate those which they think are fitting and of a high-enough quality. In case you note that your strings don't go in for some time (and no alternate suggestion as well), you can contact one of the proofreaders via the sidebar on the right. To achieve this, type "@" followed by the name and then add the message (e.g. "@NameHere: Please look through my translations on this file").
After the strings have been validated, an unregular job is run to copy the strings over to the actual source code and are merged via (Gerrit)[https://review.lineageos.org]

{% include tip.html content="You can check who is proofreader for your language on the [Contributors(http://wiki.lineageos.org/contributors.html#translations-proofreaders) page.
In case is no proofreader for your language listed, please also check the [crowdin translators list](http://translate.lineageos.org/project/lineageos/translators). You can filter for your specific language and then click "details" for each of your fellow contributors and see, if they are T (translator) or P (proofreader)" %}

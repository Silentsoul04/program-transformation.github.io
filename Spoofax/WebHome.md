::: {.fullPage}
::: {.twikiMiddleContainer}
::: {.twikiLeftBar}
::: {.twikiLeftBarContents}
**[Spoofax](http://www.program-transformation.org/view/Spoofax/WebHome)**

\

**[Home](WebHome){.twikiLink}**

**[Tour and screenshots](Tour){.twikiLink}**

**[Documentation](Documentation){.twikiLink}**

**[Download](Download){.twikiLink}**

**[Research](Research){.twikiLink}**

**[Development](Development){.twikiLink}**

**[Support](Support){.twikiLink}**

\

\
:::
:::

::: {.twikiMain}
::: {.toolBar}
::: {.flexMenuBar}
::: {.flexMenu onmouseover="return showMenu(event, 100);" onmouseout="return hideMenu(event, 100);"}
Page

::: {#flexMenuContent100 .flexMenuContent}
-   [Edit
    Page](http://www.program-transformation.org/edit/Spoofax/WebHome?t=1536825363)
-   [Rename
    Page](http://www.program-transformation.org/rename/Spoofax/WebHome)
-   [Attach
    File](http://www.program-transformation.org/attach/Spoofax/WebHome)

<!-- -->

-   [Printable](http://www.program-transformation.org/view/Spoofax/WebHome?skin=print.pattern)
-   [Wiki
    Source](http://www.program-transformation.org/view/Spoofax/WebHome?skin=text&raw=on&contenttype=text/plain)

<!-- -->

-   [Rev
    10](http://www.program-transformation.org/view/Spoofax/WebHome?rev=1.10)
    [(diff 9)](http://www.program-transformation.org/rdiff/Spoofax/WebHome?rev1=1.10&rev2=1.9)
-   [Rev
    9](http://www.program-transformation.org/view/Spoofax/WebHome?rev=1.9)
    [(diff 8)](http://www.program-transformation.org/rdiff/Spoofax/WebHome?rev1=1.9&rev2=1.8)
-   [Rev
    8](http://www.program-transformation.org/view/Spoofax/WebHome?rev=1.8)
    [(diff 7)](http://www.program-transformation.org/rdiff/Spoofax/WebHome?rev1=1.8&rev2=1.7)
-   [Total
    History](http://www.program-transformation.org/rdiff/Spoofax/WebHome)

<!-- -->

-   [More
    \...](http://www.program-transformation.org/oops/Spoofax/WebHome?template=oopsmore&param1=1.10&param2=1.10)
:::
:::

::: {.flexMenu onmouseover="return showMenu(event, 102);" onmouseout="return hideMenu(event, 102);"}
Web

::: {#flexMenuContent102 .flexMenuContent}
-   [Recent Changes](WebChanges){.twikiLink}
-   [Notify Service](WebNotify){.twikiLink}
-   [News](WebNews){.twikiLink}

<!-- -->

-   [Page Index](WebIndex){.twikiLink}
-   [Search](WebSearch){.twikiLink}

<!-- -->

-   [More
    \...](http://www.program-transformation.org/oops/Spoofax/WebHome?template=oopsmore&param1=1.10&param2=1.10)
:::
:::

::: {.flexMenu onmouseover="return showMenu(event, 103);" onmouseout="return hideMenu(event, 103);"}
Wiki

::: {#flexMenuContent103 .flexMenuContent}
-   [About
    TWiki](http://www.program-transformation.org/view/TWiki/WebHome)
-   [Text
    Formatting](http://www.program-transformation.org/view/TWiki/TextFormattingRules)

<!-- -->

-   [Registration](http://www.program-transformation.org/view/TWiki/TWikiRegistration)
-   [Change
    Password](http://www.program-transformation.org/view/TWiki/ChangePassword)
-   [Reset
    Password](http://www.program-transformation.org/view/TWiki/ResetPassword)

<!-- -->

-   [Users](http://www.program-transformation.org/view/Main/TWikiUsers)
-   [Groups](http://www.program-transformation.org/view/Main/TWikiGroups)
:::
:::
:::
:::

::: {.twikiTopic}
 {#section .twikiTopicTitle}

::: {.twikiWebTitle}
:::

::: {style="margin-right: 1.5em; overflow : hidden; padding-bottom: 10px; text-align: center;"}
The Spoofax Language Workbench {#the-spoofax-language-workbench style="font-size: 400%; font-variant: small-caps;"}
==============================
:::

 {#section-1 .twikiTopicTitle}

Spoofax is a platform for developing textual domain-specific languages
with full-featured Eclipse editor plugins.

[![Installation](http://strategoxt.org/pub/Spoofax/WebHome/eclipse_logo_white-300x174.jpg "Install in Eclipse"){width="150"
height="87"}](Download)

With the Spoofax/IMP language workbench, you can write the grammar of
your language using the high-level [SDF](../Stratego/SDF){.twikiLink}
grammar formalism. Based on this grammar, basic editor services such as
syntax highlighting and code folding are automatically provided. Using
high-level descriptor languages, these services can be customized. More
sophisticated services such as error marking and content completion can
be specified using rewrite rules in the
[Stratego](../Stratego/StrategoLanguage){.twikiLink} language.

[]{#News}[]{#_News_} [News](News){.twikiLink}
---------------------------------------------

::: {.newsitem}
[]{#1.1}

### []{#Spoofax_1_1_released} Spoofax 1.1 released

We are happy to announce the release of Spoofax 1.1! This is the first
major release since version 1.0.2 and includes major features and
improvements. Spoofax 1.1 supports all current Eclipse versions, up to
version 4.2.2.

You can update your Eclipse from
<http://download.spoofax.org/update/stable>

One of the most important improvements in Spoofax 1.1 is the inclusion
of [NaBL](NaBL){.twikiLink}, the Spoofax Name Binding Language.
[NaBL](NaBL){.twikiLink} is used in all new projects created and
significantly simplifies name binding analysis, as well as any editor
services that depend on it (e.g., code completion, reference resolving)

[NaBL](NaBL){.twikiLink} is documented at the following pages:

-   Tutorial <http://metaborg.org/wiki/nabl>
-   Examples <http://metaborg.org/wiki/nabl/examples>
-   Research paper <http://researchr.org/publication/KonatKWV13>

Other highlights of the 1.1 release include:

-   Improved build process: generated files can be deleted, building &
    loading are separated, projects can be cleaned
    (<http://yellowgrass.org/issue/Spoofax/577>,
    <http://yellowgrass.org/issue/Spoofax/591>,
    <http://yellowgrass.org/issue/Spoofax/578>)
-   Improved Stratego editor with multi-file reference resolving based
    on [NaBL](NaBL){.twikiLink}
    (<http://yellowgrass.org/issue/Spoofax/12>)
-   Extended support for customizing refactoring UI
    (<http://yellowgrass.org/issue/Spoofax/440>)
-   Automatic configuration of git/svn ignore settings
    (<http://yellowgrass.org/issue/Spoofax/573>)
-   Added support loading for Java-based plugin dependencies, in case
    your plugin depends on some other plugin such as EMF
    (<http://yellowgrass.org/issue/Spoofax/322>)

And there were a number of notable changes under the hood:

-   Much improved completion engine
    (<http://yellowgrass.org/issue/Spoofax/360>)
-   We now show a nice warning if Eclipse is not configured with a
    proper stack and heap size
    (<http://yellowgrass.org/issue/Spoofax/86>)
-   Files are now queued for re-analysis even if their editor is not
    open (<http://yellowgrass.org/issue/Spoofax/224>)

A comprehensive list of changes can be viewed at
<http://yellowgrass.org/tag/Spoofax/1.1>.

*2013-01-28*

### []{#Spoofax_QA} Spoofax Q&A

We have started a Q&A site for Spoofax to build a knowledge base of
common questions and answers. Join us at
<http://yellowgrass.org/questions/Spoofax>

[]{#1.0.2} *2012-02-15*

### []{#Spoofax_1_0_2_maintenance_releas} Spoofax 1.0.2 maintenance release

Today we\'re releasing a minor maintenance release of Spoofax, version
1.0.2. This release fixes a memory leak that was introduced in the 1.0
release. There are no new features in this release, those will be
included in the upcoming 1.1 release instead. The new version is now
available from the update site at `http://spoofax.org/update/stable`.

[]{#1.0}

::: {.newsitem}
*2011-12-28*

### []{#Spoofax_1_0} Spoofax 1.0

We\'re pleased to announce the release of Spoofax 1.0. A number of
significant new features have been added since the last stable release,
a long list of bugs has been fixed, and various minor improvements were
introduced.

Highlights of the release include:

-   Support for [writing tests for language
    definitions](Testing){.twikiLink}
-   Support for [defining refactorings](Refactorings){.twikiLink}
-   Major improvements to content completion:
    [Spoofax/289](http://yellowgrass.org/issue/Spoofax/289),
    [Spoofax/357](http://yellowgrass.org/issue/Spoofax/357)
-   Support for using rewrite rules to disambiguate syntax:
    [Spoofax/328](http://yellowgrass.org/issue/Spoofax/328)

The new version is now available from the update site at
`http://spoofax.org/update/stable`.

In addition to these features, we\'re actively working on improving
Spoofax with new features. In particular, we are now working on
providing full support for debugging, on an interactive shell for
Stratego and custom languages, and a new meta-language called
SpoofaxLang to define languages in a more modular fashion.

A full list of feature requests and issues addressed in the new version
is provided at <http://yellowgrass.org/tag/Spoofax/1.0>.
:::

[]{#Features} Features
----------------------

**Edit and use your language in one Eclipse window**
:::
:::
:::
:::
:::

![side-by-side.png](http://strategoxt.org/pub/Spoofax/Features/side-by-side.png)

**Deploy your editor as a portable Eclipse plugin**

![exporting.png](http://strategoxt.org/pub/Spoofax/Features/exporting.png)

**Specify custom errors, warnings, and notes**

![error-marking.png](http://strategoxt.org/pub/Spoofax/Features/error-marking.png)

**Support content completion**

![content-completion.png](http://strategoxt.org/pub/Spoofax/Features/content-completion.png)

**Support reference resolving**

![reference-resolving.png](http://strategoxt.org/pub/Spoofax/Features/reference-resolving.png)

**Use concise rewrite rules for code generation**

\
![rewrite-rules.png](http://strategoxt.org/pub/Spoofax/Features/rewrite-rules.png)

**Generate code directly from any editor or selection**

\
![code-generation.png](http://strategoxt.org/pub/Spoofax/Features/code-generation.png)

**Apply refactoring transformations on the source code**

\
![refactoring-support.png](http://strategoxt.org/pub/Spoofax/Features/refactoring-support.png)

**Get a live abstract syntax view**

\
![show-abstract-syntax.png](http://strategoxt.org/pub/Spoofax/Features/show-abstract-syntax.png)

*[(more features)](Features#other){.twikiAnchorLink}*

\
\

\
[]{#TopicEnd}

::: {.twikiTopicInfo .twikiRevInfo .twikiGrayText .twikiMoved}
:::

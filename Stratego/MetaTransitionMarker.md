::: {.fullPage}
::: {.twikiMiddleContainer}
::: {.twikiLeftBar}
::: {.twikiLeftBarContents}
  ----------------------------------------------------------------------------------
  [![](../pub/Stratego/StrategoLogo/StrategoLogoTextlessWhite-100px.png)](WebHome)
  ----------------------------------------------------------------------------------

**[Home](WebHome){.twikiLink}**

-   [Documentation](StrategoDocumentation){.twikiLink}
-   [Language](StrategoLanguage){.twikiLink}
-   [Research Papers](StrategoPublications){.twikiLink}
-   [Applications](StrategoApplication){.twikiLink}

**[Download](StrategoDownload){.twikiLink}**

-   [Continuous build](ContinuousBuild){.twikiLink}
-   [Extensions](AdditionalPackageDownload){.twikiLink}

**[Support](StrategoSupport){.twikiLink}**

-   [Mailing lists](MailingList){.twikiLink}
-   [IRC](irc://irc.freenode.net/#stratego)
-   [Users Days](StrategoUsersDay){.twikiLink}
-   [Bug Reports](http://yellowgrass.org/project/StrategoXT)

**[Developers](StrategoDev){.twikiLink}**

-   [Subversion](https://svn.strategoxt.org/repos/StrategoXT/strategoxt/trunk)
-   [Buildfarm
    results](http://hydra.nixos.org/jobset/strategoxt/strategoxt-release/all)
:::
:::

::: {.twikiMain}
::: {.toolBar}
::: {.flexMenuBar}
::: {.flexMenu onmouseover="return showMenu(event, 100);" onmouseout="return hideMenu(event, 100);"}
Page

::: {#flexMenuContent100 .flexMenuContent}
-   [Edit
    Page](http://www.program-transformation.org/edit/Stratego/MetaTransitionMarker?t=1536825600)
-   [Rename
    Page](http://www.program-transformation.org/rename/Stratego/MetaTransitionMarker)
-   [Attach
    File](http://www.program-transformation.org/attach/Stratego/MetaTransitionMarker)

<!-- -->

-   [Printable](http://www.program-transformation.org/view/Stratego/MetaTransitionMarker?skin=print.pattern)
-   [Wiki
    Source](http://www.program-transformation.org/view/Stratego/MetaTransitionMarker?skin=text&raw=on&contenttype=text/plain)

<!-- -->

-   [Rev
    1](http://www.program-transformation.org/view/Stratego/MetaTransitionMarker?rev=1.1)
-   [Total
    History](http://www.program-transformation.org/rdiff/Stratego/MetaTransitionMarker)

<!-- -->

-   [More
    \...](http://www.program-transformation.org/oops/Stratego/MetaTransitionMarker?template=oopsmore&param1=1.1&param2=1.1)
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
    \...](http://www.program-transformation.org/oops/Stratego/MetaTransitionMarker?template=oopsmore&param1=1.1&param2=1.1)
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
Meta Transition Marker {#meta-transition-marker .twikiTopicTitle}
======================

::: {.twikiWebTitle}
Stratego \-- Strategies for Program Transformation
:::

In [meta programming with concrete object
syntax](MetaProgrammingWithConcreteObjectSyntax){.twikiLink} the
transitions from the meta language to the object language and vice versa
are marked by special constructors: [meta transition
markers](MetaTransitionMarker){.twikiLink}. [meta
explode](MetaExplode){.twikiLink} uses these constructors to determine
the object fragments in the abstract syntax tree that have to be
exploded to the meta language.

For the embedding of an object language in Stratego the following
markers are used:

-   quotation: denoting a transition from the *meta* language to the
    *object* language.
    -   `ToTerm`
    -   `ToStrategy`
    -   `ToBuild` denoting `!t`

<!-- -->

-   antiquotation: denoting a transition from the *object* language to
    the *meta* language.
    -   `FromTerm`
    -   `FromStrategy`
    -   `FromApp` denoting `<s>`

\
[]{#TopicEnd}
:::

::: {.twikiTopicInfo .twikiRevInfo .twikiGrayText .twikiMoved}
:::
:::
:::
:::

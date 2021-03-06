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
    Page](http://www.program-transformation.org/edit/Stratego/MatchSymbolsInBuildPatterns?t=1536825599)
-   [Rename
    Page](http://www.program-transformation.org/rename/Stratego/MatchSymbolsInBuildPatterns)
-   [Attach
    File](http://www.program-transformation.org/attach/Stratego/MatchSymbolsInBuildPatterns)

<!-- -->

-   [Printable](http://www.program-transformation.org/view/Stratego/MatchSymbolsInBuildPatterns?skin=print.pattern)
-   [Wiki
    Source](http://www.program-transformation.org/view/Stratego/MatchSymbolsInBuildPatterns?skin=text&raw=on&contenttype=text/plain)

<!-- -->

-   [Rev
    1](http://www.program-transformation.org/view/Stratego/MatchSymbolsInBuildPatterns?rev=1.1)
-   [Total
    History](http://www.program-transformation.org/rdiff/Stratego/MatchSymbolsInBuildPatterns)

<!-- -->

-   [More
    \...](http://www.program-transformation.org/oops/Stratego/MatchSymbolsInBuildPatterns?template=oopsmore&param1=1.1&param2=1.1)
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
    \...](http://www.program-transformation.org/oops/Stratego/MatchSymbolsInBuildPatterns?template=oopsmore&param1=1.1&param2=1.1)
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
Match Symbols In Build Patterns {#match-symbols-in-build-patterns .twikiTopicTitle}
===============================

::: {.twikiWebTitle}
Stratego \-- Strategies for Program Transformation
:::

-   No
    [WildCards[^?^](http://www.program-transformation.org/edit/Stratego/WildCards?topicparent=Stratego.MatchSymbolsInBuildPatterns)]{.twikiNewLink
    style="background : #FFFFCE;"} should occur in Build\'s, or a
    wildcard could be interpreted as the identity strategy in a
    [TermWrap](TermWrap){.twikiLink} interpretation.

<!-- -->

-   As patterns may only be used in matching positions, or is there a
    sensible interpretation? how about considering it as the basis for a
    [TermWrap](TermWrap){.twikiLink}: `!t1[x@t2]` is equivalent to
    `!t1[<!t2>x]`

\-- [EelcoVisser](../Main/EelcoVisser){.twikiLink} - 10 Dec 2001\

------------------------------------------------------------------------

[CategoryBugs[^?^](http://www.program-transformation.org/edit/Stratego/CategoryBugs?topicparent=Stratego.MatchSymbolsInBuildPatterns)]{.twikiNewLink
style="background : #FFFFCE;"} \|
[StrategoBugs[^?^](http://www.program-transformation.org/edit/Stratego/StrategoBugs?topicparent=Stratego.MatchSymbolsInBuildPatterns)]{.twikiNewLink
style="background : #FFFFCE;"} \|
[CategoryToDo[^?^](http://www.program-transformation.org/edit/Stratego/CategoryToDo?topicparent=Stratego.MatchSymbolsInBuildPatterns)]{.twikiNewLink
style="background : #FFFFCE;"} \|
[LanguageExtensions](LanguageExtensions){.twikiLink}\
[]{#TopicEnd}
:::

::: {.twikiTopicInfo .twikiRevInfo .twikiGrayText .twikiMoved}
:::
:::
:::
:::

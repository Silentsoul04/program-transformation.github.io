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
    Page](http://www.program-transformation.org/edit/Stratego/StrategoEmacsMode?t=1536825504)
-   [Rename
    Page](http://www.program-transformation.org/rename/Stratego/StrategoEmacsMode)
-   [Attach
    File](http://www.program-transformation.org/attach/Stratego/StrategoEmacsMode)

<!-- -->

-   [Printable](http://www.program-transformation.org/view/Stratego/StrategoEmacsMode?skin=print.pattern)
-   [Wiki
    Source](http://www.program-transformation.org/view/Stratego/StrategoEmacsMode?skin=text&raw=on&contenttype=text/plain)

<!-- -->

-   [Rev
    6](http://www.program-transformation.org/view/Stratego/StrategoEmacsMode?rev=1.6)
    [(diff 5)](http://www.program-transformation.org/rdiff/Stratego/StrategoEmacsMode?rev1=1.6&rev2=1.5)
-   [Rev
    5](http://www.program-transformation.org/view/Stratego/StrategoEmacsMode?rev=1.5)
    [(diff 4)](http://www.program-transformation.org/rdiff/Stratego/StrategoEmacsMode?rev1=1.5&rev2=1.4)
-   [Rev
    4](http://www.program-transformation.org/view/Stratego/StrategoEmacsMode?rev=1.4)
    [(diff 3)](http://www.program-transformation.org/rdiff/Stratego/StrategoEmacsMode?rev1=1.4&rev2=1.3)
-   [Total
    History](http://www.program-transformation.org/rdiff/Stratego/StrategoEmacsMode)

<!-- -->

-   [More
    \...](http://www.program-transformation.org/oops/Stratego/StrategoEmacsMode?template=oopsmore&param1=1.6&param2=1.6)
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
    \...](http://www.program-transformation.org/oops/Stratego/StrategoEmacsMode?template=oopsmore&param1=1.6&param2=1.6)
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
Stratego Emacs Mode {#stratego-emacs-mode .twikiTopicTitle}
===================

::: {.twikiWebTitle}
Stratego \-- Strategies for Program Transformation
:::

The Stratego Emacs mode is currently available at:

-   <https://svn.strategoxt.org/repos/StrategoXT/stratego-editors/editor/trunk/emacs/stratego-mode.el>

[]{#Installation_instructions} Installation instructions
--------------------------------------------------------

Put the file stratego.el in some directory and make sure it is your in
your emacs [loadpath](http://www.emacswiki.org/cgi-bin/wiki/LoadPath).

For example add this to \~/.emacs :

      (add-to-list 'load-path "~/.myemacs")

To bind the Stratego mode to .str files add this to \~/.emacs :

      (autoload 'stratego-mode "stratego")
      (setq auto-mode-alist (cons '("\.str$" . stratego-mode) auto-mode-alist))

Currently sdf syntax coloring is in the stratego-mode as well. To bind
the stratego-mode to .sdf files add this to \~/.emacs :

      (setq auto-mode-alist (cons '("\.sdf$" . stratego-mode) auto-mode-alist))

[]{#Author} Author
------------------

-   [Otto Skrove Bagge](OttoSkroveBagge){.twikiLink}

[]{#Other_Useful_modes} Other Useful modes
------------------------------------------

-   [CUA Mode](http://www.emacswiki.org/cgi-bin/wiki/CuaMode) for
    ctrl-cxv cut copy paste, shift text selection, ctrl-z undo.

\
[]{#TopicEnd}
:::

::: {.twikiTopicInfo .twikiRevInfo .twikiGrayText .twikiMoved}
:::
:::
:::
:::

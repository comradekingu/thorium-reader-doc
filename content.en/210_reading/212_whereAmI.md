---
title: "Where am I?"
description: "Know where you are in a book."
draft: false
weight: 212
toc: false
---
{{< columns >}}
The keyboard shortcuts <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>k</kbd>
allows to get a quick mention of the reading position in the document.
This information will be displayed in the notification area at the bottom left
of the interface and will be read by a screen reader.

<--->
<img src="/thorium-reader-doc/images/local-fr/thorium-whereami-ctrlK.png" alt="Screenshot, notification area, current page 103 - progress = 14/25 (barrel incident) [32%] H1 VII / H2 Barrel incident."/>

{{< /columns >}}

When you look at the `Navigation` menu, Thorium shows the current chapter
in the `table of contents` and the current page in the `Go to page` menu.

<img src="/thorium-reader-doc/images/local-fr/thorium-whereami-tdmfocus.png" alt="Screenshot, reading a book with title VII Barrel Incident. The navigation pane is open, the table of contents shows the title Barrel Incident in a square which indicates that this is the chapter being read."/>

# Access more informations

{{< columns >}}

Use the *Information* function (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd>)
to open a panel that displays the title structure and page number.

In addition to the book information, this sign shows at the subheading Progression:

- the chapter number out of the total number of chapters;
- the title of the current chapter;
- the percentage read of the current chapter;
- the current page;
- the title structure (h1 is a level 1 title, h2 is a level 2 title, etc.)

Press the  <kbd>Escape</kbd> key to close the `Information` panel
and return to the text.

<--->

<img src="/thorium-reader-doc/images/local-fr/thorium-progression.png" alt="Screenshot, progress: 14/25 (barrel incident) [1%] h1: VII"/>

{{< /columns >}}

{{< details "Use **Where am I** with NVDA">}}

Press the <kbd>NVDA</kbd> + <kbd>F7</kbd> keys, and then the
tab key until you get the header view.
This shows you where you are in the title structure.

Press the <kbd>NVDA</kbd> + <kbd>Enter</kbd> keys to save the current position.
Then <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd> to place the
cursor in the Progress section of the dialog box containing information about the
information dialog box. The number of the current HTML document in relation to the
the total number of documents, the percentage, the current page and the corresponding
section are displayed, with the option of displaying links to
scroll backwards and forwards. After closing the dialog, for example by
for example by pressing  <kbd>Escape</kbd> key, it is possible to return to the point
through the screen reader link (marked with a double underline) in the main
underline) in the main content frame (which can be navigated to with the
with the <kbd>Tab</kbd> key or with the letter  <kbd>M</kbd>  in navigation mode).

{{< /details >}}

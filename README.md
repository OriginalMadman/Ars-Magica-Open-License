![](arm5openlicenselogo.png)
<br/>
<br/>
# The Complete Corpus in Friendly Markdown Format
### All 53 official books of the Ars Magica RPG Open License
<br/>
This is a work-in-progress repository for machine-extracted, manually fixed markdowns of a complete set of the official Ars Magica Open Licensed material. These files should all be of a significantly better quality than what has been released openly so far.

* In the **raw-md** folder, you'll find raw output dumps (from a longer workflow of re-OCR and AI-enhanced extraction and conversion) that are mostly in pretty good shape (3rd edition books excluded). However, expect that tables, index and anything obscured by graphics may be broken. Headings are often a bit garbled, and text may be out of sequence or missing due to borked pdf layouts. NOT RECOMMENDED FOR USE!
* In the **wip** folder, is manual fixing work-in-progress. Whatever is here can be expected to be in much better shape than the raw markdowns. All extraneous image links and html is gone from all files (the br's are required for multiline tables), and so's plenty of junk. Use these files until **done** is populated. If you want to help fix something, checkout these.
* In the **wip-mediawiki** folder, you'll find everything from the **wip** folder converted (via pandoc in gfm mode) to Mediawiki format. This is for convenience and testing. I can't take submissions for fixes on this. Please submit for Markdown, which is a way more convenient format. Also note that they aren't necessarily kept up to date with wip versions.
* In the **done** folder, I expect to place finished Markdown files in tip-top shape as I/we progress. These will be the permanent complete versions.

The public is welcome to commit fixes, new and better versions of any of these files (I mainly expect this to be by manual edit while referencing the original works). Please make sure to provide information on what's been corrected, as well as any remaining issues. I'll try to quickly accept improvements to the repository after review (make my life easier, and it will be faster). *As of now, the 3rd edition supplements are most in need.*
<br/>
<br/>
#### Why Markdown?
There are several good reasons why Markdown may be the best “forever” format for the Ars Magica Open License text content:

Markdown's greatest practical strength for open-license content is that it is a universal source format. It is plain text, even human-readable without a renderer - and readily convert to any format (HTML, PDF, EPUB, DOCX, Google DOCS, MediaWIKI etc), natively version-controlled with Git, and readable by both humans and machines without ANY proprietary software. It carries no vendor lock-in and is durable across decades.

This write-once, publish-anywhere model means the canonical open-license text can stay clean and unencumbered, while feeding any wanted derivatives in the easiest possible manner (compare this with copy/pasting from PDF (everyone’s favorite…?), trying to convert .docx formats or manually reformatting plain text headings and tables).

You can straight open a markdown in google docs, word, (modern) notepad - or use Visual Code, Typora, Notepad++ (with plugin) etc or copy paste as-is to Websites (like GitHub), Blogs (WordPress, Medium), Notes (Notion, Obsidian), Chats (Slack, Discord), and Forums (Like https://forum.atlas-games.com/c/games-discussion/ars-magica/15 ) as they all support Markdown natively.
<br/>
<br/>
<br/>
**Note:** *The excellent folks at redcap.org also have a project to provide these materials to the public on their wiki. However the project seems to have slow progress as of late, and at a less complete stage than this (redcap team is welcome to grab anything here to help of course).
https://www.redcap.org/page/Ars_Magica_Open_Content_Conversion_Tracker*
EDIT: YR7 of that project is now helping with this and the plan is to convert from Markdown to Mediawiki for redcap.org once files are polished up a bit more.
<br/>
<br/>
<br/>
**Shameless Plug:** If you are here for Ars Magica content, you're very likely to appreciate my other project - The Ars Magica Chronology: https://forum.atlas-games.com/t/the-ars-magica-chronology-project-200-pages-timeline-of-the-order-and-the-history-of-magic/171381
<br/>
<br/>
<br/>
**License:** All text of Ars Magica 5th Edition and its sourcebooks (53 books total) has been released under an open license:
*Based on the material for Ars Magica, ©1993–2024, licensed by Trident, Inc. d/b/a Atlas Games®, under Creative Commons Attribution-ShareAlike 4.0 International license 4.0 ("CC-BY-SA 4.0")*
https://www.atlas-games.com/arsmagica/openars

Of course, the full PDFs or Physical books are much nicer with layout, pictures, maps and so on. I highly recommend you get the ones you want and support our favorite publisher: https://www.atlas-games.com/arsmagica

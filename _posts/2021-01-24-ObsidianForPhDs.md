---
layout: post
title: Obsidian, the answer to note-taking for the PhD?
author: "Elizabeth Case"
categories: tools
tags: [note-taking, tech, tools, knowledge-management, obsidian]
image: 
---

My whole life I've struggled to stay organized, and the latest iteration of this battle is notetaking for knowledge building -- a.k.a. how to learn and remember what I learn for my PhD. 

Over the last few years, I've realized that I need two things from a notetaking system: 
- frictionless consistency
- multiple modes of organization 

During my masters, I created a daily template in TextEdit that I would copy to a new document each morning. But while this standardized my notes, the copying was tedious, and it was difficult to find information after writing it down -- defeating the point of taking notes in the first place. **In fact, I find that if I can't find information I've taken notes on, it makes taking future notes even harder: putting in that time feels futile.**

**But organization is key to developing a knowledge base, and in essence, that is exactly what a PhD is:** developing a knowledge base that allows you to hypothesize, make inferences, extrapolate, connect. Daily notes, project notes, notes on papers, code documentation -- all of it should lubricate the wheels of future thinking / work.

The latest, and most promising of these efforts, is [Obsidian](https://obsidian.md/), a markdown-based app that enables consistency, provides a multiplicity of search functions and note connections, and can be modified to your needs (and tastes) through user-developed plugins and custom CSS. Writing/note-taking should be pleasurable! Customization goes a long way toward this.


### Main features
I was looking for a few key features in an app, and Obsidian has them all:
1. **local, universal file storage**-- none of this garbage about needing to be online to access your notes (Roam, Notion), or having your notes stored in some proprietary format (Evernote). Instead, all of Obsidian's notes (and other similar programs, like Zettlr) are stored as markdown files.
2. **many different ways to search** -- the first level of accessing information is through file hierarchies, but Obsidian also offers:
	- *excellent search capabilities:* the search is very good at finding whatever you're looking for (and sorts/selects by tags, content, filename, etc)
	- *flawless internal linking:* one of the backbones of Obsidian, it is incredibly easy to link not only to other files in your "Vault" (file hierarchy), but to individual sections/paragraphs within them. Just type double brackets `[[ file name ]]` and start typing the file name; Obsidian will automatically link to it or create a new file if it doesn't yet exist. This makes creating or referencing files *super easy* and really helps me stay organized.
	- *backlinks:* the hot new thing for notetaking apps, backlinks show you which files link to the one your on; this can sometimes lead to interesting insights, e.g. when multiple files from different trains of thought lead to the same place
	- *networked graphs:* building off internal file links, networked graphs show you how all your files are connected (which files are linked to who). fun to click around, find random connections, follow pathways
	- *tags*: search by tags, and/or check the tag pane for a list of tags in your vault. Tags are really useful for keeping track of different projects & paper sections. My only issue is that it's easy to mistype tags, and mistyped tags still get added to the main tag list.
3. **external file linking** -- I am mad-good at getting distracted, so I want to be able to click on a reference and have that file open, whether it's a PDF, a piece of code in Matlab, or my thesis proposal in Powerpoint. In Obsidian, you can do this! As simple as linking to a website: `[text](file:///User/... )`
4. **daily templates** -- this is a plug-in (more below), but essential (see above: mad-good procrastinator). I made [a daily template](https://github.com/Elizabethcase/elizabethcase.github.io/blob/master/assets/docs/DailyTemplateObsidian.md?raw=true). Now I just click a single button for a fresh day's worth of notes! 
5. **Zotero integration** -- it's not a perfect plug-in, but I can import my [Zotero](https://www.zotero.org/) library, and cite papers directly in Obsidian. This is super useful when I'm close-reading a paper, and will probably get more useful as I start to write my dissertation.
6. **flexibility/open source** -- this wasn't a *must* but it's a huge bonus -- Obsidian's user base is active and constantly developing plug-ins for the app that really improve day-to-day usage. Plus I can customize the CSS so that my workspace is a pleasure to write in & with.


### Plug-ins
Obsidian has both core and third-party plug-ins. I depend on a few for my workload:

#### Core plug-ins
1. *Daily Note's* -- with a click, create a new daily note from a template that you build. Many ideas around daily notetaking exist online, do whatever is simplest for you and stay consistent. Mine has a link to the previous day and the next day, a log of my sleep and emotional state, and four header sections: To Do, Morning Intake, Work, Writing
2. *Graph View* -- I love a visual representation.. and a way to just click around with abandon to jog my memory
3. *Tag Pane* -- in particular, this plug-in makes it really easy to track notes from projects, specially across Daily Notes

#### Third-party plug-ins
1. *Advanced Tables* -- makes using markdown tables a breeze
2. *Calendar* -- sometimes I want to generate a Daily Note for sometime in the future; this let's me do that
3. *Citations* -- Zotero integration, holy grail
4. *CSS snippets* -- oh boy does my workspace look good
5. *Paste URL into selection* -- copy a link, select a word,  ctrl+shift+v, voila
6. *Sliding Panes* -- allows you to have a couple of panes open at once, which makes for easier referencing and note building

### Other features that improve Obsidian:

1. [Espanso](https://espanso.org/) -- a text expander
	-  The `:bc`  (short for breadcrumb) at the top of my Daily Notes template auto fills so that I can click to yesterday or tomorrow, e.g. `[[20210124-Sun|<< Yesterday]] | [[20210126-Tue|Tommorrow >>]`
	-  `:zoom` writes out my personal zoom link
	-  `:orcid` writes out my orcid number
	-  `:cell` writes out my cell number
	-  
	- I also use `:meet` so that a meeting template auto generates, looks like: 
###  Meeting
	- Tags:
	- [Zoom link]()
	- [Agenda link]()
	- Attendees:
	- Tasks:
	- Notes: 

### Features I would love to see/use:
1. Scheduled reviews of notes - give me an easy way to do a weekly/ monthly review, e.g. autopopulate a note with that week's or month's Daily Notes. There's probably a hacky way to do this with regex + templates.
2. Translate markdown in realtime: Obsidian has two modes, edit and preview. Edit shows most of the markdown. Preview translates the markdown. I wish Obsidian would take a note from Zettlr and just make the markdown disappear as I write. You can do this with css customization, but it often doesn't work well. 

A post is coming soon about how to set up and use Obsidian. I'd love to hear about what you use to take notes! If you have any tips, comments or questions, feel free to reach out.
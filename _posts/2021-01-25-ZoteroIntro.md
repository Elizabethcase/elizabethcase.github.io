---
layout: post
title: Zotero as a Reference Manager
author: "Elizabeth Case"
categories: tools
tags: [reference-manager, tech, tools, knowledge-management, zotero]
image: zotero_library
---

While [Obsidian can be a useful tool](https://elizabethcase.github.io/tools/Obsidian.html) for managing your personal, day-to-day notes, the bulk of knowledge in a science PhD comes from papers. A reference management system is crucial for saving papers you read or plan to read, and organizing and exporting citations.

Other than a personal file management system (e.g. saving papers in folders of your choosing), there are two main software options: Mendeley and Zotero. Mendeley is owned by Elsevier, one of the largest scientific publishing companies in the world. Zotero is open source. In general, I try to use open source products where I can, because #powertothepeople, and open source developers tend to be more responsive to user needs.

So, Zotero is an open-source resource manager - a place for you to store, organize, sort and cite documents like journal articles, book chapters, software, etc. For ease, I will just refer to any and all reference material as "papers".

## Zotero Basics

### Folder organization

Zotero is organized into Libraries, which can be further subdivided into groups, sub-groups, etc. Personally, I think it is helpful to have two sets of folders in your library: 

- one that contains all the papers for a particular research project/paper/thesis
- another that groups papers by topic/keyword.

Another useful folder for organization is the **inbox / to-read** (just make sure to refile papers you read!).

I also have folders for papers I used to prep for my qualifying exam, paper collections from various seminars & classes, etc. 

### Notes, tags, etc

For each indexed item, you can add your own notes (e.g. from reading the paper), tags, etc. I personally don't use tags. The search function, combined with filing away in the correct folder, is good enough for me. I *do* use notes -- generally highlights and comments from reading the paper. I have started to translate these notes into Obsidian when there's a paper I really need to know well. The ability to extract annotations is expanded on below in plug-ins.

### Plug-ins 

While you can add files to, export citations from, etc manually  Zotero, a few plug-ins increase it's usefulness significantly:

1. Browser extension
2. Text editor integration
3. Annotation extraction 

#### Browser extension

The browser plug-in connects your desktop library to the internet. When you access a resource you want to save online -- a paper, an article, a piece of software -- you click the Zotero button, choose the folder you're going to save it in, and voila, the PDF is downloaded and the metadata has been extracted, and it's all indexed in your library. Absolutely crucial to my workflow.

The [Firefox extension can be downloaded](https://www.zotero.org/download/) directly from the Zotero website. 

#### Text editor integration
I have written both of my journal papers, and my exam papers, in World. Yeah, I know, maybe I should use latex, finally commit to Overleaf, etc. Perhaps I will get there eventually. But for now, I do my writing in Word.

With Zotero, you can insert citations *in situ*, e.g. as you're typing away. They also have extensions for LibreOffice and Google docs. [Here's a link to the plug-ins](https://www.zotero.org/support/word_processor_integration).

#### Annotation extraction

[Zotfile](http://zotfile.com/#extract-pdf-annotations) is the newest addition to my workflow, and it is a homerun. When reading a paper, I usually
1. print the paper
2. highlgiht and annotate
3. transfer those highlights and notes to the digital PDF

The last thing I want to do after all those steps is then spend time copying and pasting those notes and highlights into the Notes section of Zotero or into a file in Obsidian. Now I don't have to -- Zotfile will automatically extract highliights and notes *by color* into Zotero. These can then be copied into Obsidian, or left for your future self in Zotero. 

[Zotfile's documentation](http://zotfile.com/#extract-pdf-annotations) is pretty thorough, but to install, right click `download --> save link as`. Then open up Zotero. Choose  `Tools --> Add Ons` from the top menu. Click on the little gear button in the upper right hand corner, then click `install add-on from file` and choose the Zotfile xpi file you just downloaded. There's lots of ways to customize your Zotfile experience; I've found it most reliable to just leave things in their default settings.

You can also use Zotfile for tablet <--> computer PDF syncing.

#### Other useful plugins

- [Better BibTex](https://retorque.re/zotero-better-bibtex/) (more useful citation keys)
- [Mdnotes for Zoter](https://github.com/argenos/zotero-mdnotes)o (export as markdown)
- [Zotero Memento ](https://github.com/leonkt/zotero-memento/releases/tag/v1.0.1)(saves webpages robustly, e.g. through multiple sources like internet archive)
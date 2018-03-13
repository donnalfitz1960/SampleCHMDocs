This repository contains live (but scrubbed) compiled help modules for prospective employers to review.

The source for each is a custom XML file (with variable options) based on a DTD for standardization.  The XML is generated via XSLT steps to individual topic HTML files.  One of the XSLT steps reads the topics and creates the .hhp. .hhc, and .hhk files for use in HTML Help Workshop.

Once all files have been created, the .hhp (HTML Help Workshop project file) is opened which opens the tool.  The project was then immediately generated to .chm.

There are further steps that can be taken -- the chm can be generated via another tool into online Web help format, with TOC, tabs, and breadcrumb navigation.  In this repository, only the CHMs are shown.

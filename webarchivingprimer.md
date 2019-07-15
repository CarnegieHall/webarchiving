# Web Archiving Primer

*DRAFT*

## What is Web Archiving?
"The process of selecting, capturing, saving and making accessible select content available online (e.g. websites)" - (p. 8 of [Web Archive Intro](https://www.slideshare.net/annaperricci/web-archiving-intro-circa-2015) by Anna Perricci).

Web content is very vulnerable to loss. Carnegie Hall is attempting to address this by building a web archiving strategy based with its [web archiving workplan](https://carnegiehall.github.io/webarchiving/workplan.html).

[Web archiving is an aspect of archiving for Carnegie Hall. Our work to preserve "content" presented on the web (photos, resources, media), must be done in tandem with archiving the experiencing of interacting  with and accessing that content online. While we have systems in place to archive assets, we need to also capture how those assets (context, form, etc) are shared.]

## What are Carnegie Hall's web archiving goals?

### Carnegie Hall Web Archiving Purpose Statement
The Carnegie Hall Archives aims to create a historic record of Carnegie Hall’s websites, available for internal reference and limited public use. The Archives will collaborate with each Department to capture a representative sample of their web resources. The preserved, curated materials will depict the content, style, and impact of the Hall’s online initiatives.

### Questions to consider

- How do we represent the web-based output from Carnegie Hall? Do we want evidence that X site existed at this time, contained this information as a snapshot? Or do we want to capture the experience of using the site?

- What needs are being met by web archive capture of sites?

- How is it possible to build in sustainability factors into creation? How can we support preservation by starting at the point of creation with responsible practices? 



### What are significant properties of websites?

What are the 'significant properties' or aspects of a website that need to be captured or maintained to appropriately represent what the site is? Does it matter if an aspect is missing in the captured/archived version? One way to assess this is to do a side-by-side comparison of the live site and capture. We can then ask ourselves if the site is "complete" based on what appears or doesn't appear in the capture. 

Some questions to consider when doing this comparison and thinking about signficant properties:
- Are images missing?
- Are media files not playing?
- Are text or design elements missing or inaccurate because the CSS is not captured? 
- Is navigation required, and to what extent? What links are broken?
- For sites with features that no longer function - how do you capture the existence and/or experience of the older, functioning site?

## Different types of captures

### Needs-based capture levels
Web Archiving can be done at different levels: 
1. Dynamic, curated capture to represent functionality and features
2. Low fidelity capture like high-level crawls (Wayback Machine) or even as simple as screenshots
3. Content harvest where all assets, media are captured for future management or reuse in updated capacity to align with current web goals 

![Screenshot of 1996 Carnegie Hall website](/ch1996.png)

_1996 iteration of the Carnegie Hall website (captured by and accessible in the Wayback Machine from Internet Archive)_

### Capture tools
#### Crawls
Crawler is software that indexes web content. Saved by a crawl: (also by AP)
- Code/info in web programming language (HTML, Flash)
- Some formatting (e.g., CSS)
- Text
- Images
- Some media files (embedded, but not the streamed ones)
- Documents, spreadsheets, presentations, data sets (XML, PDF, CSV)

**Crawling Tools**: [Archive-It](https://archive-it.org/); [Wget](https://en.wikipedia.org/wiki/Wget)

#### Curated captures
Some of the complex aspects of websites cannot be captured by crawling tools. To grab embedded media, Flash-based features, or interactive functions, the user may choose to manually navigate the site contents during the web archive process. Using curation tools, the user has more control over what is gathered, and can ensure that the most granular or complex significant properties are contained in the site archive.

Because there is more active choice in using curation tools, the user has to decide what is worthy of capture and what quality is expected. The user is responsible for creating a site archive that includes all the in-scope significant properties. 

**Manual Capture Tools:** [Webrecorder](https://webrecorder.io/) ("Unlike conventional crawl-based web archiving methods, [Webrecorder] allows even intricate websites, such as those with embedded media, complex Javascript, user-specific content and interactions, and other dynamic elements, to be captured and faithfully restaged.")

#### Web Archiving formats

[WARC](https://www.loc.gov/preservation/digital/formats/fdd/fdd000236.shtml) - (Web ARChive) file format: "specifies a method for combining multiple digital resources into an aggregate archival file together with related information. The WARC format is a revision of the Internet Archive's ARC File Format format that has traditionally been used to store 'web crawls' as sequences of content blocks harvested from the World Wide Web. The WARC format generalizes the older format to better support the harvesting, access, and exchange needs of archiving organizations. Besides the primary content currently recorded, the revision accommodates related secondary content, such as assigned metadata, abbreviated duplicate detection events, and later-date transformations."

#### How to view captured sites

[Wayback Machine](https://archive.org/web/) (Internet Archive): "The Internet Archive Wayback Machine is a service that allows people to visit archived versions of Web sites. Visitors to the Wayback Machine can type in a URL, select a date range, and then begin surfing on an archived version of the Web" (Wayback Machine).

[Webrecorder](https://webrecorder.io/) (UI and Player): "Webrecorder is a web archiving service anyone can use for free to save web pages. Making a capture is as easy as browsing a page like you normally would. Webrecorder automatically archives the page, along with any additional content triggered by interactions" (Webrecorder). Webrecorder hosts and provides download access to WARC files, regardless of whether or not the files were initially created using its tools.


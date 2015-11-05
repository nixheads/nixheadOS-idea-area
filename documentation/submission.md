# Submission

This section will probably outline the submission process for documentation of nOS.
This is vary a bit depending on what section of documentation you're doing.

### Documentation types:

* Manpages
* GuideBooks?
* Markdown
* PDFs
* tutorials

## Manpages

Manpages will mostly likely be done using the tool help2man,
(or pandoc, or if you're into it just write raw manpages :P).

## Guidebooks

I think guidebooks or any sort should be done in one of three forms

* Gitbook
* LaTeX(could be .pdf,.dvi, or another format)
* HTML(on a website, most likely plaintext[ofc] so we can be text-based-browser friendly)

## Breif Descriptions

### Gitbook

I have a short outline of Gitbook in [tools](tools.md) section of the guide.
The reason I would choose GitBook is because it's incredibly simple as you can use
things like:

* TeX
* Markdown
* ASCIIdoc

but still get a comprehensive and eloquent results.


### LaTeX/TeX/etc

LaTeX would be ideal for producing PDFs as it's robust nature and featureset.

### HTML

Basic plaintext website format, ***NO***  B$(e.g. JS, ***NO FUCKING FLASH OR JAVA***).
I would like to model it after something like [tlpd.org](https://www.tldp.org) (e.g. [parition guide on tldp.org](http://www.tldp.org/HOWTO/html_single/Partition/)).

## Submission Process

### Guidebooks

Guidebooks would have to meet some simple requirements:

* be under an appropriate license(e.g. CreativeCommons)
* be quality:
	* minimal typos(these can always be fixed)
	* be clear and to the point
	* have multiple ways of showing things if needed (e.g. how to do something through terminal, and GUI)
	* be able to be understood by both n00bs and experts alike(assuming topic is SIMPLE enough)
* be under a git repository so it's easily accessible to the public.


Once these qualifications (and any others suggested/in the future) are met, the guidebook goes through a chain of people(suppose alike to kernel patch development):

* Guidebook writer: proofread(one last one before submitting it to anyone else, of course the writer will have done this MULTIPLE times before(
* Guidebook team leader(if Guidebooks get split off into their own section of the documentation team)
* ???(will be others maybe if needed, we can always fill shit in)
* Vice Head Documenter
* Head Documenter
* Other head members of the project(e.g. head programmer[just for more checking of "oh yeah this shit is right"])

If approval is not met during one of these steps the submission goes back to the beginning of the chain for the write to fix(ofc there will be feedback to help him fix his/her shit).

Assuming though the guidebook makes it through all ranks of documentation checks a couple things will most likely happen:

* Your git repository if not already forked into the organizations repos will be forked into the organization for ease of access for other people
* Your guidebook will be added to an official list of guidebooks for nOS
* Your guidebook will be imported to the organizations gitbook repos.


(note, technically guidebooks ONLY have to go through all these statges in you want them to be official, though I would suggest you to go through this process,

### LaTeX/TeX/etc(i.e. TeX languages)

These pretty much fall under the same guidelines as [guidebooks](#guidebooks) with a few exceptions.

If approval is met things will go as such:

* Your git repo will be forked under the organization
* Your PDF will be added to the official list
* Your PDF will be hosted(somehwere) available for the public

### HTML 

HTML(tutorials, guides, etc) would have to meet some simple requirements:

* most likely abide by aesthetics of [tldp.org](https://www.tldp.org)
* be under an appropriate license(e.g. CreativeCommons)
* be quality:
	* minimal typos(these can always be fixed)
	* be clear and to the point
	* be able to be understood by both n00bs and experts alike(assuming topic is SIMPLE enough)
* be under a git repository so it's easily accessible to the public.

### Markdown

Markdown guides/documentation will most likely be short and sweet little guides, following the rules/process of [guidebooks](#guidebooks).

# BlogSpot-Metadata-Template
Blogspot template with Schema microdata modifications

Provided is a BlogSpot (Google Blogger) template modified to eliminate Schema.org errors when testing with [Google's Structured Data Testing Tool (SDTT)](https://developers.google.com/structured-data/testing-tool/)  as of January 29, 2016.  This is modified from a standard "Simple" Template created by Designer: Josh Peterson (URL:www.noaesthetic.com). The template seems to retain all of the functionality of the "Blogger Template Designer".

The template is intended for those wishing to start a new Blogger blog.
For instruction on how to modify your existing template, see the [Wiki](https://github.com/WeaverStever/BlogSpot-Metadata-Template/wik).

<b>*** WARNING:</b> Installing over an existing blog will destroy your existing layout and other preferences. 

<h3>Required modifications:</h3>

There are two locations in the Template for the URL to your properly sized logo, which is required, by Google's (SDTT). 
Search the within the template for "Schema Mods:" to locate those areas and provide the URLyour your image. See [Blogger: publisher structured data error](https://github.com/WeaverStever/BlogSpot-Metadata-Template/wiki/Blogger:-publisher-structured-data-error)

<h3>Other modifications:</h3>
<b>There is also a commented area in the <Head> section for providing your Google Plus identity.</b>
```
<!--  Schema Mods: Code to provide Google+ account programatically (for removal of "About Me" gadget)
   <link rel='Author' href='http://plus.google.com/xxxxxxxxxxxxxxxxxxxxx'/>
   <link rel='Publisher' href='http://plus.google.com/xxxxxxxxxxxxxxxxxxxxx'/>
-->
```
Just provide your Google+ id in the place of the xxxxxxxxxxxxxxxxxxxxx and uncomment.

<h3>Resources</h3>

Hat Tip to Technohalf for sharing a [tutorial](http://www.technohalf.com/2015/12/how-to-fix-all-structured-data-errors.html) with mostly correct information at:<br/> 
[Google's Structured Data Testing Tool:](https://developers.google.com/structured-data/testing-tool/)<br/>
[Google's Rich Snipets for Articles:](https://developers.google.com/structured-data/rich-snippets/articles)<br/>
[Schema.org: Article](https://schema.org/Article)<br/>

<h3>Additional</h3>
There is an additional "datePublished" possible schema error (server setting) that has to be manually adjusted, short times/dates like 3:39PM are not accepted. This setting is not stored in the Template.
Here's the fix. http://newbloggerthemes.com/blog/fix-posted-date-undefined-error-blogger/

This editor's coffee and peanut butter fund, [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RJNBR2FZW9DAJ).

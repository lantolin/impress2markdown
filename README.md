# impress2markdown

XSLT document that transforms LibreOffice Impress slides to Markdown 

## But why?

To facilitate the migration of slides from LO to remark.js

Just sharing my own quick-and-dirty solution for my problem.

## My problem

I have many LibreOffice Impress presentations. I am considering a migration to [remark.js](http://remarkjs.com/). 

I just wanted to know how hard was going to be to migrate my LO content and if I could automate all or part of the effort.

After some googling I could not find any solution that suited my needs. So I developed my own.

## My solution

LO documents are just XML, so what I want is something that translates XML to Markdown.

Unfortunately the right technology for that is XSLT which is hideous. But that's life.

So I put together an small XSLT that transforms the basic elements of a LO Impress document into Markdown.

It is far from perfect, but it covers my needs.

Here it is in case it is of any help to you. Any improvements, suggestions, better aproaches, etc. are more than welcome.

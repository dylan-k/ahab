
AHAB!    
=====
                                  
A baseline Mobi template
------------------------

<pre>
:-...-----------::///++oooossssooo++//////////+//++////++oooosssyhhhhddd
/:----..```````......--//+oooooooo++++//-://+++++/....--:////+/++ssyhhhh
///:-....````````.....-:::/++ooooooooo+.:s++/++o/```.-+oo/:-:://++++++oo
////:--...``.``````.-::::-::/++oooooos--sso+//+/-``.-:shhyho:/+oooo+oooo
///+////:-.`````````.--::::/:/+++oooo:.:ho++++:-```.:+ymmmmdyo+ossssssss
-://++++//-`````````````..-::--::////--os////:-```.-+ydmmmmddyo++oosssss
/////++///:-.``````````````..--......--s/-.-/:.``.-+ydmmmmdmdyh//++ossss
++//++//////::-..``````````...-..```..:s-.:hy-``.:+yddmmmdmmhhh/++oossss
+++////+++++///:--...............``..-++-/hy-``-/+yhdmmmmmmdyho/+oosssss
+//++++///++////::::-::::///::::-..---o/ods.``-+syhddmmmmmdhy+/++++oooss
so+oosso++///:-``.-:://///++++/:::--.-oyd/```-+shdddmmdmmmhhy+oooo+++ssy
sssssyyyssoo+//:::://+++++++oo+/:---../o. `.:ohddhhhhhdmmdhy//+osossssss
yyyyyyyyyyysso+++/:://////////++/--:.``.--/shhddhshhdhdmdhhs:+oosyyyysss
yyyyyyyyyyyyyyssoo+++////++///++:////://oyhmmmmhoyddmhmmdhhoosyyyhyyyyyy
yyyyyyyyyhhhhhyyyyyssooo++/+o++/+/++oosyhdmmmmdyyddmmdmmdhhssyyyyysyyyyy
yyyyyyyyyyyyyyyyyyyyyssssssssso/:///+yyhddmmmmdhddmmmmNmddhyyyyyyyyyyyyy
hhyyyyyyyyyyyyyyyyyyyyyyyyysyyos//+osyhdmmmmmmdddmmNNNmddmyyysssyyyyyyyy
ddhhhhhhhhyyyyhhhhhhhhyhhhsyhy+://oyshdmNNNmmmdmmNNNNNmddd++ossssyyyyyyy
mmddddddddhhhhhhhhhhhhhhhyshyo::/ossydmNNmNNNmmmNNNNNmdddy+ooossssyyyyyy
mmmmmddddddddhhhyyyyyoo+++oo/:/+syysdmmdddmNNmmmmNNNmmdhho/+ooossoooo+oo
mmmmdddddddddhhhhysso++++o++:+osssydmdhdmmNNmmhddmmmdddyy///+/+////////+
mmmmmddddddddhyhyysysssss++/+o/syyhhhdddmmmmmyyhddddhhhs+//:::::-.:://+/
ddddddddddhhhyhhhyyyyyss++/+o+sssoohddddmmmmhsssyhhhyyso/////://++++++++
hhddddddddddhhhhsyhysosyh++o/ss++shhdddddddhssosssssosso--:://+++++//+oo
yyyyhhhhhhhhyyyyyyyooyhho+/ooo+yhddhyhdhhhyss/:/ososooo:.---::::://:::/+
ssoossyyyyyyyysysoysssdso+++/ssshhyhhhhooo++.``-///o+++-.`.--::::::::--:
yhyyyyyyyysssss+-+s+shy+oso:-+o+/+oosy+/+--/-`.-///+//+hs/:-::::/::----:
hhhhhhyyyyso++/.:::/oy/++/:.-:/o/-///:::`./-::`---/:----:oss-.......----
hhhhhhyyyyso+:.--.:/:::-/-:o--..-:-./..``:-++.+/.:/`-:````/yo...````.-..
hhhyyyysssoo//--.:://:-+-.//-.-..-..`.``-/ohdoso+//::s/:shsoh:.-+syyo-`.
ssssssooo+//++/:::-.-:....--..:/+////:-.`oyddhhyyy+yhhyysyyoyyhhhdddo//+
oo+++++//:-::::/-....---:/+oso+//:/++:::--ysssyhhhhhdhhhdddhdmmdmmmh+ooo
ooossoo+oooooso++oosso+++///++//+//+++osoooo+odmmNmmmmmmmmhhhddmmmmddhhh
ddmmmmmmddddhhysssssyhhsyhhdddhhhhhhhyhhhhyhhsydhyyhhhyyyhhdddmdmddddddh
ddddmmmmdmddhhyyyyhdhhhhhddmmmmdddhhyooosso+oshdhhsyydhddmmmmmmmmmmmdhhh
mNNNmmmmmmdmmmddddmmmdmddmmmmmmmmddhhhdhhdmmmNNNNmmmmmmmmmmmmmmmmmmmmddh
</pre>

------------------------------------------------------------------------  

### Ahab! ###

Super-simple baseline .mobi templates. Here ya go. 

It's also meant to be a bit geeky. It's for those of us who like to hand-code 
websites. Who want to know what's going on under the hood. Who are obsessive
about CSS class naming and indent styling and get pleasure knowing the 
innards of the machines they produce are as beautiful and efficient as 
possible. 

The original I'm working from provided a minimum working example, but for my baseline, 
I've added a few extras, like the epub:type attributes that help with semantic clarity. 
I'm also refining this readme file as I go.


### Mobi? ###

Mobi is Kindle's ebook format. It's sort of like EPUB's step-brother. 
If you have a properly produced .mobi file you can publish on the 
[Kindle Direct Publishing](http://kdp.amazon.com) platform. 


### This template ###

This template is meant to get you from *thinking* about publishing a piece of 
text you have to *actually publishing* it on Kindle Direct Publishing. If you 
have a long-form blog post composed mainly of text, I suspect you could 
convert it to a proper .mobi file using this template in fifteen minutes. 
Obviously, more complex texts (and cover production, etc) take more time. 

So this template is mainly about minimizing friction. 


### Covers ###

Amazon revised their [cover guidelines](https://kdp.amazon.com/self-publishing/help?topicId=A2J0TRG6OPX0VM) in early 2012. Here are the base requirements:

- Minimum of 1000 pixels on the longest side 
- Ideal height/width ratio of 1.6 
- 2500 pixels on the longest side. 
- .png is not allowed for cover images. Use .jpg or .tiff. 

note: eink Kindles have a screen ratio closer to 1.3. 

note: .pngs are allowed everywhere else, but not as cover images. 


### CSS ###

Kindle Format 8 supports CSS media queries. It seems a little bit out of the
scope of a baseline template, but if you're interested, [Liz Castro](http://www.pigsgourdsandwikis.com/2012/01/media-queries-for-formatting-poetry-on.html)
explains all. @font-face rules only work on Kindle Fire. A lot of css rules only work on Fire. Floats, for example. The simpler you keep your CSS, the saner you'll be. Here's the full [list of support for HTML and CSS tags](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000729901)


### What are these other files? ###

Toc.ncx & content.opf are the two slightly alien files of this collection.

OPF means "Open Packaging Format". From [Wikipedia](http://en.wikipedia.org/wiki/EPUB#Open_Packaging_Format_2.0.1):

> The OPF file, traditionally named content.opf houses the EPUB book's 
> metadata, file manifest, and linear reading order. This file has a 
> root element package and four child elements: metadata, manifest, 
> spine, and guide. All of these except guide are required. Furthermore, 
> the package node must have the unique-identifier attribute. The .opf 
> file's mimetype is application/oebps-package+xml.

The .ncx file is explained thusly: 

> The NCX file (Navigation Control file for XML), traditionally named toc.ncx, 
> contains the hierarchical table of contents for the EPUB file. The specification 
> for NCX was developed for Digital Talking Book (DTB), is maintained by the DAISY 
> Consortium, and is not a part of the EPUB specification. The NCX file has a 
> mimetype of application/x-dtbncx+xml.

Exciting stuff! *zzzzzz*

I've done my best to obviate thinking too much about these files.


### Publish! ###

So you have your cover. You have your properly formated .mobi. You've tested it
in Kindle Previewer and it looks pretty good on all the devices. Now, how do you publishing? 

**first step: create an EPUB file**

I like to start with an EPUB file, because those are useful to have around. If you don't need need an EPUB file, skip to the second step. Use Kindle previewer, along with the content.opf file created previously.

1. create a .zip file that contains the following:
- the ``/META-INF/`` directory
- the ``/OEBPS/`` directory
- the ``mimetype`` file

2. change the .zip file's file extension to .epub

**second step: convert EPUB to MOBI**
you can do this [using Calibre](http://manual.calibre-ebook.com/conversion.html) or...
you can do this with [Kindlegen](http://www.amazon.com/gp/feature.html?docId=1000765211) or...
you can do this using [Kindle Previewer](http://www.amazon.com/gp/feature.html?docId=1000765261)

3. share your kindle book with readers

You can just mail the .mobi file to friends, put it up on a server, upload it 
to a forum — distribute any way — and any Kindle will be able to open the file. 

But if you want to "publish" it on Amazon — set prices and get it properly listed —  then [Kindle Direct Publishing](http://kdp.amazon.com) is what you want. It should be pretty self explainatory.


### Extend ###

This is by no means exhaustive. It's meant to give anyone interested in .mobi a little boost. I've tried to strip away all the unnecessary gunk. What's remaining should be relatively self explanatory.


### Resources ###

A 'satellite' post on craigmod.com about this template lives here:
http://craigmod.com/satellite/ahab/

- Kindle Format 8 [Guidelines](http://www.amazon.com/gp/feature.html?docId=1000729511) are a good place to start
- [Kindle Previewer](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765261)
- [Kindlegen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211)
- [Send to Kindle](http://www.amazon.com/gp/feature.html/?docId=1000778781)
- [Formatting Poetry for EPUB and Kindle](http://bencrowder.net/blog/2011/06/formatting-poetry-epub-kindle/)

There are a lot of people out there who have spent a lot more time working on
this stuff than I have. I referenced Liz Castro's [blog](http://www.pigsgourdsandwikis.com/search/label/Kindle/)
any number of times. 

More detailed [examples of EPUB files](https://github.com/IDPF/epub3-samples) are available.








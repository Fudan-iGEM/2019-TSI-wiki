# iGEM site
It was initially developed by Tian Huang for 2018, and later modified by Liang Cai for 2019.

## For wiki coder
The content of XXX.html should be copied into Team:Fudan-TSI/XXX page, keep {{Fudan-TSI}} but delete the jquery link before &lt;html&gt;. The site has a function to import jquery automatically, thus there is no need to import again.

The wiki template should be blank, because the code to suppress iGEM HQ formating has now be included in each page.

The part &lt;/p&gt;&lt;/div&gt;&lt;/div&gt;&lt;/div&gt; behind &lt;html&gt; is to tags open before #mw-content-text.

The file etc-nginx.conf is for running a mirror site.

Both .py files could be used to running locally, very good for site building and testing. Run [the local site](http://127.0.0.1:8000) and start coding!

## Branches
* 1107 - live at http://2018.igem.org/Team:Fudan
* 2019fix - live at https://2019.igem.org/Team:Fudan-TSI
* 2019prep - modified 2018 for 2019, in Aug 2019
* 2019zhang - some pages from Zixuan Zhang
* 2019ing - edits in Oct 2019
* greatBay - mirrors of 2018 GreatBay_China and 2019 GreatBay_SZ

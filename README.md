# Silverstripe SEO Module

## Maintainer Contact

* Bart van Irsel (Nickname: hubertusanton)
* [Webium](http://www.webium.nl)


## Requirements

* SilverStripe 5.*

## Documentation

This module helps the administrator of the Silverstripe website in getting good results in search engines.
A rating of the SEO of the current page helps the website editor creating good content around a subject
of the page which can be defined using a google suggest field.

The fields for meta data in pages will be moved to a SEO part by this module.
This is done for giving a realtime preview on the google search result of the page. 

In seo.yml config file you can specify which classes will NOT use the module. 
By default every class extending Page will use the SEO module.

## Screenshots

![ScreenShot](https://raw.githubusercontent.com/hubertusanton/silverstripe-seo/master/1.png)
![ScreenShot](https://raw.githubusercontent.com/hubertusanton/silverstripe-seo/master/2.png)

## Installation
Place the module dir in your website root and run /dev/build?flush=all

## TODO's for next versions

* Create a google webmaster code config 
* Only check for outgoing links in content ommit links within site
* Translations to other languages
* Check for page subject usage in other pages 
* Check how many times the page subject has been used and give feedback to user
* (Re)Calculate SEO Score in realtime with javascript without need to save first
* Put html in cms defined in methods in template files
* Check extra added db fields/ many_many DataObjects for SEO score and make this configurable

## License

This module is published under BSD 2-clause license, although these are not in the actual classes, the license does apply:

http://www.opensource.org/licenses/BSD-2-Clause

Copyright (c) 2017, Bart van Irsel

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

    Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
    Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

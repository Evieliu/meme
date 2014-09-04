# Meme v.2

<<<<<<< HEAD
Contributors: Yuri Victor, Joshua Benton, Matt Montgomery, Ivar Vong, Steve Peters, Flip Stewart.
=======
Contributors: Yuri Victor, Joshua Benton, Matt Montgomery, Ivar Vong, Steve Peters, Flip Stewart. Backbone refactor by Greg MacWilliam.
>>>>>>> Complete refactor with model-view separation. Fixes several UI bugs.

Meme is a generator that Vox Media uses to create social sharing images.

![screenshot](readme.png)

## Install

* `git clone https://github.com/voxmedia/meme.git`
* `bundle install`
* `bundle exec middleman`

This will start a local web server running at: `http://localhost:4567/`

## Customization

Settings and controls can be customized via `source/javascripts/settings.js`. Most menu options can be configured directly through settings.

## Examples

* https://twitter.com/voxdotcom/status/481671889094340608
* https://twitter.com/voxdotcom/status/479228288221470721
* https://twitter.com/voxdotcom/status/481619042545844225

<<<<<<< HEAD
## Design decisions

Images are base64 and javascript is inline. This is due to security restrictions of the HTML5 Canvas imaging object. Source images must be embedded within the page or located on the host domain to be allowed into the canvas security sandbox.

I chose middleman because there are great sensible defaults, but there's no reason this couldn't be a single page html file.

=======
>>>>>>> Complete refactor with model-view separation. Fixes several UI bugs.
## Extras

### Add fonts

Include your own fonts in `stylesheets/_fonts.scss`

Fonts are handled with sizes as variables in the javascript and can be [added here](https://github.com/voxmedia/meme/blob/master/source/partials/_javascripts.html.erb#L8)

### Add watermark

Convert an svg to base64 and [add here](https://github.com/voxmedia/meme/blob/master/source/partials/_javascripts.html.erb#L8)

## Contributing

1. Fork it ( https://github.com/voxmedia/meme/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

Copyright (c) 2014 Vox Media Inc., Yuri Victor, Greg MacWilliam

BSD license

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

# Pancake Themer

## Overview

This tool provides an interactive way to generate custom frontend CSS for installations of [Pancake](http://pancakeapp.com).

## Usage

To use, open this page: http://aepex.github.io/pancake-themer/

The left side shows a preview of your current settings, and the right side contains a list of all the pages and parts that are editable.
After going through each page and making the edits you want, click the Get CSS button at the top.

A box will appear containing your custom CSS, simply copy and paste the code into the Settings > Branding > Frontend CSS box inside of Pancake, and click Save.

If something goes horribly wrong, erasing all the code from the Frontend CSS box will set things back to how they were.

## Compatibility

Pancake Themer should be compatible with the most recent versions of Pancake 3 and 4 as long as the frontend theme is set to the default of `pancake`. If you're using Pancake 3, some settings simply won't apply to anything.

## Limitations

This hasn't been tested extensively, so use at your own risk! I highly recommend previewing your client pages afterward to make sure everything looks right.

## Advanced

Changing some parts of the theme are outside the scope of this tool, but the following may help you:

### Button Colors

Copy the following code and change the two hex colors in each line to the new colors you wish to use. The first color is the top of the button gradient, and the second color is the bottom. Then copy it again (with your new colors) add it to the Frontend CSS box (after the code from Pancake Themer).

	#buttonBar a:hover {
	background-image: -webkit-gradient(linear, left top, left bottom, from(#EF4C1A), to(#D54518));
	background-image: -webkit-linear-gradient(top, #EF4C1A, #D54518);
	background-image: -moz-linear-gradient(top, #EF4C1A, #D54518);
	background-image: -ms-linear-gradient(top, #EF4C1A, #D54518);
	background-image: -o-linear-gradient(top, #EF4C1A, #D54518);
	background-image: linear-gradient(top, #EF4C1A, #D54518);
	}

### Ticket / Task Colors

These can be changed directly within Pancake. Just go to the Ticket Statuses or Task Statuses page and enter your new background colors.

## Credits

This tool is largely based on the [Live CSS Editor](https://github.com/rukavina/live-css-editor) by [rukavina](https://github.com/rukavina).

## License

The MIT License (MIT)

Copyright (c) 2013

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
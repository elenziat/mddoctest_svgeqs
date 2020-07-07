# Test

Ok, lets see if I understand the system:

If a "paragraph"-image is followed directly by a paragraph containing inlined images, these are moved into seperate paragraphs when github creates the page:

<p align="center"><img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/cc6824dc09cabeaff44dffe078fa4051.svg?invert_in_darkmode" align=middle width=272.43645pt height=95.16181784999999pt/></p>
This sentence follows directly and contains some inlined images as <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/>.

If there is a blank line between a "paragraph"-image and the following text, its inlined images are preserved:

<p align="center"><img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/cc6824dc09cabeaff44dffe078fa4051.svg?invert_in_darkmode" align=middle width=272.43645pt height=95.16181784999999pt/></p>

Between the preceeding image and this sentence is a blank line in the readme.md file. And this paragraph containts some inlined images as well, like <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/>.


This sentence is directly before a paragraph-image and contains inlined images (<img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/>), which are preserved.
<p align="center"><img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/cc6824dc09cabeaff44dffe078fa4051.svg?invert_in_darkmode" align=middle width=272.43645pt height=95.16181784999999pt/></p>
This sentence follows directly and contains some inlined images as <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/>


This sentence is directly before a paragraph-image and contains inlined images (<img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/>), which are preserved.

<p align="center"><img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/cc6824dc09cabeaff44dffe078fa4051.svg?invert_in_darkmode" align=middle width=272.43645pt height=95.16181784999999pt/></p>
This sentence follows directly and contains some inlined images as <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/>


# CSS-learning-basics
My attempt to learn CSS.
1. [Very basics](/CSS-very-basics) : [Referred to this Kevin Powell's playlist.](https://www.youtube.com/playlist?list=PL4-IK0AVhVjM0xE0K2uZRvsM7LkIhsPT-)
2. [Flexbox](/CSS-learning-flexbox) : [Referred to this Kevin Powell's playlist.](https://www.youtube.com/playlist?list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd)
3. [box-shadow](/CSS-learning-box-shadows) : [Referred to this Kevin Powell's playlist.](https://www.youtube.com/playlist?list=PL4-IK0AVhVjPV_GpQj-jAiPP4MrQDoRcM)

Some important notes to myself :
1. <b>em and rem :</b><br>Use rem for setting font sizes. Using em may lead to compounding issues. em set to font sizes references to its parent element while rem refers to the root(html) element. em set to any other property(margin, padding) besides font size refers to the font size of that element and not the root element. Thus, prefer rem for other uses. [This](https://www.youtube.com/watch?v=pautqDqa54I)
2. <b>Fonts :</b><br>Always mention what font you'd use.
Most of the times, not all OS and/or browsers would have all the fonts. Use font stack in such cases. https://www.cssfontstack.com/
<br>If a font name has multiple words, put them all inside quotation marks.

3. <b>Links pseudo-class order :</b><br> link -> visited -> hover -> active
4. <b>List style position :</b><br>list-style-position: inside;<br>Firefox and safari have default values as inside but Chrome has default value as outside. Set it as INSIDE.
5. <b>vmin for title :</b><br>Use vmin for title's font size for better responsiveness, but it may backfire in mobile's landscape view.
6. <b>ROFL! Both are same :</b><br>width: 600px; max-width: 100%; <br> width: 100%; max-width: 600px; <br> [This](https://css-tricks.com/tale-width-max-width/)
7. <b></b><br>

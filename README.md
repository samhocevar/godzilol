# Godzilol

Wreak havoc on the Internet with this awesome bookmarklet!

Just add the following code to a bookmark and click on it to make any webpage
you’re viewing 84% more awesome:

    javascript:(function()%7Bgodzilol=%22%3Ca%20href='javascript:(function()%7B
    document.getElementById(%5C%22lolling%5C%22).remove();return%7D)();'%20style=
    'display:block;background:none!important;padding:25px 25px 0 0;'%3E%3Cimg%20
    src='https://github.com/samhocevar/godzilol/raw/master/img/godzilol.gif'%20
    border=0%20width='100%25'%20heigth='100%25'%3E%3C/a%3E%22;var%20div_popup;
    div_popup=document.createElement('div');div_popup.innerHTML=godzilol;div_popup
    .id=%22lolling%22;div_popup.setAttribute(%22style%22,%22position:fixed;z-index
    :1000;bottom:0px;left:0px;width:100%25;height:auto;max-height:100%25;%22);
    document.getElementsByTagName(%22body%22)%5B0%5D.appendChild(div_popup);%7D)()

Here are pictures of how awesome it looks like:

![example](img/godzilol-example.png)
![example2](img/godzilol-example2.png)

[GNAA](http://www.gnaa.eu/)


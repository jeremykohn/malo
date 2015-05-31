Malo is ultra small css library for building web sites.

It is meant to be structural base for small or medium web sites.

Malo derives from it's bigger brother [Emastic CSS Framework](http://code.google.com/p/emastic/).

Why should you use Malo?

Because it's:

    Ultra small (compressed is 0,25 kb or 8 lines of CSS! )
    Personalized width of the page in (%, px, em)
    Super flexible.
    Easy to use. 

How Malo works?

Malo is based on the principle that every column can be divided into two, three, four and five parts.

    100% = 50% + 50%
    100% =~ 33,33% + 33,33% + 33,33%
    100% = 25% + 25% + 25% + 25%
    100% = 20% + 20% + 20% + 20% + 20% 

Also you can use nested columns

100% = 50% + 50% ( and inside 25% + 25% + 25% + 25%)

I think that with this system you can cover 85% of every grid you can imagine.

About CSS

malo.css is made of two parts: basic reset and the grid system

The grid part is made of classes from dp100 (div percent 100) to dp20 floated to left and using the hack for IE: display: inline; *margin-left:-0.04em; (be careful if you change default 1em = 16px)

Examples:

    Test1
    Test2
    Malo1
    Malo2
    Malo3
    Malo4
    Malo5
    Malo6
    Malo7
    Malo8
    Malo9
    Malo10
    New: Malo ID
    Prototyping with Malo CSS Library 

Tested with:

IE:5.01,5.5,6,7,8, Firefox:1.5,2,3, Opera:8.53, 9.23, Safari:2.0 - 4.0 , Chrome 0.3, Konqueror: 3.5, 4.0, camino-1.6.5, kazehakase-0.5.2, galeon-2.0.4, seamonkey: 1.1.12, 2.0

Note:In IE the columns(div) will have -0.04em. That will prevent the grid from breaking apart.

Comments and suggestion 

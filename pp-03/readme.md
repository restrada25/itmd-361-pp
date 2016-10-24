## ITMD 361, Production Problem 3: Relative Units in CSS

For this production problem, you will be doing some math using the formula we talked about in class
on September 21. Specifically,

    target ÷ context = result

Remember that, by default, most browsers set 1em = 16px.

You’ll then use that to compute the values for the CSS styles below.

1. Convert the base font-size listed here from pixels to ems:

      html {
<<<<<<< HEAD
        font-size: 1.1875em; /* 19px */
=======
        font-size: 19px;
>>>>>>> 51ae64fbe2f67a542c90d3450ca3b1ac37367bef
      }

2.  Convert the base font-size listed here to ems, and set the line-height in ems accordingly:

      html {
<<<<<<< HEAD
        font-size: 1.0625em; /* 17px */
        line-height: 1.4117em; /* 24px */
=======
        font-size: 17px;
        line-height: 24px;
>>>>>>> 51ae64fbe2f67a542c90d3450ca3b1ac37367bef
      }

3. Set the padding for this page to 12px on top and bottom, and 6px on left and right. Express in
ems:

      html {
<<<<<<< HEAD
        font-size: 1.125em; /* 18 */
        padding: 0.666em 0.333em 0.666em 0.333em; /* TRBL TB=12px and RL=6px */
=======
        font-size: 1.125em;
        padding:
>>>>>>> 51ae64fbe2f67a542c90d3450ca3b1ac37367bef
      }

4. Consider the following CSS. Assuming a browser with its base size at 1em = 16px, how big is h2,
in pixels?

<<<<<<< HEAD
      html { 
        font-size: 1.125em; /* 18px */
      }
      figure {
        font-size: 0.888em; /* 16px */
      }
      figure h2 {
        font-size: 1.4375em; /* 23px */
=======
      html {
        font-size: 1.125em;
      }
      figure {
        font-size: 0.888em;
      }
      figure h2 {
        font-size: 1.4375em;
>>>>>>> 51ae64fbe2f67a542c90d3450ca3b1ac37367bef
      }

=== Real Buddha Quotes ===
Plugin Name: Real Buddha Quotes
Contributors: suttafriends
Plugin URI: https://suttafriends.org/help/real-buddha-quotes-wordpress-plugin/
Tags: Buddhism, Dhamma, Dharma, quotations, quote, Buddha
Requires at least: 3.0.1
Tested up to: 6.2
License: Code: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Stable tag: trunk

Displays a random quotation from the Buddha found in the Dhammapada. Includes shortcode and widget.

== Description ==
The internet is full of fake quotations attributed to the Buddha. By using this plugin you can help spread the actual words of the Buddha with your website visitors.

You can display this quote using a shortcode or a widget. (At the moment, there is no block for this plugin. If you would like to help create one, please contact us!)

There is the option for the citation of the verse to link back to the SuttaFriends.org website so your readers can see the quotation in the context of the whole Dhammapada and have the chance to explore more real Buddha quotes.

== Installation ==
After installing you will see no change to your website. You will either need to add the widget to your widget area or include a shortcode on one of your pages.

## Shortcode

To include a random Dhammapada in the content of a page or post, simply insert the shortcode

`[random-dhammapada]`

To make the citation (e.g. "Dhammapada 20") link back to the verse on SuttaFriends.org, go to Settings>Real Buddha Quotes

## Inserting into your theme

If you like to put the quotation somewhere on your website that does not allow shortcodes, you can add this PHP to one of your theme files:

`echo random_dhp_shortcode();`

This will insert the quotation. There are no parameters. Only try this if you are familiar with codign in PHP. Always make a backup before changing templates.

## Styling
Styling of the quotation and the citation is done through css. We recommend the following:

`div.random-dhammapada{
	border:solid 1px;
	padding:10px;}

p.rdhp-verse {
	font-style:italic;}

div.rdhp-citation {
	text-align:right!important;}

p.rdhp-attribution, p.rdhp-verse {
	margin-bottom:0px;}

p.rdhp-attribution {
	font-size:.9em;}`

If you like the citation (e.g. Dhammapada 175) to appear on the next line, add this CSS:

`
.rdhp-cite-link {display:block}
`

	
### Drop cap

The following code could create a drop cap (first letter larger size).

`p.rdhp-verse:first-child:first-letter {
  float: left;
  font-size: 3.5em;
  line-height: 2empx;
  padding-top: .15em;
  padding-right: .1em;
  padding-left: 0px;`
  
You will need to adjust all of the sizes and test on desktop as well as mobile to make sure it looks correct in different contexts.
  

== Frequently Asked Questions ==

= Whose translation of the Dhammapada is this? =

The translation is attributed to Ven. Kiribathgoda Gnanananda. The entire translation can be read at [SuttaFriends.org](https://suttafriends.org/dhammapada). There you can find out about [how to get the print book](https://suttafriends.org/book/dhammapada-what-does-the-buddha-really-teach/)

= What is the copyright for this text? =

The text of the Dhammapada is copyright Mahamegha Publications.

== Screenshots ==
1. There is only one setting, but you can also find detailed instructions on the settings page.
2. There are no settings for the widget, other than an optional title.
3. This is an example of the widget, styled with the suggested css.
4. Using the shortcode you can add the quotation anywhere on you site, seamlessly integrating into your own look and feel.	
5. Don’t be afraid to experiment with different blocks. Here is the built in Gutenberg MEdia & text block.
6. And this is what the front end looks like.
7. Your theme or custom blocks may have even fancier blocks. Here is the Stackable Blockquote block.
8. And this is what the front end looks like.
9. You can create drop caps through css. See instructions on the settings page.
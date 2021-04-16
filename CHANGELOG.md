# OLD Changelog for historical purposes ONLY. 
<b><i>NOTE: Latest version of the changelog has moved to https://github.com/MobiGary/MobiriseM4blocks/blob/main/CHANGELOG.md andf the new project repisotory is here https://github.com/MobiGary/MobiriseM4blocks</i></b>


All <b>OLD</b> notable changes to this project will are documented below.

## Version 3.3 - MobiGaryMenu-v3.3.mbrext (2021-JANUARY-14)
- Added new gear icon "MM Minumum Height" option to allow setting of the minimum menu height. This now allows configurable minimum menu height from 40px to 150px on the gear icon.
- Modidifed CSS code for TL Menu to allow better bottom padding slider configuration. This helps when when letters with tails are used in the top line message (eg.the letter g in the word "Message"). This was added after a forum user reported the issue. 

## Version 3.2 - MobiGaryMenu-v3.2.mbrext (2020-OCTOBER-20)
- After a forum user released the "Bootstrap SVG Icons" (1100+) as a Mobirise Extension I noticed alignment variations of icons when mixing icons from different icon packs when used in some Mobirise M4 themes. Therefore CSS has been adjusted to handle alignement of icons better (if enabled) for both M4 and the new M5 Mobirise themes in both M4 and M5 builders.

## Version 3.1 - MobiGaryMenu-v3.1.mbrext (2020-OCTOBER-18)
- Added an additional gear icon option to allow the logo image (if enabled) to be rotated and have a border style and thickness.
- Added an additional gear icon option to allow the button(s) (if enabled) to move when hovered over.
- Modified CSS to change vertical alignment of icons (if displayed) to better suit the Mobirise 5 theme in addition to existing M4 themes.

## Version 3.0 - MobiGaryMenu-v3.0.mbrext (2020-OCTOBER-14)
- Added an additional gear icon section at the top of the menu "Global Menu Config". In this section added two new controls "Menu Top Line Font Weight" & "Menu Font Weight". These 2 new settings allow font weights from 100 to 900 matching the css font-weight property. This allows more granular control of the font weight for the menu top line text, menu text, brand name text. Note however, the actual available choices on the 100 to 900 scale are based on the font used as not all fonts have all variants available.
- Various CSS changes to fix some menu and button text alignment and padding issues when the menu is used with the following Mobirise Themes: Attorney M4, Agency M4, Conference M4, Modern M4 & Studio M4 which have different inherited CSS than the other M4 themes. Tested on all M4 themes in MR builder v4.12.4 and all M4 themes plus the new M5 theme in Mobirise builder v5.2.0.

## Version 2.9 - MobiGaryMenu-v2.9.mbrext (2020-OCTOBER-02)
- Added an additional gear icon control "MM Logo Top/Btm Padding px" to allow granular configuration of the menu logo top and bottom padding. Values between 1px and 10px permitted on the gear icon slider.

## Version 2.8 - MobiGaryMenu-v2.8.mbrext (2020-SEPTEMBER-25)
- Change to the logo margin & padding settings to better control the logo placement when "MM Logo Size" & "MM Logo Size Scroll Sticky" are both set to the same size. 

## Version 2.7b - MobiGaryMenu-v2.7b.mbrext (2020-SEPTEMBER-23)
- Minor change to menu logo file location following Mobirise release of new builder v5.1.9 (which fixes an issue regarding image file locations they introdeced in 5.1.8). The original MobiGary Menu v2.7 released 21/09/20 referenced the logo file from the web as a temporary measure until Mobirise fixed the issue with the builder.

## Version 2.7 - MobiGaryMenu-v2.7.mbrext (2020-SEPTEMBER-21)
- Added an additional gear icon control for the maximum width of the Main Menu "MM Max Width px". This new slider alows px settings ranging from 1200px to 1800px to provide users greater control over the maximum width of the main menu.

Screeenshot of "gear" items here: https://github.com/MobiGary/Mobirise-Configurable-Bootstrap-Menu/blob/master/MobiGaryMenuCog-v2.7.jpg

## Version 2.6 - MobiGaryMenu-v2.6.mbrext (2020-SEPTEMBER-06)
- Changed the format of the file from a zip file (containing and exported Mobirise project with the MobiGary Menu block) to a Mobirise extension (mbrext) file.
- Modified the Gear Icon Settings to separate out box shadow options for MainMenu (MM) and Sub Menu (SM). Previously they were combined. This now allows box shadow settings to be configured as on/off for MM and SM individually. This change was made as result of an enhancement request on the Mobirise forum.
- Moved the location of MM Transparrent on/off setting and MM Opacity slider setting next to each other. Made more sense to have them both together.

## Version 2.5 - MobiGaryMenu-v2.5.zip (2020-AUGUST-20)
- CSS changes to due to changes in new inherited CSS in Mobirise v5 that caused some minor issues. This new version behaves better in terms of Menu Logo dimensions and Menu Brand Name alignment in both Mobirise 4 and Mobirise 5 builder.

## Version 2.4 - MobiGaryMenu-v2.4.zip (2020-AUGUST-15)
- Modified the Gear Icon for setting "Icon Area Width" and "Buttons Area Width" to have a PX setting slider rather than a slider based on a CSS formula.
- Added more granular options for "Brand Name Area Width" on the gear icon. Individual PX width settings now possible for various different screen widths. This allows for more flexibility in controlling the Brand Name width and text wrapping at various screen width breakpoints.

## Version 2.3 - MobiGaryMenu-v2.3.zip (2020-AUGUST-10)
- Added "MM Show Brand All screen px width" gear icon toggle switch & also "MM Brand Name Dont Show Under px" gear icon slider that appears if "MM Show Brand All screen px width" option is de-selected. This allows the option of only showing the brand name above a certain configured screen px width. 

## Version 2.2 - MobiGaryMenu-v2.2.zip (2020-AUGUST-09)
- Added "MM Mobile Brand Name Area Width" & "MM NonMobile Brand Name Area Width" gear icon sliders to control the witdth and text wrapping of the Brand Name if "MM Show Brand Name" is selected. This gives more granular control of the Brand Name text formatting in both mobile (<992px) and non mobile display widths (992px or greater).

## Version 2.1 - MobiGaryMenu-v2.1.zip (2020-MAY-17)
- Added "MM Icons Area Width" gear menu slider to allow control over the size of the icons area if menu icons are enabled. This allows finer control over the placement, wrappig & padding around icons.
- Added "MM Button Area Width" gear menu slider to allow control over the size of the button area if menu buttons are enabled. This allows finer control over the placement, wrapping & padding around buttons.

## Version 2.0 - MobiGaryMenu-v2.0.zip (2020-MAY-13)
- Following Mobirise Forum feedback, modified CSS to improve menu link text, logo and brand name alignment within the Main Menu area.
- Modified CSS to change top padding if no menu logo selected. This moves the "X" (top right) of the Mamburger Menu down the screen slightly in this mode as it was slightly too high in this mode previously.
- Added "TL Top Border Color", "TL Top Border Thickness", "TL Bottom Border Color" & "TL Bottom Border Thickness" gear menu items to allow a border line to be placed above and below the top line message area if desired. If thickness sliders are set to zero, no border is applied.
- Modified the "MainMenu Hover Underline Thickness", "MainMenu Underline Thickness" & "SubMenu Underline Thickness" gear icons to allow more precice thickness settings by reducing the slider step setting from 0.5px to 0.25px.
- Simplified the wording and reordered some items of gear icon settings.

## Version 1.9 - MobiGaryMenu-v1.9.zip (2020-MAY-11)
- Following Mobirise Forum feedback, enhanced code to provide an additional gear icon configuration option for the top line message. Added "Show Top Line on HamMenu" gear icon option. This extra choice allows the top line message to either show or not show on the Hamburger Menu. If de-selected, the top line message is only displayed when not in Hamburger Menu mode.
- Corrected a single character typing mistake in the HTML gerar icon selection HTML code which caused a gear icon option display issue if both "TL BG Gradient Colour Style" PLUS "T-B 4 Col" were both selected.

## Version 1.8 - MobiGaryMenu-v1.8.zip (2020-MAY-10)
- Following Mobirise Forum feedback, enhanced code to provide additional gear icon configuration options for the top line message. Added "TL BG Gradient Col" gear icon option. If this new option is selected, additional options are displayed allowing either 2, 3 or 4 gradient background colors to be selected in either Left-to-Right or Top-to-Botton gradient configuration. If this new "TL BG Gradient Col" option is not selected, the single color top line background color is used.

## Version 1.7 - MobiGaryMenu-v1.7.zip (2020-MAY-09)
- Following Mobirise Forum feedback, enhanced code to provide more gear icon configuration options for the scrolling top line message.
- Made the minimum thickness of the menu top line smaller so it takes up less space when set to the minimum top and bottom padding settings on the gear icon.
- Tided up the gear icon menu plus added some section dividers to separate out the Menu Top, Main and Sub-Menu components on the gear icon.

## Version 1.6 - MobiGaryMenu-v1.6.zip (2020-MAY-08)

- Enhanced CSS code to better support temporary pausing of the scrolling top line message if you mouse hover over it (if configured in the "Top Line Scroll Mouse Hover Pause" gear icon option). This option now supports several browser types including some newer and some older browsers. 

## Version 1.5 - MobiGaryMenu-v1.5.zip (2020-MAY-07)

- Enhanced CSS code to better handle formatting of hamburger and collapsed menus on IE11. 
- Added a new cog option for "Show Top Line" which allows a message banner line above the menu if enabled. Additionally, a sub option is displayed allowing you to select if you wish the top line to be removed when scrolling down the page if "sticky" menu used. If "Show Top Line" is enabled a choice of "None", "Flash", "Pulse" or "Scroll" options are provided. Color, size and alignment of the top line text is selected in the normal method with Mobirise builder by clicking the text and completing the dropdown presented.

## Version 1.4 - MobiGaryMenu-v1.4.zip (2020-MAY-01)

- Removed small amount of orphan code identified in the mbr-parameters section. This orphan code had no ill effects on the operation of the menu in v1.3. This v1.4 update is just to tidy up the code.

## Version 1.3 - MobiGaryMenu-v1.3.zip (2020-APRIL-24)

- Solved a slight sub-menu hover color change delay which exhibited itself on Chrome browser if you had iconfonts and text on sub-menu items and also configured a different color for hover over the menu text. What would happen is the text would change color first and then there would be a slight delay before the iconfont changed color also. This was due to a transition timing setting in the CSS which has now been modified.

## Version 1.2 - MobiGaryMenu-v1.2.zip (2020-APRIL-23)

- Added "MainMenu Hov UL Col" cog item at the request of a Mobirise forum user. Previously in v1.1 the hover color of the main menu items was used also for the underline hover (if selected). This color is now configurable.

## Version 1.1 - MobiGaryMenu-v1.1.zip (2020-APRIL-23)

- Added "MainMenu Items Hov Bkg" cog item. If this option is not selected, as with v1.0 no background hover color will be applied to the menu. If the new cog option is selected, an additional option will be displayed "MM Items Hov Bkg Col" allowing you to set the hover background color of main menu items (and hamburger menu).

## Version 1.0 - MobiGaryMenu-v1.0.zip (2020-APRIL-21)

- After testing and feedback, published latest version as v1.0

## TEST Version 20200420 (2020-APRIL-20)

- Added "Menu BoxShadow Inner Location" enhancement on the cog allowing you to specifiy "Bottom Only" or "All 4 Sides".

## TEST Version 20200419 (2020-APRIL-19)

- Added "Logo Size Scroll Sticky" extra slider. In addition to the existing cog item to control the Logo image size the cog also now has a “Logo Size Scroll Sticky” slider. This allows you to set the size of the logo for when/if you use sticky mode. It changes the logo size as you scroll down the page and the menu stays stuck – the overall result is the amount the menu shrinks or grows in height on scroll is now configurable from the cog for desktop mode operation of the menu. You could therefore select a smaller/same size/larger logo size on sticky scroll to control exactly how the sticky menu scroll looks. 

- Added "Menu BoxShadow Inner" as well as "Menu BoxShadow Outer" cog options. Allows you to control the color and opacity of the main menu & sub menu inner and outer box-shadow individually. Can be set between 0 and 1 in increments so if you only want one of the shadows for example set the one you don't want to 0. 

## TEST Version 20200417 (2020-APRIL-17)

- Addition of a cog item "SubMenu Item Hover" giving a toggle if a hover color over text required or not. If enabled a color selector is then displayed below it.

- Addition of a cog item "MainMenu Hover Underline Thickness". Allows the thickness of the hover underline to be set. It was fixed at 1px before (if option enabled). Now variable from cog.

- Changed the step values of some cog items to give greater granular control.

- Various enhancements to look and feel of main menu "collapsed" mode when enabled.

## TEST Version 20200416v2 (2020-APRIL-16)

- Changed hover so menu items that have social icons next to them also hover in same colour seected in the cog. Previously there was a hover conflict with the CSS setting iconfont hover colour (selecting what was chosen in the main menu for all iconfonts in all menus). Faulty part of CSS removed now.

## TEST Version 20200416 (2020-APRIL-16)

- The "Collapsed" cog item is back.

- Some spelling mistakes on the cog have been corrected.

- In desktop mode (not mobile) if you use icons on your menus as well as text, when you hover over a menu link that has both text+icon, the hover color changes to the on-hover "Main Menu Item Hover" color cog item both together (rather than separately as before).

- Removed the cog item to set icon color as this was partly to blame for the issue above (in conjunction with the associated CSS). So now if you wish to set a social icon color (if you use them in the menu) just click on the social icon and set it manually.


## TEST Version 20200415v2 (2020-APRIL-15)

 - Changes in this version all relate to the hamburger menu. There is now a cog entry to specifically set the Hamburger background color (which i'm calling Level 1) as well as Hamburger Menu Level 2 (or greater), hence L2+ on the cog - background color. Of course if you want L1 and L2 to be the same color so no difference shows on the Hamburger menu, then set them both the same color in the cog. But flexibility is there. HamMenu Opacity setting is still there for the Hamburger Menu and it controls both L1 & L2+ colour settings the same amount (whatever you set on the slider) of opacity for the Hamburger Menu. Move the slider all the way if you want no opacity.

## TEST Version 20200414v2 (2020-APRIL-14)

- Added box-shadow menu cog optioon.

## TEST Version v20200414 (2020-APRIL-14)

- This is the initial release of the MobiGary Mobirise Configurable Menu for Mobirise. Various cog options availabe to make settings quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS.


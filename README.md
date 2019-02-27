#Basic design requirements
Hi there, for our mutually productive work we need to discuss some design stuff. From you as a designer, we will need to get all components made according to the technical specifications and some separate files wich contain things from UI KIT. 

##UI Kit:
  - Components for all versions (mobile, tablet?, desktop)
  - Shadows and border-raius
  - Fonts and typography
  - Buttons and inputs
  - Color
  - Icons

##Good design:
  - Typography duplicated to separate file
  - Text styles, colors, borders, etc. are used only from UI Kit
  - No wild rebuilds of components at different resolutions
  - The interface is divided into components
  - All components made in the same style

Main characteristics - **system, thoughtful, logical.**

####Components for all versions:
  - Use default container resolutions: **1140px** or between 1100 and 1200 pixels
  - Background images might be greater than container
  - Our design system supports 12 columns
  - Use *logical* indents, for example: 
    - 70px top, 100px bottom for each component, it is NOT dogma, if you need to use other indents DO it!
    - Our recomendations: 30/50/70/100/130px etc.
  - Remember about logical indents between the text and other components


####Fonts and typography:
  - Remember about headings hierarchy **h1-h6**
  - If it is possible use ONE font-family
  - If it is possible use Google Fonts
  - If it is possible use NOT more than 2 font style, for example: regular and bold

####Buttons and inputs:
  - Please do NOT use gradient borders
  - Make a hover effect

####Color:
  - If it is possible, please do NOT use more than 3 color (Grey, Black and White are not considered)
  - Please do NOT use gradient text

####Icons:
  - Use SVG icons, for example you can find it here: flaticon.com
  - If it is possible do NOT use gradient, or if you decide to use gradient icons we want wo get it separate!

##Good to have at the end:
  - All files with main design (all components)
  - Separate files with UI Kit Stuff
  - Sliced pictures and icons
  - If it is possible design contain real texts

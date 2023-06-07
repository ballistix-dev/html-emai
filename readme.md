#  HTML Email Workflow

## Updates

### June 07, 2023

 -  ~~Remove the Mautic specific code eg. data-section-wrapper="1"~~
 - ~~Remove the background colour in the style tag (it is repeated) and also remove the semicolon after the hex code in the bgcolor tag - example screenshotted from template~~
 - ~~Change rgb colours to hex code~~

 - ~~Change margin-bottom styling so its margin instead with the 3 figures. Example below~~

        <p style="margin-bottom: 16px;"> to <p style="margin: 0px 0px 16px;">

 - ~~Change ‘Margin: auto’ to ‘margin: auto’~~
 - ~~Remove any text styles within all img src styling~~
 - ~~In the img src styling, have the background as transparent~~
 - ~~Add the narrow-padding-on-narrow class~~
 - ~~Add a lot of the ‘Preview Text Spacing Hack’ code so that it pushes the content of the email completely out of the preview text when an email is sent~~
 - Add in both contact name codes for both Mautic and vTiger
 - ~~Make the alt text blank so it appears as alt=""~~
 - ~~Update subscribe link in footer to~~

         <a href="{unsusbcribe_url}" style="color: #B8B8B8; text-decoration: none;" target="_blank">Managed Subscription Preferences</a>

 - ~~Add a section for bullets that are images~~
 - Fix hover on buttons ---> *did we decide to use image for buttons*
 - ~~Is it possible for a 2 column text/image alternating layout to stack like the below on mobile?~~

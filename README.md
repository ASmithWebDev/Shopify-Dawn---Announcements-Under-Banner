# Under Header Announcements For Shopify Dawn Theme
Welcome to my GitHub repository where I have shared the code for adding an announcement banner under the header that is responsive for both mobile and desktop sites with the option to add SVG Icons. This code was written by modifying the Shopify Dawn theme in version 7.0.1. The original theme was developed by Shopify and credit goes to the original developer. With this modification, you can add an announcement banner under the header to your Shopify store, which can be used to communicate important information, such as sales, promotions, or important announcements. The announcements are editable in the Shopify Theme customise customize it to meet your specific needs. Feel free to use this code in your own projects.

# Setup

**I recomend duplicating your theme so you are not editing a live site**

Log in to your Shopify Dashlane

Go to `Online Store` under Sales Channels

On your theme press the `...` then `edit code`


## Create liquid file

In the `Sections` folder click `add a new section`

Ensure `liquid` is selected and enter the file name: `under-banner`

Copy the code from my `under-banner.liquid` file into the new file

## Upload liquid file

In the `Assets` folder click `add new asset`

Ensure `liquid` is selected and enter the file name: `under-banner`

Upload my `section-underheader.css` here

## Edit theme.liquid

In the `Layout` folder select the theme.liquid file

Find this line of code:

>{% section 'header' %}

and under it on a new line enter this line of code

>{% section 'under-header' %}

## Customising the Announcements

The under header should now appear in the Theme Customizer and can be edited from there.

### Adding SVG Icons

Under the column in the theme editor there is a text box to enter SVG code.

For mine I used Font Awesome, found the icon I wanted and copied the SVG code into this box.

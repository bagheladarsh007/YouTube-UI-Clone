# YouTube-UI-Clone

# HTML Structure Explanation

This README explains the structure and elements of the provided HTML code.

### `<!DOCTYPE html>`
- This declaration specifies the document type and version of HTML being used, which is HTML5 in this case.

### `<html>`
- The root element of an HTML document, encapsulating the entire content.

### `<head>`
- Contains meta-information about the HTML document, such as character encoding, viewport settings, linked resources, and the document's title.

    - `<meta charset="UTF-8">`: Specifies the character encoding as UTF-8, which supports a wide range of characters and symbols.

    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Defines the viewport settings for responsive design.

    - `<link href="...">`: Links external resources, in this case, a Google Fonts stylesheet.

    - `<title>Document</title>`: Sets the title of the webpage.

    - `<link rel="stylesheet" href="style.css">`: Links an external CSS stylesheet for styling the HTML content.

### `<body>`
- Contains the main content of the webpage, including headers, navigation, and video listings.

#### Header Section
- The header section contains the site's logo, search bar, and various icons.

    - `<div class="header">`: The container for the header section.

    - `<div class="header-left">`: Contains the menu icon and the site's logo.

    - `<div class="header-search">`: Contains the search bar and a search icon.

    - `<div class="header-icons">`: Contains various icons for actions like video search, camera, apps, notifications, and user profile.

#### Main Body Section
- The main body section contains the sidebar with categories and a list of recommended videos.

    - `<div class="mainBody">`: The container for the main content.

    - `<div class="sidebar">`: The sidebar section for navigation.

        - `<div class="siderbar_categories">`: The container for sidebar categories.

            - Individual category elements with icons and text.

            - `<hr>`: A horizontal line to separate categories.
            - 

    - `<div class="videos">`: The main content area for video listings.

        - `<h1>Recommened</h1>`: Heading for the recommended videos.

        - `<div class="videos_conatiner">`: Container for individual video listings.

            - Individual video elements with thumbnail, author details, title, and view count.

- The provided README explains the structure of the HTML code and key elements used for creating the webpage.

### Screenshorts
In this youtuble clone there is mainly 3 sections 
#### 1 Header Section
<img width="954" alt="yy1" src="https://github.com/bagheladarsh007/YouTube-UI-Clone/assets/142333682/72382f1d-1c8a-49bd-ac6c-d821ee3b7ccd">

#### 2 Side bar Section
<img width="149" alt="yy2" src="https://github.com/bagheladarsh007/YouTube-UI-Clone/assets/142333682/2bf63667-370c-4fd8-8e57-9d905ef90f2d">

#### 3 Video Sectiom
<img width="797" alt="yye3" src="https://github.com/bagheladarsh007/YouTube-UI-Clone/assets/142333682/93d2ed7e-f08f-4ce6-9134-098421de37d3">




 ### CSS Properties Explanation
 Here's an explanation of the CSS properties used in the provided code:

- `@import url(...):` Imports external fonts from Google Fonts to be used in the webpage.

- `*:` Selects all elements on the page.

- `margin: 0; padding: 0;:` Resets the margin and padding of all elements to zero, ensuring a consistent baseline for styling.

- `box-sizing: border-box;:` Ensures that the total width and height of an element include padding and border, not just the content.

- `.material-icons:` Selects elements with the class "material-icons" and sets their color to a shade of gray.

- `.header:` Styles the header section, including setting its height, alignment, and padding.

- `.header-left:` Styles the left part of the header, containing the logo and menu icon.

- `.header-search form:` Styles the search bar, including the border and flex display.

- `.header-search input:` Styles the search input field, setting its width, padding, and removing the border.

- `.header-search button:` Styles the search button.

- `.mainBody:` Sets the height and overflow for the main content area.

- `.sidebar:` Styles the sidebar, including its width, background color, and scrollbar behavior.

- `.sidebar_categories:` Styles the categories within the sidebar, arranging them in a column layout with margins.

- `.sidebar_category:` Styles individual category items in the sidebar, including padding and hover effects.

- `hr:` Styles horizontal lines with a specific height and background color

- `.videos: Styles the video section, including background color, width, height, overflow behavior, and padding.

- `.videos_container:` Styles the container for video elements, arranging them in a row with space between and allowing wrapping.

- `.video:` Styles individual video elements, setting their width and margin.

- `.video_thumbnail:`` Styles the video thumbnails, ensuring they cover the designated space.

- `.author img:` Styles author images, setting their size and border-radius.

- `.video_details:` Styles the video details section, arranging elements in a row.

- `.title:` Styles video titles, arranging them in a column layout.
 
- `h1:` Styles level 1 headings with a specific font size and margin.

  ### Hosted link
  you can see here the hosted link : https://bagheladarsh007.github.io/YouTube-UI-Clone/

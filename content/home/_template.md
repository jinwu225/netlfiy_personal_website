---
# Begin Front Matter
# YAML Formatted Begin with triple-dashes (---) and TOML Formatted Begin with triple-plus (+++)

# Type of block/widget
# Link: https://wowchemy.com/blocks/
# options: blank, testimonials, logos, pricing_plans, about, accomplishments, contact, 
# experience, features, hero, collection, portfolio, slider, tag_cloud, people
widget: 

# Whether this file represents a page section
# options: true, false
headless:  

# Section Options 
title: ''
subtitle: ''
weight: 10    # Section Position (Integer Value)
active: false # Activate this widget? true/false

# Section Design 
design: 
    # options: "1", "2"
    # "1": Single Full-Width Column - Section Title Above Section Content
    # "2": Section Title to the left of Section Content
    columns: 

    # options: 1 (List), 2 (Compact), 3 (Card), 4 (Citation), 5 (Showcase), Masonry, <self-defined view>
    view:

    # Flip alternate rows when in Showcase view?
    # options: true, false
    flip_alt_rows: true 

    # Background option 1 - Color 
    background:
        # Choose a color such as from https://html-color-codes.info
        color: 'navy'
         # Text color (true=light, false=dark, or remove for the dynamic theme color). 
        text_color_light: true

    # Background option 2 - Gradient
    background:
        # Choose colors such as from https://html-color-codes.info
        gradient_start: '#4bb4e3'
        gradient_end: '#2b94c3'
        # The gradient angle from 0-360 degrees
        gradient_angle: 180
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true

    # Background option 3 - Image
    background:
        # Name of image in `assets/media/`.
        image: background.jpg
        # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
        image_darken: 0.6
        #  Options are `cover` (default), `contain`, or `actual` size.
        image_size: cover
        # Options include `left`, `center` (default), or `right`.
        image_position: center
        # Use a fun parallax-like fixed background effect on desktop? true/false
        image_parallax: true
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true

    # Background option 4 - Video 
    background:
        video:
            # Name of video in `assets/media/`.
            path: background-video.mp4
            # Post-processing: flip the video horizontally?
            flip: false

    spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["20px", "0", "20px", "0"]
    
    # Customization of Widget with CSS
    advanced:
        css_style: ''
        css_class: ''

# End Front Matter
---
<!--Begin Section Content-->
<!--Text Guide
# Example 1 - Bold Text
**Hello** 

# Example 2 - Callout note where "filtering publications" is underlined and 
refered to <File folder>/publication folder
{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}


-->




 text, images, videos, galleries - and even HTML code!-


<!--Gallery album reference the assets/media/albums/demo folder-->
{{< gallery album="demo" >}}

<!--End Section Content-->
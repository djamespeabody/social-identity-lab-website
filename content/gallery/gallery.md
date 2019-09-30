+++
# About widget.
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = false  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear in.

title = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
  
[[gallery_item]]
  album = "gallery_folder"
  image = "dog_1.jpg"
  
[[gallery_item]]
  album = "gallery_folder"
  image = "dog_2.jpg"
  
+++
<h2>Our Lab in Action!</h2>
{{< gallery album="<gallery_folder>" >}} 

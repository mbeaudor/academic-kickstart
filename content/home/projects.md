+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "My PhD Project"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "orchidee.png"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""

 # Using neural networks algorithm => calculate the ammonia fluxes with IASI column measurements. 

+++
{{< figure library="true" src="orchidee.png" title="" lightbox="true" >}}

My PhD project includes **modeling approaches** consisting in better understanding and representing the **nitrogen cycle** at global scale. I am particularly interested by the impacts of the **agricultural sector** on the **air quality and the climate**.
Livestock activities and the fertilization input are major sources of nitrogen.  
The models that are at stake are ORCHIDEE for the continental surface compartment and LMDz-INCA for the atmospheric part.
* After identifying the key processes in ORCHIDEE.
One of the objectives of my project is to develop a module related to **livestock emissions** at global scale taking into account feeding and manure management. 
This module will be used to set up diferent types of scenarios in order to better analyze the evolution of the agriculture.
* Secondly, I will work on the impact of the emissions on the **atmospheric composition** and on the potential feedbacks associated. To do so, I will need to develop a part of the **coupling between ORCHIDEE and LMDz-INCA** in order to make the atmopshere and the biosphere interacting.  
* Beside, I have the idea to evaluate the atmopsheric ammonia concentration calculated by INCA with current available **satellite data** as IASI. 




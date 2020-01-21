+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active =  true # Activate this widget? true/false
weight = 5  # Order that this section will appear.

title = "Meta Learning for Human Language Technology"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "#F7F7F7"
  
  # Background gradient.
  # gradient_start = "#FFFFFF"
  # gradient_end = "#FFFFFF"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
<!--weight:  5-->

**Special session at INTERSPEECH 2020, Shanghai, China**

## Description

Deep learning based human language technology (HLT), such as automatic speech recognition, intent and slot recognition, or dialog management, has become the mainstream of research in recent years and significantly outperforms conventional methods. The technology also has widespread applications in the industry. Several most famous examples include Siri, Alexa, Google Assistant, and Cortana. However, deep learning models are notorious for being data and computation hungry. These downsides limit the application of such models from deployment to different languages, domains, or styles, since collecting in-genre data and model training from scratch are costly.

Meta learning, or Learning to Learn, is one way to mitigate the above problems. Meta learning learns better learning algorithms, including better parameter initialization, optimization strategy, network architecture, distance metrics, etc., from multiple learning tasks. Meta learning has been showed the potential to allow faster fine-tuning, converge to better performance than model pretraining, and even achieve few-shot learning in several areas, including computer vision and translation.

The goal of this special session is to bring together researchers and practitioners working on meta learning in different HLT fields to discuss the state-of-the-art and new approaches, and to share their innovation, insights, and challenges, and to shed the light on future research directions. We will explore how to improve learning efficiency in data usage and in computation with meta learning for HLT tasks. We also aim to align academic efforts with industrial challenges, to bridge the gap between research and real-world product deployment.


<!--{{% alert note %}}-->
<!--Important information-->
<!--{{% /alert %}}-->

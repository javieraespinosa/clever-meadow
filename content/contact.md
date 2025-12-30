---
# type : landing
type : page
title : "Contact"
active : true
weight : 41


toc:	false
share: false
commentable: false
editable:	false
reading_time: false


pager: false

design:
  # Use the new Gradient Mesh which automatically adapts to the selected theme colors
  background:
    # text_color_light: true # White text

    # image:
    #   filename: stacked-peaks.svg

    gradient_mesh:
      enable: true



# image:
#   filename: delft.jpeg  # Path relative to page bundle or in assets/media/
#   focal_point: Smart      # Smart, Center, TopLeft, etc.
#   preview_only: false     # true = show on social/lists but HIDE on actual page
#   alt_text: "Description" # Accessibility text


# cover:
#   image: "delft.jpeg"      # Local filename or remote URL
#   style: "gradient"       # gradient (default), glass, blur, minimal, default
#   height: "medium"        # small, medium (default), large, full
#   hidden: false           # Hide cover if cover image exists


  # # Image Positioning (0-100%)
  # position:
  #   x: 50
  #   y: 50

---

<span id="magic" style="cursor:pointer; text-decoration: underline; ">
  click to reveal email
</span>


**Department of Informatics**    
Université Claude Bernard Lyon 1      
Bât. Nautibus, Campus la DOUA   
25 av. Pierre de Coubertin, 69622 Villeurbanne, France 

<script>
  const el = document.getElementById("magic");
  const parts = ["amF2aWVyLmVzcGlub3Nh", "dW5pdi1seW9uMS5mcg=="]; 
  el.addEventListener("click", () => {
    el.textContent = atob(parts[0]) + "@" + atob(parts[1]);
  });
</script>


**ERIC: Knowledge Engineering Research Lab**   
Université Lumière Lyon 2   
Bât. K, Campus Porte des Alpes    
5 av. Pierre Mendès France, 69676 Bron Cedex, France
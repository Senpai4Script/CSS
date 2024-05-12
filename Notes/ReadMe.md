# ================== Responsive Designs =====================

# ================== Sizing Units
# px : pixel (fixed_Size)
# % : percent (Size_distribution_Accordingly)
# vw / vh : vertical width & height (vh < vw )
# vmax / vmin : viewpoint minimum / maximum (valuevmin | 3vmin)
<h2 style="font-size: 7vmax">font-size: 7vmax</h2>
<h2 style="font-size: 7vmin">font-size: 7vmin</h2>

# em  
 <div style="font-size: 50px" id="parent">
      <h1 style="font-size: 1em">1em = parent_font_size</h1>
      <h1 style="font-size: 2em">Size 2em</h1>
      <h1 style="font-size: 3em">Size 3em</h1>
    </div>

# 1rem = 16px (size depends on root/parent)
  <div style="font-size: 50px" id="parent">
      <h1>1rem = 16px</h1>
      <h1 style="font-size: 1rem">1rem = 16px * 1</h1>
      <h1 style="font-size: 2rem">2rem = 16px * 2</h1>
      <h1 style="font-size: 3rem">3rem = 16px * 3</h1>
    </div>


# ================== Layout of Website
# absolute vs flex ?
# => flex
# reason : while aligning object using position: absolute it sucks to responsive
# why display : flex?
# flex-direction
# flex-wrap (parent)
# justify-content
# align-items etc


# ================== Media Queries (response according sizeValueOfScreen)
# min height/width
# max height/width

# syntax:
@media (screen_size){
    selector{
        prop : value;
    }
}
# code_execution ? below = 600px
    @media (max-width: 600px) {
        .box {
          background: rgb(0, 2, 6);
          color: aliceblue;
        }
      }





# ================ Key-Points for Responsive Web
# CSS FlexBox
# CSS Units
# Responsive Typography
# Mobile First Approach
# Flexible Images & Media

# ----------- :)) practice !
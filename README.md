# Gridfinity_Mapper
A vibe-coded drag-and-drop graphical HTML web app for planning and tracking Gridfinity drawer layouts, because I needed a flexible way of tracking my Gridfinity hardware drawers. 
It's just HTML, so you can <a href="https://html-preview.github.io/?url=https://github.com/TMarski/Gridfinity_Mapper/blob/main/Gridfinity_Mapper.html">try it out live in your browser!</a>

For those unaware, Gridfinity, described as "the modular, open-source grid storage system", is a whole storage ecosystem which uses 3D printed bins to store items on grid of 42mm cells. It has totally transformed my garage.
You can learn more about the Gridfinity specification at <a href="https://gridfinity.xyz/">Gridfinity.xyz</a>.


# Features
- A graphical drag-and-drop UI for quickly rearranging your bins
- A hierachical system based on "Drawers" and "Bins". Create a drawer of any given grid size, then create bins of specific X and Y sizes within those drawers.
- Assign custom colors to your bins (mine are all orange, but yours can be any color you want).
- Add custom attributes to each bin, such as hardware specifications, Amazon product URLs, or any other detail you want to track
- Import and export as JSON, allowing you to backup your layouts, edit them in other applications, or perhaps even use a custom LLM tool calling process to query an AI about your inventory (more details on that coming soon)


# Drag and Drop!
<img src="https://raw.githubusercontent.com/TMarski/Gridfinity_Mapper/refs/heads/main/assets/Gridfinity_mapper_drag_n_drop.gif" width=50% height=50%>


# Color-Code!
<img src="https://github.com/TMarski/Gridfinity_Mapper/blob/main/assets/Gridfinity_mapper_drawer_layout.png" width=50% height=50%>


# Customize!
<img src="https://raw.githubusercontent.com/TMarski/Gridfinity_Mapper/refs/heads/main/assets/Gridfinity_mapper_bin_json.png" width=25% height=25%>


# Quick Start Guide
- First, define a Drawer by setting the Drawer name and size, then click on Add Drawer.
- Next you'll create your first bin. Click anywhere on the grid to set the location of the upper left corner of the bin. Optionally label the bin.
- With a bin selected, you can use the menu on the right side of the screen to set the bin's color, add notes, create custom JSON attributes, or resize it. Make sure to click Save.
- You can also move or duplicate the bin to the Holding Area. The Holding Area is a list of bins which are not assigned to any drawer. This is useful for moving a bin between drawers, or for making space if you have a gridlock situation while organizing a full drawer.
- When you're done, you can use the menu on the left hand side to Import or Export a JSON file.



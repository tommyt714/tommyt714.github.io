<html>
<body>
   <h1>Welcome</h1>
   <p>Thanks for checking out my personal website!  You've found the funneled intersection of my personal and professional interests
      ranging from engineering to cocktails, all steeped in a background mission of ecological sustainability and environmental justice.
      Feel free to poke around, check out my code tinkerings, give me a follow if you'd like.
   </p>
   <center><cite>All I want is to save the world</cite></center>
   <br>
   <h2>Personal Links</h2>
   <a href="mailto:tommythompson714@gmail.com">Email</a><br>
   <a href="https://www.linkedin.com/in/thomas-thompson-pe/">LinkedIn</a><br>
   <a href="https://www.github.com/tommyt714/">GitHub</a><br>
   <a href="https://www.kaggle.com/cobo714/">Kaggle</a>
   <hr>
   <h1>Pet Projects</h1>
   <h2>Collingswood ADA Curb Ramp Assessment</h2>
   <a href="https://github.com/tommyt714/CollingswoodADA">CollingswoodADA Repository</a>
   <a href="https://www.kaggle.com/cobo714/collingswoodada">Jupyter Notebook on Kaggle</a>
   <br>
   <br>
   <p>The Americans with Disabilities Act of 1990 (ADA) regulates standards for pedestrian civil infrastructure such as doorways, sidewalks,
      parking lots, and access ramps.  Curb ramps are shallowly sloped transitions typically between a pedestrian walkway and a roadway,
      such as at the corners of a four-way intersection.  Curb ramps have set design standards for how steep they can be (in both directions),
      the directions they face, and the types to be used in different scenarios.</p>
   <p>In Collingswood, NJ, a suburb of Philadelphia, all curb ramps within a half-mile radius of the local train (PATCO) station were
      inspected for compliance with ADA.  Over 400 ramps were observed with over 250 marked as non-compliant for a variety of reasons.
      Using the GeoPandas and Folium packages in Python, the ramps were mapped to allow for a geospatial analysis of ADA compliance.
      Future work includes implementing a functionality to determine the most efficient route from any given point to the train station using
      only compliant ramps and running it through a public web application.
   </p>
   <img src="GoodBad_map.png" alt="Map of Collingswood, NJ with blue, half-mile radius circle centered around train station and green and red markers
                                   depicting compliant and non-compliant ADA curb ramps, respectively">
   <br>
   <h2>State Point Analysis Optimization</h2>
   <a href="https://github.com/tommyt714/WastewaterStatePointAnalysis">WastewaterStatePointAnalysis Repository</a>
   <br>
   <br>
   <p>State Point Analysis (SPA) is a graphical-analytical model of secondary sedimentation in an activated sludge wastewater treatment process.
      It allows the operator to visualize the settling characteristics of the solids in secondary clarifiers as they compare to the hydraulic
      properties of the tanks??? influent.  Ultimately, the operator can use the results of the analysis to optimize secondary treatment on the
      basis of the return activated sludge (RAS) flow rate.</p>
   <p>While usually a visual tool, SPA has been integrated preliminarily into a program that takes certain input parameters and analytically
      calculates the optimal return activated sludge flow rate for ideal and most efficient operation.  Naturally, this model is a
      simplification of a complex and dynamic treatment process and involves multiple assumptions/idealizations.  It is intended, however,
      to act as a conservative guideline to improve ease of operation, ensure stability of the sludge blanket and food-to-mass ratios,
      and maximize energy efficiency related to the oxygen transfer of the aeration system.
   </p>
   <img src="SPA_graph_descriptor.png" alt="Plotted state point analysis curves including labels for each key feature">
   <br>
   <h2>LabSolutions Output Parsing</h2>
   <a href="https://github.com/tommyt714/ParsingLabSolutionsASCIIOutput">ParsingLabSolutionsASCIIOutput Forked Repository</a>
   <br>
   <br>
   <p>The original purpose of this script is to resolve a bug in the data management software of a major scientific instrumentation
      company???s High Performance Liquid Chromatography (HPLC) machine that would cause the system to output incorrect data in the more readable,
      tabular format but correct data in the raw ASCII files when using bracketed standards.  Therefore, this script receives as input the
      ASCII files containing the correct data and outputs a single text file containing all of the samples, elutants, and their concentrations in a table.</p>
   <p>The Python version of ASCIItoTable is intended to be a more user- and software-friendly update to the original script written in
      Excel 2010's VBA.  An improvement was deemed necessary as a result of regular software updates and new versions of the Microsoft Office
      suite causing bugs in the original script that could only be resolved with tedious code adjustments and/or toggling of specific references
      in the IDE. The original version also did not allow for easy accessibility on unix-based operating systems such as Mac OS or Linux.
      Python was ultimately chosen for its popularity and ubiquity and its simple portability between operating systems as well as the ease-of-use
      of its I/O and string manipulation capabilities, especially with the desired inputs and outputs being merely text files.
   </p>
   <a href="https://www.researchgate.net/publication/295891707_Automated_Parsing_of_a_LabSolutions_Batch_Results_File_ASCII_Output_When_Using_a_Spreadsheet_or_Statistical_Package_to_Summarize_Data">Check out the published white paper here!</a>
   <br>
   <br>
   <h2>Snake PyGame</h2>
   <a href="https://github.com/tommyt714/PythonInPython">PythonInPython Repository</a>
   <br>
   <br>
   <p>Snake is a classic video game style that became greatly popularized by its inclusion on Nokia cell phones in the late 1990s.
      The concept is quite simple: the player controls a constantly moving, linear avatar (the snake) around a two-dimensional play area with the
      goal of consuming dots (mice) that appear randomly one at a time around the area.  The snake can only turn at 90-degree angles, and any
      collision with its own body (and sometimes the walls) results in a game over.  Each mouse extends the snake???s body, thus making the gameplay
      increasingly difficult.</p>
   <p>Pygame is a Python package designed for streamlining the development of smaller-scale video games.  In order to further develop my familiarity
      with the Python language, I resolved myself to recreate Snake using this package???s graphical modules.  Future work includes finishing other
      Pygame-based classics such as clones of Pac-Man, Tetris, and Breakout and hosting them all on a single digital arcade-like web application.
   </p>
   <br>
   <hr>
   <h1>Mixology</h1>
   <span>Instagram: <a href="https://www.instagram.com/theetohexperiment/">@TheEtOHExperiment</a></span>
   <br>
   <br>
      <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/CDTmnPMnJ4U/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-version="13" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:16px;"> <a href="https://www.instagram.com/p/CDTmnPMnJ4U/?utm_source=ig_embed&amp;utm_campaign=loading" style=" background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" target="_blank"> <div style=" display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg width="50px" height="50px" viewBox="0 0 60 60" version="1.1" xmlns="https://www.w3.org/2000/svg" xmlns:xlink="https://www.w3.org/1999/xlink"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g transform="translate(-511.000000, -20.000000)" fill="#000000"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style=" color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;"> View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style=" background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style=" width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style=" width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style=" background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style=" width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style=" background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a href="https://www.instagram.com/p/CDTmnPMnJ4U/?utm_source=ig_embed&amp;utm_campaign=loading" style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" target="_blank">A post shared by Tommy Thompson (@theetohexperiment)</a></p></div></blockquote> <script async src="//www.instagram.com/embed.js"></script>
   <hr>
   <h1>About Me</h1>
   <a href="resume_current.pdf?raw=true" download="Thompson_resume">Download My R&eacute;sum&eacute;!</a><br>
   <br>
   <p>My name is Tommy Thompson, and I'm a licensed Professional Environmental Engineer, 
      passionate coder, and home mixologist living in the Greater Philadelphia area.  I'm currently looking to make the complete career
      metamorphosis into Software Development/Data Analytics because silently screaming and cursing at my computer screen may well be
      the only kind of productivity that sparks true joy in me.  Until I achieve that dream, I'll keep toying around on here and on
      Kaggle.com to try to make sense of the world while simultaneously changing it for the better.
   </p>
</body>
</html>

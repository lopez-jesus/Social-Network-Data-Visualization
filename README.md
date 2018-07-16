# Social-Network-Data-Visualization
This projects builds upon the previous one we completed: "Classifying Nobel Prize Physicists by Physics Field.  In that project, we assigned each Nobel Prize Physicist to one of 6 physics subfields. We will extend that by graphically representing all these physicists and physics subfields as a social network.

To open and view the social network, you must download the .html and .json files. You can view  small_network.json by opening small_network.html. You can view the physicists.json file by opening the index.html file.

NOTE: For this to work, the .json files MUST be inside a folder named "data", which is itself inside a folder which contains the .html files. Otherwise, the visualization will not work.

Recommend browser to view these .html files is Firefox.

When you open up the index.html file, you will see a social network. Each circle represents either a physicist ("red") or domain ("blue"). Additionally, clicking on one of them will highlight the 8 closest connections. The size of each circle is determined by how many words were in the corresponding Wikipedia entry.

The .ipynb contains the code used to produce these social networks.

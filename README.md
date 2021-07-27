# protviewer - Work in progress
3D protein visualisation for exploration of Uniprot annotations on PDB and SwissModel protein structures.

Idea is to create an easy and fast way for students to explore sequence annotations in a structural context. Search for a gene with a UniProt accession code, then select either an experimental structure from the PDB or a homology model from the SWISS-MODEL respository if available.

![image](https://user-images.githubusercontent.com/25435513/125088953-d31cef00-e0c5-11eb-98c7-732edea32a11.png)

A variety of annotations can be displayed, more to be added.

Large degree of control over the viewer, including representations, colors, showing contacts within a range of a selected residue etc.

More to be added. Good amount of errors and issues.

Currently being written as an electron app. A web based version will probably be available once I bother to sort out web hosting.

# If you want to run it...

You will need Node.js and npm installed. In the folder you download all the files to, open a terminal and type "npm start" - this will hopefully start up the app.

If you have problems feel free to get in contact, although I can't guarantee I'll be able to respond/help in any reasonable amount of time.

# Acknowledgements

If you use this for anything, please cite these libraries/software.

* 3D protein visualisation using NGLviewer (https://github.com/nglviewer/ngl)

  * AS Rose, AR Bradley, Y Valasatava, JM Duarte, A Prlić and PW Rose. NGL viewer: web-based molecular graphics for large complexes. Bioinformatics: bty419, 2018. doi:10.1093/bioinformatics/bty419
  * AS Rose and PW Hildebrand. NGL Viewer: a web application for molecular visualization. Nucl Acids Res (1 July 2015) 43 (W1): W576-W579 first published online April 29, 2015. doi:10.1093/nar/gkv402

* Sequence manipulation suite (https://www.bioinformatics.org/sms2/)

* xml-js (https://github.com/nashwaan/xml-js)


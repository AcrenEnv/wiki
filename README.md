# Welcome to Acren
Acren is a decentralized platform that allows transparent and safe donation for environmental protection.
Through Acren, donors and farmers who want to implement environmental protection measures (EPM) are directly connected. Donors are given the opportunity to donate for environmental protection measures and farmers will implement these. A DApp ensures that the entire donation process is safe, transparent and traceable.
A verification process ensures that the farmers provide the environmental protection measures.

# This wiki
This wiki presents the individual components of the Acren platform in an easily understandable way. This wiki contains general and detailed concepts, explanations and guides. It contains all necessary technical specifications, but also high-level descriptions of the platform and processes.

This wiki was created with MKdocs [http://www.mkdocs.org/](http://www.mkdocs.org/). As theme the Material theme [https://squidfunk.github.io/mkdocs-material/](https://squidfunk.github.io/mkdocs-material/) was used.

# Access
This wiki can be accessed online at https://wiki.acren.org.
For local installation and collaboration in the wiki, please follow the instructions in the following tutorial.

## Local installation of Acren wiki
Der The easiest way to set up this Wiki locally is to install MKdocs ([http://www.mkdocs.org/](http://www.mkdocs.org/)) and Material theme ([https://squidfunk.github.io/mkdocs-material/](https://squidfunk.github.io/mkdocs-material/)):

1. Install Python3 (and set the PATH environment variable)
[https://www.python.org/](https://www.python.org/)
2. Install Mkdocs
``pip3 install mkdocs``
3. Install Material Theme
``pip3 install mkdocs-material``

Please check the version of mkdocs with ``mkdocs --version``
You should use a mkdocs version >= 0.17.5. Older versions (e.g. 0.16.2) may cause problems.

After installing MKDocs and Material Theme, the local version can be accessed from the cloned folder with command ``mkdocs serve``.
The locally installed wiki will be accessible via http://127.0.0.1:8000.

## Contributing
**Contributing content is very easy!** Just edit the files contained in the wiki directory.

You can edit the files either directly on GitHub, or clone the project and push changes to a separate branch.

## User Guide
See a detailed guide here: [http://www.mkdocs.org/user-guide/writing-your-docs/](http://www.mkdocs.org/user-guide/writing-your-docs/)

**Please Note:** Before considering a new page, pls look at the wiki structure and see if it fits as an addendum to an existing article or consider if your content may be suited for the **FAQ**, or the **glossary**

### To add a new page:
  1 - Create a new markdown file (.md) in a subfolder of /wiki/

  2 - Add a new entry that points to your newly created file under the **nav-section** in *mkdocs.yml*

### To add a new category:
  1 - Create a subfolder in /wiki/

  2 - Add a new entry that points to your newly created folder under  the **nav-section** in *mkdocs.yml*

### Images:
  To add an image first upload it to /images/subfolder/, then insert a link to the file in your document:

  ```![ImageName](image/subfolder/imagefile.png)```
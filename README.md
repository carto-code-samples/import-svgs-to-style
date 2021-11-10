# import-svgs-to-style
Imports a folder of SVG files into an ArcGIS Pro style. The new .stylx file is saved in the same folder as the .svg files. 

### Requirements
- ArcGIS Pro version 2.8

### To use:
- After installing this add-in, open ArcGIS Pro and go to the Add-In tab. 
- Click the Import SVGs To Style button, navigate to and select a folder that contains .svg files, then click OK. 
- A new style file will be created in the same folder as the .svg files and automatially added to the current project. 

### To install:
Clone this repository and double-click the .esriAddinX file located here to install the add-in:

`..\import-svgs-to-style\ImportSVGsToStyle\bin\Debug\SetPointRotationToAngleField.esriAddinX`

To install without cloning this repository, download that individual file from this repo and run it:

https://github.com/carto-code-samples/import-svgs-to-style/blob/main/ImportSVGsToStyle/bin/Debug/ImportSVGsToStyle.esriAddinX

### To modify:
Install Visual Studio 2019 and the ArcGIS Pro SDK for developers following the instructions in this repo:

https://github.com/Esri/arcgis-pro-sdk/wiki/ProGuide-Installation-and-Upgrade

Clone this repository and open the solution file inside the main folder named ImportSVGsToStyle.sln

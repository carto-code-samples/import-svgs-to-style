# import-svgs-to-style
Imports a folder of SVG files into an ArcGIS Pro style. The new .stylx file is saved in the same folder as the .svg files. 

### Requirements
- ArcGIS Pro versions 2.8, 2.9, 3.0

### To use:
- After installing this add-in, open ArcGIS Pro and go to the Add-In tab. 
- Click the Import SVGs To Style button, navigate to and select a folder that contains .svg files, then click OK. 
- A new style file will be created in the same folder as the .svg files and automatially added to the current project. 

### To install:
Clone this repository and double-click the correct .esriAddinX file for your version. It will then automatically be copied into your ArcGIS Pro Addins folder and will  be accessible in the Add-Ins tab in ArcGIS Pro the next time you open it.
- For Pro 2.8 and 2.9:
`..\import-svgs-to-style\v28\ImportSVGsToStyle\bin\Debug\SetPointRotationToAngleField.esriAddinX`
- For Pro 3.0:
`..\import-svgs-to-style\v30\ImportSVGsToStyle\bin\Debug\net6.0-windows\SetPointRotationToAngleField.esriAddinX`

To install without cloning this repository, download that individual file from this repo and run it.
- For Pro 2.8 and 2.9:
https://github.com/carto-code-samples/import-svgs-to-style/blob/main/v28/ImportSVGsToStyle/bin/Debug/ImportSVGsToStyle.esriAddinX
- For Pro 3.0:
https://github.com/carto-code-samples/import-svgs-to-style/blob/main/v30/ImportSVGsToStyle/bin/Debug/net6.0-windows/ImportSVGsToStyle.esriAddinX

### To modify:
Install Visual Studio 2022 and the ArcGIS Pro SDK for developers following the instructions in this repo:

https://github.com/Esri/arcgis-pro-sdk/wiki/ProGuide-Installation-and-Upgrade

Clone this repository and open the solution file inside the main folder named ImportSVGsToStyle.sln

# How to make a PCB (Toner transfer method)

The method of manufacturing a PCB using the toner transfer method is performs by printing a workpiece of PCB at a laser printer with using photo paper. After that, the image of the resulting blank is transferred to the copper clad board using clothes iron. The next step is etching the printed circuit board and preparing the mounting holes. Further, tinning of PCB is carried out and a layer of solder mask and silkscreen are applied. Instead of a solder mask, it is possible to apply a protective varnish.

## Required components
To manufacture a PCB you will need:

- Single-layer copper clad board which corresponding size of the designed PCB  
- Tool for trimming the PCB workpiece  
- Fine grained sandpaper  
- Glossy photo paper. Its size should be greater than or equal to the manufactured PCB  
- Clothes iron  
- Degreaser or solvent  
- Plastic or glass container for etching PCB  
- Hydrogen peroxide, 3% solution, 100 ml.  
- Citric acid, 30 g.  
- Table salt, 5 g.  
- Drill machine for drilling holes (in case of using TH components)  
- Drills, diameter 0.6 mm. and 1 mm. (in case of using TH components)  
- Liquid tin (optional)  
- Flux  
- Solder  

The manufacture of a PCB by **toner transfer method is based on the preliminary preparation of the template of the PCB and subsequent printing on photographic paper using a laser printer**. Next, the resulting image of the PCB is transferred to the copper clad board by heating. After that, the top part of the photo paper is removed, and the toner remains on the copper clad board. After that, etching and subsequent processing of the finished PCB is carried out.  

**This method is excellent for projects where there is no need for a low thickness of tracks, as well as for projects where there is no need to manufacture a large number of printed circuit boards (1-2 pieces)**. However, when using this method, there may be difficulties with the quality transfer of toner on the cooper clad board. In addition, this method is the cheapest if you have a laser printer at home.  

If you need to perform very tight placing of components or use a low thickness of the tracks, it is better to choose the photoresist method.  

As an example for the production of a PCB by toner transfer method, we will use the [Antenna Mini-Whip (TH)] module.

## Template preparation
First, go to the page of the module you are interested in on the EasyEDA website.  
![Module page](../Resources/PCB%20Toner%20transfer/PCB-1-Module-page.png)  

Select the Documents section, move down and click the "Open in Editor" button.  
![Open button](../Resources/PCB%20Toner%20transfer/PCB-2-Open-button.png)  

To prepare a future template, in the EasyEDA editor, choice PCB file and make: "Document -> Export -> PDF".  
![Template prepare](../Resources/PCB%20Toner%20transfer/PCB-3-Template-prepare.png)  

In the export settings, **you need to set the following parameters**:  
- Export option - PDF;  
- Layer type - Separated layer;  
- Color - Black on White;  

Layers settings:  
- TopLayer - export (true) - mirror (true);  
Other layers doesn't used.  
![Export settings](../Resources/PCB%20Toner%20transfer/PCB-4-Export-settings.png)  

After setting the above settings, click the "Export" button, after which the required file will be automatically downloaded. If the project has several PCB files, repeat this action for each of the files. In our example, we perform export for Antenna Mini-Whip PCB (TH) files: Main module and Antenna Mini-Whip PCB (TH): Power feed unit.  

The next step is to transfer the resulting images of PCBs to photo paper. Open the downloaded image files of the PCBs (I use Adobe Acrobat Reader DC) and print the received files using: File -> Print ... (Ctrl + P).  

At this stage, you need to set the following parameters:  
- Page Sizing & Handling - Push "Size" button and choice "Actual size";  
- Orientation - Portrait (This setting will set printing from the upper left corner of the paper);  

However, do not rush to print the template itself, you need additional settings.  
![Template print](../Resources/PCB%20Toner%20transfer/PCB-5-Template-print.png)  

Now you need to turn off the toner save function when printing (this is necessary in order to get more toner on the photographic paper and later on the PCB). To do this, you need to set this function in the settings of your printer before printing (for different printer models, the settings may vary).  
![Toner settings](../Resources/PCB%20Toner%20transfer/PCB-6-Toner-settings.png)  

Now you can insert photo paper into your printer and print the templates. After printing templates, do not touch the toner surface with your hands, as in this case the toner may not be transferred to the PCB.  
![Printed templates](../Resources/PCB%20Toner%20transfer/PCB-7-Printed-template.png)  

Now you need to gently trim the excess photo paper on the outer outline of the printed template.  
![Template trimming](../Resources/PCB%20Toner%20transfer/PCB-8-Template-trimming.png)  

Now you have ready templates for toner transfer, now prepare the copper clad board for the subsequent transfer of the toner. Cut the copper clad board according to the size of the printed template.  
![Copper clad board trimming](../Resources/PCB%20Toner%20transfer/PCB-9-Copper-clad-boadr-trimming.png)  

The resulting workpiece should be gently sanded with fine sandpaper to remove any oxides formed. Do not apply great effort and do not use coarse-grained sandpaper to avoid spoiling the workpiece.  
![Copper clad board sanding](../Resources/PCB%20Toner%20transfer/PCB-10-Copper-clad-boadr-sanding.png)  

Now, treat the surface of the workpiece with a solvent or degreaser. After this stage, do not touch the working copper surface with your hands.  
![Finish preparing](../Resources/PCB%20Toner%20transfer/PCB-11-Finish-preparing.png)  

Now you are ready to transfer the toner to the workpiece. Turn the clothes iron to the maximum temperature and wait for it to warm up. Place the printed pattern on top of your cut out workpiece.  
![Template placing](../Resources/PCB%20Toner%20transfer/PCB-12-Template-placing.png)  

Cover your workpiece with a sheet of plain paper and heating it for about 20 seconds. Do circular motions with an iron without applying significant effort.  
![Heating](../Resources/PCB%20Toner%20transfer/PCB-13-Heating.png)  

After the warm-up is over, place the warmer workpiece under the small press (I use several books) and allow the workpiece to cool completely (about 20 minutes).  
![Workpiece pressing](../Resources/PCB%20Toner%20transfer/PCB-14-Workpiece-pressing.png)  

The next step is to remove the top of the photo paper under which the toner remains. In a small basin pour water at room temperature and place the workpiece there for about 40 minutes.  
![Workpiece soaking](../Resources/PCB%20Toner%20transfer/PCB-15-Workpiece-soaking.png)  

After a lapse of 40 minutes, remove the workpiece from the water and gently, rolling with your fingers, remove the top layer of photo paper.  
![Paper remove](../Resources/PCB%20Toner%20transfer/PCB-16-Paper-remove.png)  

Now your workpiece is ready for etching. Prepare the etching solute according to the following instructions:
- Take a plastic or glass container and pour in it 100 ml of 3% hydrogen peroxide;
- Add 30 grams of citric acid;
- Add 5 grams of table salt.
Thoroughly mix the resulting solute until all components are completely dissolved.  

Place your workpiece in the prepared solute.  
![Performs etching](../Resources/PCB%20Toner%20transfer/PCB-17-Performs-etching.png)  



[Antenna Mini-Whip (TH)]: <https://easyeda.com/igor.nikolaevich.96/Antenna_Mini_Whip-d8935f151d3a4221a9a3aacae3acdb65>

Other articles:  
[How to export Gerber file from EasyEDA](./How%20to%20export%20Gerber%20file%20from%20EasyEDA.md)  
[How to order from JLCPCB](./How%20to%20order%20from%20JLCPCB.md)  
[How to order from LCSC](./How%20to%20order%20from%20LCSC.md)  
[How to make a PCB (Photoresist method)](./How%20to%20make%20a%20PCB%20(Photoresist%20method).md)  
[How to work with SDR receivers on Linux](./How%20to%20work%20with%20SDR%20receivers%20on%20Linux.md)
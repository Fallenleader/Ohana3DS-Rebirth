## **Ohana3DS Special Pikachu Edition**

### **What is Ohana3DS?**

Ohana3DS is a work in progress tool used to view, extract, and ultimately replace data from decrypted 3DS roms.

Examples of such are the ability to view Models, Textures, even some animations.

Ohana3DS aims to be a one stop shop for all 3DS rom viewing, extracting, editing needs.

The Rebirth variant is a C# recode of the original Ohana3DS which was coded in VB. Unlike its predecessor, it has many additional features, though is working on reimplimenting some of the older ones no longer available. Source for rebirth is located at:

https://github.com/gdkchan/Ohana3DS-Rebirth

Original Ohana3DS source code is no longer avaliable except through forked variations which should be considered obsolete.

### **What is the difference in this version?**

This version incorporates different patches and fixes explicitly geared towards extracting models, animations, and anything else pokemon related.

While I will attempt to push changes from vanilla Ohana on a regular basis, this should only be a last resort measure.

It should also be understood that this tool becomes completely obsolete when vanilla fully addresses many of its current issues that makes this version special for pokemon games.

I also plan to reimpliment a decryption option again, which has not been reintroduced since the original Ohana3ds.

### **How do I compile/Requirements to build?**

Visual Studio Community 2015

https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx

Download this source as a zip file, or obtain this source using GIT desktop.

If you downloaded the Zip, extract it to a folder somewhere on your computer.

Look for the "_Ohana3DS Rebirth.sln_" file, and open it in Visual Studio.

In the menu you will see a "build" option. Click this then click on "Build Ohana3DS Special Pikachu Edition".

Your build will be located in the bin folder inside the project folder.

### **Off topic, but who are you?**

The name's **Fallenleader**, I am learning as an Indie Game Developer, currently working on a 3D Pokemon PC/Android remake for the original Pokemon games Red/Blue that heavily depends on Ohana to rip models and animations.

### **Credits**
**Indirect contributors (people who shared code that was implimented in this build):**

GDKchan - original source
Quibilia - Support for PB and PK animations and Pokemon specific fixes to the DAE format.

**Direct contributers (people who submitted a pull request regardless if they indirectly contributed or not):**

Help out today!!!


### **Is there anything else to add?**

Yea, I will NOT be implimenting Quibilia"s DAE modifications for batch processing and packing textures into models.

While these features may be useful for some, this is counterproductive to the aim of this tool, which is to allow people to extract the formats for modification, not simply data mining or one stop shop.

This tool is more focused towards people who need these files seperate, such as animators, graphic artists and game designers who need the flexibility of seperate files for editing purposes, but specifically from the Pokemon games.

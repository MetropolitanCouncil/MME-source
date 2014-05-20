Minnesota Metadata Editor
==========

MME is a DotNet incarnation of a simple editor for GIS metadata XML files that adhere to the Minnesota Geographic Data Standard, MGMG2. 

####Version
    1.1.23

What it is
==========
The Minnesota Metadata Editor (MME) is a desktop application that is intended to simplify and expedite the process of developing geospatial metadata.  

The program operates as a standalone application that edits metadata XML files.

The MME allows users to create, edit and display metadata that adheres to the [Minnesota Geographic Metadata Guildelines (MGMG version 1.2)](http://www.mngeo.state.mn.us/committee/standards/mgmg/metadata.htm), an implementation of the Federal Geographic Data Committee's (FGDC's) Content Standard for Digital Geospatial Metadata (CSDGM).  

The MME is a customized version of the EPA Metadata Editor (EME) 3.1.1.  For more information on the EPA Metadata Editor, see [https://edg.epa.gov/EME/](https://edg.epa.gov/EME/). 

###How you use it

It always helps to read the help: http://www.mngeo.state.mn.us/chouse/mme/Minnesota_Metadata_Editor_Help.pdf.

MME can be installed and run in several modes:

####As an installed application 
MME can be installed as a normal Windows program executable from the start menu. After installation, a local copy of the application database is created from the program's \template directory on first run for each user. The user's copy of the application database can then be further customized as needed per individual by selecting **Tools > Open Database**. 

 	Windows Administrative privileges are required on Windows 7 or 8 for this type of installation.

If you have installed the editor this way, then go to the Windows Start > Minnesota Metadata Editor to open it. 

An installed version of the MME always uses a local copy of the application database stored in the user's data directory. 

The first time an installed application is started, the user's local directory is checked for a copy of the database. If none is found, a new folder is added to the user's Documents local data directory and a copy of the contents the application's \template folder is made. The \template folder contains the metadata.mdb:

 **..\Minnesota Metadata Editor 1.1\template -> ..AppData\Roaming\MnGeo\Minnesota Metadata Editor\**

####As a portable application from your computer
Run as portable application, MME needs no installation. Just unzip the contents of the application to any folder on your computer Then open the folder and double-click **Minnesota Metadata Editor.exe** to run it. If you have MS Access installed on your computer, you can launch Access to edit the application database using Tools > Open Database from within the application.

####Setting up the MME Database

When you first install MME, it can be helpful to edit the MME Database to ensure that the defaults for the metadata fields match your specifications. Please see the help section titled 'Customizing the Metadata Editor Database' for more information on configuring the database with default values to meet your needs.



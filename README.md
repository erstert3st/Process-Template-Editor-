# Retired Visual Studio Extensions

Visual Studio 2017 has changed the hosting model for the extensions packages. Thus an extension has to be rebuild if it is to work with VS2017. This in turn may prevent the extension working with older versions of Visual Studio.

The problem could be partially addressed by allowing Visual Studio users to access older releases of the extensions when required. However it is problematic as Microsoft Visual Studio Market place allows access only to the latest release of a package. 

This repository is an attempt to soothe the pain by giving a shelter for the older versions of the active Visual Studio extensions. 

Found on https://www.omnibuscode.com/board/board_dev_t_tfs/38612
virustotal: https://www.virustotal.com/gui/file/3afc2d55197eac729387c5418425f5c203994231095dbc671252d94ac3f01321/detection

Download, 
<vs17InstallDir>\Common7\IDE>VSIXInstaller.exe "<PathTo>Microsoft.TeamFoundation.ProcessTools.TemplateEditorForTFS2017.vsix"



## Process Editor Tool

An extension to Visual Studio "2017" Community (and other versions) which provides a convenient method for viewing and updating process templates. The Process Editor also provides tools for updating global lists and work item types, as well as viewing the attributes of work item fields.  This tool was formerly provided via Team Foundation Server 2015 Power Tools (and earlier versions). This is a client extension which needs to be installed by each user locally for their own version of VS.

 

Summary of tools

Once installed, the Process Editor is accessible from the Visual Studio Tools menu. From it, you can access these four main tools:

Work Item Types: Import and export the XML definition file for a work item type (WIT)  
Process Template: Open and edit a process template (you can only edit the old-style work item forms, those that don’t reflect the new web layout)
Work Item Field Explorer: Review the list of fields and their attributes defined for a collection
Global List: Import and export a  global list XML definition file

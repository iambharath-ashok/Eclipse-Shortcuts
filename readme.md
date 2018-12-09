#  Eclipse Shortcuts and Productivity 

## 1.	Managing Multiple Workspaces

		1.	Working with multiple Eclipse Workspaces
		
			-	Working with multiple workspaces
			-	Create a short cut with -data "Workspace location"
			
				ex: c:\eclipse.exe -data C:\Projects\Workpsace\Java
				
		2.	Identifying which eclipse instances

			-	Sol : show the workspace location with full path
			
			-	Window -> Preferences -> General -> Window Title
			
		3.	Saving Scree Space by replacing common prefix for the packages
		
			-	Use the abbreviated package for the common prefix packages
			-	Saves the lot of screen space
		
		
			-	Window -> Preferences -> Java -> Appearance -> Abbreviate Package Names

			
		4.	Importing already installed plugins from existing Eclipse

			-	File -> Import -> From Existing Eclipse
			-	Export -> Installed items to a file
			
	
	
## 2.	Navigation

		1.	In-place Outline (Ctrl + 3)
		
			-	We can start searching directly what ever that comes to mind
			-	Searching from instant whole Eclipse
			
		2.	Hovers (Java > Editors > Hovers) 
		
			-	Press F3 to go the particular file 
			
			-	Press Ctrl + F3 Quick Outline of the file by placing caret on the required file
			
			-	Viewing the Java Doc if the warning are there
			
				-	Ctrl + Shift and hover on the warning 
				
			-	Viewing the Source code of the file 
			
				-	Press shift and hover on the file
		
			-	Vertical Ruler for Warnings
			
				-	Window -> Preferences -> Java -> Editor -> Hovers
				-	This will expand the vertical ruler for the overlapped warnings
				
		
		3.	Externalized Strings 	
		
			-	Ctrl + Click on the Property it will take to the source code where property has been used
		
		
		4.	Bookmark the important code 
		
			-	Imp code can be bookmark and view at bookmark section

			
## 3. 	Coding 

		1.	Show Annotations
		
			-	Show Annotations is used the commit history if code is connected with VCS
		
		
		2.	Block Selection Mode
		
			-	Very useful when editing a common section of code
			-	Enable by clicking on toggle block section button
			-	Alt + Shift + a
			
		3.  Formatter Profile

			-	Skipping few lines of code to get formatted
			-	Window -> Preferences -> Java -> Code Style -> Formatter
		
			
			
## 4.	Debugging

	1.	Smart Stepping to particular method
		
		-	Put caret on the particular method and press Ctl + F5
		-	Or click on Ctl + Alt + method
		-	No need to step in the series of method calls
	
			
	2.	Step filter

		-	Filtering the Stepping in to default classes
		-	Search directly ctlr +f3 and step and add the packages that needs to filter

	3.	Group the Breakpoints
	
		-	Group the break points by different views 
			
			-	Files
			-	Exceptions
			-	Bug
			-	We can create our own while working on the bug
			
	4.	Print-Points 
	
		-	Used in Debugging
		-	Used to Sysout the something to console while debugging
		-	No need to write a Sysout line 
		-	How to use
			
			-	Add a Debug point and update the debug the point with the Break Point properties
			
				-	Add the Sysout line
				-	Return False
				
				

				
				
## 5. 	Java 8 Development

	1.	Quick Assists
		
		-	Convert the Anonymous Inner class to Lambda Expression or Method Reference
		-	Select the section of code that has Anonymous Inner class and press Ctl +1 and choose to convert to  Lambda Expression or Method Reference
		-	To add types -> add inferred lambda parameter types
		
		
		-	short cut Ctl + 1


		
## 6.	Shortcuts
	
	1.	List all the shortcuts
	
	
		-	Ctrl + Shift + L - twice takes to keys sections
		-	In keys section we can modify the short cuts to our own custom one
		
	2.	Ctrl + Shift + p takes to matching braces
	3.	Ctrl + e to open all the opened editors
			

# WizBiz-ShoppingPortal
Shopping portal for the WizBiz startup company

Procedure:

naming standards for version control and files

	•	No Versioning is to be included in file names. All versioning is handled by Git.
	
	•	All files are to use no more than 32 characters, and use only numbers, letters and hyphens.
	
	•	All file names are to use the ‘kebab-case’ capitalisation style.
	
	•	Folder naming conventions are the same as file naming conventions mentioned above.

folder structures/file organisation

	•	All files are to be enclosed in a relevantly named folder, except for the license, readme and build files.
	
	•	Folder names are considered relevant if they accurately describe the contents of all files enclosed, in a concise and recognisable way.
	
	•	All file names should be simple words that precisely describe the purpose of the file

what determines a change of version?

	•	Use git tags for versioning.
	
	•	Apply semantic versioning rules in the [v.MAJOR.MINOR.PATCH] format.
	
	•	Any non-backwards compatible changes are considered a MAJOR change, and therefore the versioning should increment the MAJOR number.
	
	•	Any ADDITIONAL functionality that is still backwards compatible results in a MINOR incrementation.
	
	•	Any bug fixes simply increment the PATCH number by 1, grouped bug fixes should increment the patch number by 10.
	

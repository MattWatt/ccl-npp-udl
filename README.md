# ccl-npp-udl
User Defined Language(UDL) file for Notepad++ to provide syntax highlighting and code folding for Cerner CCL (Discern Explorer)

## Features
- Incorporates as many keywords as possible using official documentation
- Keywords are broken out into more distinct groups for individual styling.  
- Improved code folding (with exception of folding whole SELECT queries due to limitations of UDL 2.0)
- Requires Notepad++ 6.2 or greater ([supporting UDL 2.0](http://notepad-plus-plus.org/news/notepad-6.2-release-udl2.html))

## Install
- Download the `ccl.xml` file
- Open Notepad++
- Navigate to `Language -> Define your language...`, select `Import` and choose the `ccl.xml` file you downloaded.
- Restart Notepad++ and the **Language** menu will show the newly added language option at the bottom.
- Open a CCL file of your choice.

## Usage
Opening a CCL will with an extension of: .prg .ccl .inc .tst should automatically apply the CCL Language theme, or it can be manually selected through the **Language** menu.

## Notes
The stylings can be modified to your own preferences without having to recreate the keyword lists or groups.  I intentionally selected bold and distinguished color schemes for each grouping of like syntax.

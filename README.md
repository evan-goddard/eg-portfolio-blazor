# eg-portfolio-blazor
 Evan Goddard's Portfolio - Created with Blazor WebAssembly App

Website Link: https://evan-goddard.github.io/eg-portfolio-blazor/

To get the files from the Blazor WebAssembly Application, follow the below steps:

1. Right click on the Blazor WebAssembly App in the solution explorer of Visual Studio (NOT the solution, the app should one of the immediate items within the solution)
<br/>a. The symbol for the app should be a blue circle 'internet' symbol with a white (or black) rectangle 'page' behind it

2. Click the "Publish" option
<br/>a. This will open a new tab

3. If a profile does not exist, create a new profile and use the "Folder" option. This 'published to folder' will NOT be the github repo. It MUST be separate.
    
4. Click the "Publish" button of the folder profile
<br/>a. The "Publish" action will create one file and one folder in the desired folder. A "web.config" file and a "wwwroot" folder. We only need the "wwwroot" folder, whose contents are going to be the contents of the 'Github Pages' repo

5. Navigate to the published files and copy the contents of the "wwwroot" folder to the 'Github Pages' repo
<br/>a. It may be worthwhile to remove all the files from the local 'Github Pages' repo, so that were removed since the previous publish are removed
<br/>b. If doing 'a', do NOT remove the '.gitattributes', 'README', or the '.nojekyll' files!

6. Edit the 'index' file's < base href="" / > tag to read the base path of the 'Github Pages' repo
<br/>a. Example: < base href="/eg-portfolio-blazor/" / > (without spaces inbetween the angle brackets)


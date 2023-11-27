# Welcome to Reboot X

Here you'll find some useful links and data sources for the day!

CDI Hack Data.xlsx - This is a data dictionary that reflects data used to calculate the Consumer Digital Index. You can use it to create mock data - but please be clear this will only be dummy data and not reflect any real data.

Data set for homeless project.xlsx - This is sample data that relfects what a homeless charity might hold. You can create more mock data from it if you need to.

Constellation

Here is the link to access the documentation:
https://rebootxconstellation.z33.web.core.windows.net/setup/developers

And to download the package:
https://rebootxconstellation.z33.web.core.windows.net/downloads/constellation-core-0.11.6-reboot.0.tgz

You'll then need to update your package.json to reference the tar file. The path will be relative to where you have stored the tar file. Please save this outside of your project directory - the tar file should not be committed to GitHub. Altenatively, please ensure the file is added to your .gitignore so that it is not included in any commit history. You must delete this tar file after Reboot X is over.

    "@constellation/core": "file:./path/to/tarfile.tz",

You can then run either of the below commands depending on your package manager:
yarn add styled components
npm install --save styled-components








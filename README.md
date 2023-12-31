# Welcome to Reboot X

Here you'll find some useful links and data sources for the day!

<ins>Data Sources and Links</ins>

There are a couple of data sources in the root of this directory:

CDI Hack Data.xlsx - This is a data dictionary that reflects data used to calculate the Consumer Digital Index. You can use it to create mock data - but please be clear this will only be dummy data and not reflect any real data.

And the link to the Consumer Digital Index we just published:
https://www.lloydsbank.com/banking-with-us/whats-happening/consumer-digital-index.html

Data set for homeless project.xlsx - This is sample data that relfects what a homeless charity might hold. You can create more mock data from it if you need to.

<ins>Constellation</ins>

Please **do not use Constellation if you are assigned the Homeless Host challenge**, you will need to use an Open Source library - for example, MUI or Boostrap.

You can use create React app to start a new project, the documentation can be found here:
https://create-react-app.dev/docs/getting-started

Here is the link to access the documentation. Please note the setup is different than the documentation because we are outside of the LBG environment, the instructions can be found below to set it up locally.
https://rebootxconstellation.z33.web.core.windows.net/setup/developers

And to download the package:
https://rebootxconstellation.z33.web.core.windows.net/downloads/constellation-core-0.11.6-reboot.0.tgz

You'll then need to update your package.json to reference the tar file. The path will be relative to where you have stored the tar file. Please save this outside of your project directory - **the tar file should not be committed to GitHub**. Altenatively, please ensure the file is added to your .gitignore so that it is not included in any commit history. You must delete this tar file after Reboot X is over.

    "@constellation/core": "file:./path/to/tarfile.tgz",

You can then run either of the below commands depending on your package manager:

    yarn add styled components
    
or
    
    npm install --save styled-components

<ins>Challenges Wording</ins>

It's estimated that on any given night in the UK, around 2,500 people will sleep on the streets. Many homeless charities have networks of people who are willing to provide a bed for the night for those in crisis. Managing that availability, however, is time consuming and constantly changing. We'd like to invetsigate how we can use technology to simplify the process. Whatever we develop must be secure, easy to use and as automated as possible.

A growing number of people within the UK are digitally disadvantaged and under-confident when it comes to using online services. Come up with a way of creating a more inclusive and accessible digital banking experience to support people with different abilities and needs.

<ins>Judging Criteria</ins>

💡 The Idea 
Useful - Does the idea meet it's chosen challenge statement? How well does it serve our customers? Does it provide customer value?
Desirable - How novel is the idea? Does it replicate an existing solution?
Feasible - Is the idea achievable, realistic and possible to deploy as a product or service?
Viable - Could the solution provide genuine customer or business value?

➕ Potential Development
Roadmap - Do they have a view of what they would build if given more time and have a defined Minimum Viable Product
Complexity - Is there consideration of maintenance & serviceability and how easy would it be to take this into a production environment?
Ongoing Development - What further development possibilities have been identified?
Limitations - Have the team identified any problem areas of the application that would need to be resolved?

💻 Architecture & Use of Technology
Platform - Does the idea show good creative use of the available platform & technology? For example using Azure or Power Platform
Data - Have appropriate data sources been used?
Engineering - How complete is the solutions architecture and components e.g. front-end/back-end, APIs etc?
Security - Has any consideration been given to security? How data would be protected and mis-use of the solution?

🎨 Design & Inclusion
Available - Is the product or service considerate of a wide range of people - does it exclude use by anyone with different disabilities?
Useable - Is the product or service easy to interact with, so that users of all abilities have equitable experiences?
Personal - Is the product or services designed with individuals and their unique personal circumstances in mind, responding to and anticipating their needs?
Accessibility - Did the prototype make use of inclusive research, design and coding tools?

    








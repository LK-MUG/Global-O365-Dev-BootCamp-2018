# Pre-requisites for the bootcamp

# 1. Install a modern browser

Please ensure that you have one of [Chrome](https://www.google.com/chrome/), Edge, [Firefox] (https://www.mozilla.org/en-US/firefox/new/) or Safari installed as a few of the demos do not work in Internet Explorer.

# 2. Set up your SharePoint Framework development environment

## Install developer tools

### Install NodeJS

Install the [NodeJS LTS version](https://nodejs.org). 

### Install Visual Studio Code

You can use any code editor or IDE that supports client-side development to build your web parts. For our Office365 Bootbamp labs, we will be using [Visual Studio Code](https://code.visualstudio.com/)

### Install Git command line tools
Install the [Git source control tools](https://git-scm.com/)

## Clone our starter repo

### Create a working folder
Create a working folder where you want to work on the bootcamp SharePoint Framework labs. We recommend using a simple folder structure, something like "c:\Work\bootcamp" on Windows, or "~/code/bootcamp" on a Mac or Linux machine.

### Clone the repository from Github
Open a command prompt in your working folder, and then run the following command:
```sh
git clone https://github.com/LK-MUG/spfx_bootcamp_starter.git
```
### Install the npm packages
In your command prompt in the working folder, you need to run the following commands to install all the dependencies that the starter projects need.
```sh
cd spfx_bootcamp_starter
cd Session2_Github_Webpart
npm i
cd ..
cd Session4_Webpart_Using_MS_Graph
npm i
```

# 3. Setting Up  Office 365 PowerShell Components

### Install SharePointPnPPowerShellOnline or Office 365 CLI for the package deployment exercise

We would need one of the two options installed so we can automate our deployment pipeline. There will be a small exercise use one of the two tools bellow to deploy the solution you created on the Bootcamp. 

#### Option 1: How to install SharePointPnPPowerShellOnline and PowerShell 5.0 (supproted on Windows only)

Here is a manual on how to install SharePointPnPPowerShellOnline PowerShell module if you decided to use PowerShell. We will need it  for the solution deployment exercise.

[Install SharePointPnPPowerShellOnline, PowerShell 5.0 link](https://github.com/SharePoint/PnP-PowerShell/wiki/Install-SharePointPnPPowerShellOnline,-PowerShell-5.0-and-Nuget-behind-proxy)

#### Option 2: Install Office 365 CLI (supported on MAC, Windows, Linux)

If you prefer to use CLI tool and bash here is a manual on how to install Office 365 CLI. We will need it for the solution deployment exercise.

[Install Office 365 CLI link](https://aka.ms/o365cli)

# 4. (optional) Set up your Office 365 tenant

> [!NOTE] 
> We will supply shared logins for our dev Office tenant on the day. You're welcome to set up your own tenant but it is not required

To build and deploy PowerApps, Flows, and client-side web parts using the SharePoint Framework, you need an Office 365 tenant. 

If you don't have one, you can get an Office 365 developer subscription when you join the [Office 365 Developer Program]( https://developer.microsoft.com/office/dev-program?ocid=BootCamp2018_DevProg). See the [Office 365 Developer Program documentation](https://docs.microsoft.com/en-us/office/developer-program/office-365-developer-program) for step-by-step instructions about how to join the Office 365 Developer Program and sign up and configure your subscription.  

> [!NOTE] 
> Make sure that you are signed out of any existing Office 365 tenants before you sign up for the Office 365 Developer Program.

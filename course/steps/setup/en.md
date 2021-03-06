# Basic configurations

<a href="https://bit.ly/setup-vtex" target="_blank"><img src="https://user-images.githubusercontent.com/18701182/70204540-be18f680-16ff-11ea-994d-ef580767a673.png" 
alt="IMAGE ALT TEXT HERE" width="600" height="360" border="10" /></a>

> For your Mac setup video, [click here](https://bit.ly/setup-vtex-mac)

## Introduction 

Before getting your hands dirty and learning more about VTEX IO's Store Framework, you'll need to set up a few basic configurations, such as:

- Installing **Git**; 
- Installing **Toolbelt**; 
- **Logging into** a VTEX account;
- Creating a development **workspace**;
- **Linking** your local files to the platform.

Have a look at the step-by-step below for each of these configurations:

## Installing Git 

Install Git on your computer by clicking on the link below and selecting your operating system (Windows, MAC or Linux):

[https://git-scm.com/downloads](https://git-scm.com/downloads)


## Installing Toolbelt

**Toolbelt** is a VTEX **command line** tool. It allows you to perform any activity on the platform, such as creating a new development workspace, logging into a VTEX account, developing new apps, or managing already existing ones, etc.

Since it's Toolbelt that establishes the communication between the developer and the platform, you'll need it in order to perform all the activities put forward during the Store Framework course. 

1. Install [**Node.js**](https://nodejs.org/). If you are using a MAC, also install [**Yarn**](https://yarnpkg.com/);
2. Run `npm i -g vtex` in your terminal if you're using Windows or `yarn global add vtex` if you're using MAC;

Your can run `vtex-v` (Windows) or `vtex` (MAC) to confirm whether the Toolbelt installation was as expected.

Once successfully installed, your next step is to *log into* a VTEX account. 

## Logging in

1. Run `vtex login VTEXaccount` in your terminal, replacing `VTEXaccount` with the name of the account in which you want to work. For example, `vtex login appliancetheme`.

2. After *logging in*, run `vtex whoami` to confirm the account and workspace in which you find currently are.

Workspaces are nothing other than what the namesake suggests. On VTEX IO, accounts have three main workspace types, namely [master](https://vtex.io/docs/recipes/store/promoting-a-workspace-to-master), [production](https://vtex.io/docs/recipes/store/creating-a-production-workspace) and development. 

The next step is to create a development workspace, which will allow you to play with the configurations throughout the course without altering the store's final public version.

## Creating a development workspace 

1. Run `vtex use workspace-name`, replacing `workspace-name` with the desired name. For example, `vtex use devworkspace`.

### Accessing your workspace

After creating the workspace, you'll be able to access it at this link: `https://{workspace}--{account}.myvtex.com`, replacing `{workspace}` and `{conta}` with the name of the previously created workspace and account. For example, `https://devworkspace--appliancetheme.myvtex.com`

---

After setting up the basic configurations, you're ready to start the course!

## Click on Close Issue to continue

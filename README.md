Weather My Child's Way +RTP app - Web version
=========================================
The [Weather My Child's Way +RTP](https://weathermychildsway.rocks/) app is powered by Sequencing.com's [Sequencing.com's](https://sequencing.com/) [Real Time Personalization (RTP)](https://sequencing.com/developer-documentation/what-is-real-time-personalization-rtp/) technology. 

The app empowers parents with a daily, genetically tailored forecast for optimizing the health of their child. 

Contents
=========================================
* Editions
* Introduction
* Information flow
* Project
* Requirements
* Installation
* Configuration
* Troubleshooting
* Maintainers
* Contribute

Editions
=========================================
Weather My Way +RTP 
* Repo = https://github.com/SequencingDOTcom/Weather-My-Way-RTP-app
* App = https://weathermyway.rocks

Weather My Child's Way +RTP
* Repo = This repo
* App = https://weathermychildsway.rocks

Introduction
=========================================
The [Weather My Child's Way +RTP app](https://weathermychildsway.rocks/) codebase is a C# .NET implementation that shows how to combine real-time weather data with the genetic data from the child of the app user.

[Register for a free account](https://sequencing.com/user/register/) to learn more about Real-Time Personalization technology and gain full access to this technology. Development using RTP is free.

Information flow
========================================
1. App-user validates using Sign in with Sequencing.com.
2. If successful, app either auto-detects geographic location or user can manually input location. The app works for most locations throughout the world. 
3. Next, user selects a genetic file for analysis. Sample files are also provided. File selector code is open source and available here: https://github.com/SequencingDOTcom/File-Selector
4. The app will then be personalized to the genes of the child of the app user by combining an analysis of the child's genes with an analysis of the current weather forecast.
* Two [App Chains](https://sequencing.com/app-chains) that use Sequencing.com's API are utilized for this app: 
** Chain10 (Predisposition to skin cancer)
** Chain88 (Vitamin D supplements likely to protect health). will then process the user’s genes and combine it with real-time weather data. 
* Forecast screen contains both the weather forecast and the genetically tailored forecast, which is personalized insight to help the user optimize the health and wellness of his or her child.
* All analysis occurs in real-time.

Project
========================================
This codebase is supplied as a C# Visual Studio project with MVC as the coding pattern. The code included mainly three components

* Models: Implemented as C# class objects.
* Controllers: Implemented as C# class objects.
* Views: Implemented as HTML pages with basic templating and styling.

Requirements
======================================
The main requirement is installed Visual Studio or the free Visual Web Matrix that can be obtained from the following links

* Visual Web Matrix: http://www.microsoft.com/web/webmatrix/
* Visual Studio: http://www.visualstudio.com

We have included all the supporting binaries to execute the code. The following external binaries are used, if you require them separately.

* JSON .NET: https://json.codeplex.com/
* REST Sharp: http://restsharp.org/

Installation
======================================
The app is developed as a web application and so no installation as such is required. Simply clone this repository on your workstation/ computer and open the project in Visual Studio/ Visual Web Matrix. Then click the play button and you should be on your way. Then follow the screen instructions.

Configuration
======================================
There are no strict configurations that have to be performed. However, there are some settings while using the app.

Troubleshooting
======================================
* To experience the app, [register for a free account](https://sequencing.com/user/register/) and use your account credentials when running the demo. You may then access all developer tools and information directly from the [Developer Center](https://sequencing.com/developer-center/).
* Confirm all the dependency dlls loaded correctly.
* Confirm you are connected to the internet since the API calls will be made to our server and the weather data servers as well.
* Confirm you have the latest version of the code from this repository.

Maintainers
======================================
The codebase is actively maintained by [Sequencing.com](https://sequencing.com/). Please email the Sequencing.com bioinformatics team at gittaca@sequencing.com if you require any more information or just to say hola.

Contribute
======================================
We encourage you to passionately fork us. If interested in updating the master branch, please submit a pull request. If the changes contribute positively, we'll let it ride.

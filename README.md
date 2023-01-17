<!--

██████╗ ██╗ ██████╗ ███████╗ ██████╗ ███╗   ██╗
██╔══██╗██║██╔════╝ ██╔════╝██╔═══██╗████╗  ██║
██████╔╝██║██║  ███╗█████╗  ██║   ██║██╔██╗ ██║
██╔═══╝ ██║██║   ██║██╔══╝  ██║   ██║██║╚██╗██║
██║     ██║╚██████╔╝███████╗╚██████╔╝██║ ╚████║
╚═╝     ╚═╝ ╚═════╝ ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
                                               
██████╗  ██████╗ ███████╗███████╗███████╗      
██╔══██╗██╔═══██╗██╔════╝██╔════╝██╔════╝      
██████╔╝██║   ██║███████╗███████╗█████╗        
██╔═══╝ ██║   ██║╚════██║╚════██║██╔══╝        
██║     ╚██████╔╝███████║███████║███████╗      
╚═╝      ╚═════╝ ╚══════╝╚══════╝╚══════╝      

█████╗█████╗█████╗█████╗█████╗█████╗█████╗█████╗
╚════╝╚════╝╚════╝╚════╝╚════╝╚════╝╚════╝╚════╝
                                               
███╗   ███╗ █████╗ ██╗   ██╗████████╗██╗ ██████╗    
████╗ ████║██╔══██╗██║   ██║╚══██╔══╝██║██╔════╝    
██╔████╔██║███████║██║   ██║   ██║   ██║██║         
██║╚██╔╝██║██╔══██║██║   ██║   ██║   ██║██║         
██║ ╚═╝ ██║██║  ██║╚██████╔╝   ██║   ██║╚██████╗    
╚═╝     ╚═╝╚═╝  ╚═╝ ╚═════╝    ╚═╝   ╚═╝ ╚═════╝    
                                                    
████████╗██╗  ██╗███████╗███╗   ███╗███████╗
╚══██╔══╝██║  ██║██╔════╝████╗ ████║██╔════╝
   ██║   ███████║█████╗  ██╔████╔██║█████╗  
   ██║   ██╔══██║██╔══╝  ██║╚██╔╝██║██╔══╝  
   ██║   ██║  ██║███████╗██║ ╚═╝ ██║███████╗
   ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝     ╚═╝╚══════╝
                                                                                                                 

BY 		ANGELO <angelo@pigeonposse.com>
FOR 	PIGEONPOSSE.COM

-->

# Mautic Theme by PIGEONPOSSE™

[![License](https://img.shields.io/github/license/PigeonPosse/mautic-theme?color=blue&label=License&style=flat-square)](https://packagist.org/packages/pigeonposse/mautic-theme)
[![Version](https://img.shields.io/packagist/v/pigeonposse/mautic-theme?color=a1b858&label&style=flat-square)](https://packagist.org/packages/pigeonposse/mautic-theme)
[![Web](https://img.shields.io/badge/Web-grey?style=flat-square)](https://pigeonposse.com/) 
[![About us](https://img.shields.io/badge/About-us-grey?style=flat-square)](https://pigeonposse.com/?popup=about) 
[![Donate ko-fi](https://img.shields.io/badge/Donate-pink?style=flat-square)](https://pigeonposse.com/?popup=donate) 

## 🗒 Description

A theme for _Mautic_ developed by _PigeonPosse_.

## 🗝 Prerequisites

1. A [_Mautic_](https://www.mautic.org/) installation

## 🔑 Installation

The installation can be done in several ways like:

### ⚡️ Fast

1. **Download** github project.
2. **Compress** all the files in a ```.zip``` and name it ```pigeonposse-theme```
3. Go to the **themes** section of your _Mautic_
4. **Upload** your ```.zip``` file from the install field and press the install button,

### 📚 Manual

1. **Download or clone** this project into your _Mautic_ ```/themes``` folder.
2. **Clean** your _Mautic_ **cache**. There are two options to do that:
	- Remove cache folder "prod":
		```bash 
		# For Mautic 3.x: 
		rm -r {YourMauticDirectory}/var/cache/prod 
		# For Mautic 2.x:
		rm -r {YourMauticDirectory}/app/cache/prod
		```
	- Execute Mautic cache command: 
		```bash
		# For Mautic 3.x: 
		php {YourMauticDirectory}/bin/console cache:clear
		# For Mautic 2.x:
		php {YourMauticDirectory}/app/console cache:clear
		```
3. You should now see the _PigeonPosse_ theme in your list of themes.

## ⚙️ Usage

The use of this theme is **like any other of Mautic**.

## 👨‍💻 Development

- About _Mautic_ development:

	[![Check docs](https://img.shields.io/badge/Check-docs-grey?style=flat-square)](https://developer.mautic.org/)

- About _Symfony_ development:
	
	[![Check docs](https://img.shields.io/badge/Check-docs-grey?style=flat-square)](https://symfony.com/doc)

## ☕ Donate

Help us to develop more interesting things.

[![Donate](https://img.shields.io/badge/Donate-grey?style=flat-square)](https://pigeonposse.com/?popup=donate) 

## 📝 History

Read about the history of the project.

[![Read more](https://img.shields.io/badge/Read-more-grey?style=flat-square)](https://github.com/PigeonPosse/mautic-theme/blob/main/HISTORY.md)

## 📜 License

This software is licensed with GPLv3 (GNU GENERAL PUBLIC LICENSE Version 3)

[![Read more](https://img.shields.io/badge/Read-more-grey?style=flat-square)](https://github.com/PigeonPosse/mautic-theme/blob/main/LICENSE)

## 🐦 About us

_PigeonPosse_ is a ✨ **code development collective** ✨ focused on creating practical and interesting tools that help developers and users enjoy a more agile and comfortable experience. Our projects cover various programming sectors and we do not have a thematic limitation in terms of projects.

[![More](https://img.shields.io/badge/Read-more-grey?style=flat-square)](https://github.com/PigeonPosse/PigeonPosse)

### Collaborators

|                                                                                    | Name        | Role         | GitHub                                         |
| ---------------------------------------------------------------------------------- | ----------- | ------------ | ---------------------------------------------- |
| <img src="https://github.com/AngelEspejo.png?size=72" style="border-radius:100%"/> | AngelEspejo | Author       | [@AngelEspejo](https://github.com/AngelEspejo) |
| <img src="https://github.com/PigeonPosse.png?size=72" style="border-radius:100%"/> | PigeonPosse | Collective	  | [@PigeonPosse](https://github.com/PigeonPosse) |


<br>


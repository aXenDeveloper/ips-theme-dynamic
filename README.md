![Header image](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/1.png)

# Dynamic Theme

(PSD) Graphic Theme - [Grzegorz](https://www.pecetowicz.pl/profile/32013-grzegorz/)

Built-in Font Awesome 5 icons.

## 🏷️ Requirements

- [IPS Community Suite: 4.7 version](https://invisioncommunity.com/)

## 🧰 Install

1. Go to: AdminCP -> Customization -> APPEARANCE -> **Themes**,  
   ![Select Plugin](https://files.axendev.net/github/theme/admincp_select.png)
2. Click on the **Create new** button,
   ![Create new](https://files.axendev.net/github/theme/create_new.png)
3. Click on the link **manual upload**,  
   ![Manual Upload](https://files.axendev.net/github/theme/manual_upload.png)
4. Select file **.xml** from packet and click next button,
5. Go to theme settings,
6. Go to **Global tab** and **select your IPS version**
   ![Manual Upload](https://files.axendev.net/projects/ips/themes/dynamic/version.png)

## 🛠️ Update

1. Go to: AdminCP -> Customization -> APPEARANCE -> **Themes**,  
   ![Select Plugin](https://files.axendev.net/github/theme/admincp_select.png)
2. Search your theme and click **Upload a new version**,  
   ![Upload a new version](https://files.axendev.net/github/theme/new_version_upload.png)
3. Select file **.xml** from packet and click upload button,
4. Go to theme settings,
5. Go to **Global tab** and **select your IPS version**
   ![Manual Upload](https://files.axendev.net/projects/ips/themes/dynamic/version.png)

## 🔨 Configuration

### Icons navBar

Example code:

```
nav .ipsNavBar_primary li[data-navext="Forums"] a::before {content: "\f015" !important;}
```

- **data-navext** - The name of the item menu. You can find it by clicking on F12 in the browser and selecting the item tab.!  
  ![data-navext](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/navBar_icons.png)
- **f015** - [Unicode Font Awesome 5](https://fontawesome.com/icons)

### Icons widgets

Example code:

```
.cWidgetContainer .ipsWidget[data-blockid*="forumStatistics"] .ipsWidget_title::before {content: "\f015";}
```

- **data-blockid** - The name of the item widget. You can find it by clicking on F12 in the browser and selecting the item tab.  
  ![data-blockid](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/widgets_icons.png)
- **f015** - [Unicode Font Awesome 5](https://fontawesome.com/icons)

## 🔧 Default settings

Buttons:

- **Primary button** - #5c64c5
- **Alternate button** - #8b69c2
- **Normal button** - #5c64c5
- **Light button** - #1b1d25
- **Light button font** - #5c64c5
- **Very light button** - #0b0c10
- **Very light button font** - #5c64c5
- **Button bar** - #1e2029
- **Link button** - #5c64c5
  Front-End Colors:
- **Brand Color** - #5c64c5
- **Body background** - #141519
- **Header Background** - #141519
- **Header Text** - #ffffff
- **Main Navigation Background** - #5c64c5
- **Main Navigation Text** - #888b98
- **Secondary Navigation Background** - #131419
- **Secondary Navigation Text** - #ffffff
- **Dark area background** - #0f1015
- **Area background** - #15161d
- **Light area background** - #17181f
- **Reset area background** - #111217
- **Selected** - #1d1727
- **Selected Border** - #8b69c2
- **Tags** - #8b69c2
- **Prefix** - #5c64c5
- **Widget Title Bar Text** - #ffffff
- **Moderated Light Background** - #210000
- **Moderated Text** - #bb5454
- **Activity Timeline Color** - #5c64c5
- **Item Status Badges Active** - #5c64c5
- **Mentions** - #5c64c5
- **Highlighted Post Background** - #8b69c2
- **Highlighted Post Border** - #5c64c5
- **Comment Count Background** - #22242d
- **Comment Count Font** - #ffffff
- **Active Input Border** - #5c64c5
  Text:
- **Base text color** - #888b98
- **Dark text** - #ffffff
- **Light text** - #55606f
- **Link color** - #959faf
- **Link hover color** - #5c64c5
- **Section title bar text** - #ffffff
- **Footer Links** - #656872
- **Tags** - #ffffff

## 📷 Screenshots

![2](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/2.png)
![3](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/3.png)
![4](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/4.png)
![5](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/5.png)
![6](https://raw.githubusercontent.com/aXenDeveloper/ips-theme-dynamic/master/screenshots/6.png)

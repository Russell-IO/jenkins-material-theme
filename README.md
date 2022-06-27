![image](https://russell-io.github.io/jenkins-material-theme/images/logo.svg)
# jenkins-material-theme
Beautify your Jenkins with the Material Design theme!

<a href='https://pledgie.com/campaigns/32522'><img alt='Click here to lend your support to: Jenkins Material Theme and make a donation at pledgie.com !' src='https://pledgie.com/campaigns/32522.png?skin_name=chrome' border='0' ></a>

Website: https://russell-io.github.io/jenkins-material-theme/
So you love **Jenkins** but hate its ugly user interface and icons... Me too! Introducing **Jenkins Material Theme**.
You can turn your favorite frog CI tool into a handsome prince in few steps!   
 
## Features
* Just one small css file (35K)
* Embed minified SVG images
* Multiple ways to install
* Customize the color and logo using the [generator][generator]

## Screenshots
[![Screenshot jenkins-material-theme main](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-main.png)](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-main-large.png)      [![Screenshot jenkins-material-theme legend](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-legend.png)](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-legend-large.png) [![Screenshot jenkins-material-theme console](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-console.png)](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-console-large.png)
[![Screenshot jenkins-material-theme history](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-history.png)](https://russell-io.github.io/jenkins-material-theme/images/screenshot-jenkins-theme-material-history-large.png)


## Installation 

### Using this GitHub page (recommended) (auto-updated)

1. Choose your color:
![image](https://russell-io.github.io/jenkins-material-theme/images/pallete.png)

2. Replace `{{your-color-name}}` in the URL by the chosen color: `https://russell-io.github.io/jenkins-material-theme/dist/material-{{your-color-name}}.css`

3. Install [Jenkins Simple Theme Plugin][simple]

4. Click `Manage Jenkins`

5. Click `Configure System` and scroll down to `Theme`

6. Set the CSS field to the generated URL.

7. Click `Save`


## Development

CSS file are minified and compressed with Grunt. To prepare the environment:

```
npm install
grunt
```

This will generate the following file:
- dist/material-light.css

## Compatibility
- Simple Theme plugin 0.3
- Jenkins 1.636
- Firefox 3.5+
- Chrome 4+
- Safari 4+
- Opera 15+
- Microsoft IE11 and Edge


If you are experiencing issues please let me know! Also, feel free to contribute!

## License
http://afonsof.mit-license.org/

## Thanks to
- [Simple Theme Plugin][simple] for the Simple Theme plugin
- [Google][google] for the the material design inspiration and the icons
- [Material Design Icons][material-design-icons] for some extra icons
- [Stylish][stylish] for making the test of new versions easy
- [canon-jenkins][canon-jenkins] for the base theme
- [@Heldroe][heldroe] for Firefox and Microsoft support
- [@bootstraponline][bootstraponline] for Jenkins native plugin

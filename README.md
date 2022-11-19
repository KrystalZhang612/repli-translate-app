# KrystalZhang-RepliTranslate App
My replica of Google Translate App, which is one of the greatest multi-language translator applications in the world that helped me a lot throughout my education. I built this App using HTML, CSS and Javascript in Vscode IDE.
## ***[Copyright and Commercial Use Disclaimer](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#please-carefully-read-licensemd-about-the-open-source-restrictions-and-the-personal-use-policy-of-this-project-under-gpl-30-license-any-commericial-uses-on-this-project-by-other-than-the-owner-krystalzhang612-or-the-authorized-users-and-organizations-including-unauthorized-modifications-forks-pull-requests-and-other-commercial-related-uses-will-be-subjected-to-copyright-violation-with-sebsequent-legal-concerns)***

⏬

### ***Please carefully read [LICENSE.md](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/LICENSE) about the Open Source restrictions and the personal use policy of this project under [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html), any commericial uses on this project by other than the owner [@KrystalZhang612](https://github.com/KrystalZhang612) or the authorized users and organizations, including unauthorized modifications, forks, pull requests, and other commercial-related uses will be subjected to copyright violation with sebsequent legal concerns.***

## RepliTranslate App Overview:
<div>
  <img src ="https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/RepliTranslate%20App%20Overview-1.png">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/RepliTranslate%20App%20Overview-2.png">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/RepliTranslate%20App%20Overview-3.png">&nbsp; 
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/RepliTranslate%20App%20Overview-4.png">&nbsp; 
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/RepliTranslate%20App%20Overview-5.png">&nbsp; 
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/RepliTranslate%20App%20Overview-6.png">&nbsp; 
</div>

# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#method-to-run--test-the-project-locally)<br/> 
[Prerequisites & Setups](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#prerequisites--setups)<br/> 
[Debugging&Troubleshooting](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#debuggingtroubleshooting)<br/> 
[Synchronous Developing Notes](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#synchronous-developing-notes)<br/> 
[Testing Result](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#testing-result)<br/> 
[Tags and Topics](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#tags-and-topics)<br/> 
# Contribution
[Author](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md#author)
# Functionalities/Demo
- Allows users to translate amongst different languages and obtain accurate translation results.
# Compatibility
|  Browsers          | Supported          |
| -------            | ------------------ |
| Google Chrome      | :white_check_mark: |
| Microsoft Edge     | :white_check_mark: |
| Firefox            | :white_check_mark: |
| Apple Safari       | :white_check_mark: |
| Opera              | :white_check_mark: |
| DuckDuckGo         | :white_check_mark: |
# Method to Run & Test the Project Locally
### `METHOD 1`: 
### Download the entire project to the local directory.
### Open the project with Vscode on local device.
### Install Vscode Extension [Live Server Vscode Extension v5.7.9](https://www.vsixhub.com/vsix/1950/)
### Click `Go Live` on the bottom bar to view and test the translate at http://127.0.0.1:5500/translatelanguage/
### `METHOD 2`:
### Have Node.js installed in your system.
### Use `cd` to navigate from Console at the project directory
### Run `npx http-server`
### Run and test the translator App at http://127.0.0.1:8080 or http://172.20.10.8:8080
### Hit CTRL-C to stop the server
# 🛠️  Developing Languages, Tools, and Techniques Needed
[Vscode 1.73.1](https://code.visualstudio.com/updates/v1_73)<br/>
[JavaScript](https://javascript.com)<br/> 
[HTML5](https://en.wikipedia.org/wiki/HTML5)<br/> 
[CSS3](https://en.wikipedia.org/wiki/CSS)<br/> 
[Live Server Vscode Extension v5.7.9](https://www.vsixhub.com/vsix/1950/)<br/>
<div>
  <img src = "https://github.com/devicons/devicon/blob/master/icons/visualstudio/visualstudio-plain.svg" title = "VSCODE" alt = "VSCODE" height = "60" width = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title = "Javascript" alt = "Javascript" height = "60" width = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title = "HTML5" alt = "HTML5" height = "60" width = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/css3/css3-original.svg" title = "CSS3" alt = "CSS3" height = "60" width = "60"/>&nbsp; 
</div>

# Prerequisites & Setups
Use `touch` command in the local Console to create needed files.
# Synchronous Developing Notes
Set up buttons for homepage in [index.html](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/translatelanguage/index.html):
```JavaScript
<div class = "hero">
        <p>About 3,470,000 results (0,22 seconds)</p>
        <button>TRANSLATE</button>
</div>
```
[index web server done setting up.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/index%20web%20server%20done%20setting%20up.png)<br/>
Insert input and output with their placeholders:
```JavaScript 
 <div class = "text-input">
       <textarea spellcheck="false" class = "form-text"
placeholder="Type text to translate..."></textarea>
       <textarea spellcheck="false" readonly disabled class =
"to-text" placeholder ="Translation"></textarea>
  </div>
```
[input and output text boxes initial looks.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/input%20and%20output%20textboxes%20initial%20look.png)<br/> 
Add CSS styles to make the translator align at center in [style.css](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/translatelanguage/style.css):
``` CSS
body {
    display: flex; padding: 0 10px;
    min-height: 100vh;
    align-items: center;
    justify-content: center;
    background: #85A6D4;
} .hero {
    max-width: 690px;
    width: 100%;
    padding: 30px;
    text-align: center;
    background: #fff;
```
[translator with better alignment.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/translator%20with%20better%20alignment.png)<br/> 
Add smooth radius effects to the button:
```CSS
.hero button {
    width: 30%;
    padding: 14px;
    border: none;
    margin-top: 9px;
    font-size: 17px;
    background: #85A6D4;
    border-radius: 100px;
    color: #fff;
    cursor: pointer;
}
```
[button with radius.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/button%20with%20radius.png)<br/>
Add a two-way switching arrow:
```CSS
 .button .change {
    color: #002fa7;
    font-size: 20px;
    cursor: pointer;
    transition: transform 0.2s ease;
}
.button i:active{
    transform: scale(0.9);
}
```
[two-way switching arrow.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/two%20way%20switching%20arrow.png)<br/>
Add groupy textarea styles:
```CSS
... .groupy {
    border: 2px solid #080808;
    background: #E0FFFF;
}
...
.text-input .to-text {
    border-left: 2px solid #080808;
}
.text-input textarea {
    resize: none;
    height: 100px;
    width: 100%;
    background: none;
    border: none;
    font-size: 18px;
    padding: 10px 15px;
```
[groupy textarea styles added.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/groupy%20textarea%20styles%20added.png)<br/>
# Debugging&Troubleshooting
ERROR: [countries.js](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/translatelanguage/countries.js) script and references not imported. DEBUGGING: order issue. In Index.html:
```JavaScript 
<script src="countries.js"></script>
<script src="script.js"></script>
```
import countries before scripts to make the countries references function.<br/>
[done implementing translator.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/done%20implementing%20translator.png)<br/> 
  
# Testing Result 
[index web server done setting up.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/index%20web%20server%20done%20setting%20up.png)<br/>
[input and output text boxes initial looks.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/input%20and%20output%20textboxes%20initial%20look.png)<br/> 
[translator with better alignment.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/translator%20with%20better%20alignment.png)<br/> 
[button with radius.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/button%20with%20radius.png)<br/>
[two-way switching arrow.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/two%20way%20switching%20arrow.png)<br/>
[groupy textarea styles added.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/groupy%20textarea%20styles%20added.png)<br/>
[done implementing translator.PNG](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/done%20implementing%20translator.png)<br/> 

# Tags and Topics 
node-js, front-end, vscode, npm-package, npx, localhost, css, html, javascript, translator-app. 

# Author
Krystal Zhang
https://github.com/KrystalZhang612<hr>
*This file was generated by [RepliTranslateApp-readme](https://github.com/KrystalZhang612/KrystalZhang-RepliTranslate-App/blob/main/README.md), on November 15th, 2022*

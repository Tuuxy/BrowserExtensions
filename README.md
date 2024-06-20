# The dangers of browser extensions 

## What are browser extensions ? 

Browser extensions are small software programs that customize and enhance the functionality of web browsers.

## Composition 

Extensions are often packaged as ZIP files containing JavaScript and other necessary files. They typically consist of several files, including at least a manifest.json and a content.js or background.js file.

- manifest.json 

It serves as metadata, detailing permissions, resources and other details required by browsers.

- content.js : 

Contains the executable javascript code that interacts with web pages. Most web pages use javascript for their front-end. 

## What can it do ? 

Anything javascript can !
It can manipulate DOM elements and modify pages dynamically, it can communicate with servers and databases, transmit user data or even receive instructions from outside sources.

Possibilities : 

- Spyware 
- Keylogger
- Access Private Data
- Alter HTML content and page appearances
- Inject Ads
- Compromise browser sessions
- Perform Cross-Site Scripting (XSS) attacks.
- Conduct Man-in-the-Middle (MitM) attacks.
- Perform Clickjacking attacks.
- Manipulate browser settings, such as changing the default search engine or homepage.


... And many more !

## How to protect against it ? 

- Read Permissions : Before installing an extension, review the permissions it requests. You can also check it at any time in the manifest.json.

- Source Verification : Prefer extensions from official stores. While not foolproof, these platforms generally examine extensions for security. 

- Code Review : Advanced users can examine extension code for suspicious activities. 

- Update : Keep browser and extensions up to date. Outdated extensions can have security vulnerabilities.

- Keep it simple : Limit the number of extensions installed. The more extensions, the higher the attack surface.

## Examples

--- WORK IN PROGRESS ---

Keylogger + Bypass 2FA 

------------------------

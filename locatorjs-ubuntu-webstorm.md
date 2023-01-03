# Set up LocatorJS for Webstorm on ubuntu

LocatorJS is an amazing tool that allows to to click through your react components in your browser and jump directly to your IDE.
Setting up is straigt forward but for webstorm on ubuntu, it was not working. This is how i fixed it.

- Install the Jetbrains toolbox
- Install Webstorm from the toolbox
- Install the LocatorJS chrome extension
- Open your react website. Click the extension icon on the top-right and select 'Custom'
- Set this as url scheme. Replace the [project-name] part with your own project name: 
```jetbrains://webstorm/navigate/reference?project=[project-name]&path=${projectPath}${filePath}:${line}:${column}```

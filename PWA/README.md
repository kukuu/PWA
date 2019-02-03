
# Progressive Web App

https://github.com/kukuu/AGILITY/blob/master/ProgressiveWebApp.md 

## Comments

The comments in the JS files this  serve to provide explanation for the script in some of its behaviour. There are cleaner versions labelled with the prefix light.

### Using Workbox by Google

The second half of the aplication uses Workbox by Google to improve performance and management. You realise the increase in volume of the dynamic assets as they cache. 

Also, there is no lazy loading in the first half of the application. You expect files which only change in the file system to be updated and not all files as it currently is.

i. npm i --save workbox-sw
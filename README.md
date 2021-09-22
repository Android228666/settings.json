# settings.json
{
"liveSassCompile.settings.formats": [
{         
"format": "expanded",
"extensionName": ".css",         
"savePath": "/css"       
},       
{         
"format": "compressed",
"extensionName": ".min.css",
"savePath": "/css"       
}     
],     
"liveSassCompile.settings.excludeList": ["**/node_modules/**", ".vscode/**"],     
"liveSassCompile.settings.generateMap": true,     
"liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"]   
}

Normalize:
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/0.6.0/modern-normalize.min.css"/>

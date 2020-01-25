# WurstBoostLib

1. Add File "settings.json" in ".vscode" folder
Example content:

{
  "wurst.javaOpts" : [ "-XX:+UseG1GC", "-XX:+UseStringDeduplication", "-XX:+AggressiveOpts", "-Xmx1G" ],
  "files.associations" : {
    "wurst.build" : "yaml"
  },
  "search.useIgnoreFiles" : false,
  "yaml.schemas" : {
    "./.vscode/wbschema.json" : "/wurst.build"
  },
  "wurst.wurstJar" : "C:\\Users\\dkinv\\.wurst\\wurstscript.jar",
  "wurst.wc3path" : "E:\\Gry\\Warcraft 3\\Warcraft III"
}

And edit for your own tego-tego
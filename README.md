# Minimalistic Java EE 8 / Jakarta EE + MicroProfile Quickstarter

A quickstart maven archetype for creating greenfield Java EE 8 / Jakarta EE project with MicroProfile 2+ APIs.


Fire up your CLI and type:
```mvn archetype:generate -Dfilter=com.airhacks:javaee8-essentials-archetype```
to create a fully fledged Java EE 8 "kB" project. Use the most recent version.

Also checkout: [mvn archetype:generate tuning](http://adambien.blog/roller/abien/entry/maven_archetype_generate_tuning)

In the IDE of your choice use the group ```com.airhacks```, then the artifact id ```javaee8-essentials-archetype``` and also select the most recent version.

Shortcut (copy and paste, replace ```PROJECT_NAME``` and ```GROUP_ID```):

```mvn archetype:generate -DarchetypeGroupId=com.airhacks -DarchetypeArtifactId=javaee8-essentials-archetype -DarchetypeVersion=0.0.4 -Darchetype.interactive=false --batch-mode -Dversion=0.0.1 -DgroupId=GROUP_ID -DartifactId=PROJECT_NAME```

The "Watch and Deploy" [WAD](https://github.com/AdamBien/wad) tool works best with this archetype. It continuously watches and deploys your ThinWAR without any additional configuration.

## Maven Archetype and wad.sh in Action

[![Jakarta EE / MicroProfile QuickStarter](https://i.ytimg.com/vi/8w_a-yEl2Wg/mqdefault.jpg)](https://www.youtube.com/embed/8w_a-yEl2Wg?rel=0)


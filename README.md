Idea Plugin Application Component Demo
===========================================

Init code when IDEA is starting, and also provide some functions across actions.

Run plugin in IDEA:
-------------------

```
./gradlew runIde
```

Build the plugin to a zip
-------------------------

```
./gradlew buildPlugin
```

It will generate the plugin file in `./build/distributions`

Notice
-------

- Use `version 'IC-2018.1.5'` every time to reduce download. (about 500M)
- Don't forget to change `id` and `name` in `resources/META-INF/plugin.xml` to current project
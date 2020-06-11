# jN Plugins

jN Plugins repository hosts the list of plugins which use jN to extend the Notepad++. These plugins can be
installed through the buildin plugin manager of jN-Npp-Plugin.

## How to publish new plugin

Fork this repository and add the link to your plugin in `plugins.json` then create pull request.

```
{
  ...
  'My Cool Plugin',{
    'description': 'My Cool Plugin',
    'url':  'https://github.com/myaccount/mycoolplugin/plugin.json',
    'version': '1.2.3'
  }
}
```

# qgis-pluginbuilder-minimalresult

This repo automates the release of a qgis -minimal- plugin, to be served by qgis-plugin-server

# steps
1. [Install QGIS](https://qgis.org/en/site/forusers/download.html)

2. [Install plugin builder](https://plugins.qgis.org/plugins/pluginbuilder3)

3. Run plugin builder to make the simplest plugin, each form is filled with the name to 
![builder-form](img/plugin_builder_form.png)
![manager-view](img/manage_and_install_plugins.png)
  
4. This one just display a web page adding [QWebEngineView](https://www.riverbankcomputing.com/static/Docs/PyQt5/api/qtwebenginewidgets/qwebengineview.html?highlight=qweb#QWebEngineView) through QtDesigner to the dialog. Plus a minor interaction...

6. Add the github action that zips and releases it


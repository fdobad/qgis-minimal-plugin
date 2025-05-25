# translation 

1. i18 directory contains

    es.ts <- es locale typescript file

2. a_translation_module.py calls on init

     locale = QSettings().value('locale/userLocale')[0:2]
     locale_path = os.path.join(
         self.plugin_dir,
         'i18n',
         'ATraslationClass_{}.qm'.format(locale))

3. scan for translation strings
    
    pylupdate5 a_translation_module.py -ts i18n/es.ts

4. compile translation strings

    lrelease i18n/es.ts -qm i18n/ATraslationClass_es.qm

        
/usr/share/qgis/python/plugins/processing/algs/gdal/GdalAlgorithm.py
/usr/share/qgis/python/plugins/processing/algs/gdal/GdalAlgorithmDialog.py
/usr/share/qgis/python/plugins/processing/algs/gdal/GdalAlgorithmProvider.py

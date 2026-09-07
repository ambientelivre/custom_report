# Custom Report for GLPI 
Allows you to use time posting in tasks to manage hours spent per customer using groups as customer separation.

Requirements
------------
GLPI 9.1.

Images
------------
Menu
------------
![image](https://github.com/ambientelivre/custom_report/assets/97977665/9f20d9c0-81d2-4a9e-a6c0-f8ed919b3840)

Relatório Suporte
-----------------
![image](https://github.com/ambientelivre/custom_report/assets/97977665/00d1e702-9e6a-43d6-a00d-2ca732b789d8)

Relatório Técnico
-----------------
![image](https://github.com/Migueldv06/miguel_custom_report/assets/97977665/dd64dc7c-5e07-4370-88eb-546c3186a9fa)


Installation
------------

This plugins installs as any other GLPI plugin.

1. Place the current source code tree in a directory named `customreport` and move this
   one inside the `plugins` directory of your GLPI installation.
2. Go to *Setup* > *Plugins*.
3. Look for the *Custom Report* plugin's row.
4. Click on the *Install* button.

Refresh the page and enjoy 

Uninstallation
--------------

This plugins uninstalls as any other GLPI plugin.

1. Go to *Setup* > *Plugins*.
2. Look for the *Custom Report* plugin's row.
3. Click on the *Uninstall* button.
4. Delete the `plugins/customreport` directory of your GLPI installation.

New Feature for 3.0 
--------------
For future!
* in this moment No support Groups Requiriments.
* i18N en.


## Author & Maintenance

Developed and maintained by **Miguel Domiciano Vieira** ([@Migueldv06](https://github.com/Migueldv06)),
GLPI specialist at [Ambiente Livre](https://www.ambientelivre.com.br).

Ambiente Livre has worked with the GLPI platform since 2008 and maintains this plugin as
part of its public contributions to the GLPI ecosystem.

## Compatibility

| Plugin version | Tested GLPI version |
|---|---|
| 1.x | 9.1+ |

> Update this table as you test against newer versions (10.x / 11.x) — listing only
> "GLPI 9.1" makes the plugin look unmaintained.

## Used In

This plugin has been used in GLPI implementation, customization and support projects
carried out by Ambiente Livre for public and private clients.

## Contributing

Suggestions, issues and pull requests are welcome. Please open an issue describing the
problem or proposed improvement.

## Support

- Website: https://www.ambientelivre.com.br

## License

Distributed under the GPL-3.0 license. See the [LICENCE](./LICENCE) file.

## Changelog

- **1.0** — Initial release: manage and track activity hours in GLPI using groups as
  customer separation.

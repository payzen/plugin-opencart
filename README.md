# PayZen for OpenCart

PayZen for OpenCart is an open source plugin that links e-commerce websites based on OpenCart to PayZen secure payment gateway developed by [Lyra Network](https://www.lyra.com/).

# Installation

- Unzip downloaded archive and copy the `upload` directory contents to your website root folder.
- Browse to `Extensions > Payments` in OpenCart Back Office.
- Click on the `Install (+)` button in the `Action` column of the desired PayZen payment method.

# Upgrade

To update the payment plugin, you must first uninstall and delete the previous version. Make sure you saved the parameters of your plugin before deleting it.

To uninstall the payment module: 

- Browse to `Extensions > Payments` in OpenCart Back Office.
- Search for the old version of the module, then click on the `Uninstall (-)` button.
- Manually delete files `payzen.php` and `payzen_multi.php` (folder `/admin/controller/extension/payment/`) via FTP.
- Please consult previous chapter `# Installation` to perform the module installation.

# Configuration

- Browse to `Extensions > Payments` in OpenCart Back Office.
- Click on the `Edit` button in the `Action` column of the desired PayZen payment method.
- You can now enter your gateway credentials.
- Click on the `Save` button.

## License

Each PayZen payment module for OpenCart source file included in this distribution is licensed under the GNU General Public License (GPL 3.0 or later).

Please see LICENSE.txt for the full text of the GPL 3.0 license. It is also available through the world-wide-web at this URL: http://www.gnu.org/licenses/gpl.html.
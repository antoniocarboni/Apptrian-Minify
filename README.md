# Apptrian-Minify v2.0.1 (Last Version) For Magento 1.x
### This is a composer installer version of Apptrian_Minify

#### Installation Instructions

If you are using Expire Headers before merging and minifying CSS/JS files you must disable Expire Headers. You can enable Expire Header after everything is merged, minifyed and tested to work.

- Log in to Magento Admin
- (Optional) Disable Magento Compiler if you are using it (System > Tools > Compilation)
- Go to (System > Magento Connect > Magento Connect Manager) and install extension
- Go back to Magento Admin
- Flush Magento Cache (System > Cache Management), then log out from Magento Admin and log back in
- (Optional) Enable Magento Compiler by clicking "Run Compilation Process" button (System > Tools > Compilation)
- Enable (System > Configuration > Developer > CSS Settings > Merge CSS Files)
- Enable (System > Configuration > Developer > JavaScript Settings > Merge JavaScript Files)
- Flush and Refresh Magento cache (System > Cache Management)
- Visit several pages of your site on the frontend and wait for them to fully load. (Visit home page, one CMS page, one category page, one product page, cart page, and checkout page. This is done so Magento default merger can merge CSS and JS files, and some extensions add CSS and/or JS files only on specific pages not globally.)
- Click Minify button and wait for CSS/JS files to be minified.
- (Optional) If you are using Expires header for CSS and JS files remember to empty your web browser's cache.
- (Optional) If you are using CDN make sure you flush/empty CDN cache.

If you have any questions send email at service@apptrian.com

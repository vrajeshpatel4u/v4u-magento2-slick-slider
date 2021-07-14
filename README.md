How to add slider using Slick in Magento2?

Download this module:V4U Slick

Copy this module and paste in magento-root/app/code folder

Run the following commands:

php bin/magento module:status

php bin/magento module:enable V4U_Slick

php bin/magento setup:upgrade

php bin/magento setup:static-content:deploy

php bin/magento cache:clean

You can call slider.phtml file in block by using

{{block class="Magento\Framework\View\Element\Template" template="V4U_Slick::slider.phtml"}}

How to use Slick slider in CMS Page and Block read the "How_to_add_slick_slider_magento2" file.

<b>Supports : Magento 2.0.x, 2.1.x, 2.2.x, 2.3.x and 2.4.x</b>

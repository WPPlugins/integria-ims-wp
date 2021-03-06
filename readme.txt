=== Integria IMS integration for Wordpress ===
Contributors: articast 
Tags: integria, leads, ticketing, support, crm, integration, customer support
Requires at least: 1.0
Tested up to: 1.0
Stable tag: 1.0
License: Apache License 2.0
License URI: https://www.apache.org/licenses/LICENSE-2.0

== Description ==

Use Wordpress pages to create support tickets directly in [Integria IMS help desk software](https://integriaims.com/en/product/help-desk-software/ "Integria IMS help desk software"). You can choose custom forms created with formidable and set the REST API integration do the rest for you. You can also use Integria IMS WP plugin to insert your leads in Integria IMS from a custom form. 

This plugin has been developed by [Integria IMS team](https://integriaims.com/ "Integria IMS team"). Sourcecode is available at [https://github.com/articaST/integriaims-wp/](https://github.com/articaST/integriaims-wp/ "https://github.com/articaST/integriaims-wp/")

Sections:

*	__Setup:__ here, you can set the data of your Integria:
	*	Integria API url: Copy here the url of your Integria.
	*	User ID: You can find it in menu 'People'. In the table, search 'User ID'.
	*	User pass: Your password for that user.
	*	API pass: In  Integria, go to gearwheel at top right, and search 'API Password'.
*	__Leads:__ here, you can create and delete forms to send to Integria to create leads.
	*	You must first specify here the form fields before inserting a form into a web page.
	*	When you create a form, remember to set the fields 'Name', 'Email' and 'Company' as required.
	*	Remember that if a form is already in the table, you can not re-create or modify it. You must delete it and create it again.
	*	You have to select a form to load the options.
	*	You can't put the same form field for several options.
	*	_"Create Leads"_
		*	Language: Valid values are:
			*	de: Deutch
			*	en_GB: English
			*	es: Spanish
			*	fr: French
			*	pl: polish
			*	ru: Rusian
			*	zh_CN: Chinese
		*	ID Product: You can find it in menu 'Support'. On the left, click the first icon and select 'Product types' and search 'ID' in the table.
*	__Tickets:__ here, you can create and delete forms to send to Integria to create tickets.
	*	You must first specify here the form fields before inserting a form into a web page.
	*	When you create a form, remember to set all the fields as required.
	*	Remember that if a form is already in the table, you can not re-create or modify it. You must delete it and create it again.
	*	You have to select a form to load the options.
	*	You can't put the same form field for several options.
	*	The text field prevails over the select field.
	*	_"Create Tickets"_
		*	Priority: Valid values are:
			*	10 → 0 Maintenance.
			*	0 → 1 Informative (default):
			*	1 → 2 Low.
			*	2 → 3 Medium.
			*	3 → 4 Serious.
			*	4 → 5 Very serious.

== Pre-requirements ==
*	You must have the [Formidable](https://es.wordpress.org/plugins/formidable/ "Formidable") plugin installed.

== Installation ==
1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. In the menu, below Settings, you will see 'IntegriaIMS WP'. Use it to configure the plugin.
4. Go to 'Setup' and fill the fields with your Integria data.
5. You can create forms with Formidable plugin to use later to create leads and tickets.
6. Go to Tickets or Leads and click the button Create to add the new form.
7. Insert the shortcode of the Formidable form in a page. Fill it, and send it to check if the lead/ticket is inserted correctly.

== Screenshots ==
1. This is the Setup Menu where you must configure your access credentials to Integria.
2. Here are the forms leads you have created.
3. Click the button "Create" to create a new form Lead, then Save Changes.
4. Here are the forms tickets you have created.
5. Click the button "Create Ticket" to create a new form Ticket, then Save Changes.
6. Create previously your forms with the plugin Formidable.


== Changelog ==


== Upgrade Notice ==




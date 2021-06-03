## ERPNext WooCommerce Connector

WooCommerce connector for ERPNext

This connector allows the synchronisation of items, stock, customers, addresses, sales orders, sales invoices and payment entries to a WooCommerce instance. (Note: I didn't test Sales Invoice and payment entries)

It requires the Frappe Framework and [ERPNext](https://erpnext.org).

This is the enhanced version of WooCommerce Connector by solving variant sync issue.


#### License

AGPL

#### Installation

On the ERPNext server, run

    $ cd /home/frappe/frappe-bench
	$ bench get-app https://github.com//aadhilpm/woocommerceconnector.git
	$ bench install-app woocommerceconnector




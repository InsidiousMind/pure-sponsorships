# Pure Charity Sponsorships Plugin

A collection of shortcodes to show sponsorships on your WordPress site.

It depends on the Pure Charity Base Plugin being installed and it's credentials configured to work.

## Features

* The plugin enables 3 shortcodes for use in any page you want to.
* Possibility to configure between 3 display styles.
* Possibility to configure the plugin to use custom fields you have on the app.
* Possibility to customize the main color of the elements.
* Possibility to add a custom image to show as brand on the views.

## Installation

1. Copy the `/purecharity-wp-sponsorships` folder to the `/wp-content/plugins` on your WP install
2. Activate the plugin through the 'Plugins' menu in WordPress
3. You're done!

## Shortcodes

### Sponsorships Listing
`[sponsorships program_id=X]`

Possible parameters:
* `program_id` - (Required) The id of the program to show
* `per_page` - The amount of records to fetch per page
* `reject` - (1,2,3) List of IDs of sponsorships to reject on the listing

### Single Child
`[sponsorship_child]`

Possible parameters:
* `child_id` - The id of the child to show

### Sponsorship Program
`[sponsorship id=X]`

Possible parameters:
* `id` - The sponsorship id

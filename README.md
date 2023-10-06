
# GJ5 Dictionary WordPress Plugin

## Overview

GJ5 Dictionary is a WordPress plugin designed to identify specific words in the posts' body and titles and wrap them in a special `span` class for translation. The plugin offers an admin interface to manage these words for different locales (US, AU, NZ).

## Features

- **Admin Panel**: Accessible by authors, editors, and administrators to manage the dictionary.
- **Word Replacement**: Automatically wraps specified words in posts with a `translate-block` class.
- **Role-based Access**: Only users with specific roles can access the admin panel.

## Installation

1. Download the plugin files.
2. Upload the plugin folder to your `/wp-content/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in WordPress.
4. Access the "GJ5 Dictionary" option in the admin menu to configure.

## Usage

### Admin Panel

1. Navigate to "GJ5 Dictionary" in the wp-admin.
2. You'll find three columns: "US", "AU", "NZ".
3. Enter the words specific to each locale.
4. Save your changes.

### Post Translation

1. The plugin automatically scans each post for the words specified in the admin panel.
2. It wraps those words with a `span` tag with the class `translate-block`.

## Requirements

- WordPress 4.0 or higher
- PHP 7.0 or higher
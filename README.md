# Happy QR reader - Wordpress plugin 

## Project Overview
This WordPress plugin adds a custom element/block that integrates a QR code reader. The QR code reader extracts URLs from QR codes, adds configurable parameters (retrieved from the user profile or other sources within WordPress), and automatically opens the modified URL.

## Features
Custom WordPress Element/Block:

A user-friendly element/block that can be easily added to any page within a WordPress site.

## QR Code Reader:
Seamlessly integrates within the WordPress block.
Accurately reads QR codes and extracts the embedded URL.

## URL Parameter Addition:
Extracts the URL from the QR code.
Optionally adds additional configurable parameters to the extracted URL.
Parameters are read from the user profile or other sources within WordPress.
Example parameters include Customer ID, Team ID, Game ID, Server ID, Controller ID, and UTM parameters.

## Auto-Open URL:
Automatically opens the modified URL after reading the QR code and adding the necessary optional parameters.

## Installation
Download the plugin files from this repository.
Upload the plugin files to your WordPress site's /wp-content/plugins/ directory.
Activate the plugin through the 'Plugins' menu in WordPress.

## Usage
Navigate to the page or post editor in your WordPress admin dashboard.
Add the custom QR code reader block to any page or post.
Configure the parameters to be added to the URL (these parameters will be retrieved from the user profile or other sources within WordPress).
Scan a QR code using the element/block.
The QR code reader will extract the URL, add the configured parameters, and automatically open the modified URL.

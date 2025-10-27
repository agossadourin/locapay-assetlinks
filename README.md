# LocaPay Business App Links Configuration

This project contains the configuration files for LocaPay Business app links (Digital Asset Links).

## Files

- `index.html` - Main page for the app links configuration
- `.well-known/assetlinks.json` - Digital Asset Links configuration for Android app verification
- `.well-known/apple-app-site-association` - Universal Links configuration for iOS app verification

## Purpose

This configuration allows the LocaPay Business Android and iOS apps to be verified as the default handler for specific URLs, enabling deep linking functionality.

## App Configuration

- **Package name (Android)**: `com.locapay.business1`
- **Domain**: `https://business.locapay.app`
- **Deep link route**: `/alert/:id`
- **SHA256 fingerprint**: `BA:6B...`

## Digital Asset Links

The `assetlinks.json` file contains the necessary configuration to verify the relationship between the LocaPay Business domain and the Android app (`com.locapay.business1`).

## Universal Links

The `apple-app-site-association` file contains the configuration for iOS Universal Links.

## Usage

Deploy this to your web server at `https://business.locapay.app` to enable app link verification for the LocaPay Business mobile application.

# locapay-assetlinks

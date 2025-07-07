# LocaPay App Links Configuration

This project contains the configuration files for LocaPay app links (Digital Asset Links).

## Files

- `index.html` - Main page for the app links configuration
- `.well-known/assetlinks.json` - Digital Asset Links configuration for Android app verification

## Purpose

This configuration allows the LocaPay Android app to be verified as the default handler for specific URLs, enabling deep linking functionality.

## Digital Asset Links

The `assetlinks.json` file contains the necessary configuration to verify the relationship between the LocaPay domain and the Android app (`com.locapay.locapay`).

## Usage

Deploy this to your web server at the root domain to enable app link verification for the LocaPay mobile application.

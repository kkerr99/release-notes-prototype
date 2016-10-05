+++
date = "2016-10-04T20:50:45-07:00"
draft = true
title = "Drupal Registration v7.x 2.13"

+++

Released: 07/08/2014

This release resolves two issues with setShare arguments used with the Janrain
Social Sharing component and adds support for Mobile WebView. Also, the
dependency on Fancybox is enforced only for legacy versions of Janrain
Registration.

# Changes

- The module now provides variables to the Janrain Social Sharing settings in
  the correct order.
  - Fixed
  - Deployment required
- The share widget used by the Drupal module now escapes single quotes in the
  title of a Drupal page.
  - Fixed
  - Deployment required
- Resolved an issue where a blank login page was rendered when viewing a
  Drupal site (with the Janrain module installed) inside of an iOS WebView 
  component. This must be enabled in Settings.
  - New
  - Configuration required
- The Fancybox dependency is no longer enforced for the latest version of
  Janrain registration.
  - Updated
  - Deployment required

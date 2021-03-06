Mobile: correct UI issue with tags that were longer than page width
Mobile: add advanved option to import dives from local cloud cache directories
Mobile: fix broken editing of location, suit, buddy, and dive master
Mobile: fix missing translations on Android
CSV export: support for multiple cylinders
CSV import: support for multiple cylinders for Subsurface CSV files
CSV import: multiple bug fixes for Subsurface CSV files
Mobile: convert entered email to lower case
desktop: localize salinity string with respect to thousands separators
desktop: update date and time fields on maintab if user changes preferences
mobile: small improvements to usability with dark theme
Core: improve service selection for BLE, adding white list and black list
Filter: fix searching for tags [#2842]
Desktop: fix plotting of thumbnails on profile [#2833]
Core: always include BT/BLE name, even for devices no recognized as dive computer
Core: fix failure to recognize several Aqualung BLE dive computers
Mobile: show dive tags on dive details page
Desktop: update SAC fields and other statistics when editing cylinders
Desktop: Reconnect the variations checkbox in planner
Desktop: add support for dive mode on CSV import and export
Desktop: fix profile display of planned dives with surface segments

libdivecomputer:
  - work around Pelagic BLE oddity (Oceanic Pro Plus X and Aqualung i770R)
  - OSTC3 firmware update improvements

---
* Always add new entries at the very top of this file above other existing entries and this note.
* Use this layout for new entries: `[Area]: [Details about the change] [reference thread / issue]`
# vim: textwidth=100

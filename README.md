# TinyMCE Video Lesson Plugin for Moodle™

The TinyMCE Video Lesson plugin adds an editor button that allows teachers to insert Video Lesson content directly into Moodle text editors.

It works in conjunction with the Video Lesson activity module (`mod_videolesson`) to simplify embedding video lesson content across the LMS.

---

## Purpose

This plugin enhances the Moodle TinyMCE editor by providing a dedicated button to insert Video Lesson content into:

- Course descriptions
- Labels
- Activity descriptions
- Page resources
- Any Moodle area that supports the TinyMCE editor

---

## Features

- TinyMCE editor integration
- One-click insertion of Video Lesson content
- Seamless integration with `mod_videolesson`
- Moodle-native implementation

---

## Requirements

- Moodle 4.4.12 or later
- TinyMCE editor enabled
- Video Lesson Activity (`mod_videolesson`) installed and configured
- Video Lesson Filter (`filter_videolesson`) enabled, if embedded Video Lesson content is rendered through Moodle text filtering

---

## Installation

1. Download the plugin ZIP file or clone this repository.
2. Rename the extracted folder to `videolesson` if needed.
3. Copy the folder to:  /path/to/moodle/lib/editor/tiny/plugins/videolesson
4. Log in to Moodle as an administrator.
5. Go to Site administration → Notifications and complete the installation.
6. Go to Site administration → Plugins → Text editors → Manage editors.
7. Ensure TinyMCE editor is enabled.
8. Ensure Video Lesson Activity (mod_videolesson) is installed and configured.

---

## Dependency

This plugin requires:

- `mod_videolesson`

Ensure the activity module is installed before using the TinyMCE integration.

---

## Documentation

For installation, configuration, and usage guides, see:
https://www.mooplugins.com/docs-category/video-lesson-activity/

---


## Release notes

### Version 1.0.0

Initial public release of TinyMCE Video Lesson Plugin for Moodle.

Included features:

- Added TinyMCE editor button for inserting Video Lesson content.
- Added integration with Video Lesson Activity (`mod_videolesson`).
- Added support for inserting Video Lesson content into course descriptions, labels, activity descriptions, Page resources, and other TinyMCE-supported text areas.
- Added Moodle-native TinyMCE plugin structure using the `tiny_videolesson` component.


---

## License

This plugin is licensed under the GNU GPL v3 or later.

See the LICENSE file for details.

---

Moodle™ is a registered trademark of Moodle Pty Ltd.  
This plugin is not affiliated with or endorsed by Moodle Pty Ltd.

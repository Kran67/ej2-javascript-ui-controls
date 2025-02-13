# Changelog

## [Unreleased]

## 28.1.39 (2024-01-14)

### PDF Parser

#### Bug Fixes

- Resolved an issue where the file size increases when exporting a rubber stamp annotation with an image and appearance using the XFDF format.

## 28.1.38 (2025-01-07)

### PDF Parser

#### Bug Fixes

- Resolved an issue that caused the application to crash when loading large data during the encoding process.
- Resolved an exception encountered while adding a line annotation with appearance and Unicode text when the caption is set to false.
- Resolved an issue where the file size increases when exporting a rubber stamp annotation with an image and appearance using the JSON format.

## 28.1.37 (2024-12-31)

### PDF Parser

#### Bug Fixes

- Resolved an issue with parsing annotations with appearance while export and import multiple times using the FDF format.
- Resolved an issue with preserving the popup annotation appearance during flattening.
- Resolved an issue where the text markup content entry was missing while exporting annotations using JSON and XFDF formats.

## 28.1.36 (2024-12-24)

### PDF Parser

#### Bug Fixes

- Resolved an issue with preserving radio button fields during flattening.
- Resolved the PDF document corruption issue while adding a new line annotation with appearance and rotation.

## 28.1.35 (2024-12-18)

### PDF Parser

#### Bug Fixes

- Resolved an issue with preserving images while splitting pages in a PDF document.
- Resolved an issue with retaining existing button fields when the flatten option is set to true.
- Resolved an issue with parsing comments from free-text annotations when importing multiple times using the XFDF format.
- Resolved an exception encountered while adding a newly created ink annotation to a PDF page.
- Resolved an issue with modifying the destination property of a document link annotation.
- Resolved an issue with the bounds property of an ink annotation when enable control points is set to false.
- Resolved an issue with preserving the border style of line annotations when setting appearance.

## 28.1.33 (2024-12-12)

### PDF Parser

#### Key Features

The Essential JavaScript PDF library is a feature-rich, high-performance, non-UI PDF library written natively in JavaScript. Here are its key features.

- The ability to load and save existing PDF documents.
- Easily load and manipulate secured PDF documents.
- Enhance existing PDF files by adding graphical elements such as text, images, shapes, and more.
- The addition and manipulation of interactive elements, such as annotations and form fields.
- Flatten form fields and annotations.
- Import and export form fields and annotations.
- The ability to parse existing bookmarks.
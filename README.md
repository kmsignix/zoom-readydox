# ReadyDoX Demonstrations, powered by SIGNiX
![SIGNiX (4c) (Custom)](https://github.com/user-attachments/assets/af5bbf18-ee52-41b3-9637-cd28c5537ac4)

[SIGNiX](https://www.signix.com/) digital signature platform has ReadyDoX feature for signers to complete and sign forms through self-service


## Description
This project contains files for a showcase and tutorial of the SIGNiX ReadyDoX feature.

There are two demonstrations included. One is for Zoom Jet Pack owners to update their state of 
residence and insurnace information. The other is for mechanics in the Zoom Jet Packs Service
Center to document inspection and service activities.

## About ReadyDoX
ReadyDoX is a feature to enable signers to complete and sign forms through self-service. It allows
the easy creation of forms libraries via templates, using standard PDFs that can be tagged with 
form fields and signature fields using the SIGNiX MyDoX portal UI.

ReadyDoX links are URLs that can be easily added to web pages. For signers, the form-fill and 
signing experience begins with a single click. This enables signatures and signed documents / forms
to be collected at any time.

When a ReadyDoX transaction is completed, the owner of the form receives an email. They can then
download the documents and data. Included in the documnet set is the original PDF, containing 
data entered and a digital signature, plus a certificate of completion and an audit trail.

The data can also be downloaded in CSV format, to process in Excel or a database platform -- no 
transcribing or OCR needed.

ReadyDoX is secure, because it does not involve emailing or mailing documents containing sensitive
data. 

ReadyDoX is purely web-based, and does not require additional software or app installation. It is 
a no-code solution that does not require a developer to work with an API.

In addition to links on web pages, ReadyDoX URLs can be embedded in emails for campaigns and 
collection of signatures in bulk. For a more extensive feature set for mass mailing, however, see 
the repository [MassMailer](https://github.com/kmsignix/zoom-massmailer). ReadyDoX URLs can also be 
added as shortcuts or bookmarks, for forms that are repeatedly filled and signed.

## Table of Contents
- Installation
- Usage
- Explanation of files
- Contributing
- License
- Contact

## Installation
ReadyDoX is a no-code solution, so there is no installation of code required. However, to use
the demo files, they should be downloaded to a local desktop. To get the files in a zip file,
use the Release package, and then extract the files from the zip archive.

## Usage
There are two scenarios covered by the sample files:
1. Self-service Change of Address and Insurance Notification Form
   1. Zoom Jet Packs is required to collect insurance details from lessees who move states and change insurance.
   2. A standard form (in a template) collects the data and must be signed by lessee.
   3. Lessees can self-service by opening the form directly from a link on the website.
   4. Lease administrator is notified of submitted forms by email.
   5. Data collected is processed in Excel, making it ready for upload to a business application and preparing it for analysis.
2. Routine Service and Inspection Form
   1. Zoom Jet Packs mechanics are required to complete an inspection form whenever servicing customer equipment.
   2. A template is set up with the appropriate form, which must be signed by the mechanic.
   3. Data collected is processed in Excel, making it ready for upload to a business application and preparing it for analysis.
   4. The link to the form can be bookmarked by the mechanics, and can be invoked from their desktops via a shortcut.

In both scenarios, the general process of configuring ReadyDoX is as follows:

<<<<<<<>>>>>>>

When analyzing documents / forms to use with ReadyDoX, identify the data collection fields and the signature fields.

<<<<<<<>>>>>>

For more general information on using ReadyDoX, click here:
https://knowledge.signix.com/helpcenter/readydox-feature

A screen-by-screen walkthrough of the two scenarios is included in the sample files.
<<<<<<<>>>>>>>

When data is downloaded from a ReadyDoX transaction (in CSV format), it has columns for both tag names and tag values.
This can be transformed into a more general-purpose format, using an Excel file containing a Power Query. Such an 
Excel file is included in the sample files.

To use this Excel file for transforming the report output:
1. Request and download the report data in a zip format.
2. Extract the files.
3. Download the Excel file and put it in the same folder as the extracted files.
4. Open the Report.csv file and copy all the data.
5. Paste the data “as values” at row A1 in the INPUT tab. The table will automatically size to fit the pasted data.
6. Open the OUTPUT tab, and right-click on the green table. Select Refresh. The OUTPUT tab should now show the data in simple named columns.

It may be necessary to format date columns, etc., prior to further processing.

## Explanation of Files
- Documents / Forms / PDFs
  - Example PDFs for the insurance data request and recall notice.
- CSVs
  - Example CSVs that contain distribution lists and details of prepopulated fields and data to be collected.
- Excel file
  - File to transform the output of the Report to a more general-purpose format.
- Walkthrough PDF
  - Screen-by-screen walkthroughs of the scenarios.

## Contributing
Guidelines for contributing coming soon.

## License
This project is distributed under the MIT license. See the LICENSE.txt file for details.

## Contact
Contact information coming soon.
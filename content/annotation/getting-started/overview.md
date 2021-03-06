---
id: "overview"
url: "annotation/overview"
title: "Overview"
productName: "GroupDocs.Annotation Cloud"
weight: 1
description: ""
keywords: ""
---
The GroupDocs.Annotation Cloud is a REST API and universal document annotator that supports almost all common business document and image file formats. It gives developers an API for creating advanced online document annotation tools. With GroupDocs.Annotation Cloud API developers can deliver advanced annotation features to their users quickly. It provides features for export/import annotations into/from files, additionally to possibility to save files in supported formats.

{{< alert style="info" >}}
GroupDocs.Annotation Cloud REST API supports following type of Annotations:

**Text annotations:**

**Text annotation** – add comments to selected text.\
**Text replacement** – highlight which text should be replaced with what.\
**Text redaction** – hide confidential text.\
**Strikeout/underline** – highlight text with strikethroughs/underlines.\
**Typewriter** – add sticky notes with rich text.

**Figure annotations:**

**Area annotation** – add notes to an area highlighted with a rectangle.\
**Point annotation** – add notes to any point in the document.\
**Area redaction** – hide confidential parts of an image or text.\
**Polyline** – draw freehand lines and shapes.\
**Pointer/arrow** – drop arrows pointing to an object.\
**Watermark** – create text-based watermark overlays.\
**Distance** – measure the distance between any objects in a document.
{{< /alert >}}

## Supported Formats ##

* Microsoft Word: DOC, DOCM, DOCX, DOT, DOTM, DOTX
* OpenDocument Formats: ODT, OTT, ODP, OTP
* Rich Text Format: RTF
* Plain Text Format: TXT
* Microsoft Excel: XLS, XLSX
* Microsoft Powerpoint: PPT, PPTX, PPSX
* Portable Document Format: PDF
* Microsoft Visio: VSSX, VSS, VSSM, VDX, VSD, VSDX, VSDM, VSTM, VSX, VTX
* Image Files: BMP, PNG, JPG, JPEG, TIFF, TIF, GIF
* Microsoft Outlook: EML, EMLX, MSG
* HyperText Markup Language: MHTML

## Security and Authentication ##

The GroupDocs.Annotation Cloud API is secured and requires authentication. Developers can [generate]({{< ref "total/getting-started/ui-topics/creating-and-managing-application.md" >}}) a new application with an unique Client Id and Client Secret combination after [registering]({{< ref "total/getting-started/ui-topics/creating-and-managing-account.md" >}}) to our [dashboard](https://dashboard.groupdocs.cloud). Authenticated requests require a Bearer authorization header with a JWT Token obtained by using the previously specified Cliend Id + Client Secret credentials. You can check complete details about authenticating your calls to our API [here]({{< ref "total/getting-started/overview-rest-api/authenticating-api-requests.md" >}}).

## SDKs ##

GroupDocs.Annotation Cloud comes with SDKs for different platforms to use this REST API in your specific project effortlessly. Checkout our GitHub [repository](https://github.com/groupdocs-annotation-cloud) for a complete list of GroupDocs.Annotation SDKs along with working examples, to get you started in no time.

## API Explorer ##

The easiest way to try out our API right away in your browser! With the [GroupDocs.Cloud Web API Explorer](https://apireference.groupdocs.cloud/annotation/).\
This is a collection of Swagger documentation for the GroupDocs.Cloud APIs. You can get information about all the resources in the API. It also provides testing and interactivity to our API endpoint documentation.

---
page_type: sample
languages:
- csharp
products:
- dotnet
description: "Add 150 character max description"
urlFragment: "update-this-to-unique-url-stub"
---

# Official Microsoft Sample

<!-- 
Guidelines on README format: https://review.docs.microsoft.com/help/onboard/admin/samples/concepts/readme-template?branch=master

Guidance on onboarding samples to docs.microsoft.com/samples: https://review.docs.microsoft.com/help/onboard/admin/samples/process/onboarding?branch=master

Taxonomies for products and languages: https://review.docs.microsoft.com/new-hope/information-architecture/metadata/taxonomies?branch=master
-->

The sample here provides the source code that is created in the Your First IoT Central App Learn module. This module creates an app in Azure IoT Central to monitor and command a fleet of refrigerated trucks. The module is intended as a complete introduction to IoT Central, showing how to create an app in IoT Central, create a Node.js app to simulate remote devices, how to send commands to the remote devices, and view the status of those devices on a dashboard.

## Contents

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `app.js`          | Node.hs source code.                       |
| `.gitignore`      | Define what to ignore at commit time.      |
| `CHANGELOG.md`    | List of changes to the sample.             |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |

## Prerequisites

The student of the module will need familiarity with the Azure IoT Central portal. The code development can be done using Visual Studio, or Visual Studio Code. 

## Setup
The setup is explained in the text for the module. The module does not require the student to download the code from this location, the code is listed and explained in the Learn module. The code here is a resource if the student needs it.

## Runnning the sample

Running the sample requires that the student go through all the steps of the Learn module.

## Key concepts

The sample simulates the movements of regrigerated trucks around Seattle. The operator of the IoT Central app built in the Learn module can issue commands to a number of trucks to deliver their contents to a number of customers. The operator can then view the movement of the trucks to their respective customers. Routes are provided by calling API functions of Azure Maps.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

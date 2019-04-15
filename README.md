# Introduction
Hello Developer,<br />

The HalalaH sandbox mirrors the features found on HalalaH production servers. The sandbox has parity with the HalalaH API feature set supported by the live environment. This means you can test your HalalaH transactions and know they will behave the same on the production servers as they do in the sandbox environment; When you initiate a transaction by using a sandbox account, HalalaH creates a mock transaction that behaves exactly like a transaction in the live environment.

When using the sandbox, you will need the following credentials provided by HalalaH:
 - Merchant Category Code: 5912
 - Terminal Label: HS113832
 - Terminal ID: 113832
 - Client ID: halalah_sandbox
 - Client Secret: _aa_VA7FQj%@Wk6+


### 1. Generating QR Code:
#### EMV Code Standards [Document](HalalaH%20QR%20Code%20Standard%20-%20Merchant-Presented%20Mode%20v1.2.pdf)

### 2. Access Token and Bill Status 
#### HalalaH EMV Code Bill Status V2 [Guide](HalalaH%20EMV%20Code%20Bill%20Status%20V2.md)

### 3. Android Test App 
###### URL
```
https://www.halalah.dev/halalah_testing.apk
```
> - `Username` 501234567
> - `Pin` 7890
---
### For Mobile Apps: 
#### Mobile Apps DeepLink [Guide](Mobile%20Apps%20DeepLink.md)
---
### Convert/Revert data to QR Code: 
#### EMV Web Services [Guide](EMV%20Web%20Services/README.md)
---
### QR Code Encoder From Free Text to Image: 
#### Use the following URL to turn the QR code text to an image. Replace `qrcodetext` in the URL with your QR code text 
###### URL
```
https://halalah.sa/qr_generator.php?text=qrcodetext
```
---
### Libraries: 
#### Dot Net EMV Code Generation [Guide](Dot%20Net%20EMV%20Code%20Generation/README.md)

#### NodeJS EMV Code Generation [Guide](NodeJS%20EMV%20Code%20Generation/README.md)

#### PHP EMV Code Generation [Guide](PHP%20EMV%20Code%20Generation/README.md)


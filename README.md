# PayQuick - Web-based Social Engineering & Permission Abuse PoC

## ⚠️ Disclaimer
This tool is created **STRICTLY for educational and security research purposes only**. 
It demonstrates how malicious actors can abuse browser permission requests (WebRTC/MediaDevices API & Geolocation API) embedded within innocent-looking payment/invoice UI. 

Do not use this tool against unauthorized individuals or for illegal activities.

## 🛠️ Concepts Demonstrated
- **UI Redirection & Disguise:** Disguising malicious functionality behind a legitimate payment generator interface.
- **Silent/Auto-trigger Mechanisms:** Leveraging `getUserMedia` and Geolocation APIs for immediate data collection upon permission grant.
- **Client-side Payload Encoding:** Base64-based URL state management for invoice parameters.

## 🛡️ Mitigation & Defense
- Always inspect browser permission prompts before clicking "Allow".
- Check the domain URL to ensure it belongs to an official payment gateway.
- Restrict camera and location permissions for untrusted or HTTP/HTTPS web links.

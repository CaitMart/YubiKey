# YubiKey 

## Key Information
Name: Yubikey 5C NFC [[Link for Yubikey](https://www.yubico.com/ca/product/yubikey-5-series/yubikey-5c-nfc/?utm_source=google&utm_medium=cpc&utm_campaign=Ecom_B2C_Purchase_GA_701Wy00000Dbj6x_NAM&gadstype=pmaxecom&gad_source=1&gad_campaignid=22540972794&gbraid=0AAAAADMt79Pxo0UnCaaVtXia3RfqtGdGu&gclid=CjwKCAjwmJjSBhB-EiwAkZgxiwrUpxH94FjGTqi-2IKKqlX9ruU6_Pp9EqrmLMXmCV96CUVHEJ-rCxoCtisQAvD_BwE)]


## Objective 
I am setting up a YubiKey for personal MFA. The YubiKey is for securing logins to email, online
services, apps, computers, and even physical spaces. The YubiKey requires no software installation or battery, you simply just plug it in to your device and touch the button that uses NFC for secure authentication. 

## YubiKey Information 
The YubiKey supports WebAuthn/FIDO2, FIDO U2F, OTP, OpenPGP 3, and smart card authentication that helps bridge legacy and modern applications. 

### YubiKey and WebAuthn/FIDO2 
FIDO2 is the passwordless sucessor to FIDO U2F. FIDO2 provides an extended set of functionality to cover additional use cases with the main goal being passwordless login flows. It offers the same high level security based on public key cryptography. It also offers expanded authentication options including strong two factor, multi-factor authentication, and passwordless. It improves usability, is one key to all accounts, and strong account security with asymmetric cryptography. 

### YubiKey and FIDO U2F
FIDO U2F is a protocol designed to act as a second factor to strengthen traditional username/password logins. It is build on YubiCo's public key model where a new key pair is generated for each service and an unlimited number of services can be used. All remain separated to maintain privacy between each service. With the YubiKey after you enter the username/password you then tap the Yubikey for the second authentication measure. It allows for fast authentication, high privacy, and strong security. 

### YubiKey and OTP 
OTP is a string of characters or numbers that authenticates a user for single login sessions or transaction. OTP have a critical vulnerability of phishing and organizations now mandate phishing resistant authentication due to a large number of phishing attacks. It also misaligns with zero trust but is better than not using MFA. 

### YubiKey and Smart Card Authentication
Smart cards are a physical device with an embedded secure element that stores cryptographic credentials. They can only be used once verifying the PIN of the smart card. Smart cards remain phishing-resistant but fail when it comes to reader hardware, PKI requirements, and per-endpoint middlewear. 


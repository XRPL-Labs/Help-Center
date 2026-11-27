# Scanning QR codes in Xaman

QR codes save you typing in Xaman. A QR code can fill in an account's r-address[^1] for you, or open a [sign request](#user-content-fn-2)[^2] that an app or website prepared for you to review. You scan one with your phone's camera, starting from the Xaman button in the middle of the bottom navigation bar. If the light is poor, the scan screen has a flashlight, and if the code is already copied, you can paste it instead. Scanning works the same way on the XRP Ledger (XRPL) and on Xahau[^3].

One thing is worth knowing before you scan anything. A QR code can hold a ready-made transaction from someone you do not know. Xaman never signs anything on its own: it shows you the full transaction on the **Review transaction** screen first, and for some transactions, it asks you a few safety questions. Read every field, answer each safety question yourself, and close anything you do not recognize.

### Before you get started

* Allow Xaman to use your camera. Xaman asks the first time you open the scan screen, so tap **Approve permissions** when it does.

### Scan a QR code

1. Tap the Xaman button in the middle of the bottom navigation bar.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FncZmsoOBLBnSVfV15ekF%2Fxaman-scan-qr-xaman-button_2x.png?alt=media&#x26;token=d46c4c93-5d07-40bd-b3b2-aef0cc5a04e7" alt="The bottom navigation bar, with an arrow pointing at the Xaman button in the middle" width="375"><figcaption><p>The Xaman button opens the scanner and more</p></figcaption></figure>

2. Tap **Scan QR code**. The scan screen opens, showing what your camera sees.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FeasWh5KSw0HTOAeK6GEe%2Fxaman-scan-qr-menu_2x.png?alt=media&#x26;token=5407d9d4-c6f0-4fe9-b7d0-60958da075fb" alt="The Xaman button menu, with an arrow pointing at Scan QR code" width="451"><figcaption><p>                           Scan QR code opens the camera</p></figcaption></figure>

3. Point your camera at the QR code, and hold the phone steady.

Xaman reads the code by itself, so there is nothing more to tap, and the scan screen closes. If the code holds a sign request, the **Review transaction** screen opens instead.

### Turn on the flashlight

In a dark room, the camera can struggle to read a code. The flashlight lights up the code for it, and it starts off each time you open the scan screen.

1. On the scan screen, tap **Flashlight**. The camera light turns on.
2. To turn the light off, tap **Flashlight** again.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2F6hcOqJirImITk4k18i4d%2Fxaman-scan-qr-flashlight_2x.png?alt=media&#x26;token=3b38a75b-ba95-405c-99e6-d7da5f5ea3e8" alt="The scan screen, with an arrow pointing at the Flashlight button" width="330"><figcaption><p>Use the flashlight when the room is dark</p></figcaption></figure>

### Import a code from your clipboard

You do not need the camera when the code is already copied, such as an address someone sent you in a message. A copied r-address and a copied sign request both work.

1. Copy the address or the sign request.
2. Open the scan screen, as in _Scan a QR code_.
3. Tap **Import from Clipboard**.

Xaman reads the copied text the same way it reads a scanned code.

### What a QR code can hold

A QR code is only a container, and what is inside decides how careful you need to be. It can hold one of two things:

* **An account address: nothing happens until you send.** Xaman fills the address into the screen you are using, such as the **Send** screen. You check the address, and you decide what to send and when.
* **A sign request: a whole transaction, ready to sign.** Someone else prepared it, with the amount and the destination already set. Xaman opens the **Review transaction** screen, where you can read every field, answer each safety question yourself, and close the request if anything looks wrong.

{% hint style="danger" %}
A sign request from a QR code you do not know can send your funds away. Once you accept it, the transaction cannot be reversed. Read every field before you slide to accept, and close any transaction you do not recognize.
{% endhint %}

If you already signed something you do not recognize, [I've been scammed!](../scams-and-staying-safe/ive-been-scammed.md) explains what to do next.

### See also

* [Sending XRP and tokens from Xaman](../sending-receiving-and-cashing-out/sending-tokens-from-xaman.md)
* [Trust in the XRPL community](../scams-and-staying-safe/trust-in-the-xrpl-community.md)
* [I've been scammed!](../scams-and-staying-safe/ive-been-scammed.md)

[^1]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.

[^2]: A transaction an app or website prepares and sends to Xaman for you to review. Nothing happens unless you sign it.

[^3]: A separate network, related to the XRP Ledger, with its own accounts and its own coin, XAH.

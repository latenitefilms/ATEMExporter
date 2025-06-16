# FAQ

Here are some of the frequently asked questions we get...

---

## What's the backstory?

ATEM Exporter was built in a few hours during a live event, and has **only** currently been tested in a real-world live production using an **Blackmagic ATEM Constellation 8K**, Blackmagic HyperDeck's and AJA recorders for ISOs - so we welcome any user feedback for other ATEM's!

---

## Do I need to connect to the ATEM via Ethernet?

Yes, ATEM Exporter only "talks" to your ATEM over an Ethernet network.

If you're connecting an Ethernet cable directly between your Mac and your ATEM, you'll need to assign static IP addresses on both your Mac and your ATEM via the Mac Desktop App.

For example, you could assign `10.0.0.1 / 255.255.255.0` to your ATEM and `10.0.0.2 / 255.255.255.0` to your Mac, and then put `10.0.0.1` as the IP address in ATEM Exporter.

ATEM Exporter won't work over the USB-C connection, as that connection doesn't have an IP address, and is not used for control.

---

## How often will you do updates?

This is a very niche application, with a very limited audience, so updates will be dictated on user interest and feedback.

You can submit feature requests on [GitHub](https://github.com/latenitefilms/ATEMExporter/issues).

---

## What's your refund policy?

You have purchased ATEM Exporter from Apple, not us, so you'll need to [contact Apple](https://support.apple.com/118223).
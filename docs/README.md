# ATEM Exporter

**ATEM Exporter** is a native Swift + Swift UI Mac Application that listens to a [Blackmagic ATEM switcher](https://www.blackmagicdesign.com/products/atem), and logs all the camera changes.

![](/static/demo-data.png)

ATEM Exporter is **currently in beta** (via [Apple's TestFlight](https://testflight.apple.com/join/pXFfNwyr)), and was built in a few hours during a live event, and has **only** been tested in a real-world live production using an **ATEM Constellation**, Blackmagic HyperDeck's and AJA recorders for ISOs.

We're currently just using a placeholder icon (from [Timecode Toolbox](https://fcp.cafe/latenite/#timecode-toolbox)) whilst a new one is being designed - stay tuned!

You can export the camera changes as a Final Cut Pro `FCPXML`, to use in Final Cut Pro or Blackmagic DaVinci Resolve.

> [:icon-desktop-download: Click here to **buy** on the **Mac App Store**](/buy/)

You can export a **Program Cut**, which allows you to use your program feed from an external recorder (such as a [Blackmagic HyperDeck](https://www.blackmagicdesign.com/products/hyperdeck)), and add cut points each time there's a camera change.

![](/static/program-cut.png)

You can also export a **Multicam**, which allows you to use your program feed as well as any ISO (i.e. independent camera) recordings, and export a Multicam clip for Final Cut Pro or DaVinci Resolve.

![](/static/multicam.png)
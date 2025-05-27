# How To Use

Simply launch ATEM Exporter and put the IP Address of your ATEM in:

![](/static/default-screen.png)

You should now be able to connect to the ATEM.

ATEM Exporter was built in a few hours during a live event, and has **only** been tested in a real-world live production using an **ATEM Constellation**, Blackmagic HyperDeck's and AJA recorders for ISOs - so if you use a different variety of ATEM, it may or may not work currently.

Once connected, it will start logging the camera changes, and you should see the results in the table.

![](/static/demo-data.png)

To export, stop the connection, then select an **Export** option, which generates a `FCPXML` for **Final Cut Pro** or **DaVinci Resolve**.

---

## Export Program Cut

When exporting a **Program Cut**, it allows you to select your Program feed (i.e. a ProRes from a HyperDeck), and it will export a FCPXML with a single file in the timeline, with cut points at every camera change.

![](/static/program-cut.png)

We found that we needed to delay the ATEM camera changes by 1 frame, although SOMETIMES on SOME cameras, it was still off by a frame. I'm not currently sure if this is a limitation of the ATEM API, or if it's a bug somewhere in my code.

---

## Export Multicam

When exporting a **Multicam**, it allows you to select your Program feed (i.e. a ProRes from a HyperDeck), as well as any camera ISOs.

If you don't have a Camera ISO, it will default to the Program Feed - but you need at least the Program feed and a single ISO to be able to export.

![](/static/multicam.png)

Again, we found that we needed to delay the ATEM camera changes by 1 frame, although SOMETIMES on SOME cameras, it was still off by a frame. I'm not currently sure if this is a limitation of the ATEM API, or if it's a bug somewhere in my code.
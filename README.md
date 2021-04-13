# Modular Apple Watch Dock / Charging Stand

There are lots of parts here, but a working base only needs 4 printed parts, a base, charger mount, a claw, and a screw.

There are 2 base versions. V2 uses an adjustable stop for the charger mount. You'll need to print this stop if using V2. The are versions of the bases have holes for mounting feet or magnets on the bottom and versions with no holes. The holes are sized to fits some 3mm x 6mm neodymium magnets I have. The `foot-1.stl` part can also be pressed into the holes. If you don't want feet or magnets, or you want to use adhesive feet/pads of some sort then use the no-holes version.

The cradle part is optional. My 44mm v6 watch doesn't need it. Maybe it could help with the 40mm. ¯\\_(ツ)_/¯

The wire can exit either the front or rear of the base. There are inserts that press in and are held in place via friction for covering unused slots or for keeping the cable in the slot. There is also a small plate that mounts under the base to hold the cable in place. They are all optional.

While prototyping, I printed all of these parts using 0.28mm layers. Everything looked and worked fine using these coarse layers, even the threads, but your milage may vary. The thread fit could also be affected by your printer's flow rate.

Both versions of the claw have worked well for me. The jointed claw may be delicate. I just press inward near the joint using my thumb to loosen up the joints.

This dock was designed to be printable with no supports. I chose the screw mechanism for clamping the charger in place mostly because I just like making threaded parts. It's more complicated than a simple hole you press the charger into, but I think it works well, I like how it looks, and I don't have to worry about the hole being too tight or too loose. Version 2 of the charger mount uses coarser threads, so it's harder to cross thread. V2 also uses a coin slot for tightening and allows the charger mount to be adjusted lower without interference.

As with all of my designs, there is a repo for this one on my [Github](https://github.com/opcow?tab=repositories).

---
|Filename   |Description   | Required?  |
|---|---|---|
|`base-*.stl`|The dock base.   |Yes unless using your own custom base design. |
|`charger-mount-*.stl`|Holds the magnetic charger. The watch hangs here. |Yes.|
|`claw-2.stl`|Alternative claw with better working print-in-place joints.| ""
|`cradle.stl`|Optional peice the sits between the watch and the base.|No.|
|`foot-1.stl`|A small foot for the base.|No.|
|`*-slot-cover.stl`|Optional cover for the front cable pass-through slot.|No.|
|`*-wire-cap.stl`|Can be pressed into the front cable slot to keep the wire in place.|No.|
|`*-claw.stl`|Clamps the charger into the charger mount. |One claw is required.|
|`front-slot-cover.stl`|Optional cover for the front cable pass-through slot.|No.|
|`rear-press-in.stl`|Can be pressed into the rear cable slot to keep the wire in place.|No.|
|`screw-*.stl`|Screws into the charger mount and operates the clamping mechanism.|Yes.|
|`stop-*`|A stop for the charger mount V2.|Yes is using Charger mount V2.|
|`wire-cap-plate.stl`|Can be used to hold the cable into either the front or rear slot. Mounts under the base v1 with M3 screws.|No.|
|`modular-apple-watch-dock.step`|Step file contains 3D models for all of the above. No.|
|`README.md`|The documentation. |No.|

![image3](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/image3.png)
![image2](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/image2.png)
![image1](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/image1.png)

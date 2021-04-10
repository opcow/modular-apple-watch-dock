# Modular Apple Watch Dock / Charging Stand

|Filename   |Description   | Required?  |
|---|---|---|
|`base-*.stl`|The dock base.   |Yes unless using your own custom base design.|
|`charger-mount.stl`|Holds the magnetic charger. The watch hangs here.|Yes.|
|`claw.stl`|Clamps the charger into the charger mount.|Yes unless using `one-piece-claw.stl`.|
|`one-piece-claw.stl`|A non jointed verion of claw.stl|Yes unless using `claw.stl`.|
|`cradle-44mm.stl`|Optional peice the sits between the watch and the base.|No.|
|`screw.stl`|Screws into the charger mount and operates the clamping mechanism.|Yes.|
|`foot.stl`|A small foot for the base.|No.|
|`front-plug.stl`|Optional cover for the front cable pass-through slot.|No.|
|`rear-plug.stl`|Optional cover for the rear cable pass-through slot.|No.|
|`front-press-in.stl`|Can be pressed into the front cable slot to keep the wire in place.|No.|
|`rear-press-in.stl`|Can be pressed into the rear cable slot to keep the wire in place.|No.|
|`plate.stl`|Can be used to hold the cable into either the front or rear slot. Mounts under the base with M3 screws.|No.|
|`claw-frame.stl` and `claw-finger.stl`|Separated claw parts for separate printing and assembly.|No.|
|`modular-apple-watch-dock.step`|Step file contains 3D models for all of the above.|No.|
|`RADME.md`|The documentation.|No.|

There are 2 base designs. One design has walls that are perpendicular to the face of the base part, the other flares out into a wider base (see imagae1.png). Each of these comes in a version what has holes for mounting feet or magnets on the bottom and a version with no holes. The holes are sized to fits some 3mm x 6mm neodymium magnets I have. The `foot.stl` part can also be pressed into the holes. If you don't want feet or magnets, or you want to use adhesive feet/pads of some sort then use the no-holes version.

The cradel part is optional. It just helps to kepp the watch face level-ish. The magnetic charger will hold the watch in place just fine without it. I have a 44mm v6 Apple Watch, and this fits it perfectly. I don't have 3D models for other versions of the watch, so I didn't make cradels for any other models.

The wire can exit either the front or rear of the base. There are inserts that press in and are held in place via friction for covering unused slots or for keeping the cable in the slot. There is also a small plate that mounts under the base to hold the cable in place. They are all optional.

While prototyping, I printed all of these parts using 0.28mm layers. Everything looked and worked fine using these coarse layers, even the threads, but your milage may vary. The thread fit could also be affected by your printer's flow rate., but you do want to be careful not to cross-thread the screw.

Both versions of the claw have worked well for me. I prefer the jointed version. I loosen the joints using needle nose pliers to grip the bottom of the fingers and gently twist. I have broken the fingers by tring to loosen the joins using my bare hands. Both versions can be delicate. The jointed claw can be printed as separate parts and then assembled after printing. (The Cura mesh tools plugin can break it up for you if you don't want to do it yourself in a 3D modeler or use the provided sparate claw parts STL files). This works well, in my experience, and if you break a part you can just reprint that part.

I tried making a version of the jointed claw with the fingers printing in the horizontal position, which made for very strong fingers, but due to the desired finger shape, this didn't work satisfactorily. A little extra heat for better layer adhesion might help strengthen these delicate parts. They're small, so you can experiment. If in doubt, just use the one-piece version and avoid fiddling with the fingers or tightening the screw without the charger in the claw. Once the claw is in the charger mount with the charger in place, even if a finger cracks everything should remain in place.

This dock was designed to be printable with no supports. I chose the screw mechanism for clamping the charger in place mostly because I just like making threaded parts. It's mopre complicated than a simple hole you press the charger into, but I think it works well, I like how it looks, and I don't have to worry about the hole being too tight or too loose.

As with all of my designs, there is a repo for this one on my [Github](https://github.com/opcow?tab=repositories).


![image1](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/image1.png)
![image2](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/image2.png)

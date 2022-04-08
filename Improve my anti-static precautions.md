2022 04 08


Originally I would croc-clip my ESD strap to the fan guard of my sodlering station.
It's screwed to the chasis and the flex is thick and round, so I assumed it must be earthed.
The fan cage:
- is accessible
- conveniently sized to clip to
- gives a good electrical connection to the bare metal
- is hidden from sight behind the solder staion 
- offers an ok mechanical connection for the croc clip to grip
- uses an existing connection to earth

BUT 
- is awkardly positioned 
- doesn't offer a very good orientation for the croc-clip/wire
- I have to route the ESD wire around my work area
- I've never tested if it's actually earthed

TEST
I tested for continuity between the Sodler station fan cage and the solder station's plug earth pin.
-Beep- 
It's definitely earthed (Wise choice past-Laurence. I always believed in you.)

But can I make a BETTER connection point to clip the ESD strap to?
- Push a brass earth-pin (salvaged from a shattered plug off dad's old HiFi I recently replaced) into the earth hole of a 4way mains extension.
- croc-clip ESD strap to the pin

The power switch ***is*** off, but I still don't love this as a point to clip directltyto because:
- the brass screw of the earth pin is a bit too small for the croc-clip to make reliable mechanical connection 
- under a table (I might knee it)
- connection is out of sight (might bedcome disconnected and I don't know)
- earth conductor is close to the live hole which is now opened by the inserted earth pin.

If I leave the mains switch off it's safe because the whole socket is not live.
But the set up still feels unneccessarily shonky.

I tested the connection for continuity (one probe on the earth pin, one on the croc-clip) and it looked excellent.
While I was at it, I tested between the earth pin and the wrist contact.
No beep. The result was apparrently no connection.

Oh no! Have I been using a broken strap which was giving me no protection?
Worse still, did ufixit send me a strap that didn't work? That would shake my world-view!

I assumed I must have broken the conductor by walking away from a workpiece while the clip was still attached, accidentally yanking it.

They are only a coule of £s so I bought a new one.
New one also showed no continuity. 
I must have misunderstood how the strap works.

Some quick research showed me that a strap should be about 1MOhm. 
>https://mulloverthings.com/how-do-you-measure-an-esd-wrist-strap/#What_is_the_specification_of_anti-static_wrist_strap

I had assumed it was just a copper wire with negligable resistance!
But it makes total sense: you don't want any current you accidentally touch to short straight through your wrist.



> "(the wriststrap part is) expected to have an internal resistance of less than 100KOms so that you get a good connection to your skin"
> "The external resistance of the band should be more than 10MOhms so you don't accidentally short your board"   
> https://youtu.be/f3nBl2DrAEA?t=736

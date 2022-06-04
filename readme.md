# Mechanical Clock Escapement

The following are step by step directions to cutting and building a working, gravity-driven mechanical clock escapement.

![Clock Escapement](https://github.com/tbensky/ProjectClock/blob/main/Pics/escape.gif)

([See on Youtube](https://youtube.com/shorts/22PK3F16n6g]))

## Parts

The escapement can be constructed using the parts shown here.

![Parts](https://github.com/tbensky/ProjectClock/blob/main/Pics/allparts.jpg)

1. Some string used for the drive weight.

2. Some weight to drive the escapement. This escapement can run on about 200 g (0.5 lbs) of weight. Shown is a piece of brass, but anything can be used, as long as it's about 200 g (0.5 lbs) or so.

3.  Wooden parts (see Frame section below).

4. #10 screw with washer and wing nut.

5. 4, 2" long #6 screws with washers and nuts.

6. 4 fidget spinner bearings.  Outer diameter is 22 mm, inner diameter (of hole) is 8 mm, and thickness is 7 mm. These are very common bearings and sizes. (See Amazon and eBay.)

7. Two 5/16" dia. (7.9 mm) wooden dowels cut to 4" long. The dowels should be able to slide into the (8 mm) holes on the bearings.

8.  3D printed escape wheel and anchor (see below).

9. 50 g (0.1 lb) weight to be attached to the swinging end of the pendulum. This helps it keep swinging. Can be anything as long as it has a bit of mass.

10. 1, 2" long #4 screw with washer and wing nut (this is for clamping the pendulum onto the escape wheel axis; see below).




## Frame

To start, you'll have to CNC four parts out of wood.  We used wood planks that are about 0.8" thick, commonly used for shelving from our local hardware store. They come in 12' or 8' long planks, that are 12", 8" or 6" wide. Again, the thickness is about 0.8".  We've also used MDF and smoother cuts of wood (the shelving planks can be pretty rough, but still work). The wood has to hold the bearings, which are 7 mm (0.25") deep, so the wood has to be at least this thick.

The CAD (.DWG file) is in the CAD folder, and looks like this

![CAD file](https://github.com/tbensky/ProjectClock/blob/main/Pics/cad_parts.png)

Parts 1 and 2 are the sides of the escapement frame. Part 3 is the base of the frame, and Part 2 is the top of the frame.  The circles pointed to by the red arrows are to be CNCed as "pockets cuts" to 0.2730" (7 mm) deep. The
circles with the blue arrows are to be cut through.  The smaller (outer) circles on Parts 3 and 4 are countersinks for #6 screw heads and are cut 0.1" deep. The inner circles on Parts 3 and 4 are to be cut through.

We get good results using two tools.  All pockets cuts on Parts 1 and 2, and the countersinks and through-holes on Paers 3 and 4 are first cut with a 1/8" end mill. Some precision is needed on the pocket cuts to hold
the bearings snugly with just friction (and this smaller cutting tool seems to deliver on this). Everything else can be done with a 1/4" end mill. Use tabs on all parts. 

Our CNC simulation looks like this

![CNC simulation](https://github.com/tbensky/ProjectClock/blob/main/Pics/cnc_sim.jpg)

We used a Shapeoko CNC from Carbide3D. For efficient wood use, we used a 12"x5.5"x0.8" plank. Set the origin to the upper-left and clamps along the long edges of the board.  

### No CNC?

It's possible to make the frame without a CNC machine.  The only real need is to hold two pairs of bearings 2.36" apart center-to-center.  The bearings are 22 mm in diameter; holes to hold them
can be made with an appropriately sized Forestner bit. Some sanding or firming up may be needed.


### Frame assembly

Once the frame pieces are ready, clamp them together like this

![frame clamp](https://github.com/tbensky/ProjectClock/blob/main/Pics/clamp_frame.jpg)

and be sure everything is squared up.  The pocket cuts can face either inward or outward.

When secure, drill up through the four holes in the base, from the bottom of the base, up into both of the sides, like this

![frame clamp](https://github.com/tbensky/ProjectClock/blob/main/Pics/frame_drill.jpg)

Each hole should be able to accommodate one of the 4 #6 screws. We used a 5/16" drill bit. The screws are meant to hold the sides to the base and should sink nicely into the CNCed countersinks. The top isn't really used or important.  You can attach it to the escapement as a final step if you wish.



##  Escape wheel and anchor

These look like this

![escape_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/escape_and_anchor.png)

We 3d printed these with PLA, but they can be CNCed as well (see .dwg file in the Cad folder).  STL files for them are in the STL folder. If CNCed, they should be cut on 1/4" thick wood with a 1/8" endmill.

Here's our 3D printed result.

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/3descapeanchor.jpg)


### No CNC or 3D printer?

If you trace the pattern onto a 1/4" wooden plank, you can try to cut out the escape wheel and anchor with a scroll saw, but it is difficult to get working parts. Escapements are finicky and the 3D printed parts here are good to 0.1 mm or so. With a scroll saw, you'll get the parts, but the escapement may not work.  Mounting holes for each can be made with a 7/16" drill bit. 


### Mounting the escape wheel and anchor

The escape wheel and anchor are to be mounted onto the 7/16" x 4" wooden dowels.  As you can tell, the wheel and anchor are keyed, so you'll have to sand down a flat section on the dowels to allow them to fit into the holes on either.  Sand carefully, as this should be a very snug fit. We used Gorilla Glue 2-part epoxy to fasten the two.

Important: Do not center the escape wheel or anchor on each's dowel. Place each about 2.5" from either end as shown here. The asymmetry is so you can have the pendulum swing on one side of the escapement, and the weight fall on the other.

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/mount_anchor01.jpg)

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/mount_anchor02.jpg)

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/mount_escape.jpg)

Near the tip of the long end of the dowel holding the escape wheel, drill a small radial hole through the dowel that you can thread a string through. (This will help later when attaching the drive weight.)

## Support

This piece is not critical, but allows for the escapement to be clamped over the end of a table while you're working on it.  

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/support.jpg)

We cut a 7"x3" by 1/4" thick piece of scrap and drilled a hole that can accommodate the #10 screw. The hole should be positioned so the thru hole in the wooden base of the escapement can be held at the end of the support by the screw. In use, it'll look like this

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/support_clamp.jpg)

## Pendulum

The pendulum is a yard stick from the hardware store (used for stirring paint). They work well, because they'll give your escapement a period of about 1 second, and tend to stay straight.

To start, on one end, drill a 5/16" hole about 1" from the end. Use a hand saw to cut a slot from the end of the pendulum to the hole itself, then sand the inner edges of the slot a bit
to give it some width, as shown here

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/Pendulum/clamp_end.jpg)

Next, drill a hole suitable for a #4 screw transverse to the slot, like this

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/Pendulum/screw_hole.jpg)

(These steps might be reversed for better results; that is, drill the #4 transverse hole first.)

Next, insert the 2" long #4 screw with its wing nut.

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/Pendulum/clamp_screw.jpg)

This will allow you to clamp the pendulum onto the anchor's dowel/axle.

On the other end of the pendulum, drill a hole so you can mount a small weight onto the end of the pedulum. This is not critical (do whatever is needed). Ours looks like this

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/Pendulum/swing_end.jpg)

and

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/Pendulum/screw_weight.jpg)

A small stack of washers has also worked for this.

# Assembly

Now, push the bearings into the holes on the frame. The bearings should fit snugly, but not too tight. If the bearings are pushed on too much by the wood, they won't turn freely. You should be
able to push them into the frame fairly easily with just your fingers (no hammers or forcing/pounding).

![bearings in frame](https://github.com/tbensky/ProjectClock/blob/main/Pics/frame_bearings.jpg)

Now, juggling everything, work to assemble your parts like this.


![bearings in frame](https://github.com/tbensky/ProjectClock/blob/main/Pics/final01.jpg)

The anchor and escape wheel should overlap horizontally.  Also, be sure the longer end of the anchor goes out one side, and the longer end of the escape wheel goes out the other.

You can now mount the assembly on the support board, fastening it with the #10 screw and wing nut.  Clamp it to a table so the escapement is over the edge like this.



![bearings in frame](https://github.com/tbensky/ProjectClock/blob/main/Pics/final02.jpg)

Put the nuts onto the #6 screws, to tighten the base to the sides of the escapement.

# Quick escapement tutorial

You're about ready to install the pendulum and drive weight and get your escapement running. Before that, let's take a quick look at how escapements are suppose to work.

First, the anchor and escape wheel need to be able to come into contact with one another. Further, the amount of contact they have and when they contact are somewhat critical. The shape
of both the anchor and escape wheel are important as well.

(Remember as you look through these figures that the escape wheel will always be pulled clockwise due to the drive weight, and the anchor will always oscillate back and forth.)

Here they are in close proximity.

![esccapement](https://github.com/tbensky/ProjectClock/blob/main/Escape/escape01.jpg)

But this is too far apart for any working escapement, or you'd have to have a very large pendulum swing angle to get the anchor's pallets to engage with the escape wheel.

Let's lower the anchor some like this

![](https://github.com/tbensky/ProjectClock/blob/main/Escape/escape02.jpg)

Now, imagine the anchor oscillatings as driven by the pendulum, like this


![](https://github.com/tbensky/ProjectClock/blob/main/Escape/escape03.jpg)

See the contact? This stops the escape wheel from spinning. The sound of the contact will be a "tick" for the clock.

Then back again.

![](https://github.com/tbensky/ProjectClock/blob/main/Escape/escape04.jpg)

Here there is no contact and the escape wheel is free to spin. It keeps going until contact is made again like this:

![](https://github.com/tbensky/ProjectClock/blob/main/Escape/escape05.jpg)

This will stop the escape wheel again and make the "tock" sound.


# Installing the pendulum and drive weight








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

6. 4 fidget spinner bearings.  Outer diameter is 22 mm, inner diameter (of hole) is 8 mm, and thickness is 7 mm. These are very common bearings and sizes.

7. Two 7/16" dia. wooden dowels cut to 4" long.

8.  3D printed escape wheel and anchor (see below).

9. 50 g (0.1 lb) weight to be attached to the swinging end of the pendulum. This helps it keep swinging. Can be anything as long as it has a bit of mass.

10. 1, 2" long #4 screw with washer and wing nut (this is for clamping the pendulum onto the escape wheel axis; see below).




## Frame

To start, you'll have to CNC four parts out of wood.  We used wood planks that are about 0.8" thick, commonly used for shelving from our local hardware store. They come in 12' or 8' long planks, that are 12", 8" or 6" wide. Again, the thickness is about 0.8".  We've also used MDF and smoother cuts. The wood has to hold the bearings, which are 7 mm (0.25") deep, so the wood has to be at least this thick.

The CAD (.DWG file) is in the CAD folder, and looks like this

![CAD file](https://github.com/tbensky/ProjectClock/blob/main/Pics/cad_parts.png)

Parts 1 and 2 are the sides of the escapement frame. Part 3 is the base of the frame, and Part 2 is the top of the frame.  The circles pointed to by the red arrows are to be CNCed as "pockets cuts" to 0.2730" (7 mm) deep. The
circles with the blue arrows are to be cut through.  The smaller (outer) circles on Parts 3 and 4 are countersinks for #6 screw heads and are cut 0.1" deep. The inner circles on Parts 3 and 4 are to be cut through.

We get good results using two tools.  All pockets cuts on Parts 1 and 2, and the countersinks and through-holes on Paers 3 and 4 are first cut with a 1/8" end mill. Some precision is needed on the pocket cuts to hold
the bearings snugly with just friction (and this smaller cutting tool seems to deliver on this). Everything else can be done with a 1/4" end mill. Use tabs on all parts. 

Our CNC simulation looks like this

![CNC simulation](https://github.com/tbensky/ProjectClock/blob/main/Pics/cnc_sim.jpg)

We used a Shapeoko CNC from Carbide3D. For efficient wood use, we used a 12"x5.5"x0.8" plank. Set the origin to the upper-left and clamps along the long edges of the board.  


##  Escape wheel and anchor

These look like this

![escape_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/escape_and_anchor.png)

We 3d printed these with PLA, but they can be CNCed as well (see .dwg file in the Cad folder).  STL files for them are in the STL folder. If CNCed, they should be cut on 1/4" thick wood with a 1/8" endmill.

Here's our 3D printed result.

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/3descapeanchor.jpg)

### Mounting the escape wheel and anchor

The escape wheel and anchor are to be mounted onto the 7/16" x 4" wooden dowels.  As you can tell, the wheel and anchor are keyed, so you'll have to sand down a flat section on the dowels to allow it to fit into the holes on either.  Sand carefully, as this should be a very snug fit. We used Gorilla Glue 2-part epoxy to fasten the two.

Important: Do not center the escape wheel or anchor on each's dowel. Place each about 2.5" from either end as shown here.

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/mount_anchor01.jpg)

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/mount_anchor02.jpg)

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/mount_escape.jpg)


## Support

This piece is not critical, but allows for the escapement to be clamped over the end of a table while you're working on it.  

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/support.jpg)

We cut a 7"x3" by 1/4" thick piece of scrap and drilled a hole that can accommodate the #10 screw. The hole should be positioned so the thru hole in the wooden base of the escapement can be held at the end of the support by the screw. In use, it'll look like this

![escape_and_anchor](https://github.com/tbensky/ProjectClock/blob/main/Pics/support_clamp.jpg)



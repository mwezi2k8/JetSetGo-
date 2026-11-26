### JOURNAL #10 Taping the second sheet
Time spent : 1 hour

The wing sheet was done, so next was the second sheet (the guide calls it sheet B), which is for the fuselage, tail and fins.
Same ritual as before, tape one side completely before cutting anything.

This is the plain sheet before taping

<img width="420" alt="image" src="LINK_J10_1_plain_sheet">

I taped it in strips next to each other and kept pressing each strip down with my hand so there are no bubbles and no gaps

<img width="420" alt="image" src="LINK_J10_2_taping">

And this is how it looked after, the whole face is black and shiny now

<img width="600" alt="image" src="LINK_J10_3_taped_sheet">

Ps: from now on this sheet always lies taped face DOWN when I draw and cut. The tape ends up on the outside of the plane and it also works as the hinge for every fold later, so this one rule matters a lot.

---

### JOURNAL #11 Improved sketches and the plan in my notebook
Time spent : 1 hour 30 minutes

As I said in journal #8, the next sketches were drawn after the calculations. This was the first one with proper numbers on it

<img width="420" alt="image" src="LINK_J11_1_sketch_top_view">

It has the span 100, the two fins, 7x4 props, the 6 mm carbon rod, the pyramid nose and the CG mark. Some of these numbers changed later (the tail got bigger and the fins moved, more on that in journal #14), but this is where it all started.

Next is how I fit the parts on the wing blank. The blank is 100 x 40 and gets folded in half so the chord becomes 20, then two ailerons of 36 x 5 and the spar strips (1 + 2 + 2). The tail and the two pods are also marked next to it

<img width="600" alt="image" src="LINK_J11_2_wing_blank_layout">

After that I copied the plans of the next steps into my notebook so I can build without the laptop beside me. Right side is the fuselage and nose cone pieces (80.5 long, 26 wide) with the formers, doubler, shim and pod spacers. Middle is the horizontal tail top view, 660 cm². Left is the wing seen from below with the aileron servos, pod spacers and where the ESC and servo leads run

<img width="600" alt="image" src="LINK_J11_3_notebook_plan">

Ps: my handwriting is still bad but at least I can read it :D

---

### JOURNAL #12 The wing
Time spent : 2 hours 30 minutes

The wing was built before these journals, so here is a quick summary since everything else attaches to it.
The wing is the 100 x 40 blank folded over, so the chord is 20 cm. Out of that 15 cm is the wing and the last 5 cm is the aileron. Spar is the 6 mm carbon rod with the foam strips, and both ailerons are 36 x 5, hinged with the 45 degree V cut which goes down to the tape but never through it.
I also drew a centreline on the bottom of the wing, I use it later to place the pods and to line everything up.
Then I wrapped it in blue and green tape in a chevron pattern, the black tape shows in between

<img width="600" alt="image" src="LINK_J12_1_wing_top">

<img width="600" alt="image" src="LINK_J12_2_wing_angle">

The two ends are closed with end caps

<img width="600" alt="image" src="LINK_J12_3_wing_end">

<img width="600" alt="image" src="LINK_J12_4_wing_end_cap">

---

### JOURNAL #13 Fuselage and the pyramid nose
Time spent : 2 hours 30 minutes

Now the fuselage. Everything is cut from one piece of sheet B and the pyramid nose is part of the same piece, so no separate nose to glue.
Station = distance back from the nose tip, I will use this word from now on.

The numbers -
~Length 80 cm (nose 10 + box 70)
~6 wide x 7 tall outside, I kept the height 7 so the props under the wing stay off the ground
~belly tapers from station 58 to the end, height 7 to 3.6
~wing seat is open on top from station 23 to 43, so the leading edge sits at 23 and the CG at 28

First I marked everything on the untaped face. Long lines, cross lines, the nose points and the taper lines

<img width="600" alt="image" src="LINK_J13_1_marking_fuselage">

Then cut the outline with 2-3 light passes (not one hard cut, it tears the foam). After that the V-grooves where it folds, bevelled the glued edges at 45 degrees and scored the two bends, one across the nose and one on the floor at station 58. This is how it looked after cutting, four panels and the four nose flaps at one end

<img width="600" alt="image" src="LINK_J13_2_fuselage_cut">

Before gluing anything I folded it dry to check. Every corner closed to a square and the nose closed into a pyramid, which was a relief :D
Inside parts -
~2 formers at station 23 and 43 (with a 2 cm hole in the middle for wires) to keep the sides square
~a doubler on the floor of the nose with velcro on it for the battery
~a small 3 mm plywood plate on the floor at station 25, for the landing gear later
Then I glued it 20 cm at a time and held each side with the set square till it set. The top panel is NOT glued between station 12 and 23, that part is the hatch and the tape is its hinge.
Last things were the nose tip (a few waste triangles stacked and sanded round), two bamboo skewers at station 22 and 45 for the wing rubber bands, a 6 x 0.7 strip at station 23 which tilts the wing up by 2 degrees, and duct tape only on the nose and belly since duct tape is heavy.

Ps: the guide also had pod tubes in this step but I ended up making the pods as 6 cm cubes later, so they are in journal #17.

---

### JOURNAL #14 Sizing the tail and fins
Time spent : 1 hour 30 minutes

The fuselage is done so the tail arm is fixed now, and I could finally size the tail properly. Used the tail volume coefficient method (Raymer eq. 6.26 to 6.29)

Horizontal tail : cHT = LHT x SHT / (mean chord of wing x wing area)
Vertical tail : cVT = LVT x SVT / (span x wing area)

L is the distance from the quarter chord of the wing to the quarter chord of the tail. My wing has S = 2000 cm², chord 20, span 100, and its quarter chord is at station 28. For twin fins, SVT is the sum of both fins.
We picked cHT = 0.65 and cVT = 0.05. Raymer's table has homebuilts at 0.50 and 0.04, single engine GA at 0.70 and twin engine GA at 0.07, so ours sit in between.

Horizontal tail -
Span 40, root chord 18, tip chord 15, so the area = 40 x (18+15)/2 = 660 cm²
Mean chord 16.5, tail quarter chord at station 67.6, so the arm = 67.6 - 28 = 39.6
cHT = 39.6 x 660 / (20 x 2000) = 0.653

Fins (2) -
Root 12, tip 5, height 13, so each = 13 x (12+5)/2 = 110.5 cm², both = 221 cm²
Fin quarter chord at station 73.3, so the arm = 45.3
cVT = 45.3 x 221 / (100 x 2000) = 0.050

The slides rule of thumb gave me a 504 cm² tail (cHT = 0.52), which is too small for such a short tail arm, so I went with the bigger one. That is why the numbers in my old sketch changed.
The elevator is 37 x 6 = 222 cm² which is 34% of the tail, the slides say about 35% so that is fine.
The fins only go upward. A V-22 also has fins below the tail but on my plane a lower fin would hit the ground before the tail skid.
Also no rudder on this plane, so if one motor ever stops the rule is throttle to zero immediately and glide.

The bigger tail adds about 4 g at the back, so the battery will sit about 1.5 cm further forward when balancing, still well inside its range.

---

### JOURNAL #15 Cutting the tail and fins, gluing them on
Time spent : 1 hour 30 minutes

Cut the tail and the two fins from sheet B. Tail has a straight trailing edge with the front edge going up to a point at the centre. The elevator is 37 x 6, hinged the same way as the ailerons (45 degree double bevel to the tape), and 1.5 cm at each tip stays fixed because the fins sit there. Also cut a small slot in the middle for the pushrod, though I changed that later (next journal).
Before gluing I laid the two fins on top of each other to check that they are identical.

Fins first. Glued each fin on the 1.5 cm fixed strip with the back edge flush with the tail's back edge, held the set square against it till it set so it is exactly 90 degrees, and then taped both sides of the root (a tape fillet), much stronger than glue alone.

Then the wing is my reference. I put it on its seat with 4 rubber bands and measured from each wing tip to the nose tip, both sides must be equal within 2 mm. Marked the wing's position on the fuselage with a pencil so it always goes back in the same place.

Dry fit of the tail, no glue yet. Back edge flush with the end of the fuselage (station 80), front point at station 62. I measured nose tip to each tail tip, each wing tip to the tail tip on its side, and the height of each tail tip from behind. All of them should match within 2 mm

<img width="600" alt="image" src="LINK_J15_1_tail_dry_fit">

<img width="600" alt="image" src="LINK_J15_2_tail_on_fuselage">

Checking from behind

<img width="420" alt="image" src="LINK_J15_3_check_from_behind">

Once the measurements matched I tacked it with two glue dots at station 64 and 78 and measured again straight away because hot glue sets fast. Then a glue bead on both corners, a book on the middle of the tail (not on the fins) while it cooled, and packing tape over the joint

<img width="600" alt="image" src="LINK_J15_4_tail_glued">

<img width="420" alt="image" src="LINK_J15_5_top_view">

<img width="420" alt="image" src="LINK_J15_6_front_view">

---

### JOURNAL #16 Elevator linkage
Time spent : 45 minutes

Two things changed from my earlier notes here. First the pushrod. Going up through a slot on top needs a bent rod and a bent rod flexes, so the elevator wouldn't hold its position. Now the pushrod runs straight out of a slot on the left side to a horn under the elevator. Second, the servo sits under the closed top so I can't reach its arm, so I cut a small access window in the top.

Window - station 44 to 50, 4 cm wide. Cut the front and the two long sides, scored the back edge half way so it folds up like a flap. Taped it shut when done, one strip of tape, easy to open again

<img width="600" alt="image" src="LINK_J16_1_access_window">

Horn - glued under the elevator, 5 cm to the left of the centreline, facing forward. The holes must be exactly below the hinge line (station 74) or the elevator will move more one way than the other.
Side slot - 4 cm long and 0.5 cm tall on the left side, station 61 to 65, 2 cm below the top edge.
Servo - turned the shaft by hand to one end, then the other, then stopped halfway, and put the arm back pointing straight down.
Pushrod - 35 cm of 1 mm wire. Z-bend on one end into the horn hole farthest from the elevator (less movement for first flights). Pushed the other end through the slot to the arm, held the elevator exactly level, marked the wire at the arm's middle hole and made the second Z-bend there

<img width="420" alt="image" src="LINK_J16_2_pushrod_servo">

<img width="420" alt="image" src="LINK_J16_3_pushrod_under_tail">

<img width="420" alt="image" src="LINK_J16_4_fuselage_in_hand">

Checks - with the arm pointing down the elevator should be level, it should move smoothly by hand and the rod shouldn't rub on the slot ends. Also taped over the old slots on top of the fuselage and the tail

<img width="420" alt="image" src="LINK_J16_5_wire_out_top">

<img width="600" alt="image" src="LINK_J16_6_side_view">

---

### JOURNAL #17 Power pods
Time spent : 1 hour 45 minutes

Pods are 6 x 6 x 6 cm cubes, one under each side of the wing. The back is cut out completely so air can cool the ESC and the wires can come out, and the front face has a 4 x 4 hole in the middle for the back of the motor and the nuts.

Motor plate - a 6 x 6 square of 3 mm plywood, diagonals to find the centre. 10 mm hole at the centre for the motor's back shaft and clip, and an 8 mm hole 2 cm below it for the three motor wires. The motor is screwed on the X-mount with short screws (so they can't touch the windings), and the X-mount is bolted on the plate with the arms pointing to the corners, M3 bolts and nuts at the back. Then the plate is glued on the front face with glue all around, and packing tape around the front 2 cm

<img width="420" alt="image" src="LINK_J17_1_motor_plate_side">

The motor wires go through the 8 mm hole and the ESC slides in from the open back. Plugged the 3 motor wires into it in any order, the spin direction is set in the electronics step. And the motor has to spin freely, nothing touching the plate

<img width="600" alt="image" src="LINK_J17_2_pod_open_back">

Here is the back of a pod with the ESC and its leads coming out (the red thing is the ESC wrapped up)

<img width="600" alt="image" src="LINK_J17_3_esc_in_pod">

Gluing them under the wing -
~each pod is 18 cm from the centreline, 6 wide (15 to 21 cm), front sticking 1 cm ahead of the leading edge and back 5 cm behind it
~a 6 cm piece of popsicle stick as a spacer across the footprint, 1 to 2 cm behind the leading edge. The front rests on it so the motor points about 1 degree down, which cancels the +2 degree tilt of the wing
~glued on the stick and the back 1.5 cm of the pod top, then a bead on both sides
~two tape saddles around each pod (at about 1.5 and 4 cm behind the leading edge)
~ESC leads run along the bottom of the wing to the centre and taped flat
The pods are parallel to the centreline and the motors spin freely by hand. Props stay off for now.

The motors sit a bit further back than the first plan, so the battery will go about 4 cm further forward when I balance it.

---

### JOURNAL #18 Aileron servos and the servo wires
Time spent : 1 hour 15 minutes

Nothing is cut into the wing, the servos are just glued on the bottom skin so the spar and the folded skin stay whole.

Servo position - 24 to 26.3 cm from the centreline, 8.5 to 11.8 cm behind the leading edge, lying on its side with the shaft towards the wing tip and at the back end (nearer to the aileron). The two servos are mirror images.
Before gluing, I centred each servo by hand and fitted the arm pointing straight down. Hot glue only on the servo case, never near the arm or the gears, then one strip of tape over the body.

<img width="600" alt="image" src="LINK_J18_1_servos_and_pods">

Horn - glued under the aileron in line with the servo arm (26.6 cm from the centreline), facing forward, the holes exactly below the hinge line.
Pushrod - 10 cm of 1 mm wire with a Z-bend at both ends. First bend goes in the horn hole farthest from the aileron, then hold the aileron level with the arm straight down, mark the wire at the arm's middle hole and make the second bend there.
Did the same on the other side. Checked that with the arm pointing down both ailerons are level and that nothing touches the pods

<img width="600" alt="image" src="LINK_J18_2_wing_bottom_servos">

<img width="600" alt="image" src="LINK_J18_3_servo_closeup">

The servo leads run along the bottom of the wing to the centre (about 8 cm behind the leading edge) and are taped flat, there both ailerons will plug into one Y-lead. I also had to join the servo leads with their connectors so they reach

<img width="600" alt="image" src="LINK_J18_4_servo_connectors">

Lastly the wires have to get into the fuselage, so I cut a small notch (2 cm long and 0.6 cm deep) in the top edge of each side wall at station 29.5 to 31.5 so the leads don't get pinched when the wing is on.

---

### JOURNAL #19 Wiring the ESCs
Time spent : 1 hour 30 minutes

Now the electronics I planned in journal #5 start to get real. Both ESCs share one battery and one throttle channel.

Power - the battery leads of both ESCs are soldered in parallel to one T plug, so one 3S battery feeds both. the ESCs are the red things in the pictures

<img width="600" alt="image" src="LINK_J19_1_esc_wiring">

Throttle - both ESCs go on one channel through a Y-lead. On one of the two plugs the red wire is cut and taped over (you can see the red tape on the end), so the two BECs don't fight each other

<img width="420" alt="image" src="LINK_J19_2_y_lead_red_tape">

The leads of both pods come along the bottom of the wing and meet in the middle, together with the aileron servo leads

<img width="420" alt="image" src="LINK_J19_3_leads_under_wing">

<img width="420" alt="image" src="LINK_J19_4_leads_pod_1">

<img width="420" alt="image" src="LINK_J19_5_leads_pod_2">

<img width="420" alt="image" src="LINK_J19_6_leads_pod_3">

<img width="600" alt="image" src="LINK_J19_7_leads_hanging">

Ps: this part looks like a bowl of noodles right now, I will tidy and tape everything flat later.

---

### JOURNAL #20 Wing on the fuselage
Time spent : 30 minutes

Now it is the first time I could see everything together. The wing sits on its seat on the fuselage, the leading edge on the shim and the trailing edge at station 43, held with 4 rubber bands hooked on the skewers (two straight, two crossed). Props are on too

<img width="600" alt="image" src="LINK_J20_1_wing_on_fuselage">

<img width="600" alt="image" src="LINK_J20_2_front_view_props">

<img width="600" alt="image" src="LINK_J20_3_side_view_props">

<img width="600" alt="image" src="LINK_J20_4_wing_top_floor">

<img width="600" alt="image" src="LINK_J20_5_wing_angle_floor">

It already looks like a proper plane and not a pile of foam :D
Next is the landing gear and tail skid, then balancing the plane and setting up the transmitter.

---

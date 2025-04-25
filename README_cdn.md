# Bill the Bootstrap Mill

<img src="/readme_images/Mill_Only.png" width="800">


The Bootstrap Mill is designed to be created from forms that can be cut on a PrintNC or similar router.  It uses commodity Ultra-High-Performance-Concrete (UHPC) or similar mixes to create the main forms of the machine frame.  Precision surfaces are meant to be optimized using epoxy transfer method and features are built into the frame to facilitate this more easily.  Table is 400x300mm with around 150mm of z clearance, and there is some over-travel so the spindle can reach all the way around the outside.  The box section off the the side is so that the spindle can travel over to access an ATC changer, and it also serves as a moutning point for the X motor to keep the frame mold as simple as possible.  The frame is abidextrous so the toolchanger could be mounted on either side with minimal modifications.

While the main CAD is drawn from scratch, the design obviously derives inspiration from the excellent frames and machines that are produced by https://www.cnc-technik-mueller.de/ as well as by other UHPC projects that have been posted across various websites.  By posting detailed CAD for both the machine and the molds it is our hope to create a project that anyone can reproduce, even if they are in a remote rural area without access to large machine tools that are commonly used to create the precision faces for frames like this.

<img src="/readme_images/mill_with_stand.png" width="800">


Note that this model uses components sourced from 3rd parties via GrabCAD.  All original design elements are copyright Expatria Technologies and licensed under the CERN-OHL-S 2.0 Strongly Reciprocal license.  In brief terms that means that if you use any portion of Expatria's original design in a derivative, you must release your complete design under the same or equivalent license and provide attribution to this repository.

All documentation is copyright 2025 Expatria Technologies.

### Concrete Notes

Bottom base volume:
Volume = 27.75 liters
66.6 KG
cubic feet
0.979982

Arch volume:
Volume = 30.12 liters
72.30 KG
1.0636778

Total is < 2.1 cubic feet.

138.3 lbs dry material = 1 cf. of wet mix
290.43 lbs of dry material total = 6.5 bags

### Major Components (needs update)
16mm ballscrews (1605)
20mm rails (HGR or RGR)

X axis ballscrew is 850mm
X Rails are 800mm HGH

Y axis ballscrew is 650mm
Y Rails are 600mm HGH

Z axis ballscrew is 350mm
Z Rails are 400mm HGW-CC

### Build Log
Table is 400x300mm with around 150mm of z clearance, and there is some over-travel so the spindle can reach all the way around the outside.  The box section off the the side is so that the spindle can travel over to access an ATC changer. 
The precision mounting for the rails will be done via the epoxy transfer method using a precision rod and straight edge.
Same with the joint between the fixed gantry and the base, will use annealed copper wire and steel-filled epoxy to true and bond the structure with bolts going through from the bottom into threaded inserts in the gantry.
![image](https://github.com/user-attachments/assets/176209fd-52f1-4cc6-b023-02ce6ac30be6)

I tried to pay attention to the ball-screw mounts using FK mounts and slotted plates since the relationship between the ballscrew and the frame will be subject to the layer of epoxy applied during the transfer process and that thickness is not a known datum.
In the same vein, using belt-drive between the screws and motors just to keep the package as tight as reasonably possible.  The main frame fits within a 600x600mm square.
The CAD so far is all original, but obviously lots of inspiration from the FS4MG as well as having a look at this project:
https://grabcad.com/library/uhpc-fixed-gantry-mini-cnc-machine-1
Sourcing the UHPC has been problematic in North America, but I will try using the Trinic UHPC mix and maybe do some experiments with different fibers and aggregate.
Similarly, I will try just using original JBWeld as the epoxy.  While I have found some sources for the more expensive steel-filled epoxies, it will be interesting to see how well things work with the more economical materials that you can just get at Canadian Tire.

The weight of the frame should be around 265 lbs and that is split fairly equally between the base and the gantry so it should not be too difficult to get everything into place for assembly.
Some useful vids about the different epoxy transfer techniques
https://www.youtube.com/watch?v=U7Qs-J2swIc
https://www.youtube.com/watch?v=5cvDmOos1Hk
I don't have something feel is postable yet, but I have an idea for the sidemount ATC using 3d printed herringbone gears to get a big reduction.
![image](https://github.com/user-attachments/assets/ce690171-c909-4891-bb03-2233d80e3576)

But yes, this is what has made me decide to go with the fixed-gantry approach, it is much easier to do the toolchanger compared to a lot of other options for this size/work area.

I am trying to keep the frame as bulky as possible as it's unlikely I will get quite the same performance out of the concrete as the FS3MG since I don't have access to the uber fancy mixes.
Trinic UHPC is just something that is relatively accessible to me.
Around here people haven't really moved on from just doing countertops.

Still have to do a couple of brackets (notably the Z motor) but I think the basic concept is coming together.  I just use extrusions for the stand as they are quick and easy.  Would be simple enough to convert the design to a weldment if someone was so inclined.
![image](https://github.com/user-attachments/assets/59d06d1b-aca2-4653-ad4b-d452e5018739)
![image](https://github.com/user-attachments/assets/c540b1ab-f21c-4ac9-9ef1-d38c85f79cc8)

Trying to come up with some small parts to help streamline the rail levelling.
Holder for the linear rod across the front of the axis:

![image](https://github.com/user-attachments/assets/eb74ab95-923d-46b4-904c-b78bbe305663)

![image](https://github.com/user-attachments/assets/30a84bb2-5579-42f6-9db1-723f300a7c7f)

simple set-screw to adjust the height of the master rail and minutely adjustable jack to adjust the height for casting the secondary rail.

![image](https://github.com/user-attachments/assets/61e4bec4-e937-46d4-bcd6-564eebc12be5)

Thanks to Adam the Machinist for the jack stand concept.
https://youtu.be/AdJzY1XF08A?si=qMtqyFMC3rUs9-7P

Working on the design for the gantry mold.  The 3d prints really make it neat to form some of the complex geometry.
![image](https://github.com/user-attachments/assets/5279fd59-d0e4-49f4-840f-493f63af5e1c)

And the base.
![image](https://github.com/user-attachments/assets/48582801-4634-47b9-ae54-ace0b89498d9)

Filling in the mold components.
![image](https://github.com/user-attachments/assets/31c6082e-bf59-4223-b917-1e11711bbd91)


![image](https://github.com/user-attachments/assets/94c7d27e-74fd-4ab6-811c-f48757943e5f)

![image](https://github.com/user-attachments/assets/ce68854b-e7c5-4f6f-b1df-69266feb4594)

Gantry mold is done.
![image](https://github.com/user-attachments/assets/332d6161-dad8-4634-a807-7082809f707d)

Good video about caulking concrete molds:
https://www.youtube.com/watch?v=axKAnAbgS1g

Not sure how well this shows up in the picture, but first go casting something out of UHPC:
![image](https://github.com/user-attachments/assets/24d97773-7ca2-4d9d-9ec9-2077be36f5ff)

Some small air bubbles, and still I think the mix needs more mixing (will use ice instead of liquid water next time)
I used carnuba paste wax as the mold release in two coats and it was great, the part came right out of the mold.
It really doesn't show in the picture, but the texture of the melamine is captured quite precisely by the concrete.


Results from self-levelling epoxy on the 300x650mm concrete 'surface' plate that I'll be using to form the rail beds on the main frame sections:

Can confirm that gravity works and the earth is flat.
![image](https://github.com/user-attachments/assets/3209543c-9c4c-4296-ad9a-c6a5a9c37ef7)

Basically, measuring against the granite straight edge the epoxy plate is ~15 microns fron end to end, and I can't really see a measurable deviation across the short width. 
I still have a little bit more work to do if I wanted to completely eliminate the meniscus, but I think that as-is it's good enough for my purposes as it will ensure that the rails mounting beds are quite parallel and flat.  Plus I expect there will be some amount of distortion from the act of lifting this plate and then placing it onto the frame for casting, so I don't think it's worth chasing microns just now on this piece.
Started building the mold for the lower casting:
![image](https://github.com/user-attachments/assets/651407e8-c506-4d83-a2ac-c4e532d3be39)

Still some cleanup to do on the caulking.  Lesson learned here is that you really can't have too much coverage with the paste wax ahead of applying the caulk.  Where I had good coverage, the extra caulk comes off really easily, but where I missed a spot, especially on the 3d prints with their rough texture it leaves a bit of a mess to clean up. 
![image](https://github.com/user-attachments/assets/ef83da4d-96cd-4b92-97fc-8d7c000e433e)

(bannana for scale)
Basically the X and Y axis are 600mm.
Machineable travels are ~400mm in X and 300mm in Y
150mm in Z

Running out of things to do other than pour the concrete.
![image](https://github.com/user-attachments/assets/81c1d423-5fb6-49fa-8554-6aa832cd997b)

FS4MG is a good deal IMO.  Only reason I am rolling my own was that I couldn't get one (I literally live in the middle of nowhere).

But it has been fun so far doing my own design and I do get to make the thing exactly how I want it.
I think that the frame component of Bill is around 1/4-1/3 (threaded inserts aren't free) what you'd pay for an FS4MG frame ignoring shipping, but there's still a fairly significant time component that you shouldn't ignore. 
If you factor in shipping, then the DIY frame is more compelling if you are outside EU+GBR.
In North America there is nothing like the Technik frames, zero alternatives that are the same quality or capability.

I still have to cast the gantry and I am planning to do that with an assistant and I'll try to take photos of the process from start to finish.
The Trinic premix is  38 USD per 45lb bag plus shipping.  I think it came out to around 65 usd per bag for me and it takes 8 (one extra) to make a Bill mill.
FWIW I am mixing in a small drum mixer and it does work fine, just takes longer than I think a turbine mixer would take, but the slump test is in line with expectations.
The ice helps a lot with the drum mixer.
I did try a double-paddle mixer, and it works better than the drum.  But I think you need a professional level hand mixer as mine burned out the brushes after mixing just 2 buckets.

Here is what we ended up with.

![image](https://github.com/user-attachments/assets/aa2b20b6-4961-4a05-bc59-dbd2bd5c829e)

![image](https://github.com/user-attachments/assets/f62c3979-9aa2-4637-8364-c8b79a78cee5)

Overall it seems ok.  There are a few more bug holes than I'd like, but the shape is what it's supposed to be and nothing cracked when we flipped it over.

Lessons from the first go at epoxy surface transfer:
1) As always, paste wax is your friend.  While it took some convincing, the master plate came off pretty easily all things considered.
2) More epoxy is better than less IMO.  We had some minor drama placing the top plate and had to shift it after we put it down, and I think that if I'd had less epoxy this would have been a bigger issues.
3) I should have masked both side of the run, though the inner edge is basically going to be hidden so I'm not going to spend much time on it here.

Not sure how flat it is yet, I won't have time to measure it for a few days here, but overall this seemed to work pretty good.

![image](https://github.com/user-attachments/assets/dd7ad844-e190-4335-a305-fbd0ae54f0a9)

Before I remove the tape I want to re-expose the rail holes and mount the rails so that they are supporting the epoxy when I pull the tape, but I am out of time for now. 
Also I want to come up with a better tool for applying the epoxy, a basic spreader was kind of annoying to work with.

Ok, I found some extra time and measured things a bit, and the biggest issue is that in the above photo the near rail is dropping about 15-20 microns on like the last 60mm of travel.  Everything else is more or less within 10 microns of twist and each individual guideway is within 5 microns along the length (aside from above dropping a bit).

The spec for the P grade linear rails would be 7 microns, so it's pretty close 'out of the box' 

Probably I will use a bit of additional epoxy and the straight edge to bring it in line with the rest of that side, and then lap/sand/scrape things a bit on both sides until I lose patience.

Some updates after working on trying to level the rail beds.
1) The small washers on the threaded inserts are a bit of a bad idea IMO.  Unless they are a very precise fit to the threaded inserts, they will create a small layer of concrete around the outside of the washer between the surface and the threaded insert.  Bottom line, if you are going to be putting down an epoxy layer and/or you don't need the threaded insert recessed, don't use a washer.
2) The gravity surface plate was a bit of a red herring.  The issue that I ran into was that while the intial out of the box rail beds are pretty good, they are not as good as I wanted/needed for this build.  So when I started blueing and scraping the surfaces to bring them in line, I needed to remove quite a bit more material than I wanted, and this meant that the epoxy layers got quite thin.  Eventually it got so thin in places that it started lifting from the concrete below, and so this made it impossible to blue the surface any more because you'd get false readings.  So I am re-doing the rail beds using the straight-edge directly via the precision rod approach and making sure to have at least 2.5mm of expoxy under the linear rails.

Epoxy replication with a precision straight edge (2x more accurate than a precision rod according to spec).  I did the 2nd rail with the base on the stand.  This was the most stable platform I could find for this.

![image](https://github.com/user-attachments/assets/508acfcf-935e-42e6-a837-b1d9116ade1b)

![image](https://github.com/user-attachments/assets/9fae2ab5-8789-47e4-8616-4d8814064eeb)
I used the spirit level to transfer the parallelism from the 1st side to the second side.

![image](https://github.com/user-attachments/assets/0e81f9da-e4c2-4d8f-bbe4-e3f1f8df21da)

![image](https://github.com/user-attachments/assets/c3d2bd16-3472-4618-aa1b-91f19699766e)
Ended up just using a simple adjustment screw in a 3d printed part.  This was quick and easy and I couldn't measure any deflection or settling in the plastic before doing the epoxy and final levelling.
![image](https://github.com/user-attachments/assets/f702ff99-0ff8-47aa-8618-5d33c6022714)
WIthout any scraping I ended up with about 15 microns of twist over the 600mm rails but the rail seats themselves are perfectly flat as per the straight-edge (2 microns).  I am out of patience and moving on to the gantry.

With plate installed.

![image](https://github.com/user-attachments/assets/37073053-ff66-4583-a398-4366dd6577c8)

Alrighty, lots of progress the past couple of weeks:

![image](https://github.com/user-attachments/assets/2566f7df-db9c-4090-9dc3-816467dd65e0)
Just a test fit here, they are not yet attached.  But I am pretty happy with the way things fit together.  Lots of adjustment to get the frame sqaure.   Couple of minor setbacks, but still pushing forward.  The rails that I received for the X axis were cut wrong and the holes were too close to the ends, not 30mm like the Y rails.  So for the moment I just cut down and stuck some HLTNC rails on there just to keep things moving while I wait for new rails.
Also, I really wish I had attached the extension and replicated the whole length at once.  I did it in 2 sections and the extension is not nearly as good as the main part of the X.  I am going to just live with it as the rest of the replication is quite good (same as the Y) and I am eager to push on and get things moving.
I think that things are good enough that I can get the axes nice and square in XY, which is really the most critical step.  If there are offsets in XZ or YZ I can adjust for those in other ways, either through shimming or surfacing the table.
But it is really good to see the cast sections come together so nicely. 

That's not coming apart into 2 pieces again.  Some sanding to do and then it's ready for paint.

![image](https://github.com/user-attachments/assets/36708a55-3346-46e2-bcce-587a690a7dac)
Some notes from attaching and squaring the gantry: 
It is definitely worth the effort to get things as good as you can when attaching the gantry to the base.  Despite my best efforts, after the epoxy cured I was disappointed to see that I was getting around 75 microns (3 thou) out of square across the 400mm X travel 😦 .  But I was able to fix this by actually changing the angle of the Y axis rails very slightly, and got the squarness error down to +- 2.5 microns across the whole travel, basically as good as I can measure really.  This is actually a bit of an advantage to not having a pre-machined edge that is pushing against the rails, if I had that machined into the base I'd be screwed or have to come up with another plan, maybe involving shimming the X axis rails to fix the angles.  As it is, I am quite happy with the geometry. 
I think that part of my initial inaccuracy came from the fact that I was trying to make the gantry square in the YZ dimension.  In hindsight, it was stupid to really try to do this.  Basically I ran out of adjustment (squished the annealed copper wire under the feet as far as it could go).  I was a little stumped by this, but I think it is just due to the fact that there is really no accuracy beyond woodworking on the angle between the feet and the X axis face, I should have just let the epoxy do its thing and I will fix any YZ issue by shimming the Z axis; this was always the plan to tram the Z axis in and if I had ignored this I might not have had to go back and adjust the Y axis to fix the XY squareness. 
Same with XZ, I will just adjust this by either facing the table or shimming the table where it rides on the Y axis carriages. 

Other than that, the assembly was pretty straightforward.  Lift up the gantry.  Using pliers/tweezers drop a couple of pieces of copper wire at the front and back of each foot, then using sticks apply a bunch of epoxy and lower the gantry down.  I got lots of epoxy squished out of all sides so to me the coverage is at least decent.  I ended up using threaded rods through to the bottom of the base and things are bolted/adjusted using some nuts and oversize washers.
After the epoxy cured and I did the final torquing it felt very good, the nuts tighted up and you could feel them take up the torque with no deflection.

This is the setup I used to tram the x axis nod in line with the y axis travel.   I ended up with 0.2mm shims to get it within ~12 microns over the 9 inches of span on the granite square. 

![image](https://github.com/user-attachments/assets/b22ef306-d3e1-41a7-b3f4-f377728e63eb)

![image](https://github.com/user-attachments/assets/4fb98d44-26f5-456d-ade3-29ead19d7d0c)

Don't mind the over-long M6 bolts at the top, just what I had on hand.
![image](https://github.com/user-attachments/assets/a1a09c51-110e-45f5-a398-8460e8e6c6f8)
Not sure who designed this Z axis, but they were being a little too clever trying to keep things compact.  After a lot of faffing to get clearance for the grease fittings, it finally came together.  Started measuring the XZ parallax and it's not great.  125 microns over 120mm.  No worries, you say, just tram it into square.  But adjusting tram on this thing in XZ is really difficult, the adjustment is in the bolts holding it to the X axis, and those are buried so it all has to come apart to make adjustments, and there's not really a good way to take a measurement while you have it apart.
Going to leave it for tonight and think on the best way forward.
I also don't think that the current Z design is really optimal for the mill.  It's a reverse Z (compared to PrintNC) as I originally planned to run a small 60K ISO10 spindle on here and I didn't want the spindle sticking out too far so the reverse Z seemed to make sense.  Also it's what is on the FS3/4/5MG machines, so it made sense to go that direction.  But in hindsight I think that it's not the best fit for an ISO20 spindle that can have more stickout, and with ATC you can always get an extended holder if you need to do something like surface the table.
So I might just leave the parallax error as-is (maybe do a skew correction in the control) and push on to get the mill functional enough for it to make itself a new Z axis that is a bit better design.

On the flip side, the table is within 20 microns in Z along both X and Y axes, so the fundamental geometry is there, just need some adjustment in the Z axis to get the movement in XZ sorted out.

Thinking about this, I can disassemble the Z and then take a measurement off the X rail (it is straight and square to the table) to align the machined side of the rear Z plate.  Might not be perfect, but should be able to get it a lot closer than it is now. 

Took it all apart (again) and put it back together, got it within about 20-25 microns in XZ and YZ, so it's ok for now.  I was wanting better than that, but it's a step up from my old mill so I will take it.

Spindle fit check looks good at least.
![image](https://github.com/user-attachments/assets/a3dc181a-fe8a-4019-8acf-3fda0cc365b8)
Devil is always in the details.  So many little things crop up to slow things down.  Latest is just the fact that I need to make some spacers to move the FK blocks so that the pulleys will fit with the shorter motor shafts I have on the current setup; just using some integrated stepper motors to get started.  Fancy servos maybe later, but for now I really want to get to cutting.
I did take the time to face the back of the spindle mount when I was doing the hole pattern, and I also cleaned up the bore.  These cast mounts are pretty warped out of the box.

Going to call the easy part finished here:
![image](https://github.com/user-attachments/assets/e611fcce-fb35-4183-9207-36fb910ada37)
Basically the physical build of the main machine is complete.  Motors are mounted, belts are tensioned, mounts for homing sensors are there.  Now the hard part, plumbing the air lines for the spindle and coolant, as well as all of the electrical wiring.
Still lots of stuff to make for the enclosure and a place to house the electronics and control.


![image](https://github.com/user-attachments/assets/8169d823-5784-4bf6-b7d9-297fd7dc2415)

![image](https://github.com/user-attachments/assets/7ccb8049-8878-4be2-b287-4f1288461895)

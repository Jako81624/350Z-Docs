## Clutch Hydraulic Lines
When upgrading the clutch, it is quite common that supplemental modification to the hydraulic components will be required too.  In regards to the HR-generation, the CSC (Concentric Slave Cylinder) is known to have a limited lifespan - though replacing it with an aftermarket unit tends to rememdy this issue, and some aftermarket clutch manufacturers create kits that are designed for use with OEM/OEM-Style CSCs (OS Giken, for example).

TODO: Add dimensions and sketch of slave cylinder

At the other end of the system is the master cylinder.  Details below:

    DE+:
        Bore: 
        - 5/8"in

    HR:
        Bore: 
        - 11/16"in

    All:
        Thread Size and Pitch:
        - M10x1.0

TODO: Move these to their own dedicated section

The clutch lines in the 350Z are notorious for being difficult to bleed.  This will lead a lot of people to replacing them.  In stock form, both the pre-HR and HR generation use four clutch lines.  The first leads to the clutch damper located in the front-left wheel-well behind the rearwards plastic shroud.  The second leads from the aformentioned damper, to a bracket underneath the car.  This bracket is what starts the third section - this time using flexible hose.  The final section is a short and arguably redunant hardline run that exits the flexible hose and performs a u-turn to go back into the CSC termination block.  As of writing, my experience is with the HR generation, and in this case the flexible hose is secured at both ends with horseshoe clips to a bracket on the chassis and the gearbox respectively.

The clutch lines are all threaded in M10x1.0.  When replacing the clutch lines, some will opt to replace only the soft line and leave the hardline in place.  There are many kits out there that achieve this, and, in the case of the HR, the length of the flexible section will be no longer than approximately 30cm (data sourced from UKDM RHD vehicle).

Hose Details:

    DE+:
        - Unknown, please fork and submit a pull req if known
    HR:
        Lengths:
            Short (Flexi):
            - Approx. 30cm
            Combined run (CMC to CSC termination block)
            - Approx. 228cm

        Fittings:
            Short (Flexi):
            - 2x Female M10x1.0 Circlip Fittings
            Short (Flexi to CSC termination block):
            - M10x.10 Male (Convex lip, flexi end) to M10x1.0 Male (Concave lip, termination block end)
            Hard Line (CMC to Damper)
            - M10x1.0 Male to M10x1.0 Male
            Hard Line (Damper to Flexi)
            - M10x1.0 Male to M10x1.0 Male

Many people will replace the master cylinder with an aftermarket unit when using heavier aftermarket clutches.  There is no adjustment to be made in hydraulic system.  Clutch "bite" and modulation is a function of the throw distance between the face of the CSC and your pressure plate and the bore/displacement of your master cylinder.  Clutch "weight" is a function of pressure plate strength and CSC/CMC bore.  This being said, it is *possible* to make some minor adjustments to the height of your clutch pedal by winding in the clevis on your master cylinder, and winding out either your upper clutch stopper on cars unequipped with cruise control or your clutch ASCD on cruise-equipped vehicles.  Both are located in the same place.  This will **NOT** change the characteristics of your clutch - just the height of your pedal.

There are a couple of methods by which you can adjust the modulation of your clutch. One is by changing the bore ratio between the CSC and CMC i.e. a smaller bore CMC will require less foot pressure and will displace less clutch fluid per unit distance.  The obvious warning here is that you will have to ensure that your CMC can displace _enough_ fluid to fully disengage your clutch, or you risk damaging your clutch and/or being unable to disengage the transmission from the engine entirely.  Displacement of the stock CMC is currently not documented, but based on aftermarket units I perform my calculations with 1.25" of travel.  The other option is to design a mechanism by which you can adjust the ratio of pedal to CMC plunger movement.  For example, attaching the CMC plunger closer to the point of pedal rotation would result in less lateral movement - however, this would have the unintended side-effect of actuating the plunger at an extreme angle and potentially accelerating wear significantly.  If a design comes to fruition, it will be documented here.

Common replacements for CMCs include both Tilton and Wilwood.  Dimensions are available from the manufacturer for fabricators.  Dimensions of the stock CMC will be included here when they have been obtained.  The PCD is larger than the Wilwood GS Remote as of the time of writing, and the firewall bolts appear to approximately be rotated at a 20 degree angle from the horizontal plane.  CAD drawings and adapter plates will be open sourced and included here when completed.

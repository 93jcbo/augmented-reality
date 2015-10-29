#Augmented Reality: The magical interface
======================
######JACOB AMADOR December, 2013

##Introduction
------------

Aurasma and Layar are two globally used Augmented Reality mobile apps
[[3](#r3 "Aurasma (July 10, 2013). Aurasma widens lead as world‘s leading augmented reality platform [Press release]")], [[13](#r13 "Layar (August 15, 2013). Layar Sees Growing Adoption And Tangible Results With Interactive Print")].
Both apps are used by publishers and developers to integrate augmented
reality with their product or other material. Layar boasts 55,000
publishers and 33 million app downloads. Aurasma has 20,000 publishers
and 6 million monthly users. Aurasma requires few steps to publish an
augmented reality work. Matt Mills
[[16](#r16 "Mills, M. (July, 2012). Image recognition that triggers augmented reality [Video file]")]
spoke at TED and in a few minutes was able to create an augmented
reality image and demonstrate it to the audience. Despite the combined
39 million app downloads from Layar and Aurasma alone, overall awareness
of augmented reality (AR) is low
[[9](#r9 "Juniper Research (2013a). Augmented Reality - The 8th mass medium [White paper]")].

Augmented reality is not a 21st century idea, but people do not seem to
understand what AR is, what it can do, and how it does it. This paper
will provide a brief explanation of the “what” and the “how” of AR. Once
an understanding of AR is reached we will address its function as a user
interface (UI). While there are no definitive rules for the design of
the interface, guidelines for AR UI design have been proposed in several
works
[[5](#r5 "Dao, B., & Gabbard, J. L. (2013, March). Early steps towards understanding text legibility in handheld augmented reality")], [[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")], [[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")]
which we will also examine this paper.

### History

Efforts at creating an augmented reality system began in 1960‘s,
although the term “Augmented Reality” wasn’t used until 1992 by Boeing‘s
R&D department
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")].
In 1968 Ivan Sutherland and his students at Harvard created a
see-through head mounted display (HMD) that is known as the pioneer work
for the AR field
[[26](#r26 "Van Krevelen, D. W. F., & Poelman, R. (2010). A survey of augmented reality technologies, applications and limitations")].

### What is AR now?

According to Kipper and Rampolla
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")],
Augmented Reality refers to the process of overlaying digital content
such as pictures and graphics, texts, video, or sound on top of the
real-world environment in real-time. Usually, the overlay process will
be triggered by a location or object recognition. For Aurasma, these
“triggers” are referred to as “Auras”
[[3](#r3 "Aurasma (July 10, 2013). Aurasma widens lead as world‘s leading augmented reality platform [Press release]")],
but each app has its own names for triggers. An AR system or device is
therefore the hardware or set of hardware that is used to accomplish an
augmented reality. Software is needed to create the display of an
augmented reality and in most cases is in the form of an AR mobile app
or web service that communicates with a content server. Kipper and
Rampolla describe examples that might be confused as AR but no not
quality including an image edited in Photoshop, 3D objects edited into
movies like “Jurassic Park,” and Google Goggles. The previous examples
lack the blend of digital or virtual content and the real environment in
real time.

### What makes it different than virtual reality?

The terms virtual content and virtual objects are used often when
speaking about AR, this is because AR is a variation of virtual reality
(VR) [[4](#r4 "Azuma, R. T. (1997). A survey of augmented reality")].
VR is accomplished by immersing a user into a completely artificial
environment assisted by head-mounted displays, gloves, headphones, and
standing platforms. Auditory, visual, and tactile senses are monitored
and controlled by the VR system
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")].
In contrast, AR allows for awareness and interaction with the real world
while only engaging one or two of the senses at a time. AR uses
digitally-created content, like VR, but instead of immersing the user in
the digital content, it is overlayed on top of the real world.

##Platforms
---------

Another difference between VR and AR is that AR does not require a user
to remain in the same spot. Most VR systems took up a whole room and its
components could not me moved
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")].
However, AR can be portable as well as stationary.

### Stationary

Stationary AR systems can come in the form of kiosks, such as the ones
that belong to stores or museums
[[27](#r27 "Wojciechowski, R., Walczak, K., White, M., & Cellary, W. (2004). Building virtual and augmented reality museum exhibitions")],
or can even use a webcam and personal computer
[[29](#r29 "Zugara (2013). Webcam social shopper software for kiosks [Demo]")].
The user can interact with the stationary system by walking up to it and
either manipulating objects for AR or being a part of the AR themselves.
The latter case can be seen on YouTube
[[1](#r1 "AdvertisingAdverts (February 17th, 2012). National Geographic – Augmented Reality Campaign [Video file]")]
in a video of people interacting with virtual tigers and dolphins.

### Portable

AR research and development seems to be focused mobile and wearable
technology. Although researchers often use the term “mobile AR” to
represent both handheld and wearable AR devices, in this paper mobile AR
is intended to refer to handheld devices while portable AR refers to
both handheld and wearable devices.

#### Mobile

Mobile devices like iPhones, smartphones, and tablets are convenient for
AR because AR hardware is included in the devices. Mobile devices only
require special software to display AR
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
The gyroscope, compass, camera, speakers, and screen are the main
components that AR uses on mobile devices

Due to their power efficiency design, mobile AR systems cannot
accomplish powerful AR displays
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
Form factor also presents a challenge to AR interfaces because not much
detail can be used. Ganapathy
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")]
explains that bigger screens and landscape oriented screens can have a
denser amount of information and images can also have more detail.
Smaller screens therefore should have less detail and information
density than bigger screens to retain usability.

#### Wearable

By 2018, wearable technology is expected to be a \$19 billion market
[[10](#r10 "Juniper Research (2013b). Smart wearables … beyond mobile [White paper]")].
Wearable AR device will most likely be included in that market. Google
Glass is an example of a device that uses AR, although it is not an
AR-only device. Most AR wearables will probably be in the form of HMD‘s
like the ones developed by Steve Mann
[[14](#r14 "Matyszczyk, C. (June 17th, 2012). Google-style glasses led to attack in McDonald's, professor says")],
Starner et al.
[[24](#r24 "Starner, T., Mann, S., Rhodes, B., Levine, J., Healey, J., Kirsch, D., Picard, R. & Pentland, A. (1997). Augmented reality through wearable computing")],
and Höllerer et al.
[[8](#r8 "Höllerer, T., Feiner, S., Terauchi, T., Rashid, G., & Hallaway, D. (1999). Exploring MARS: developing indoor and outdoor user interfaces to a mobile augmented reality system")].

##How does AR work?
-----------------

Augmented reality is versatile because it requires technology that
already exists on many mobile devices or that can be found at an
electronics store. Software and hardware have to work together to
develop the methods to accomplish an AR. The AR process can be divided
into three categories: recognition, processing, and display. Processing
often takes place on a server separate from the device
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")],
and because this paper is focused more towards the interaction with AR,
focus will remain on the recognition and display methods of AR.

### Recognition

There are two methods that an AR system can use to recognize a trigger
object or location. The first is by localization. Localization,
according to Gervautz and Schmalstieg (2012), is the measurement of the
device in relation to the object of interest (OI). Localization is
usually accomplished by using the GPS that most mobile devices already
have. Localization works best in an outdoors environment because of weak
indoor GPS signal
[[18](#r18 "Mulloni, A., Seichter, H., & Schmalstieg, D. (2011, August). Handheld augmented reality indoor navigation with activity-based instructions")].

The second method of recognition uses computer vision to recognize OI‘s.
Computer vision can be divided into four types
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
Using fiducial markers, or points of reference, an AR system can
recognize specific patterns on an OI and overlay the corresponding
image. With natural feature tracking the device can extract points on an
OI and compare them to an external database for recognition. A global
localization system uses 3D reconstructions of an environment to compare
buildings and there locations for recognition. This process does not use
GPS, but a premade 3D map of the area. Lastly, on-the-fly reconstruction
devices can be used to create a virtual environment using the camera
stream and compare it to other 3D maps.

At the moment the technology needed for computer vision recognition is
not reliable enough to use on portable devices. Therefore the best AR
systems will rely on localization and computer vision to recognize OI
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].

### Display

Proper display of an AR overlay requires tracking of the OI to maintain
a smooth display if the position of the device changes. Tracking is the
measurement of the device position relative to the OI by using available
sensor data and the computer vision types previously discussed
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
The display of AR is highly dependent on the graphics processor the AR
device has. Stationary devices can afford more to use more power for the
graphics processor to provide better overlays than portable devices can.
However, Metaio
[[15](#r15 "Metaio (February 21, 2013). Metaio brings world‘s first Augmented Reality Accelerated chipset to market, signs agreement with ST-Ericsson to integrate future mobile platforms [Press release]")],
an AR company, announced earlier this year that they will be partnering
with Ericsson to integrate Metaio‘s AREngine chipset into the future
mobile devices. The press release declares that the AREngine will
“drastically [reduce] power consumption making all-day AR experiences
possible”[[15](#r15 "Metaio (February 21, 2013). Metaio brings world‘s first Augmented Reality Accelerated chipset to market, signs agreement with ST-Ericsson to integrate future mobile platforms [Press release]")].
A processor like the AREngine would surely benefit both the display and
recognition stages of mobile AR devices.

##How is AR used?
---------------

Current AR usage is not limited to only wearable or mobile device
platforms, however, their portability allows for the versatility of use
across several markets like video games, tourism, and education. A
single device can be used for different markets depending on the apps or
software installed. Kiosks and other stationary AR systems are limited
in the number of uses. Kiosks will usually present specific information
such as the ones used in museum exhibitions
[[27](#r27 "Wojciechowski, R., Walczak, K., White, M., & Cellary, W. (2004). Building virtual and augmented reality museum exhibitions")].
In addition more work in AR has been done with wearable and mobile
systems than stationary systems. For these reasons, when we speak about
AR or AR systems in the rest of the paper, it will be in reference to
wearable or mobile AR and AR systems only unless otherwise specified.

### Gaming and Entertainment

The portability of Augmented Reality makes it a unique gaming interface.
With AR, a gamer has six degrees of freedom to move in to interact with
a game
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
Portable AR devices can also be used to play games that take place over
large areas for example a city. Virtual pieces of the game can be placed
at different locations in the environment which the AR device can detect
and alert the player. Projecting avatars into the real world through an
AR device yet another form of gaming that even encourages multiplayer
interactions
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")].

Examples of Augmented Reality used for gaming and entertainment are not
hard to come by. Ahonen
[[2](#r2 "Ahonen, T. (2012, June 12). Augmented Reality - the 8th Mass Medium [Video file]")]
describes several games that are currently being used in Japan.
iButterfly is a service that people can subscribe to and it involves
catching virtual butterflies throughout the city. You can look for
butterflies when you use the iButterfly mobile AR app and depending on
what species you catch, you earn coupons or points that you can spend in
an actual store. Balloon Fishing is another popular game that can be
played in any surface of water. The user opens the AR app and uses their
mobile device to fish in a body of water. A body of water can be a
puddle in the street, a bucket of water, or even a cup of water.

### Tourism

Navigation and tourism AR systems mostly rely on localization instead of
image recognition to determine display overlays. AR navigation is a
safer alternative to other types of digital navigation because the user
can keep the real world in view instead of looking away from the
direction of movement
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
Outdoor navigation systems use GPS for localization, but indoors GPS is
signal is weak. Mulloni et al.
[[18](#r18 "Mulloni, A., Seichter, H., & Schmalstieg, D. (2011, August). Handheld augmented reality indoor navigation with activity-based instructions")]
improved indoor navigation by creating an AR system that uses GPS as
well as pre-designated information points. The user moves between
information points to receive directions while weak GPS localization can
be used to make sure they don‘t deviate from the path.

A tourist that does not know the local language can use AR app World
Lens [[28](#r28 "World Lens (n.d.) [Demo]")] to translate text to
their own language. Tourist would also be able to use AR systems as a
virtual tour guide
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")].
Markers can be placed at GPS positions and the AR device can alert the
user when they are close to one. Text information or a video about the
landmark can then be overlayed on the screen. An example of such an app
is called “Tuscany + Augmented Reality”
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")].
It displays points of interest for travelers in Tuscany.

### Shopping

Marketing leads to sales and AR has potential to be used at every step
in the process
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
With an app like Layar
[[13](#r13 "Layar (August 15, 2013). Layar Sees Growing Adoption And Tangible Results With Interactive Print")]
businesses could associate their brand or products with magazines,
flyer, or other ads in an interactive digital form. If marketing can get
customers in the store, they can use AR to navigate the store, identify
the items they want, and even try on clothes without having to enter a
changing room. Zugara
[[29](#r29 "Zugara (2013). Webcam social shopper software for kiosks [Demo]")]
is a company that has patented AR software that uses a kiosk or a web
cam to record video of a shopper and then the shopper can choose
different items to overlay their own body to see how it might look on
them.

### Education

Both portable and stationary AR systems can be used for education and
training. As mentioned before, museums can use AR kiosk to improve
visitors‘ experience by making it more interactive. Wojciechowski et al.
[[27](#r27 "Wojciechowski, R., Walczak, K., White, M., & Cellary, W. (2004). Building virtual and augmented reality museum exhibitions")]
report on a project named Augmented Representation of Cultural Objects
(ARCO). Using ARCO museum visitors use cards with special markers that
represent a certain artifact and present it to the kiosk. The visitors
then see a virtual representation of the artifact as well as additional
text about the artifact on the kiosk display. They can then move the
card around to change the position of the object.

Reiners, Stricker, Klinker, and Müller
[[21](#r21 "Reiners, D., Stricker, D., Klinker, G., & Müller, S. (1998). Augmented reality for construction tasks: doorlock assembly")]
created a HMD AR system used to aid the assembly of car doorlocks for
BMW. The doorlock assembly process without AR is difficult because of
the positioning the assembler‘s hands are in and the low visibility of
the parts in the door. At the time of development Reiners et al. were
limited in tracking of objects and naïve users could not perform the
successfully. Eventually the HMD AR systems can help other type of
professionals accomplish work that requires assembly or disassembly
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")].
Unlike an ordinary manual, the AR system could overlay the steps needed
to be taken and highlight pieces of interest sparing the person from
looking away for instruction
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].

### Health

There are also applications in health care of AR, for example, relieving
phantom limb pain. Phantom limb sensation, the phenomena where an
amputee still perceives sensation from the missing limb, becomes a
problem when the person experiences pain in said limb. O'Neill and de
Paor
[[19](#r19 "O'Neill, K., & de Paor, A. (2011). The Potency of Optical and Augmented Reality Mirror Boxes in Amputees and People with Intact Limbs")]
are trying to solve the problem by applying AR. The current method to
relieve phantom limb pain is by using a mirror box illusion to give the
impression that the missing limb is intact. The goal is that by using AR
to overlay a digital reconstruction of the missing limb, patients that
do not respond well to the mirror box can also find relief
[[19](#r19 "O'Neill, K., & de Paor, A. (2011). The Potency of Optical and Augmented Reality Mirror Boxes in Amputees and People with Intact Limbs")].

Shuhaiber
[[22](#r22 "Shuhaiber, J. H. (2004). Augmented reality in surgery")]
describes how AR is used in neurosurgery. According to Shuhaiber,
neurosurgeons try to remove as little brain tissue as they can when
removing a tumor. The process of locating the tumor is facilitated by
using an MRI but the surgeon has to relate the patient‘s brain with a
separate display. By using AR, a 3D map can be overlayed directly onto
the patient‘s brain tissue allowing the surgeon to remove only the
necessary tissue.

### Other Proposals

Not all types of AR uses have been explored but there are other
suggestions. One such suggestion is for using AR for an enhanced memory
system
[[24](#r24 "Starner, T., Mann, S., Rhodes, B., Levine, J., Healey, J., Kirsch, D., Picard, R. & Pentland, A. (1997). Augmented reality through wearable computing")].
The enhanced memory system is modeled after the Remembrance Agent (RA)
for Emacs. The AR RA can be used to augment memory by searching for old
personal files that are relevant to what the user is currently working
on or reading. A user‘s conversation, book, essay, etc. could trigger
the AR RA to look up relevant resources or references that have to do
with the current information the user is receiving. The AR RA would
display this information to the user‘s display and they can choose
whether or not to pursue it further.

Some visual impairments, such as scotomas or loss of depth perception,
could possibly be corrected by modifying AR systems. Starner et al.
[[24](#r24 "Starner, T., Mann, S., Rhodes, B., Levine, J., Healey, J., Kirsch, D., Picard, R. & Pentland, A. (1997). Augmented reality through wearable computing")]
proposed using “mediated reality” to display an adjusted version of the
real world without overlaying onto the faulty version of the real world.
The user wears an opaque HMD with an attached camera. The input from the
camera is processed by the computer, remapped according to the visual
ability of the user and then displayed on the HMD. The visual remapping
can be accomplished almost real-time.

Although social networking sites have yet to venture into AR there ways
they can get involved. Recognizr is a prototype mobile app that connects
a person with their online social networking accounts
[[11](#r11 "Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging technologies guide to AR")].
The person using Recognizr can use the devices video stream to see a
friend‘s information overlayed on the display. Another idea is to use AR
to leave virtual comments and reviews of different locations. Users of
this app could scan a menu and see comments next to items and what other
people thought about them
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].

Starner et al.
[[24](#r24 "Starner, T., Mann, S., Rhodes, B., Levine, J., Healey, J., Kirsch, D., Picard, R. & Pentland, A. (1997). Augmented reality through wearable computing")]
also suggested combining AR with affective computing, the idea that
computer technology can be used to interpret and simulate human emotions
[[17](#r17 "MIT Media Lab (n.d.). Affective Computing [Description]")].
Some AR systems would be able to be adapted to record body temperature,
blood pressure, foot pressure, and skin responses. With this input the
AR system can make an educated guess at what behavior the user is
involved in, and presenting the relevant information on the display
before the user knows he needed it. Another situation the affective AR
system could detect is stress. If the biological input combined with a
scheduled appointment suggests that the user is stressed, the AR system
could block all incoming messages or bad news so the user does not
receive more stressors.

##Creating the AR interface
-------------------------

Ganapathy
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")]
believes that the success of the AR user interface depends on the
designer‘s understanding of the context of each interaction. Users
interact with the AR interface for two reasons. They are either
interacting with the device to initiate or alter a change in the current
display (manipulation) or they are interacting with the device to
examine OI‘s or virtual content (evaluation). The focal point of the UI
in this paper will be on visual feedback simply because it is currently
the most used type of AR display.

### Manipulation

A user can input information with speech, gestures, device position, or
tactile modalities
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")].
Speech is a useful way to input specific data, such as a search query,
in a short amount of time, but can be subject to miscues if a command is
accidentally said out loud. Gesture provides a quick method of scrolling
and manipulating space by panning, zooming, or rotating an environment.
Gesture can also be subject to unintended commands. Position sensors in
the device can also result in a change of the display and allow for
natural movements. Finally tactile, or multi-touch, is the most common
nontraditional interface and lets the user directly “touch” a certain
point on the display.

Gervautz and Schmalstieg
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")]
classified the some interface manipulation types. The first is called
ray picking and they state it‘s the primary manipulation mode. Ray
picking involves pointing the device‘s camera towards the OI so that the
“ray” from the camera picks the first object it hits. Sometimes, though,
aiming the device can be difficult and obstructions between the device
and OI are not ignored. Moving the position and orientation of the
device in relation to the OI can bring up a layered pie menu. This menu
offers different options based on camera pose.

Observing large environments with AR requires frequent rotation and
movement of the device
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
Moving the arm or head would be easier than walking around an entire
environment, but people might want to move around regardless.

### Evaluation

Once a user has acquired the desired perspective on the device‘s screen,
they must be able to interpret the information in a clear and quick
manner so that user experience can be optimized. Clutter needs to be
avoided
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")]
so the designer must be able to decide what information is crucial and
what can be spared
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
It is also important that the virtual objects are smoothly integrated
with the real world. With respect to the limitations of the device‘s
graphic capabilities, there are some guidelines designers can follow for
a successful interface.

#### Text

A common strategy to display text is by using backgrounds called
billboards
[[5](#r5 "Dao, B., & Gabbard, J. L. (2013, March). Early steps towards understanding text legibility in handheld augmented reality")].
Billboards are opaque shapes displayed under the text to have the text
be more legible than by overlaying it directly onto the real world. Dao
and Gabbard
[[5](#r5 "Dao, B., & Gabbard, J. L. (2013, March). Early steps towards understanding text legibility in handheld augmented reality")]
recommend using red, neon green, or yellow text to increase legibility
without billboards. A compromise would be to use semi-opaque billboard
to increase legibility but still allowing a view of the real world.

#### Contrast

Human photoreceptors cause maximum activation in the brain when hit with
light from a dark/light edge
[[20](#r20 "Purves, D. (2012). Vision: The eye")]. This translates to
the retina‘s appreciation of contrast. Contrast should be applied to
virtual icons and markers as well as text. Adding shadowing to objects
and text can help increase contrast and simulate a 3D effect that better
integrates virtual and real environments
[[5](#r5 "Dao, B., & Gabbard, J. L. (2013, March). Early steps towards understanding text legibility in handheld augmented reality")], [[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].Fortunately
most graphics processor are capable of producing shadows.

#### Organization

Information on the display needs to be grouped and placed according to
the corresponding OI in the real world
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")].
Placement of virtual content has to be able to move around with the
scene
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
If the user rotates the screen, virtual objects should still be mapped
to their respective OI‘s.

#### Distinctions

There are several distinctions the user need to be able to make about
the virtual content displayed
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")], [[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")]).
First users should be able to discriminate versus near and visible
versus far and hidden. Showing a different type of marker for things
that are not seen easily keeps people from getting confused about the
missing element of their real world scene. If occluded objects are
displayed using x-ray type visualization, the proper artificial depth
should be applied to the virtual object to complete the illusion.

Labeled items of different types need to have icons and labels of that
are dissimilar from each other for faster recognition and filtering
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
When item labels or warnings require attention their appearance should
also be distinguishable from ordinary virtual objects
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")].

The mode or state of the AR application is the last distinction the user
needs to make
[[6](#r6 "Ganapathy, S. (2013). Design Guidelines for Mobile Augmented Reality: User Experience")].
The device recognition screen should not be the same as the display
screen or any other screens that may come up for additional information.
Additionally the user needs to be able to navigate easily between the
different modes.

##Future trends in AR?
--------------------

Juniper Research
[[9](#r9 "Juniper Research (2013a). Augmented Reality - The 8th mass medium [White paper]")]
predicts that almost 200 million global users will be using some sort of
AR app on mobile and wearable devices. It is estimated that there are 60
million unique AR app users globally as of 2013. These numbers result in
an expected 27% compound annual growth rate.

### Drawbacks of AR

Apart from the low familiarity of AR, there are other obstacles to the
growth of AR
[[9](#r9 "Juniper Research (2013a). Augmented Reality - The 8th mass medium [White paper]")].
The variety of AR capable devices causes developers to choose between
all of them leaving the other device types and their users without an AR
solution. The lack of consistency between different AR systems and lack
of interface design principles results in bad user experiences and
requires the user to learn different interaction methods for every AR
system. Juniper Research believes that these obstacles will be solved
with the increasing dominance of Android, allowing developers to focus
on one type of interface.

Dependence on AR can also become a problem in the future. Because the
system can always be working, especially if it is a wearable AR device,
users can start to perform tasks with some level of reliability and
eventually gain to trust the AR system. The interaction between the
device and the user would be personal and carry certain levels of
expectation for the device. A consistent and successful device would
eventually become the mediator between the user and the informational
flow of everyday life according to Starner et al.
[[24](#r24 "Starner, T., Mann, S., Rhodes, B., Levine, J., Healey, J., Kirsch, D., Picard, R. & Pentland, A. (1997). Augmented reality through wearable computing")].
If AR fails than people can still rely on their own senses to get
around, but if a person has not removed their AR device in some time, it
might be difficult to readjust again. Think of it like the helpless
feeling people get when they lose their phones.

### Arguments against AR

Fear and misunderstanding of AR can hurt its growth. An aspect of a
user‘s fear is the loss of privacy. Privacy is becoming a priority for
users due to services such as Google Maps keeping track of where a
person has been
[[12](#r12 "Kumparak, G. (December 18th, 2013). Google‘s Location History Browser Is A Minute-By-Minute Map Of Your Life")].
In the case of Google‘s Location History feature, the information is
stored as a result of using Google‘s services in an attempt to learn
user behavior and provide future suggestions of destinations. The
feature can be disabled by unchecking a box on the main History page,
but it is doubtful many people know about it. Augmented reality relies
on GPS
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")], [[8](#r8 "Höllerer, T., Feiner, S., Terauchi, T., Rashid, G., & Hallaway, D. (1999). Exploring MARS: developing indoor and outdoor user interfaces to a mobile augmented reality system")]
in order to correctly overlay the information that is relevant to you at
the location of use such as a distance or nearby attraction. AR systems
should have the same opt-out option as Google‘s Location History to keep
private users private. Non-users also have to be considered. If people
that interact with AR users don‘t feel like their privacy is being
respected as a subject of a sort of computer vision, then it wouldn‘t
matter how well an AR system is designed because people will fear it
[[23](#r23 "Simpson, C. (March 13th, 2013). Google Hopes Google Glass Won't Get You Beat Up")].
Social acceptance of AR has been a problem before. In 2012, a man with a
HMD AR system similar in appearance to Google Glass was assaulted at a
McDonalds in France and had his documents and device destroyed
[[14](#r14 "Matyszczyk, C. (June 17th, 2012). Google-style glasses led to attack in McDonald's, professor says")].
It was unclear why the attack happened. It seems that before AR can
become a prominent interface, well written security protocols and a
social acceptance of AR need to be reached.

##Conclusion
----------

Augmented Reality is not a new idea and even though it shares a past
with Virtual Reality, it shows potential for success in many markets. To
people that don‘t understand the ways of AR, it is known as a magical
interface
[[7](#r7 "Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using handheld augmented reality")].
Magic might sound silly, but it is certainly a better alternative to
receiving a negative reaction from society. Current users of augmented
reality should act as educators and guides to people who do not know
what it is, even if it takes an AR magician
[[25](#r25 "Tempest, M. (March, 2012). A magical tale (with augmented reality) [Video file]")]
to get us to listen.

##References
----------

1. <a name="r1"></a>AdvertisingAdverts (February 17th, 2012). National Geographic –
    Augmented Reality Campaign [Video file]. Retrieved from
    [YouTube](http://www.youtube.com/watch?v=srbDZjUQwlo "National Geographic – Augmented Reality Campaign").
    
2. <a name="r2"></a>Ahonen, T. (2012, June 12). Augmented Reality - the 8th Mass Medium
    [Video file]. Retrieved from
    [TED](http://tedxtalks.ted.com/video/TEDxMongKok-Tomi-Ahonen-Augment "Augmented Reality - the 8th Mass Medium").
3. <a name="r3"></a>Aurasma (July 10, 2013). Aurasma widens lead as world‘s leading
    augmented reality platform [Press release]. Retrieved from
    [Aurasma](http://www.aurasma.com/press/hp-autonomys-aurasma-crosses-20000-customer-milestone-surpasses-6-million-users/ "Aurasma widens lead as world‘s leading augmented reality platform").
4. <a name="r4"></a>Azuma, R. T. (1997). A survey of augmented reality. Presence, 6(4),
    355-385.
5. <a name="r5"></a>Dao, B., & Gabbard, J. L. (2013, March). Early steps towards
    understanding text legibility in handheld augmented reality. In
    Virtual Reality (VR), 2013 IEEE (pp. 159-160). IEEE.
6. <a name="r6"></a>Ganapathy, S. (2013). Design Guidelines for Mobile Augmented
    Reality: User Experience. In Human Factors in Augmented Reality
    Environments (pp. 165-180). Springer New York.
7. <a name="r7"></a>Gervautz, M., & Schmalstieg, D. (2012). Anywhere interfaces using
    handheld augmented reality. Computer, 45(7), 26-31.
8. <a name="r8"></a>Höllerer, T., Feiner, S., Terauchi, T., Rashid, G., & Hallaway, D.
    (1999). Exploring MARS: developing indoor and outdoor user
    interfaces to a mobile augmented reality system. Computers &
    Graphics, 23(6), 779-785.
9. <a name="r9"></a>Juniper Research (2013a). Augmented Reality - The 8th mass medium
    [White paper]. Retrieved from [Juniper
    Research](http://www.juniperresearch.com/shop/whitepapers/mobile_augmented_reality "Augmented Reality - The 8th mass medium").
10. <a name="r10"></a>Juniper Research (2013b). Smart wearables … beyond mobile [White
    paper]. Retrieved from [Juniper
    Research](http://www.juniperresearch.com/whitepapers/smart_wearables_beyond_mobile "Smart wearables … beyond mobile").
11. <a name="r11"></a>Kipper, G., & Rampolla, J. (2013). Augmented Reality: An emerging
    technologies guide to AR. Waltham, MA: Elsevier.
12. <a name="r12"></a>Kumparak, G. (December 18th, 2013). Google‘s Location History
    Browser Is A Minute-By-Minute Map Of Your Life. TechCrunch.
    Retrieved from
    [TechCrunch](http://techcrunch.com/2013/12/18/google-location-history/ "Google‘s Location History Browser Is A Minute-By-Minute Map Of Your Life").
13. <a name="r13"></a>Layar (August 15, 2013). Layar Sees Growing Adoption And Tangible
    Results With Interactive Print. Retrieved from
    [Layar](https://www.layar.com/news/press-releases/august-2013/ "Layar Sees Growing Adoption And Tangible Results With Interactive Print").
14. <a name="r14"></a>Matyszczyk, C. (June 17th, 2012). Google-style glasses led to attack
    in McDonald's, professor says. CNET. Retrieved from
    [CNET](http://news.cnet.com/8301-17852_3-57474346-71/google-style-glasses-led-to-attack-in-mcdonalds-professor-says/ "Google-style glasses led to attack in McDonald's, professor says").
15. <a name="r15"></a>Metaio (February 21, 2013). Metaio brings world‘s first Augmented
    Reality Accelerated chipset to market, signs agreement with
    ST-Ericsson to integrate future mobile platforms [Press release].
    Retrieved from
    [Metaio](http://www.metaio.com/press/press-release/2013/metaio-brings-worlds-first-augmented-reality-accelerated-chipset-to-market-signs-agreement-with-st-ericsson-to-integrate-future-mobile-platforms/ "Metaio brings world‘s first Augmented Reality Accelerated chipset to market, signs agreement with ST-Ericsson to integrate future mobile platforms").
16. <a name="r16"></a>Mills, M. (July, 2012). Image recognition that triggers augmented
    reality [Video file]. Retrieved from
    [TED](http://www.ted.com/talks/matt_mills_image_recognition_that_triggers_augmented%20_reality.html "Image recognition that triggers augmented reality").
17. <a name="r17"></a>MIT Media Lab (n.d.). Affective Computing [Description]. Retrieved
    from [MIT Media
    Lab](http://affect.media.mit.edu/ieved%20from%20http://affect.media.mit.edu/ "Affective Computing").
18. <a name="r18"></a>Mulloni, A., Seichter, H., & Schmalstieg, D. (2011, August).
    Handheld augmented reality indoor navigation with activity-based
    instructions. In Proceedings of the 13th international conference on
    human computer interaction with mobile devices and services (pp.
    211-220). ACM.
19. <a name="r19"></a>O'Neill, K., & de Paor, A. (2011). The Potency of Optical and
    Augmented Reality Mirror Boxes in Amputees and People with Intact
    Limbs. Advances in Electrical and Electronic Engineering, 5(1-2),
    310-315.
20. <a name="r20"></a>Purves, D. (2012). Vision: The eye. In Neuroscience (5th ed.).
    Sunderland, Mass: Sinauer.
21. <a name="r21"></a>Reiners, D., Stricker, D., Klinker, G., & Müller, S. (1998).
    Augmented reality for construction tasks: doorlock assembly. Proc.
    IEEE and ACM IWAR, 98(1), 31-46.
22. <a name="r22"></a>Shuhaiber, J. H. (2004). Augmented reality in surgery. Archives of
    surgery,139(2), 170.
23. <a name="r23"></a>Simpson, C. (March 13th, 2013). Google Hopes Google Glass Won't Get
    You Beat Up. The Wire. Retrieved from [The
    Wire](http://www.thewire.com/technology/2013/03/google-hopes-google-glass-wont-get-you-beat/62936/ "Google Hopes Google Glass Won't Get You Beat Up").
24. <a name="r24"></a>Starner, T., Mann, S., Rhodes, B., Levine, J., Healey, J., Kirsch,
    D., Picard, R. & Pentland, A. (1997). Augmented reality through
    wearable computing. Presence: Teleoperators and Virtual
    Environments, 6(4), 386-398.
25. <a name="r25"></a>Tempest, M. (March, 2012). A magical tale (with augmented reality)
    [Video file]. Retrieved from
    [TED](http://www.ted.com/talks/marco_tempest_a_magical_tale_with_augmented_reality.html "A magical tale (with augmented reality)").
26. <a name="r26"></a>Van Krevelen, D. W. F., & Poelman, R. (2010). A survey of augmented
    reality technologies, applications and limitations. International
    Journal of Virtual Reality, 9(2), 1.
27. <a name="r27"></a>Wojciechowski, R., Walczak, K., White, M., & Cellary, W. (2004).
    Building virtual and augmented reality museum exhibitions. In
    Proceedings of the ninth international conference on 3D Web
    technology (pp. 135-144). ACM.
28. <a name="r28"></a>World Lens (n.d.) [Demo]. Retrieved from [World
    Lens](http://questvisual.com/us/ "WorldLens").
29. <a name="r29"></a>Zugara (2013). Webcam social shopper software for kiosks [Demo].
    Retrieved from
    [Zugara](http://zugara.com/ "Webcam social shopper software for kiosks").

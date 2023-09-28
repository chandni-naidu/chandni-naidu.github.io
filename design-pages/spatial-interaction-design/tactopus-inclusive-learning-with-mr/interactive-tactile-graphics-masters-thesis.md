# Interactive Tactile Graphics (Masters' thesis)

{% embed url="https://vimeo.com/240537460" %}

### Objective

***

#### Problem Space

Tactile graphics are textured, 2D representations of images for people with vision loss to experience otherwise visual content. While they are a significant part of learning for VI (visually impaired) students, they are also quite limited in many ways.

The objective of this design project is to find an inexpensive way for tactile graphics to be interactive, thus become better resources, particularly for education. The way in which tactile graphics can have more enhanced utility and wider application is by making the otherwise static sheet interactive. Whether it is simply providing audio labels to save braille-print space, or to provide sensory substitution to enhance perception and understanding in a way that pointers and annotations cannot, interactivity can contribute in many ways to the value of a tactile graphic.

### Design

***

#### Initial Explorations

Early explorations to look at ways to make a non-electronic, paper/plastic surface interactive.

![](<../../../.gitbook/assets/image (37).png>)![](<../../../.gitbook/assets/image (38).png>)![](<../../../.gitbook/assets/image (39).png>)

More formalised system explorations after technology research

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

#### Analysis

Of the four designs discussed in this section, the fourth, namely ‘Finger Tracking with Fixed Camera’ is found to be the most affordable. It's conceptualised as a colour tracking system as it is essential to track the index finger as distinct from others. With advanced gesture processing, the finger marker may not be necessary if the system can identify the pointing or interacting finger directly.

To explore the possibilities of this method, I prototyped interactive experiences with Processing.

Unknowns at this stage:

* Size and colour of marker that is easiest to distinguish,
* Size of tactile graphic, height at which camera is to be mounted,
* size of detached elements,
* smallest detected movement,
* easy to perform gestures, etc.

these will be derived by trying out different configurations.

Foreseeable limitation of this method

* is the inability to distinguish between hover and touch (Midas touch)
* It will require a specific gesture to activate an item, as compared to the RFID system, where a direct touch would have been possible.

#### Hardware Design

Components required

* Smart phone with camera or computer with USB webcam
* Access to internet, or offline stored data
* Headphones
* Stickers/markers for finger
* Stand for phone with adjustable height
* Tactile Graphic

### Interaction Framework

In order to design for a relatively unexplored medium of interaction, I worked out a framework of interactions, starting with basics and building on to increased complexity.

Interaction Primitives

* **Labelled**—elements on the tactile graphic are given short labels that are spoken when touched. This interaction is henceforth referred to as hover, and the information it accesses is called a short label.
* **Described**—apart from the short label, a longer description is made available on call. The method to access it is by an explicit action, such as a gesture. This interaction will be referred to as expand and the information it calls is the description.
* **Buttons**—selectable elements that perform an action.
* \*\*Input fields—\*\*for more complex interactions, users will be required to input data. These containers are referred to as fields. They may be numbers, text or boolean fields- checkboxes and radio buttons.
* **Page level controls**—a standardised panel containing controls pertaining to the entire page, such as home, title, reset, start, stop, change mode, etc.

#### Gestures and Interaction Primitives

<figure><img src="../../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

####

####

####

#### Speaking Tactile System

Thinking at an abstract level, these would be the basic, essential components in an interactive page:

![](<../../../.gitbook/assets/image (51).png>)

More complex components could be built for higher order interactions:

![](<../../../.gitbook/assets/image (52).png>)![](<../../../.gitbook/assets/image (53).png>)![](<../../../.gitbook/assets/image (54).png>)![](<../../../.gitbook/assets/image (55).png>)

#### Design Concepts

![](<../../../.gitbook/assets/image (56).png>)![](<../../../.gitbook/assets/image (57).png>)

### Evaluation and User Testing

#### Test Samples

A few examples were prototyped to a functional level to enable testing.

1. Test guide to orient participants on the gestures to be performed. Attempts before getting it right we recorded for comparing effectiveness.

![](<../../../.gitbook/assets/image (60).png>)

2. Once the gestures and their functions are familiar to the participant, this Question-Choice-Submit format of interaction was tested:
3.

    <figure><img src="../../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>
4. Exploratory Learning was tested through an audio enhanced representation of the water cycle

![](<../../../.gitbook/assets/image (61).png>)

#### User Testing, Evaluations

Learning from user feedback

![](<../../../.gitbook/assets/image (62).png>)![](<../../../.gitbook/assets/image (63).png>)![](<../../../.gitbook/assets/image (64).png>)![](<../../../.gitbook/assets/image (65).png>)

### Findings from Evaluation

**Gestures**: The gestures were found to be easy to perform once familiarised, and the functions of each gesture is also fairly well understood by the users.

**Element size**: in the current design, the area in which the gesture is performed dictates the action. Evaluation has exposed that his model could cause limitations in design of tactile graphics. This needs to be reworked to detect only the starting point. This way, typical finger-tip size of 10mm × 10mm could be the minimum element size. This still needs to be verified via testing.

**Information**: It was noticed that when the first word (or first few words) of the description were the same, users quickly decide that they must have accessed the same description twice. The second time the same word is heard, the audio is discontinued even though the following text is completely different. Labels and first words of descriptions need to be assigned uniquely or identified clearly to avoid confusion.

### Prototypes

**Software Prototype**

{% embed url="https://twitter.com/_chandninaidu/status/1396527659169972224?ref_src=twsrc^tfw|twcamp^tweetembed|twterm^1396527659169972224|twgr^|twcon^s1_&ref_url=notion://www.notion.so/c-drive/Design-Archives-62c8467cb3434508b2b6f550717cd78a?p=a263b17a320c43bf989e375ebfd940b9pm=s" %}

#### Hardware Prototype

Developed with help from classmates, students of Industrial Design

![](<../../../.gitbook/assets/image (66).png>)![](<../../../.gitbook/assets/image (67).png>)![](<../../../.gitbook/assets/image (68).png>)![](<../../../.gitbook/assets/image (69).png>)![](<../../../.gitbook/assets/image (70).png>)

### Future Work

If all of the NCERT educational content is designed in this medium using a fixed camera and inexpensively produced tactile graphics, cost of educational material for blind children could be brought down by simply reducing the amount of braille printed textbooks to be purchased.

The next task to take this forward is the content creation interface for special educators. Massive amounts of content needs to be converted from visual to interactive-tactile form.

When simple concepts are presented in an enriched, multi-media format, it becomes appealing and more engaging for sighted children as well. Keeping with principles of universal and inclusive design, content must be developed for a wider user group in the long run.

Applications of this system extend beyond education and can be applied in public spaces, transit locations, offices, restaurants, etc. where information access is currently a challenge.

Data visualisations is another area that has been developed highly for sight, but not many alternatives exist for other senses. Complex data sets may find novel expressions in this medium that enrich the experience for sighted users as well.\



# End-User Authoring of Mid-Air Gestural Interactions

This repository contains the LaTeX source files for my master's thesis. If you are using LaTex to write a thesis or a paper, you may find in it examples on how to implement various designs and behaviors.

As I wrote and designed my thesis, I relied very much on various resources created by the LaTeX community and shared online. I am publishing the source files in order to give back to this community, and lower the barriers of entry into the LaTeX world for my peers. As such, there are some (non-LaTeX) files that are missing from the repo although they have been part of the production process. These are the files involved in producing the figures ([GIMP](http://www.gimp.org/) and Visio files, source photos/screenshots etc.) which reside in a `.gitignore`d `_src` folder; and the (also `.gitignore`d) PDFs of my previous publications that go into the appendices. All LaTeX code is included.

The **master** branch contains the source files I used to compile the version of my thesis that I submitted to the Koç University [Graduate School of Social Sciences and Humanities](http://gsssh.ku.edu.tr). In the future I may create another branch that features more comments and some refactoring. For now, **master** branch is all there is.

## Compilation

I wrote my thesis on a Mac with a full-blown installation of the [MacTex](https://tug.org/mactex/) (2014 version) distribution.

The file `compile` contains a script that automates the compilation process and removes LaTeX-generated files upon successful compilation. To compile on a Mac with MacTex installed; download the repository, comment out the `\includepdf` commands at the end of the `main.tex` file, and run `source compile`. (See [this thread on Stack Overflow](http://stackoverflow.com/questions/13786499/source-vs-sh-in-linux-what-is-the-difference) to learn about `source`.)

Please note that the code, as well as the `compile` script, have never been tested on any computer other than my own. Compilation may fail on your computer, for whatever reason. Since the whole purpose of the code and the script is to exemplify LaTeX use, this doesn't worry me at all.

## IP stuff

The content of the manuscript is subject to Koç University's policies on intellectual property rights (see [here](http://gsssh.ku.edu.tr/rules-regulations) and [here](http://vprd.ku.edu.tr/research/grand)). Various bits and pieces that have somehow become part of the thesis are subject to various other policies, which should be indicated in the relevant parts of the text. Please observe these policies, along with some basic principles of academic honesty and common human decency, as you make use of this repository. As a simple rule of thumb: copying LaTeX code is cool, copying content is not.

Conversely; if my work somehow makes use of content that belongs to you (or an organization you are affiliated with), in a way that is not condoned by you (or the organization you are affiliated with); please let me know, and I will do my best to observe your policies.

## Thesis Info

The full manuscript can be found under [Releases](https://github.com/mbaytas/thesis/releases).

### Abstract

Devices that sense the alignment and motion of human limbs via computer vision have recently become a commodity; enabling a variety of novel user interfaces that use human gesture as the main input modality. The design and development of these interfaces requires programming tools that support the representation, creation and manipulation of information on human body gestures. Following concerns such as usability and physical differences among individuals, these tools should ideally target end-users and designers as well as professional software developers.

This thesis documents the design, development, deployment and evaluation of a software application to support gesture authoring by end-users for skeletal tracking vision-based input devices. The software enables end-users without programming experience to introduce gesture control to computing applications that serve their own goals; and provides developers and designers of gestural interfaces with a rapid prototyping tool that can be used to experientially evaluate designs.

### Keywords

Hotspotizer; gestural interaction; gesture authoring; visual programming; end-user development; interface prototyping; mid-air gestures; perceptual interaction; Kinect.

### Related Links

- [Koç University Design Lab](http://designlab.ku.edu.tr/)
- [Hotspotizer Project Page](http://designlab.ku.edu.tr/design-thinking-research-group/hotspotizer/)
- [Hotspotizer on GitHub](https://github.com/mbaytas/hotspotizer)
- [Hotspotizer featured on Channel 9 Coding4Fun Kinect Projects blog](http://channel9.msdn.com/coding4fun/kinect/Todays-hot-project-Hotspotizer)

### Related Academic Publications

- Mehmet Aydın Baytaş, Yücel Yemez, and Oğuzhan Özcan (2014). Hotspotizer: end-user authoring of mid-air gestural interactions. In *Proceedings of the 8th Nordic Conference on Human-Computer Interaction (NordiCHI '14)*.
- Mehmet Aydın Baytaş, Yücel Yemez and Oğuzhan Özcan (2014). User Interface Paradigms for Visually Authoring Mid-Air Gestures: A Survey and a Provocation. In *Proceedings of the Workshop on Engineering Gestures for Multimodal Interfaces (EGMI 2014)*.

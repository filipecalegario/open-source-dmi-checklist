# Open Source DMI

An Open Source DMI is a digital musical instrument with a well-documented project, that is easy to reproduce or modify, accessible in terms of cost and components availability, and is obtainable publicly for any use. [Further reading](https://link.springer.com/chapter/10.1007%2F978-3-030-60114-0_5)

# Checklist

The checklist consists of a set of questions based on each step of the DMI development process and the previously discussed challenges, especially inspired by the OSHWA certification checklist:

## General Aspects
* Is there a structured and organized website concentrating all the documentation and information about the project?
* Is there an open communication channel with the developers or makers to ask questions during the making process? (e.g., forum, e-mail)
* Is there a clear overview architecture diagram with the description of each part's details?
* Is there a description of the expected skills and resources required to realize the project?
* Does the documentation highlight critical, uncertain, difficult, or potentially confusing parts of the process of realization?

## Hardware (Mechanical Structure and Electronics)
* Is the hardware made out of an accessible consumer product? (e.g., Bela, LEGO, Arduino, hardware synthesizers)
* Are the original design files for the instrument's structure and electronic circuits publicly available (e.g., CAD files, schematics, technical diagrams)?
* Is the bill of materials publicly available and accessible? (e.g., links, prices, detailed descriptions) 
* Are there any instructions and explanations about the process of making the instrument's physical structure and electronic circuits publicly available? (e.g., wiki, Instructables, tutorials, images or videos about the process)
* Is there a source code version control publicly available for all the hardware and the mechanical structure? (e.g., git or SVN repositories)
* Are there photos at various stages of assembly publicly available?
* Are the design files licensed in a way that others may reproduce or build upon them? (e.g., Creative Commons)
* Is the construction and hardware design under an open-source license (e.g., CERN, TAPR, Solder Pad) so others may reproduce or build upon it?

## Software
* Is the software/firmware publicly available and with an open-source license?
* Is there a source code version control publicly available for the software? (e.g., git or SVN repositories)
* Does the instrument rely on an easily accessible proprietary software? (e.g., Max/MSP, Ableton Live, VST Plugins) 
* Are the support and configuration files publicly available? (e.g., mappings, software configuration diagrams, audio samples, presets, DAW project files)
* Are the presets, files, and projects licensed in a publicly available license (e.g., copyrighted audio samples)?
* Does the instrument use a standard communication protocol? (e.g., MIDI, OSC or Libmapper)

# Publication

This checklist was first published in the paper:

Calegario F., Tragtenberg J., Wang J., Franco I., Meneses E., Wanderley M.M. (2020) Open Source DMIs: Towards a Replication Certification for Online Shared Projects of Digital Musical Instruments. In: Stephanidis C., Marcus A., Rosenzweig E., Rau PL.P., Moallem A., Rauterberg M. (eds) HCI International 2020 - Late Breaking Papers: User Experience Design and Case Studies. HCII 2020. Lecture Notes in Computer Science, vol 12423. Springer, Cham. https://doi.org/10.1007/978-3-030-60114-0_5

```BibTeX
@InProceedings{10.1007/978-3-030-60114-0_5,
author="Calegario, Filipe
and Tragtenberg, Jo{\~a}o
and Wang, Johnty
and Franco, Ivan
and Meneses, Eduardo
and Wanderley, Marcelo M.",
editor="Stephanidis, Constantine
and Marcus, Aaron
and Rosenzweig, Elizabeth
and Rau, Pei-Luen Patrick
and Moallem, Abbas
and Rauterberg, Matthias",
title="Open Source DMIs: Towards a Replication Certification for Online Shared Projects of Digital Musical Instruments",
booktitle="HCI International 2020 - Late Breaking Papers: User Experience Design and Case Studies",
year="2020",
publisher="Springer International Publishing",
address="Cham",
pages="84--97",
abstract="The internet has allowed for the flourishing of several shared projects. Developers from different parts of the world can work asynchronously on the same project, formulating ideas, and implementing complex systems. For remote collaboration in software development projects, sharing information and code becomes more straightforward, given the textual and abstract nature of the source. However, for projects involving hardware and physical artifacts development, it is necessary to have a more detailed level of information, since many other characteristics of the project need to be covered in the documentation. In the case of digital musical instruments, which are physical artifacts aimed at musical interaction, we have several aspects such as mechanical structure, electronic, programming, mapping, and sound design. Currently, there are few initiatives in the literature that indicate possible ways to guide designers and developers in the process of documenting the replication of their projects. Given the importance of advancing the area of new interfaces for musical expression, the diffusion of ideas among innovators, and the popularization of innovative musical instruments, this paper discusses the challenges of sharing DMIs. Our main goal is to propose a checklist to help designers and developers to share their projects to increase the potential for replicability. As future steps, we hope to move towards a certificate that guarantees how replicable a given project is considering makers other than its developers. Besides, with better documentation and a more organized sharing process, we expect to encourage designers and developers to reproduce existing DMIs in different parts of the world so we could understand the adoption of these devices in different contexts and cultures. This paper presents a step towards making the projects more accessible to make the DMI community more connected.",
isbn="978-3-030-60114-0"
}
```

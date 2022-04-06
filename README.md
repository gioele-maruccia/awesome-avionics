<div align="center">
<hr>

# Awesome Avionics

🚀 ✈ 🚁

A curated list of avionics awesome resources. Everything you need to know to be an avionics software developer.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<img src="https://img.shields.io/github/license/gioele-maruccia/awesome-avionics"/>


<hr>
</div>

## Contents

- [OS](#os)
- [RTOS](#rtos)
- [Software Standards](#software-standards)
  - [DO-178](#do-178)
  - [DO-254](#do-254)
  - [ARINC 653](#arinc-653)
- [Requirements Engineering](#requirements-engineering)
- [Software Development](#software-development)
  - [Programming Languages](#programming-languages)
  - [Frameworks](#scripting-and-frameworks)
  - [Model Based Design](#model-based-design)
- [Testing](#testing)
- [Certifications](#certifications)
- [Books](#books)
- [Magazines](#magazines)
- [Companies](#companies)

## OS
### RTOS
- [WindRiver VxWorks](https://experience.windriver.com/redefining-rtos/p/1?utm_source=google&utm_medium=sem&utm_campaign=vp-dg-emea-vhs-sem-vxworks-exact-brand-07012021&gclid=CjwKCAjwuYWSBhByEiwAKd_n_lSSQ0QQVo927BXSAWz4XRgsQHJ5ZWa15bQpYQf-yZrEuaC3ZjWj0RoCXbQQAvD_BwE) Industry leader RTOS.
- [Lynx OS-178](https://www.lynx.com/products/lynxos-178-do-178c-certified-posix-rtos) hard real-time partitioning OS and certified DO-178B/C DAL A.
- [DDC-I DEOS](https://www.ddci.com/products_deos_do_178c_arinc_653/) DO178C DAL A verified OS.
- [INTEGRITY](https://www.ghs.com/products/rtos/integrity.html)  Flagship of Green Hills software operating systems.

- `2020` [Interference Analysis of Multicore Shared Resources with a Commercial Avionics RTOS](https://link.springer.com/chapter/10.1007/3-540-45828-X_11)
- `2019` [Virtual Integration in Avionics Systems-RTOS](https://onlinelibrary.wiley.com/doi/abs/10.1002/j.2334-5837.2019.00678.x)
- `2019` [Critical vulnerabilities to remotely compromise VxWorks, the most popular RTOS](https://info.armis.com/rs/645-PDC-047/images/Urgent11%20Technical%20White%20Paper.pdf) ![pdf]
- `2007` [A Comparison of Partitioning Operating Systems for Integrated Systems](https://link.springer.com/chapter/10.1007/978-3-540-75101-4_33)
- `2002` [Formal Modeling and Analysis of Advanced Scheduling Features in an Avionics RTOS]() ![pdf]

## Safety Standards

- [DO-178C](https://en.wikipedia.org/wiki/DO-178C) - Is the primary document with software considerations in airborne systems and equipment certification.
It was born in 2012 as an upgrade to the previous versions DO-178A (1980) and DO-178-B (1992).
- [DO-254](https://en.wikipedia.org/wiki/DO-254) - Is the primary document with guidance for the development of airborne electronic hardware.
- [Training Workshop](https://afuzion.com/private-training/avionics-hardware-do-254-training-class/?gclid=CjwKCAjwopWSBhB6EiwAjxmqDXItJQCzFkBQ8uErGtpMDUjjgVdPttywkhrc3i-8yUtdnjSn8-KvHxoCfOkQAvD_BwE) - A training class for the main aspects for avionics hardware development.
- [ARINC 653](https://en.wikipedia.org/wiki/ARINC_653) - Is a software specification for space and time partitioning in safety-critical avionics real-time operating systems (RTOS).
- [IEC 61508](https://en.wikipedia.org/wiki/IEC_61508) - International standard consisting of methods on how to apply, design, deploy and mantain autmatic protection systems called safety-related systems.
## Requirements Engineering
- [DAL](https://en.wikipedia.org/wiki/DO-178C), or Design Assurance Level, defines the amount of rigor that should be applied by the design assurance process based on the contribution to Aircraft Safety.
- [10 Practises for DO-178C Compliance](https://qracorp.com/aerospace-requirements-guide/) - Aerospace Requirements Guide and checklist: 10 Essential Best Practises for Assuring Compliance with DO-178C.

### Tools
- [IBM Rational DOORS](https://www.ibm.com/docs/en/ermd/9.6.1?topic=overview-rational-doors) - Top used requirements management tool fo requirements control.

## Software Development
### Coding Guidelines
- [MISRA](https://www.misra.org.uk/) Guidelines for the use of the C and C++ language in critical systems.
- [NASA's 10 rules](https://www.perforce.com/blog/kw/NASA-rules-for-developing-safety-critical-code#:~:text=NASA's%2010%20rules%20for%20developing%20safety%2Dcritical%20code%20are%3A,dynamic%20memory%20allocation%20after%20initialization.) NaSA's 10 Rules for developing Safety-Critical Code.
- [NASA C++ STYLE GUIDE](https://ntrs.nasa.gov/citations/20080039927) - C++ Coding Standards and Style Guide from NASA.
### Programming Languages
- [Ada](https://github.com/ohenley/awesome-ada) - Awesome Ada.
- [C](https://github.com/aleksandar-todorovic/awesome-c) - Awesome C.
- [C++](https://github.com/fffaraz/awesome-cpp#readme) - Awesome C++.
- [Python](https://github.com/vinta/awesome-python) - Awesome Python.

### Frameworks
- [Matlab](https://it.mathworks.com/products/matlab.html) - Main page.

### Model Based Design
- [Simulink](https://it.mathworks.com/products/simulink.html) - Main page.

## Testing

### Unit Tests
- [Google Test](https://github.com/google/googletest) - Google's test framework for C++.
- [Fake Function Framework](https://github.com/meekrosoft/fff) - Micro framework for creating fake C functions for tests.

### Static Analysis
- [Awesome Static Analysis](https://github.com/analysis-tools-dev/static-analysis)

## Certifications

## Books
- [Developing safety-critical software](https://www.amazon.com/Developing-Safety-Critical-Software-Practical-Compliance/dp/143981368X), by Leanna Rierson.
- [The aviation development ecosystem](https://www.amazon.com/AVIATION-DEVELOPMENT-ECOSYSTEM-Applying-Guideline-ebook/dp/B08ZYNFLTJ), by Vance Hilderman.
- [Aircraft System Safety](https://www.amazon.com/Aircraft-System-Safety-Airworthiness-Certification/dp/0081008899), by Duane Kritzinger.
- [Digital Avionics Handbook](https://www.amazon.com/Digital-Avionics-Handbook-Cary-Spitzer/dp/1138076988), by Cary Spitzer, Uma Ferrel, Thomas Ferrel.
- [Real-Time Systems](https://www.amazon.com/Real-Time-Systems-Principles-Distributed-Applications/dp/1441982361), by Hermann Kopetz.

## Magazines
- [Aviation Today](https://www.aviationtoday.com/)
- [Flying Magazine](https://www.flyingmag.com/)
- [Aeroplane](https://www.key.aero/aeroplanemonthly)

## Companies
- [Northrop Grumman](https://www.northropgrumman.com/)
- [Boeing](https://www.boeing.com/)
- [Sagetech Avionics](https://sagetech.com/)
- [Honeywell International Inc.](https://www.honeywell.com/us/en)
- [Universal Avionics](https://uasc.com/)
- [Meggitt PLC](https://www.meggitt.com/)
- [Raytheon Technologies Corporation](https://www.rtx.com/)
- [Panasonic Avionics](https://www.panasonic.aero/)
- [FLIR Systems](https://www.flir.eu/)
- [Collins Aerospace](https://www.collinsaerospace.com/)
- [BAE Systems](https://www.baesystems.com/en/home)
- [Curtiss-Wright](https://www.curtisswright.com/)
- [Safran](https://www.safran-group.com/)
- [GE Aviation](https://www.geaviation.com/)
- [L3Harris Technologies, Inc.](https://www.l3harris.com/)
- [Leonardo Company](https://www.leonardo.com/en/home)

[video]: media/icons/video.png "video"
[awesome]: media/icons/awesome.png "awesome"
[blog]: media/icons/blog.png "blog"
[book]: media/icons/book.png "book"
[github]: media/icons/github.png "github"
[pdf]: media/icons/pdf.png "pdf"
[podcast]: media/icons/podcast.png "podcast"
[search]: media/icons/search.png "search"
[stackoverflow]: media/icons/stackoverflow.png "stackoverflow"
[student]: media/icons/student.png "student"
[warning]: media/icons/warning.png "warning"

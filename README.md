# Microsystem-with-Microprocessor-8086
## 1. Project Overview
[cite_start]The objective of this project is to design a microsystem based on the **Intel 8086** microprocessor[cite: 15]. [cite_start]The system integrates specific memory components and various I/O interfaces to handle serial/parallel communication, user input, and multi-modal data display[cite: 14, 15].

---

## 2. Hardware Specifications
The architecture of the microsystem is defined by the following components:

* [cite_start]**Central Processing Unit (CPU):** Intel 8086[cite: 15].
* [cite_start]**EPROM Memory:** 128 KB, implemented using **27C512** circuits[cite: 16].
* [cite_start]**SRAM Memory:** 64 KB, implemented using **62256** circuits[cite: 17].
* [cite_start]**Serial Interface:** * Controller: **8251**[cite: 18].
    * [cite_start]Addressing: Mapped to zones `04D0H – 04D2H` or `05D0H – 05D2H`, toggleable via microswitch **S1**[cite: 18].
* [cite_start]**Parallel Interface:** * Controller: **8255**[cite: 19].
    * [cite_start]Addressing: Mapped to zones `0250H – 0256H` or `0A50H – 0A56H`, toggleable via microswitch **S2**[cite: 19].
* **Peripherals:**
    * [cite_start]**Mini-keyboard:** 9 contacts[cite: 20].
    * [cite_start]**LEDs:** 10 individual LED indicators[cite: 21].
    * [cite_start]**7-Segment Display:** 8-digit module (capable of displaying up to 8 hex characters simultaneously)[cite: 22].
    * [cite_start]**LCD Module:** 2 lines x 16 characters (interface choice is at the student's discretion)[cite: 23].

---

## 3. Software Requirements
[cite_start]All software components must be developed in **Assembly language** and structured exclusively as **subroutines**[cite: 25]. The required routines are:

* [cite_start]**Initialization:** Programming routines for both the **8251** and **8255** circuits[cite: 26].
* [cite_start]**Serial Communication:** Character transmission and reception routines[cite: 27].
* [cite_start]**Parallel Communication:** Character transmission routine[cite: 28].
* [cite_start]**Input Handling:** A scanning routine for the 9-contact mini-keyboard[cite: 29].
* [cite_start]**Visual Output:** * LED control routine (toggle ON/OFF)[cite: 30].
    * [cite_start]Hexadecimal character display routine for a specific 7-segment rank[cite: 31].

---

## 4. Documentation Structure
The final project folder must be submitted in electronic format and organized as follows:

* [cite_start]**Page 1:** Identification details (University, Faculty, Discipline, Project Title, Author, Academic Year)[cite: 49, 50, 51, 52, 53, 54, 55].
* [cite_start]**Page 2:** Project Theme (Technical Requirements)[cite: 56, 57].
* [cite_start]**Hardware Description (3–5 pages):** Detailed technical explanation of the architecture[cite: 58, 60].
* [cite_start]**Software Listing (3–7 pages):** Assembly code with clear delimiters and comprehensive comments[cite: 61, 62].
* [cite_start]**Bibliography (Last Page):** Properly cited books, articles, and links[cite: 64, 65, 68].
* [cite_start]**Schematics:** Created using CAD software (EasyEDA, Proteus, DipTrace, or OrCAD) in A4 or A3 format[cite: 79, 80].

---

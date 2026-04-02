# Microsystem with Microprocessor 8086

## 1. Project Overview
The objective of this project is to design a microsystem based on the **Intel 8086** microprocessor. The system integrates specific memory components and various I/O interfaces to handle serial/parallel communication, user input, and multi-modal data display.

---

## 2. Hardware Specifications
The architecture of the microsystem is defined by the following components:

* **Central Processing Unit (CPU):** Intel 8086.

* **EPROM Memory:** 128 KB, implemented using **27C512** circuits.

* **SRAM Memory:** 64 KB, implemented using **62256** circuits.

* **Serial Interface:** * Controller: **8251**.
  * Addressing: Mapped to zones `04D0H – 04D2H` or `05D0H – 05D2H`, toggleable via microswitch **S1**.

* **Parallel Interface:** * Controller: **8255**.
  * Addressing: Mapped to zones `0250H – 0256H` or `0A50H – 0A56H`, toggleable via microswitch **S2**.

* **Peripherals:**
  * **Mini-keyboard:** 9 contacts.
  * **LEDs:** 10 individual LED indicators.
  * **7-Segment Display:** 8-digit module (capable of displaying up to 8 hex characters simultaneously).
  * **LCD Module:** 2 lines x 16 characters (interface choice is at the student's discretion).

---

## 3. Software Requirements
All software components must be developed in **Assembly language** and structured exclusively as **subroutines**. The required routines are:

* **Initialization:** Programming routines for both the **8251** and **8255** circuits.

* **Serial Communication:** Character transmission and reception routines.

* **Parallel Communication:** Character transmission routine.

* **Input Handling:** A scanning routine for the 9-contact mini-keyboard.

* **Visual Output:** * LED control routine (toggle ON/OFF).
  * Hexadecimal character display routine for a specific 7-segment rank.

---

## 4. Documentation Structure
The final project folder must be submitted in electronic format and organized as follows:

* **Page 1:** Identification details (University, Faculty, Discipline, Project Title, Author, Academic Year).

* **Page 2:** Project Theme (Technical Requirements).

* **Hardware Description:** 3–5 pages detailing the architecture.

* **Software Listing:** 3–7 pages of code with clear delimiters and comprehensive comments.

* **Bibliography:** Properly cited books, articles, and links on the last page.

* **Schematics:** Created using CAD software (EasyEDA, Proteus, DipTrace, or OrCAD) in A4 or A3 format.

---

* **Submission:** The digital version must be uploaded to the **Virtual Campus** before the physical defense.

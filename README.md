# STM32_Learning

Pembahasan pemula berdasarkan beberapa referensi, disini saya ambil contoh yaitu STM32F207


## ARSITEKTUR ARM CORTEX-M3	

### 1. MODEL PROGRAMMER

1.1	MODE OPERASi  

1.2	REGISTER

1.3	ARSITEKTUR BUS

1.4	PIPELINE

### 2. MODEL MEMORI	
2.1	PEMETAAN MEMORI	

2.2	AKSES MEMORI	

2.3	OPERASI BIT BAND

2.4 AKSES MEMORI TAK RATA

### 3. MODEL EKSEPSI
3.1	HARD FAULT	

3.2	MEMMANAGE FAULT	

3.3	BUS FAULT	

3.4	USAGE FAULT	

3.5	SVC, PENDSV DAN SYSTICK	

3.6	TABEL VEKTOR

### 4. KENDALI INTERUPSI	

4.1	REGISTER-REGISTER NVIC

4.2	PRIORITAS INTERUPSI

4.3	KARAKTERISTIK INTERUPSI	

4.4	SETING INTERUPSI	

### 5. UNIT PROTEKSI MEMORI

5.1	REGISTER-REGISTER MPU	

5.2	PENGGUNAAN MPU	

### 6. FITUR LAINCORTEX-M3

6.1	TIMER SYSTICK

6.2	MANAJEMEN DAYA

20	K MUNIKASI MULTIPROSESOR	

6.4	KENDALI RESET	

### 7. SISTEM DEBUG	
text

### 8. SET INSTRUKSI ARM DANTHUMB-2	
text


## MIKROKONTROLER STM32F207	

### 7. SISTEMARSITEKTUR DANMEMORI	

7.1	SISTEM BUS MATRIK	

7.2	PEMETAAN MEMORI	

7.3	MEMORI FLASH	

7.4	KONFIGURASI BOOT

### 8. GPIO		

8.1	FITUR-FITUR	

8.2	PENGATURAN GPIO	

### 9. TIMER	

9.1	FITUR UTAMA	

9.2	MODE KERJA TIMER	

### 10. ANALOG TODIGITAL CONVERTER	117

10.1 FITUR UTAMA	

10.2 MODE KERJA

### 11. DIGITAL TOANALOG CONVERTER

11.1 FITUR UTAMA

11.2 MODE KERJA

### 12. KOMUNIKASI SERIAL UART/USART	

12.1 FITUR UTAMA

12.2 MODE KERJA	

### 13. SPI	

13.1 FUNGSI KERJA SPI

13.2 FUNGSI KERJA I2S

###	14 I2C

14.1 FUNGSI KERJA I2C	

14.2 FUNGSI SMBUS

### 15.	CAN	
 
15.1 FUNGSI KERJA CAN

## 16. SISTEM MINIMUM STM32F207	
16.1 CATUDAYA

16.2 SKEMA CATU DAYA STM32F207

120 R KOMENDASI RANCANGAN

16.4 SISTEM RESET	

16.5 CLOCK

16.6 KONFIGURASI BOOT

16.7 SISTEM DEBUG

## 17. ALAT PENGEMBANGAN

17.1 PROBE DEBUG

17.2 IDE

17.3 SOFTWARE PENDUKUNG	

17.4 STM32CUBEMX

17.5 ALAT PEMROGRAM FLASH

17.6 PROGRAM TERMINAL

17.7 PROGRAM PENGANALISA PROTOKOL

17.8 HAL, CMSIS DANMIDDLEWARE	

## PERIPERAL DASAR

###	18. Setup GPIO	

18.1 GPIO SEBAGAI OUTPUT	

18.2 GPIO SEBAGAI INPUT	

18.3 GPIO SEBAGAI SUMBER INTERUPSI	

### 19.	Setup UART	

19.1	KIRIM DAN TERIMA DATA SERIAL	

19.2	FUNGSI PRINTF KE PORT SERIAL	

19.3	TEKNIK PARSING DATA

### 20.	Setup TIMER	

20.1 TIMER SEBAGAI SUMBER PEWAKTUAN	

20.2 TIMER SEBAGAI PEMBANGKIT SINYAL PWM

20.3 TIMER SEBAGAI PENGUKUR SINYAL

20.4 Setup I2C	

## Setup ADC/DAC

### 21. Setup ADC

21.1 PENGUKURAN TEGANGAN DC

21.2 PENGATURAN PWM DENGAN ADC

## 22.	Setup DAC	
22.1 PEMBANGKITAN TEGANGAN DC DENGAN DAC280

22.2 PEMBANGKITAN SINYAL SEGITIGA DAN NOISE

## Setup DMA	

### 23.	UART & I2C using DMA	

23.1 TRANSFER DATA UART DENGAN DMA

23.2 TRANSFER DATA I2C DENGAN DMA	

23.3 GENERATOR SINYAL DENGAN DAC

23.4 DMA MODE NORMAL

23.5 DMA MODE CIRCULAR	

## MIKRO SD CARD & FATFS

### 24. MIKRO SD

24.1 SISTEM FILE

24.2 FATFS

### 25. Setup FATFS	

25.1 OPERASI BACA/TULIS FILE

25.2 JAM DAN TANGGAL AKSES FILE

25.3 MIKRO SD SEBAGAI PENGGANTI EEPROM

### 26. LCD TFT + TOUCH PANEL

26.1 PRINSIP KERJA LCD TFT	

26.2 PRINSIP KERJA LAYAR SENTUH	

26.3 ANTARMUKA LCD DENGAN STM32F207	

26.4 ANTARMUKA	

26.5 PENGALAMATAN

26.6 PEWAKTUAN

26.7 Setup LCD

26.8 LCD – HELLO WORLD

26.9 MENAMPILKAN FILE BMP

### 27.  DEKODER MP3 + MIDI 

### 29. USB

### 30. ETHERNET

---
## Reference :
-, AMBA 3 AHB-Lite Protocol v1.0 Specification, ARM Limited, 2001

-, AMBA Specification (Rev 2.0), ARM Limited, 199

-, Application Note Atmel AT02346: Using the MPU on Atmel Cortex- M3/Cortex-M4 based Microcontroller, Atmel, 2013

-,	Application	Note	Extending	the	DAC	Performance	of	STM32 Microcontrollers, ST Microelectronics, 2015

-, Application Note General-purpose Timer Cookbook, ST Microelectronics, 2016

-, Application Note Getting Started with STM32F20xx/21xx MCU Hardware Development, ST Microelectronics, 2011

-, Application Note How to get the best ADC accuracy in STM32Fx Series and STM32L1 Series Devices, ST Microelectronics, 2013

-, Application Note LCD-TFT display controller (LTDC) on STM32 MCU, ST Microelectronics, 2008

-, Application Note Oscillator Design Guide for STM8AF/AL/S and STM32 Microcontrollers, ST Microelectronics, 2017

-, Application Note STM32 Cross-series Timer Overview, ST Microelectronics, 2016

-, Application Note STM32 Microcontroller System Memory Boot Mode, ST Microelectronics, 2016

-, Application Note STM32’s ADC Modes and Their Applications, ST Microelectronics, 2010

-, Application note TFT LCD Interfacing with high-density STM32F10xxx FSMC, ST Microelectronics, 2008

-, Application Note Using Cortex-M3 and Cortex-M4 Fault Exceptions, Keil, 2010

-, Application Note Using STM32 Device PWM Shut-down Features for Motor Control and Digital Power Conversion, ST Microelectronics, 2016

-, ARM Accredited MCU Engineer AAME Syllabus, ARM Limited, 2014

-, ARM Cortex-M3 Instroduction, ARM University Relations, 2010

-, ARMv7-M Architecture Reference Manual, ARM Limited, 2010

-, Cortex-M3 Devices Generic User Guide, ARM Limited, 2010

-, Cortex-M3 Instruction Set Technical User’s Manual, Texas Instruments, 2010

-, Cortex-M3 Technical Reference Manual Revision r2p1, ARM Limited, 2008

-, Cortex-M3 Technical Reference Manual, ARM Limited, 2008

-, Programming Manual STM32F10xxx/20xxx/21xxx/L1xxxx Cortex-M3 Programming Manual, ST Microelectronics, 2013

-, Reference Manual STM32F205xx, STM32F207xx, STM32F215xx and STM32F217xx Advanced ARM-based 32-bit MCUs, ST Microelectronics, 2015

-, SD Card Specification Simplified Version of: Part E1 SD Input/Output (SDIO) Card Specification Version 1.00, SD Association, 2001

-, SD Specifications Part 1 Physical Layer Simplified Specifications Version 6.00, Technical Committee SD Card Association, 2018

-, User Manual Developing Applications on STM32Cube with FatFS, ST Microelectronics, 2014

Joseph Yiu, The Definitive Guide To ARM Cortex-M3 Processors Second Edition, Newnes, 2007

Richard Phelan, Improving ARM Code Density and Performance New Thumb Extensions to the ARM Architecture, ARM Limited, 2003

Shyam Sadasivan, White Paper An Introduction to the ARM Cortex-M3 Processor, -, 2006

Trevor Martin, The Insider’s Guide To The STM32 ARM Based Microcontroller An Engineer’s Introduction To The STM32 Series Version 1.8, www.hitex.com, 2009


## অধ্যায়-৪ঃ ডেভোলাভমেন্ট বোর্ডস (Development Boards)

রোবটিক্স সার্কিটের পর আমাদের কাজ হচ্ছে সার্কিটকে কন্ট্রোল করা। আর এ জন্যে আমাদের প্রয়োজন কন্ট্রোলার সার্কিট। এই কন্ট্রোলার সার্কিট এর কাজ আমরা করব ডেভোলাভমেন্ট বোর্ডস দিয়ে। যেহেতু আমরা প্রথমে Microcontroller গুলোর সার্কিট নিয়ে কাজ করব তাই আমাদের প্রথম কাজ হচ্ছে ডেভোলাভমেন্ট বোর্ডগুলোকে জেনে নেওয়া। প্রথমেই আমরা দেখব বহুল ব্যবহ্রত আরডুইনো (Arduino) বোর্ড গুলোকে।

## আরডুইনো (Arduino)
Arduino একটি নমনীয়(Flexible), সহজেই ব্যবহারযোগ্য হার্ডওয়্যার এবং সফ্টওয়্যার ভিত্তিক একটি Open Source ইলেকট্রনিক্স প্রোটোটাইপিং Platform। 
 

Arduino তে একই সাথে অনেকগুলো বোর্ড নিয়ে কাজ করা হয়। প্রায় ২০ ধরনের এর বোর্ডগুলোতে রয়েছে একেক ধরনের গঠন উপাদান আর ব্যবহারিক প্রয়োগ। আমরা বহুল ব্যবহ্রত বোর্ডগুলো নিয়ে জানব।

## ``আরডুইনো ইউনো আরথ্রি (Arduino Uno R3)``
“UNO” (ইউনো) অর্থ ইটালিয়ানের ‘এক’ এবং এটির Arduino 1.0 এর আসন্ন প্রকাশের জন্য চিহ্নিত করা হয়েছে। Arduino Uno এবং সংস্করণ 1.0 Arduino এর রেফারেন্স সংস্করণ হবে। UNO USB Arduino বোর্ডের একটি সিরিজের সর্বশেষ সংস্করণ এবং Arduino প্ল্যাটফর্মের রেফারেন্স মডেল। 
আরডুইনো বোর্ডগুলোর মাঝে সবচাইতে ব্যাসিক বোর্ড হচ্ছে UNO। এই Arduino Uno R3 আগের বোর্ডের সমস্ত বৈশিষ্ট্য ছাড়াও, পূর্ববর্তী প্রজন্মের FTDI পাওয়া যায় 8U2 এর পরিবর্তে একটি ATmega16U2 ব্যবহার করে। এই দ্রুত স্থানান্তর হার এবং আরো Memory এর সুবিধা দেয়। লিনাক্স বা ম্যাকের জন্য কোন ড্রাইভার দরকার নেই (উইন্ডোজ এর জন্য .inf ফাইল এবং Arduino IDE- এর মধ্যে অন্তর্ভুক্ত) এবং Uno কিবোর্ড, মাউস, Joystick ইত্যাদি হিসাবে দেখাতে সক্ষম।

Uno এর R3 এছাড়াও AREF এর পাশে SDA এবং SCL পিন যোগ করা। উপরন্তু, Reset পিনের কাছে দুটি নতুন পিন রয়েছে। এক IOREF পিনের সাথে বোর্ড থেকে প্রদত্ত ভোল্টেজের সাথে সামঞ্জস্য করা। অন্যটি সংযুক্ত নয় এবং পরবর্তী ব্যবহারের উদ্দেশ্যে সংরক্ষিত। ইউনোর R3 সব বিদ্যমান Shield (শিল্ড বোর্ড) এর সাথে কাজ করে। 
Arduino Uno 14 ডিজিটাল ইনপুট / আউটপুট পিন (যা 6 PWM আউটপুট হিসাবে ব্যবহার করা যেতে পারে, 6 এনালগ ইনপুট, একটি 16 MHz ক্রিস্টাল oscillator, একটি USB সংযোগ, একটি পাওয়ার জ্যাক, একটি ICSP হেডার, এবং একটি Reset বাটন। এটি Microcontroller সমর্থন এর জন্যে প্রয়োজনীয় সবকিছু রয়েছে। কেবল একটি কম্পিউটারে এটি একটি USB তারের সঙ্গে সংযোগ বা এটি একটি এসি-থেকে-ডিসি অ্যাডাপ্টার বা ব্যাটারি সংযোগ করতে হয়। 

Arduino Uno সমস্ত পূর্ববর্তী বোর্ড থেকে পৃথক যে এটি FTDI USB- থেকে-সিরিয়াল ড্রাইভার চিপ ব্যবহার করে না। পরিবর্তে, এটি ATmega8U2 মাইক্রোকন্ট্রোলার চিপটি একটি ইউএসবি-টু-সিরিয়াল কনভার্টার হিসাবে প্রোগ্রাম করে।

এক নজরে-
- **Microcontroller: ATmega328**
- **Operating Voltage: 5V**
- **Input Voltage (recommended): 7-12V**
- **Input Voltage (limits): 6-20V**
- **Digital I/O Pins: 14 (of which 6 provide PWM output)**
- **Analog Input Pins: 6**
- **DC Current per I/O Pin: 40 mA**
- **DC Current for 3.3V Pin: 50 mA**
- **Flash Memory: 32 KB of which 0.5 KB used by bootloader**
- **SRAM: 2 KB (ATmega328)**
- **EEPROM: 1 KB (ATmega328)**
- **Clock Speed: 16 MHz**
 

### সকল সংকেত সহ- 
 

## ``আরডুইনো মেগা (Arduino MEGA)- Arduino Mega 2560 R3``
Arduino মেগা 2560 ATmega2560 উপর ভিত্তি করে একটি Microcontroller বোর্ড। এটি 54 ডিজিটাল ইনপুট / আউটপুট পিন (যা 14 PWM আউটপুট হিসাবে ব্যবহার করা যেতে পারে), 16 এনালগ ইনপুট, 4 UARTs (হার্ডওয়্যার সিরিয়াল পোর্ট), একটি 16 MHz oscillator, একটি USB সংযোগ, একটি power জ্যাক, একটি ICSP হেডার, এবং একটি Reset Button। 

SEDFL এবং ASL পিনগুলি  communication পিনের কাছে অবস্থিত, এবং AREF পিন এবং দুইটি নতুন পিনের কাছাকাছি রয়েছে, IOREF যেটি shield board গুলি বোর্ডের প্রদত্ত ভোল্টেজের সাথে সামঞ্জস্য করে থাকে। ভবিষ্যতে, shield গুলি যেটি AVR ব্যবহার করে এমন বোর্ডের সাথে সামঞ্জস্যপূর্ণ হবে, যা 5V এর সাথে কাজ করে এবং 3.3V  এর সঙ্গে কাজ করে। দ্বিতীয়টি একটি সংযুক্ত পিন নয়, এটি পরবর্তীতে ব্যবহারের জন্য সংরক্ষিত। সাথে রয়েছে শক্তিশালী রিসেট এবং Atmega 16U2 এর  প্রতিস্থাপন করা  8U2।
Arduino মেগা 2560 microcontroller সমর্থন করার জন্যে প্রয়োজন সবকিছু আছে। 


এক নজরে- 	
- **Microcontroller ATmega2560**
- **Operating Voltage 5V**
- **Input Voltage (recommended) 7-12V**
- **Input Voltage (limits) 6-20V**
- **Digital I/O Pins 54 (of which 14 provide PWM output)**
- **Analog Input Pins 16**
- **DC Current per I/O Pin 40 mA**
- **DC Current for 3.3V Pin 50 mA**
- **Flash Memory 256 KB of which 8 KB used by bootloader**
- **SRAM 8 KB**
- **EEPROM 4 KB**
- **Clock Speed 16 MHz**

আরডুইনো ইউনো থেকে এর ইনপুট পিন বেশি থাকায় আমরা একই সাথে অনেকগুলো সার্কিটে ইনপুট সংযোগ করতে পারব। পাশাপাশি এর কারয ক্ষমতাও অনেক বেশি (প্রায় ১৬ গুণ)। 

 
### সকল সংকেত সহ- 
 

## ``আরডুইনো প্রো মিনি(Arduino Pro Mini 328 - 5V/16MHz)``

আরডুইনো প্রো মিনি 328 Arduino এর সংক্ষিপ্ত নকশা পদ্ধতি। এই একটি 5V Arduino 16MHz বুটলোডার চলমান (Arduino সফ্টওয়্যার মধ্যে 'Arduino Duemilanove W / 328' নির্বাচন করো)। Arduino প্রো সিরিজ সিস্টেম ভোল্টেজ (5V) এবং USB ছাড়া অপারেট করতে সক্ষম। 
Arduino খরচ কমানোর জন্য, Arduino প্রো মিনি, Arduino মিনি (একই পিন আউট) মত হয়, কিন্তু খরচ কম রাখা, সব SMD উপাদান ব্যবহার করে, এটি দুই স্তর তৈরি। এই বোর্ড FTDI বেসিক ব্রেকআউট সরাসরি সংযোগ করে প্রোগ্রামিং জন্য বোর্ড এবং স্বয়ংক্রিয় রি সেট সমর্থন করে। 
এই বোর্ডের সর্বশেষ এবং সর্বশ্রেষ্ঠ সংস্করণ ADC6 এবং ADC7 পিনের পাশাপাশি ঐচ্ছিক I2C pull-up resistors ব্যবহারের জন্য Footprints যোগ করা। 
 
এক নজরে-
- **ATmega328 running at 16MHz with external resonator (0.5% tolerance)**
- **USB connection off board**
- **Supports auto-reset**
- **5V regulator**
- **Max 150mA output**
- **Over current protected**
- **Reverse polarity protected**
- **DC input 5V up to 12V**
- **On board Power and Status LEDs**
 

আরডুইনো থেকে আমরা এবার একটু উন্নত বোর্ডে যাব। আরডুইনো থেকে অনেক কার্যক্ষম একটি বোর্ড হলো Raspberry Pi। 
 
## ``Raspberry Pi 3 Model B``

Raspberry Pi 3 মডেল B হল তৃতীয় প্রজন্মের Raspberry Pi। এই শক্তিশালী ক্রেডিট কার্ড আকারের একক বোর্ড কম্পিউটার এর অনেক Application এর  জন্য ব্যবহার করা যেতে পারে এবং মূল Raspberry Pi মডেল বি + Raspberry Pi ২ মডেল স্থানান্তরিত করে B মডেল। Raspberry Pi 3 মডেল জনপ্রিয় বোর্ড ফরম্যাট বজায় রাখার সময় B আপনাকে প্রথম প্রজন্মের তুলনায় 10 গুণ বেশি দ্রুতগতির একটি শক্তিশালী প্রসেসর নিয়ে আসে।  Raspberry Pi উপরন্তু এটি Wifi Lan এবং Bluetooth সংযোগ যোগ করে এটি শক্তিশালী সংযুক্ত ডিজাইনের জন্য আদর্শ সমাধান তৈরি করে।
 
এক নজরে –
### SoC: Broadcom BCM2837
### CPU: 4× ARM Cortex-A53, 1.2GHz
### GPU: Broadcom Video Core IV
### RAM: 1GB LPDDR2 (900 MHz)
### Networking: 10/100 Ethernet, 2.4GHz 802.11n wireless
### Bluetooth: Bluetooth 4.1 Classic, Bluetooth Low Energy
### Storage: microSD
### GPIO: 40-pin header, populated
### Ports: HDMI, 3.5mm analogue audio-video jack, 4× USB 2.0, Ethernet, Camera Serial Interface (CSI), Display Serial Interface (DSI)

সুতরাং, মূলত তুমি তোমার Project এর উপর নির্ভর করে, অনেকগুলো I/O পোর্ট প্রয়োজন হলে Arduino Due / Mega ব্যবহার করবে। আর যদি ছোট Project হয় তবে  - মাইক্রো, মিনি এবং Nano অত্যন্ত সহজ হবে। যদি তুমি IOT প্রকল্পে কাজ করো এবং Raspberry Pi বোর্ডের পরিবর্তে ইন্টারনেট অ্যাক্সেস করার জন্য Arduino (আমি সবসময় একটি লিনাক্স বোর্ডে ইন্টারনেট ব্যবহার করতে পছন্দ করি) ব্যবহার করতে পারো। কিন্তু শুরুতে আমি Uno ব্যবহার না করে  Mega কে  সুপারিশ করব। Uno ব্যবহার করা সহজ, কিন্তু Mega এর কাজ করার স্পিড অনেক ভালো আর অনেকগুলো I/O পিন এতে রয়েছে। 


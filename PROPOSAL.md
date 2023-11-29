> **A System for Monitoring Temperature and Humidity for Quality
> Warehousing of Agricultural and Pharmaceutical Products**
>
> <img src="media/image1.png" style="width:3.16495in;height:1.76202in" />
>
> **Nkatha Claire - SCM211-0307/2020**
>
> **Kinyua Vivian - SCM211-0347/2020**
>
> **Muiga Stephen - SCM211-0630/2020**
>
> **Omoga Nick - SCM211-0635/2020**
>
> **Muriuki Harun - SCM211-0743/2020**
>
> **A Research Proposal Submitted To The Department Of Pure And Applied
> Mathematics In The School Of Mathematical And Physical Sciences In
> Partial Fulfillment Of The Requirement For The Award Of The Degree Of
> Bachelor Of Science In Mathematics And Computer Science Of Jomo
> Kenyatta University Of Agriculture And Technology**
>
> **2023**

# DECLARATION

> This proposal is our original work and has not been presented for a
> degree in any other university.
>
> **Signature: …………………………………..…………Date: …………………….**
>
> **Nkatha Claire (SCM211-0307/2020)**
>
> **Signature: …………………………………..…………Date: …………………….**
>
> **Kinyua Vivian (SCM211-0347/2020)**
>
> **Signature: …………………………………..…………Date: …………………….**
>
> **Muiga Stephen (SCM211-0630/2020)**
>
> **Signature: …………………………………..…………Date: …………………….**
>
> **Omoga Nick (SCM211-0635/2020)**
>
> **Signature: …………………………………..…………Date: …………………….**
>
> **Muriuki Harun (SCM211-0743/2020)**
>
> This proposal has been submitted for examination with my approval as
> the University Supervisor.
>
> **Signature: …………………………………..…………Date: …………………….**
>
> **Dr. Richard Kariuki**
>
> **JKUAT, Kenya**
>
> **  
> **

# TABLE OF CONTENTS

> [DECLARATION [ii](#declaration)](#declaration)
>
> [TABLE OF CONTENTS [iii](#table-of-contents)](#table-of-contents)
>
> [ABBREVIATIONS AND KEYWORDS [iv](#_Toc152115043)](#_Toc152115043)
>
> [ABSTRACT [v](#abstract)](#abstract)
>
> [CHAPTER ONE [1](#chapter-one)](#chapter-one)
>
> [INTRODUCTION [1](#introduction)](#introduction)
>
> [1.1 Background of the study
> [1](#background-of-the-study)](#background-of-the-study)
>
> [1.1.1 The role of technology in storage
> [1](#the-role-of-technology-in-storage)](#the-role-of-technology-in-storage)

[1.1.2 Systems Development
[2](#systems-development)](#systems-development)

> [1.1.2.1 Real-time Systems Development
> [2](#real-time-systems-development)](#real-time-systems-development)
>
> [1.1.2.2 Applications of Real-time Systems
> [2](#applications-of-real-time-systems)](#applications-of-real-time-systems)
>
> [1.1.2.3 History of Real-time Systems
> [3](#history-of-real-time-systems)](#history-of-real-time-systems)
>
> [1.1.2.4 Types of Real-time Systems
> [3](#types-of-real-time-systems)](#types-of-real-time-systems)
>
> [1.2 Problem Statement [3](#problem-statement)](#problem-statement)
>
> [1.3 Justification [4](#justification)](#justification)
>
> [1.4 Objectives [4](#objectives)](#objectives)
>
> [1.4.1 General Objectives
> [4](#general-objectives)](#general-objectives)
>
> [1.4.2 Specific Objectives
> [4](#specific-objectives)](#specific-objectives)

[1.5 Scope of study [5](#scope-of-study)](#scope-of-study)

> [CHAPTER TWO [6](#chapter-two)](#chapter-two)
>
> [LITERATURE REVIEW [6](#literature-review)](#literature-review)
>
> [2.1 Introduction [6](#introduction-1)](#introduction-1)
>
> [2.2 Navigating Advancements in Monitoring Systems
> [6](#navigating-advancements-in-monitoring-systems)](#navigating-advancements-in-monitoring-systems)
>
> [CHAPTER THREE [9](#chapter-three)](#chapter-three)
>
> [METHODOLOGY [9](#methodology)](#methodology)

[3.1 Introduction [9](#introduction-2)](#introduction-2)

[3.2 Hardware [9](#hardware)](#hardware)

[3.3 Frontend [10](#frontend)](#frontend)

[3.4 Backend [11](#backend)](#backend)

[3.5 Data Collection Method
[12](#data-collection-method)](#data-collection-method)

[3.7 Data Flow Diagram [13](#data-flow-diagram)](#data-flow-diagram)

> [References [14](#references)](#references)
>
> [APPENDICES [16](#appendices)](#appendices)
>
> [APPENDIX 1: WORK PLAN
> [16](#appendix-1-work-plan)](#appendix-1-work-plan)
>
> [APPENDIX 2: BUDGET [17](#appendix-2-budget)](#appendix-2-budget)

<span id="_Toc152115043" class="anchor"></span>

# ABBREVIATIONS AND KEYWORDS

>  SMS -  Short Message Service
>
>  Wi-Fi - Wireless Fidelity
>
>  CDC -  Centers for Disease Control and Prevention
>
>  IoT - Internet Of Things
>
>  JSON - Javascript Object Notation
>
>  DHT22-  A digital temperature and humidity sensor
>
>  ESP32 - A feature-rich System on a Chip microcontroller
>
>  Breadboard - A plastic board with holes that allow connection of
> electrical components
>
>  MQTT - Message Queuing Telemetry Transport
>
>  IDE - Integrated Development Environment
>
>  SMTP - Simple Mail Transfer Protocol
>
>  VS Code - Visual Studio Code
>
>  PlatformIO - Cross-platform, multi-framework professional IDE tool
> for embedded systems
>
>  HTTP - Hypertext Transfer Protocol
>
>  HTML - Hypertext Markup Language
>
>  CSS - Cascading Style Sheet
>
> Chart.js - JavaScript library for data visualization
>
> GSM - Global System for Mobile Communications

# ABSTRACT 

> In an era when supply chain efficiency and product quality are
> critical, managing environmental conditions in warehouses and stores
> is critical to guaranteeing the integrity and safety of stored items.
> Temperature and humidity play a key role, particularly in industries
> like food, pharmaceuticals, and logistics. However, manual monitoring
> of these conditions is subject to human error. This study proposes a
> way to monitor these conditions both onsite and remotely through an
> application that will receive the online alerts and an SMS module for
> offline alerts aiming to improve storage conditions and protect
> product quality in the agricultural and pharmaceutical sector. The
> system will utilize DHT22 sensors together with ESP32 microcontroller
> and a GSM module for the hardware, Python and Angular framework for
> the mobile application development. This study utilizes IoT technology
> and data analysis to address a crucial need in warehouse and store
> management. Ultimately, we believe this initiative will not only boost
> product quality but also contribute to more sustainable and efficient
> operations.

# CHAPTER one

# INTRODUCTION

# Background of the study

# 1.1.1 The role of technology in storage 

> The Kenya 2023 population is estimated at 55,100,586 people at
> mid-year. This population is equivalent to 0.68% of the total world
> population. Feeding this population must be addressed by several
> approaches that include technologies to maximize yield and reduce food
> losses in the field. A recent report from the Food and Agriculture
> Organization (FAO) reveals that about 30 percent of global food is
> lost or wasted due to several factors, including poor post-harvest
> management (FAO, 2019). The African Postharvest Losses Information
> System (APHLIS) indicates that a large proportion of post-harvest
> losses is largely caused by poor post-harvest management and limited
> access to efficient storage facilities (World Bank, 2011). As such,
> improving access to proper storage facilities is vital in helping
> farmers avoid food loss, increase their income, and boost the supply
> of nutritious foods to the continent's growing number of consumers
> (Deloitte, 2015). 
>
> People in industries like pharmaceuticals work in a risk-prone
> industry where they must avoid asset failures at any cost, as making
> mistakes is unacceptable because quality control has a direct impact
> on the health of the consumer and there should be no opportunities for
> errors to be made. If biomaterial is not stored appropriately,
> medications can be exposed to varying environmental changes, making
> them lose their effectiveness. If such drugs are ingested, they can be
> harmful to consumers' health. The CDC recommends that every medication
> holding facility should have temperature monitoring devices to detect
> any temperature fluctuations. The use of continuous monitoring and
> recording devices that are known as “digital data loggers” is what the
> CDC recommends.
>
> IoT technology can help in enabling the optimal circumstances for
> supervising different stored biomaterials, chemicals and agricultural
> produce. The integration of advanced sensor technologies and
> data-driven applications presents a transformative opportunity to
> address storage challenges. IoT and smart sensors can be coupled with
> a variety of existing devices that could further enhance storage by
> facilitating accurate real-time remote monitoring of conditions. This
> has revolutionized both the agriculture and pharmaceutical industries
> in terms of resource optimization, controlling climate effects, and
> improving returns (Sensors 2016, 16, 1141).  

## 1.1.2 Systems Development

## 1.1.2.1 Real-time Systems Development

> Real-time systems are systems that provide immediate and accurate
> responses to external events. They can reduce human error by
> automating tasks that require precision, accuracy, and consistency.
> They can also be customized to meet specific requirements, making them
> ideal for a wide range of applications. The main advantage of
> real-time systems is they minimize the need for human intervention
> hence reducing the risk of errors.

## 1.1.2.2 Applications of Real-time Systems

> These systems respond to external events or input stimuli in a timely
> fashion (within finite and specified time). Timing constraints include
> response time, start time and finish time, that is, time taken to
> respond to the event, time at which the response to the event starts
> and time at which the response is given. Consider a Weapons Defense
> System, the radar system continuously monitors for potential threats
> like incoming missiles and measures the coordinates of the targets. It
> then sends these coordinates to the control system, which then
> determines the level of threat possessed by the target based on the
> information from the radar system. The command and decision system
> then calculates different parameters of the target like speed of the
> missile, flight path and possible point of impact. Based on the above
> parameters, the Control System then activates the Weapons Firing
> System, which fires continuously until the target is destroyed. The
> communication between the command and decision system and the radar
> system happens in real time since a potential threat can occur at any
> time and it is unpredictable. These systems are also applied in latest
> smart TVs, GPS Navigation Systems, almost all modern day smartphones,
> and anti-lock brakes and airbags in automobiles.

## 1.1.2.3 History of Real-time Systems

> The term real-time is derived from its use in early simulation, where
> real-time processes were simulated at a rate matching that of a real
> process. Analog computers were capable of simulating at a faster pace
> than real-time. Minicomputers, from 1970 onwards, when built into
> dedicated embedded systems increased the need for low-latency
> priority-based responses. This led to the rise of operating systems
> such as Real- Time Operating Systems, which would be used for
> time-sharing multi-user duties. Then, the MOS Technology 6502 and
> later the Motorola 68000 became popular, anybody could use their
> personal computer as a real-time system.

## 1.1.2.4 Types of Real-time Systems

> **Hard Real-Time Systems:** These are systems whereby non-compliance
> with the set restrictions can result in dire consequences. The
> usefulness of these systems drastically reduce when deadlines are
> continuously missed
>
> **Soft Real-Time Systems:** These systems can occasionally miss their
> deadlines with some acceptable low probability. No dire consequences
> result from missing the deadlines.  
> **Firm Real-Time Systems:** In firm real-time systems, missing a
> deadline is tolerable, but the usefulness of the output decreases with
> time

# 1.2 Problem Statement

> The agricultural sector, through farms and stores, industries and
> warehouses in general, play a critical role in the production, storage
> and distribution of various goods, ranging from perishable items like
> food and pharmaceuticals to durable goods such as electronics.
> However, the efficient management of these facilities is challenged by
> environmental factors, primarily temperature and humidity
> fluctuations. Currently, in Kenya, traditional methods are used to
> monitor and manage temperature and humidity fluctuations but these
> methods may not adequately address the mentioned factors. The absence
> of real-time monitoring and alert systems leave these facilities
> sensitive to adverse conditions, leading to increased product losses,
> compromised quality, and potential non-compliance with industry and
> regulatory standards. The proposed study aims to address the
> identified problems by implementing a comprehensive system of
> temperature and humidity sensors in warehouses, stores, greenhouses,
> industries and any other place where the system is applicable. Through
> the deployment of advanced sensor technologies, the study seeks to
> mitigate the challenges faced by farmers and warehouse managers by
> offering a real-time monitoring and alert systems, ushering in a new
> era of enhanced product quality, operational efficiency, and
> environmental responsibility.

#  1.3 Justification

> Through extensive survey, it has been proven that significant losses
> are incurred due to poor storage conditions, point in case being in
> agriculture and the pharmaceutical industry. Most of the existing
> systems require human intervention to check and detect abnormal
> changes in the temperature and humidity levels. The proposed system
> intends to make improvements by displaying real-time readings on a
> mobile application where the user receives online and also offline
> alerts via SMS. Consequently, this will increase productivity in
> agriculture since by giving real-time information on environmental
> conditions, agricultural operations will be optimized. Remote
> monitoring and alerts also allows stakeholders to remotely access and
> monitor temperature and humidity conditions in real-time, providing
> timely insights and enabling swift response to any deviations, and as
> a result help reduce financial losses and spoilage. There is a
> regulatory compliance that organizations should follow in terms of
> handling and storage conditions; this system will help in ensuring
> that this obligation are met.

# 1.4 Objectives

# 1.4.1 General Objectives

> To develop a system for monitoring temperature and humidity for
> quality warehousing of agricultural and pharmaceutical products.

## 1.4.2 Specific Objectives

1.  To create a sensor network by connecting a DHT22 sensor to an ESP32
    > microcontroller.

2.  To develop a user-friendly mobile application and integrate it with
    > the sensor network to display readings to the user.

3.  To establish a robust data collection and analysis framework to
    > monitor and evaluate temperature and humidity fluctuations in
    > real-time.

4.  To implement a reporting and alerts feature to notify users, either
    > online or offline, of any deviations from optimal storage
    > conditions.

##  1.5 Scope of study

> This project will exclusively focus on developing an Internet of
> Things (IoT) system tailored for the agricultural and pharmaceutical
> industries, emphasizing comprehensive environmental monitoring within
> storage and warehouse facilities. The study will specifically address
> challenges related to temperature and humidity fluctuations, aiming to
> optimize conditions crucial for product quality preservation. The
> scope includes the integration of advanced sensor technologies,
> real-time data analytics, and a user-friendly interface, with a
> primary goal of enhancing storage efficiency and minimizing
> post-harvest losses in these vital sectors

# CHAPTER two

# LITERATURE REVIEW

# 2.1 Introduction

> This chapter provides a review of literature from previous studies
> having bearing on the current study.

# 2.2 Navigating Advancements in Monitoring Systems

> Beckwith (2004) implemented a sensor network in a vineyard.
> Temperature measurements were collected during one month. The
> information was used for addressing two important parameters in wine
> production: heat accumulation and potential frost damage
>
> Hamrita (2005) developed a lab prototype for wireless measurement of
> soil temperatures. Measurements showed a high correlation (greater
> than 99%) with those obtained using a thermocouple.
>
> Lea-Cox (2007) developed a sensor network in a greenhouse that
> integrates a variety of sensors which can measure substrate water,
> temperature, electrical conductivity, daily photosynthetic radiation
> and leaf wetness in real-time. Benefits came from an improved plant
> growth, more efficient water and fertilizer applications, together
> with a reduction in disease problems related to over-watering.
>
> Bott (2007) in his study on storage conditions for stability testing
> of pharmaceuticals in hot and humid regions provides a scientific
> information useful for the definition of storage conditions for
> stability testing of pharmaceuticals suitable to the region where the
> product will be dispensed
>
> Park (2009) proposed a greenhouse automation system and mainly
> monitoring of crops conditions such as temperature and humidity of the
> crops to predict possible crop diseases and deal with them beforehand
> to increase productivity
>
> Preserving freshness and safety while extending postharvest life for
> horticultural products necessitates specific temperature and humidity
> conditions crucial for quality preservation (Kader, 2013). The process
> involves careful temperature control during initial cooling and across
> the cold chain, including transportation, storage, and retail display.
> Alongside managing relative humidity, it aims to minimize moisture
> loss. Implementing these conditions optimizes postharvest life,
> ensuring the integrity and safety of horticultural products (Kader,
> 2013).
>
> Tsang (2018) did a study to propose an IoT-driven risk monitoring
> system (IoTRMS) to oversee product quality and occupational safety
> risks in cold chains. IoTRMS integrated wireless sensor networks,
> cloud databases, and fuzzy logic to monitor environmental conditions,
> assess product quality degradation, and evaluate cold-associated
> occupational risks. Real-time monitoring ensures compliance with
> handling requirements, reducing occupational risks and enhancing
> operational efficiency within cold chain activities. This innovative
> approach addresses the lack of comprehensive risk consideration in
> cold chains, aiming to ensure secure product quality and effective
> occupational safety management
>
> According to Thakur (2019), Wireless Sensor Networks (WSN) are
> extensively employed in diverse domains like agriculture,
> surveillance, and smart technologies. Precision Agriculture (PA)
> notably embraces WSNs to measure environmental parameters such as
> humidity, temperature, soil moisture, and soil pH to optimize crop
> quantity and quality while conserving natural resources. Their study
> aimed at examining WSN technologies in PA, emphasizing their impact on
> achieving smart agriculture through monitoring environmental
> parameters like irrigation, soil properties, and temperature.
>
>  Dublin (2020) in his study on the impact of IoT technology on
> pharmaceutical green supply chain management, he notes that the
> distribution monitoring and remote control in this sector is becoming
> vital, pharmaceuticals manufacturers are always commencing more
> biologic products, which are highly sensitive to storage conditions.
>
> Haycocks (2021) says that lighting, temperature, humidity and
> ventilation should be appropriate and such that they do not adversely
> affect, directly or indirectly, either the medicinal products during
> their manufacture and storage, or the accurate functioning of
> equipment. Also storage areas should be designed or adapted to ensure
> good storage conditions. In particular, they should be clean and dry
> and maintained within acceptable temperature limits. Where special
> storage conditions are required (e.g. temperature, humidity) these
> should be provided, checked and monitored.
>
> Morchid (2023) conducted a study on the applications of IoT and sensor
> technology to increase food security and agricultural sustainability.
> The research offered four levels of the IoT architecture for smart
> agriculture: the perception or sensing and actuator layer, the network
> layer, the cloud layer, and the application layer.   
>
> Rajak (2023) did a study on the scopes and challenges of Internet of
> Things and smart sensors in agriculture and noted that  IoT-based
> smart sensors can accurately monitor environmental factors such as
> temperature, moisture, and humidity. By ensuring humidity protection
> and temperature preservation in the stockroom, it also embraces smart
> warehouse supervision.
>
> From the existing literature, it becomes evident that while there is a
> lot of information on the importance of monitoring temperature and
> humidity in different sectors, a notable gap exists in the
> availability of integrated solutions for proper storage. The current
> methods or solutions for monitoring temperature and humidity in
> storage areas, particularly in agriculture and pharmaceuticals, do not
> meet the criteria for efficiency. This is because most of the system
> mainly rely on manual monitoring and this is prone to human error.
> This proposed study seeks to address this deficiency by developing a
> mobile application that seamlessly integrates with external sensors,
> providing a holistic solution for monitoring temperature and humidity
> in storage areas and especially within the agriculture and
> pharmaceutical sectors. The proposed system aims to fill the existing
> gap and make a meaningful impact by improving how we monitor these
> conditions.**  
> **

# CHAPTER three

#  METHODOLOGY

## 3.1 Introduction

> This chapter outlines the Hardware and Software used in order to
> achieve the objectives of the study.

## 3.2 Hardware

> The proposed study will utilize the DHT22 sensors that are used to
> measure temperature and relative humidity. These sensors contain a
> chip that does analog to digital conversion and spit out a digital
> signal with the temperature and humidity. This makes them very easy to
> use with any microcontroller. Along with the DHT22 sensors the study
> will make use of ESP32, Breadboard, Resistor, and Jumper wires. After
> doing the wiring, installing the necessary libraries, and writing some
> efficient code, sensor readings will be obtained at every set time
> interval which the farmer or warehouse manager will be able to set on
> the app accordingly. The proposed system will also use the GSM module
> to send offline alerts to the relevant users
>
> First, the DHT22 is connected to an ESP32 board. To flash and program
> it, the system will use PlatformIO. PlatformIO is installed as a
> plugin and adds a completely new screen to the IDE. With it, one can
> install platform and board support for the microcontroller. The ESP32
> will then be added to support to PlatformIO and programming will be
> set to begin. To read data from the DHT22, the necessary libraries
> will be installed. The ESP32 has WiFi capabilities which are activated
> at this point. The sensor starts and connects to the Wi-Fi. Then it
> uses the Wi-Fi connection to connect to the MQTT server. The DHT22
> sensor data, temperature and humidity, are captured and manually
> parsed together to a JSON string. This string is converted to a C char
> array and sent to the MQTT server. Afterwards, the sensor goes into
> deep sleep mode, waits for the duration of the set interval, and
> repeats these steps. 

## 3.3 Frontend

> For context, it is assumed the system will be used in a warehouse
> where there are compartments and the sensors are at different
> locations within the compartment. Each sensor will be marked by number
> and registered on the system under the specific warehouse and
> compartment.
>
> **Visual Studio Code**
>
> The study will use VS code as the primary IDE and use the necessary
> plugins needed for the development of the system. 
>
> **Angular with TypeScript**
>
> The study will use the Angular framework to create the frontend logic.
> Once a page is created, HTML, CSS/SCSS, spec (for tests), and .ts
> files are created for it thus making the structure easy to work with
> even during page routing.
>
> **Ionic**
>
> In the study, the system will leverage Ionic, a platform facilitating
> the development of hybrid mobile, desktop, and progressive web
> applications using CSS, HTML5, and Sass. Emphasizing the use of web
> technologies, particularly for mobile apps, Ionic enables deployment
> through native app stores via Cordova or Capacitor. This approach
> ensures the creation of cross-platform applications, delivering a
> unified user experience across various devices while harnessing the
> flexibility of web technologies.
>
> **Chart.js and Angular Highcharts**
>
> The study will use chart js, a simple yet flexible JavaScript charting
> library for the modern web to visualize our data.
>
> Using forms, the system will be able to obtain this registration input
> from the user and record it in the database. The first page on the
> application will allow the users to either sign up or log in if they
> are already registered and will serve as a guard. If all guards return
> true, navigation continues. The responsive dashboard which will be the
> first page, will contain elements to offer concise visualizations and
> communicate the data easily. 
>
> The system will have a readings page that will display each sensor’s
> data upon selection from dropdowns containing lists of all registered
> warehouses and compartments. 
>
> The application will also have an alerts page where the user will be
> able to set the threshold conditions for each variable and alerts will
> be thrown with respect to these. All notifications will be logged on
> the page. 

## 3.4 Backend

> The approach involves establishing a Wi-Fi connection with sensors
> capable of transmitting temperature and humidity data over the
> internet using ESP32 modules. These modules directly link to Wi-Fi
> networks and facilitate data transmission.
>
> Using Python, a backend system will be constructed to receive data
> from these Wi-Fi-connected sensors. This will entail developing a
> server-side application that listens for incoming data packets or HTTP
> requests sent by the sensors.
>
> Upon data reception, the backend system will process it, employing
> Python libraries like Pandas or NumPy for data manipulation and
> statistical analysis. This aids in deriving insights from the
> temperature and humidity readings.
>
> Furthermore, a user interface or settings panel enabling users to
> establish thresholds for temperature and humidity will be created.
> This interface, using frameworks like Flask or Django, will allow
> users to input their desired threshold values.
>
> By continuously monitoring incoming sensor data, the backend system
> triggers notifications when received temperature or humidity exceeds
> the set threshold values. This notification mechanism, employing
> services like SMTP, Twilio, or Firebase Cloud Messaging, will alert
> users about threshold breaches, enabling timely actions or
> interventions based on the received data.
>
> Ensuring a secure communication protocol, robust error handling
> mechanisms, and reliability in the Python backend are pivotal for
> maintaining the integrity and reliability of the data received from
> sensors over Wi-Fi.

## 3.5 Data Collection Method

> Sensors will be programmed to collect temperature and humidity data at
> regular intervals, typically every 10 minutes. This data will be
> transmitted to the backend for storage and analysis, ensuring a
> continuous flow of real-time information.
>
> To maintain accuracy and consistency, the system will implement
> continuous data validation mechanisms. Regular checks and calibration
> of sensors will be conducted to mitigate potential sensor drift or
> inaccuracies.
>
> Scheduled maintenance routines will include calibration checks and
> performance assessments to uphold data quality standards. These
> routines will ensure that the sensors provide accurate and reliable
> readings, contributing to the overall efficacy of the system.

## 3.7 Data Flow Diagram

> Below is a data-flow diagram that gives an overview of the user
> interaction with the application;

<img src="media/image2.png" style="width:7.77001in;height:3.73196in" alt="https://lh7-us.googleusercontent.com/Uq2a5wdqOZMV2xtK66pFoJm4M9mqDftv2rUNTSDsEop00ZMC3NP231Q_CTs19cdKioNShohSqwtno8qQuh7gHkgksCFSXLrTDL6On7JtkkxgmAopgujW_q7Wof--JL-hqNEIzazoFdajFKVZxTECGdg" />

> *Figure 1: System Data Flow Diagram*
>
>  

# References

Aitkenhead, M., Donnelly, D., Coull, M., & Black, H. (2013). E-smart:
environmental sensing for monitoring and advising in real-time. *IFIP
Advances in Information and Communication Technology.*

Barmpakos, D., & Kaltsas, G. (2021). A Review on Humidity, Temperature
and Strain Printed Sensors—*Current Trends and Future Perspectives.
Sensors, 21*(3), 739.

Beckwith, R., Teibel, D., & Bowen, P. (2004). Report from the Field:
Results from an Agricultural Wireless Sensor Network. *Proceeding of
29th Annual IEEE International Conference on Local Computer Networks*;
Tampa, FL, USA.

Burrell, J., Brooke, T., & Beckwith, R. (2004). Vineyard Computing:
Sensors Networks in Agricultural Production*. Lect Note Comput Sci.*

Hamrita, T., & Hoffacker, E. (2005). Development of a “Smart” Wireless
soil Monitoring Sensor Prototype Using RFID Technology*. Appl Eng Agric.
;21*:139–143.

Han, G., Jiang, J., Shu, L., Niu, J., & Chao, H.-C. (2014). Management
and applications of trust in Wireless Sensor Networks*: A survey. J.
Comput. Syst. Sci., 80*:602–617.

Imam, S.A., Choudhary, A., & Sachan, V.K. (2015). Design issues for
wireless sensor networks and smart humidity sensors for precision
agriculture: A review. *In Proceedings of the 2015 International
Conference on Soft Computing Techniques and Implementations (ICSCTI),
Faridabad, India, 8–10* ; pp. 181–187.

Kader, A. A. (2013). Postharvest Technology of Horticultural Crops - An
Overview from Farm to Fork. *Ethiopian Journal of Applied Science and
Technology, 1*(1), 1-8.

Lea-Cox, J.D., Kantor, G., Anhalt, J., Ristvey, A., & Ross, D.S. (2007).
A Wireless Sensor Network for the Nursery and Greenhouse Industry.
Southern Nursery Association Research Conference; Atlanta, GA, USA. 8–9
August.

Liu, H., Meng, Z., & Cui, S. (2007). A Wireless Sensor Network Prototype
for Environmental Monitoring in Greenhouses. International Conference on
Wireless Communications, Networking and Mobile Computing; Shanghai,
China.

Mhatre, L., & Rai, N. (2017). Integration betouren wireless sensor and
cloud. In: I-SMAC (iot in Social, Mobile, Analytics and Cloud)
(I-SMAC).*IEEE. 779‒782*.

Ocieczek, A., Pukszta, T., Żyłka, K., & Kirieieva, N. (2023). The
influence of storage conditions on the stability of selected
health-promoting properties of tea. *LWT, 184*, 115029.

Prodanović, R., Rančić, D., Vulić, I., Zorić, N., Bogićević, D.,
Ostojić, G., Sarang, S., & Stankovski, S. (2020). Wireless Sensor
Network in Agriculture: Model of Cyber Security. Sensors.

Radosavljević, N., & Babić, Đ. (2020). Overview of Security Threats,
Prevention and Protection Mechanisms in Wireless Sensor Networks. J.
Mechatron. Autom. Identif. *Technol. 5*, 1–6.

Rault, T., Bouabdallah, A., & Challal, Y. (2014). Energy efficiency in
wireless sensor networks: A top-down survey. *Comput. Networks, 67*,
104–122.

Roy, A. S., & Bandyopadhyay, S. (2008). Agro-sense: precision
agriculture using sensor-based wireless mesh networks. In Proceedings of
the 1st ITU-T Kaleidoscope Academic Conference Innovations in NGN:
Future Network and Services.

Tsang, Y. P., Choy, K. L., Wu, C. H., Ho, G. T., Lam, C. H., & Koo, P.
S. (2018). An Internet of Things (iot)-based risk monitoring system for
managing cold supply chain risks*. Industrial Management & Data
Systems.rnal of Applied Science and Technology,* (1), 1-8.

Rajak,p.(2023),Internet of Things and smart sensors in agriculture:
Scopes

> and challenges, *Journal of Agriculture and Food Research, Volume
> 14*,100776,ISSN 2666-1543.

Dublin,G.(2020),the impact of IoT technology on pharmaceutical green
supply chain management, *International Journal of Pharmaceutical
Sciences Review and Research 16*, 121–129.

# APPENDICES 

# APPENDIX 1: WORK PLAN

# 

<table style="width:100%;">
<colgroup>
<col style="width: 20%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><h1 id="period" class="BEST"> period </h1>
<h1 id="activity" class="BEST">activity </h1></th>
<th><h1 id="september-2023" class="BEST">September 2023</h1>
<h1 id="section-1" class="BEST"></h1></th>
<th><h1 id="october-2023" class="BEST">October 2023</h1>
<h1 id="section-2" class="BEST"></h1></th>
<th><h1 id="november-2023" class="BEST">November 2023</h1>
<h1 id="section-3" class="BEST"></h1></th>
<th><h1 id="december-2023" class="BEST">December 2023</h1>
<h1 id="section-4" class="BEST"></h1></th>
<th><h1 id="january-2024" class="BEST">January 2024</h1>
<h1 id="section-5" class="BEST"></h1></th>
<th><h1 id="february-2024" class="BEST">February 2024</h1>
<h1 id="section-6" class="BEST"></h1></th>
<th><h1 id="march-2024" class="BEST">March 2024</h1>
<h1 id="section-7" class="BEST"></h1></th>
<th><h1 id="april-2024" class="BEST">April 2024</h1></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h1 id="problem-identification-and-proposal-development" class="BEST">Problem identification and Proposal Development</h1></td>
<td><h1 id="section-8" class="BEST"></h1></td>
<td><h1 id="section-9" class="BEST"></h1></td>
<td><h1 id="section-10" class="BEST"></h1></td>
<td><h1 id="section-11" class="BEST"></h1></td>
<td><h1 id="section-12" class="BEST"></h1></td>
<td><h1 id="section-13" class="BEST"></h1></td>
<td><h1 id="section-14" class="BEST"></h1></td>
<td><h1 id="section-15" class="BEST"></h1></td>
</tr>
<tr class="even">
<td><h1 id="literature-review-1" class="BEST">Literature Review</h1></td>
<td><h1 id="section-16" class="BEST"></h1></td>
<td><h1 id="section-17" class="BEST"></h1></td>
<td><h1 id="section-18" class="BEST"></h1></td>
<td><h1 id="section-19" class="BEST"></h1></td>
<td><h1 id="section-20" class="BEST"></h1></td>
<td><h1 id="section-21" class="BEST"></h1></td>
<td><h1 id="section-22" class="BEST"></h1></td>
<td><h1 id="section-23" class="BEST"></h1></td>
</tr>
<tr class="odd">
<td><h1 id="system-design-and-prototyping" class="BEST">System Design and Prototyping</h1></td>
<td><h1 id="section-24" class="BEST"></h1></td>
<td><h1 id="section-25" class="BEST"></h1></td>
<td><h1 id="section-26" class="BEST"></h1></td>
<td><h1 id="section-27" class="BEST"></h1></td>
<td><h1 id="section-28" class="BEST"></h1></td>
<td><h1 id="section-29" class="BEST"></h1></td>
<td><h1 id="section-30" class="BEST"></h1></td>
<td><h1 id="section-31" class="BEST"></h1></td>
</tr>
<tr class="even">
<td><h1 id="mobile-app-development" class="BEST">mobile App Development</h1></td>
<td><h1 id="section-32" class="BEST"></h1></td>
<td><h1 id="section-33" class="BEST"></h1></td>
<td><h1 id="section-34" class="BEST"></h1></td>
<td><h1 id="section-35" class="BEST"></h1></td>
<td><h1 id="section-36" class="BEST"></h1></td>
<td><h1 id="section-37" class="BEST"></h1></td>
<td><h1 id="section-38" class="BEST"></h1></td>
<td><h1 id="section-39" class="BEST"></h1></td>
</tr>
<tr class="odd">
<td><h1 id="app-testing-and-deployment" class="BEST">app Testing and Deployment</h1></td>
<td><h1 id="section-40" class="BEST"></h1></td>
<td><h1 id="section-41" class="BEST"></h1></td>
<td><h1 id="section-42" class="BEST"></h1></td>
<td><h1 id="section-43" class="BEST"></h1></td>
<td><h1 id="section-44" class="BEST"></h1></td>
<td><h1 id="section-45" class="BEST"></h1></td>
<td><h1 id="section-46" class="BEST"></h1></td>
<td><h1 id="section-47" class="BEST"></h1></td>
</tr>
<tr class="even">
<td><h1 id="project-compilation" class="BEST">Project Compilation</h1></td>
<td><h1 id="section-48" class="BEST"></h1></td>
<td><h1 id="section-49" class="BEST"></h1></td>
<td><h1 id="section-50" class="BEST"></h1></td>
<td><h1 id="section-51" class="BEST"></h1></td>
<td><h1 id="section-52" class="BEST"></h1></td>
<td><h1 id="section-53" class="BEST"></h1></td>
<td><h1 id="section-54" class="BEST"></h1></td>
<td><h1 id="section-55" class="BEST"></h1></td>
</tr>
</tbody>
</table>

# APPENDIX 2: BUDGET

| **Item**                                 | **Cost (Ksh.)** |
|------------------------------------------|-----------------|
| DHT22 Sensors                            | 3,000           |
| ESP32 board                              | 6,000           |
| Breadboard                               | 1,000           |
| Jumper cables                            | 300             |
| Resistor and other electrical components | 200             |
| Printing and Photocopying                | 1,000           |
| Binding                                  | 1,000           |
| Traveling expenses                       | 1,000           |
| Stationery                               | 500             |
| Miscellaneous                            | 1,000           |
| **Total**                                | **15,000**      |

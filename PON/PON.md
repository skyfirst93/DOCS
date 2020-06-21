# What Is a Passive Optical Network
A passive optical network (PON) is a fiber-optic network utilizing a point-to-multipoint topology and optical splitters to deliver data from a single transmission point to multiple user endpoints. Passive, in this context, refers to the unpowered condition of the fiber and splitting/combining components.

In contrast to an active optical network, electrical power is only required at the send and receive points, making a PON inherently efficient from an operation cost standpoint. Passive optical networks are used to simultaneously transmit signals in both the upstream and downstream directions to and from the user endpoints.

## Passive Optical Network Components and Devices
The optical fiber and splitters are the truly “passive” building blocks of the PON, with no electrical powering required. Optical splitters are not wavelength selective and simply divide any optical wavelengths in the downstream direction, of course splitting of an optical signal does incur a power loss which depends on the number of ways a signal is split. Splitters require none of the cooling or other ongoing maintenance inherent to active network components (such as optical amplifiers) and can last for decades if left undisturbed. In addition to the passive components, active end devices are required to fully create the PON network.

The optical line terminal (OLT) is the starting point for the passive optical network. It is connected to a core switch through Ethernet pluggables. The primary function of the OLT is to convert, frame and transmit signals for the PON network and to coordinate the optical network terminal (ONT) multiplexing for the shared upstream transmission. You may also see the end-user devices referred to as optical network unit (ONU), this is simply a difference in terminology between the two main standards bodies, the ITU-T who use ONT and the IEEE who use ONU, the two terms are effectively interchangeable but depend on the PON service and standard being utilized (see below).

The ONT is the powered device of the passive optical network system at the opposite (user) end of the network and includes Ethernet ports for in home device or network connectivity.

## Passive Optical Network Architecture
PON networks adopt a Point-to-multipoint (P2MP) architecture which utilizes optical splitters to divide the downstream signal from a single OLT into multiple downstream paths to the end users, the same splitters combine the multiple upstream paths from the end users back to the OLT.

Point-to-multipoint was selected as the most viable PON architecture for optical access networks with the inherent efficiencies of fiber sharing and low-power consumption. This architecture was standardized in 1998 via the ATM-PON G.983.1 specification.

Today, the ITU-T G.984 standard for G-PON has supplanted the ATM standard, since Asynchronous Transfer Mode (ATM) is no longer utilized.

A PON network starts with the optical line terminal (OLT) at the service provider source location typically known as a Local or Central Office, or sometimes referred to as an exchange or headend. From there, the fiber-optic feeder cable (or feeder fiber) is routed to a passive splitter, along with a backup fiber if one is used. Distribution fibers then connect from the splitter to a drop terminal, which can be located in a street cabinet or in a ruggedized housing mounted in a pit, on a telegraph pole or even on the side of buildings. Drop fibers then provide the final one-to-one connection from drop terminal port to an end user ONT/ONU. In some cases, more than one splitter is used in series, this is referred to as a cascaded splitter architecture.

## PON Architecture

 

The signals carried on the feeder fiber can be split to provide service to as many as 128 users with an ONU or ONT converting the signals and providing users with internet access. The number of ways the downstream OLT signal is divided or split before reaching the end user is known as the splitter or split ratio (e.g 1:32 or 1:64). 

In more complex configurations where RF video is being broadcast in parallel to the PON data service or additional PON services are co-existing on the same PON network, passive (MUX) combiners are used at the central/local office to merge the video overlay wavelength and additional PON service wavelengths onto the outbound OLT feeder fiber.

## Passive Optical Network Operation
An innovation that is integral to PON operation is wave division multiplexing (WDM), used to separate data streams based on the wavelength (color) of the laser light. One wavelength can be used to transmit downstream data while another is used to carry upstream data. These dedicated wavelengths vary depending on the PON standard in use and can be present simultaneously on the same fiber. 

Time division multiple access (TDMA) is another technology used to allocate the upstream bandwidth to each end user for a specific time period, which is managed by the OLT, preventing wavelength/data collisions at the PON splitters or OLT due to multiple ONT/ONU transmitting data upstream at the same time. This is also referred to as burst-mode transmission for the PON upstream. 

## Types of PON Service
Since its introduction in the 1990s, PON technology has continued to evolve and multiple iterations of the PON network topology have taken shape. The original passive optical network standards, APON and BPON, have gradually given way to the bandwidth and overall performance benefits of the newer versions. 

## PON Wavelength Allocation and Coexistence

G-PON
E-PON
10G-E-E-PON
XG(S)PON
NG-PON2
RF Video Overlay
## PON Applications
A PON is sometimes referred to as the “last mile” between the provider and user, or the Fiber to the X (FTTX) with “X” signifying the home (FTTH), building (FTTB), premises (FTTP) or other location, depending on where the optical fiber is terminated. Thus far, fiber-to-the home (FTTH) has been the main application for PON. 

The reduced cabling infrastructure (no active elements) and flexible media transmission attributes of passive optical networks have made it an ideal fit for home internet, voice and video applications. As PON technology has continued to improve, the potential applications have expanded as well.

The rollout of 5G continues, and PON networks have found a new application with 5G fronthaul. The fronthaul is the connection between the baseband controller and the remote radio head at the cell site. 

Due to the bandwidth and latency demands imposed by 5G, utilizing PON networks to complete the fronthaul connections can reduce fiber count and improve efficiency without compromising performance. In much the same way the source signal is split between users for FTTH, signal from the baseband units can be distributed to an array of remote radio heads.

Additional applications that are well suited to passive optical networks include college campuses and business environments. For campus applications, PON networks produce discernable advantages with respect to speed, energy consumption, reliability and access distances but mostly cost of build/deployment and on-going operation. 

PON enables integration of campus functions such as building management, security and parking with reduced dedicated equipment, cabling and management systems. Similarly, medium to large sized business complexes can reap immediate benefits from PON implementation, with the reduced installation and maintenance costs directly impacting the bottom line.

-Reference link : 
https://www.viavisolutions.com/en-us/passive-optical-network-pon#:~:text=Passive%20Optical%20Network%20Architecture,users%20back%20to%20the%20OLT.

# Computer-Networking

A computer network is a system that connects numerous independent computers in order to share information (data) and resources.

## OSI Model (Open systems Interconnection):
OSI model is a set of standards that defines how computers communicate over a network. It has 7 layer and data flow gets broken down into seven layers that build upon each other. Each layer uses data from the layer before it and serves a specific purpose in the broader network communication.

- Physical layer
- Data link layer
- Network layer
- Transport layer
- Session layer
- Presentation layer
- Application layer

### Physical layer
The physical layer is the first and lowest layer: the layer most closely associated with the physical connection between devices. The physical layer provides an electrical, mechanical, and procedural interface to the transmission medium.

### Data link layer
This layer is the protocol layer that transfers data between nodes on a network segment across the physical layer.

### Network layer
The network layer is responsible for packet forwarding including routing through intermediate routers. 

### Transport layer
The protocols of this layer provide end-to-end communication services for applications. It provides services such as connection-oriented communication, reliability, flow control, and multiplexing.

### Session layer
The protocols of the Session layer try to recover any connection losses when they happen. It also optimizes connections: if a connection is not used for a long period, Session-layer protocols may close it and re-open it later. 

### Presentation layer
The presentation layer ensures the information that the application layer of one system sends out is readable by the application layer of another system. Processes such as data encoding, compression, and encryption happen on this layer.

### Application layer
The Application layer displays the data in the correct format to the end-user—you! This includes technologies such as HTTP, DNS, FTP, SSH, and much more.

## TCP/IP Model (Transmission Control Protocol/Internet Protocol):
TCP/IP Model is less complicated as compared to OSI model and it has only 4 layers.

- Physical layer
- Network layer
- Transport layer
- Application layer

## TCP v/s UDP
TCP is a connection-oriented protocol. This means that it first establishes a link between the source and destination before it sends data. Once the connection has been made, then TCP breaks down large data sets into smaller packets, sends them along the connection, and ensures data integrity throughout the entire process. TCP is a preferred protocol when data integrity is critical, such as in any transactional system.

UDP in turn is not connection-oriented. UDP starts transmitting data immediately, without waiting for connection confirmation from the receiving side. Even though some data loss can happen, UDP is most often used in cases where speed is more important than perfect transmission, such as in voice or video streaming.

## Port Number	Process	What it’s used for

22	SSH	Secure shell, remote access, and file transfer
53	DNS	Resolving domain names into IP addresses
80	HTTP	Serving web pages
443	HHTPs	Serving web pages in a secure manner
3306	MySQL	Database connections




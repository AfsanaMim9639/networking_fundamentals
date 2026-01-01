### TCP/IP Model vs OSI Model

| Feature               | TCP/IP Model                     | OSI Model                         |
|----------------------|---------------------------------|----------------------------------|
| Full Form            | Transmission Control Protocol / Internet Protocol | Open Systems Interconnection   |
| Layers               | 4 Layers: Application, Transport, Internet, Network Access | 7 Layers: Application, Presentation, Session, Transport, Network, Data Link, Physical |
| Development          | Developed by **DARPA** for practical networking | Developed as a **theoretical model** by ISO |
| Layer Functionality  | Combines some OSI layers (e.g., OSI’s Application, Presentation, Session → TCP/IP Application) | Each layer has a **specific function** |
| Use                  | Widely used in **real-world networks & Internet** | Used as a **reference model for teaching & understanding** |
| Protocol Examples    | TCP, UDP, IP, HTTP, FTP        | TCP, UDP, IP, HTTP, FTP (same protocols map to layers) |
| Flexibility          | Less rigid, practical approach | Strict, theoretical approach     |


---


### OSI Model (Open Systems Interconnection)

The **OSI Model** is a conceptual framework with **7 layers** that standardizes network communication.

1. **Physical Layer**  
   - Deals with **hardware, cables, signals, and bits**.  
   - Example: Ethernet cables, hubs.

2. **Data Link Layer**  
   - Responsible for **MAC addressing, error detection, and frame delivery**.  
   - Example: Switches, ARP.

3. **Network Layer**  
   - Handles **logical addressing and routing** of data.  
   - Example: IP, routers.

4. **Transport Layer**  
   - Provides **end-to-end communication, error checking, and flow control**.  
   - Example: TCP, UDP.

5. **Session Layer**  
   - Manages **sessions or connections** between applications.  
   - Example: RPC, NetBIOS.

6. **Presentation Layer**  
   - Translates, encrypts, or compresses data for the application.  
   - Example: SSL/TLS, JPEG, MPEG.

7. **Application Layer**  
   - Interfaces **directly with end-user applications**.  
   - Example: HTTP, FTP, SMTP, DNS.

### Encapsulation and De-encapsulation

**Encapsulation:**  
- The process of **adding headers (and sometimes trailers) to data** as it moves **down the network layers** from Application → Physical.  
- Each layer adds its own information (like source/destination addresses, protocol info).  
- Purpose: Ensures data is **delivered correctly** across the network.

**Example:**  
Application data → TCP segment → IP packet → Ethernet frame → Transmitted over network

---

**De-encapsulation:**  
- The reverse process where **headers/trailers are removed** as data moves **up the network layers** at the receiving end.  
- Each layer reads its relevant information and passes the remaining data upward.  
- Purpose: The receiving application can **understand the original data** sent.

**Example:**  
Ethernet frame → IP packet → TCP segment → Application data

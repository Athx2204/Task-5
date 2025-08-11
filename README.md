# Task-5

**Objective:** Capture and Analyze Network Traffic Using Wireshark..

---

## Protocols Identified
1. **HTTP/XML** – Used for transferring web pages and API data.
2. **DNS** – Resolves domain names into IP addresses.
3. **UDP** – Connectionless protocol for fast data transfer.

---

## Sample Packet Details
| Protocol | Source IP     | Destination IP | Source Port | Destination Port | Length | Info |
|----------|--------------|----------------|-------------|------------------|--------|------|
| HTTP/XML | 192.168.0.103 | 192.168.0.1    | *XXXX*      | 80   | 350  | POST /ifc HTTP/1.1 |
| DNS      | 192.168.0.103 | 192.168.0.1    | *YYYY*      | 53   | 87   | Query A inference.location.live.net |
| UDP      | 192.168.0.103 | 188.187.146.78 | 10075       | 62780| 590  | Len=548 |

---

## Screenshots
- **Full Capture:** `screenshots/full_capture.png`

---

## Outcome
- Learned how to capture, filter, and analyze packets in Wireshark.
- Understood how different protocols function in real network communication.
- Documented live network traffic with examples and evidence.

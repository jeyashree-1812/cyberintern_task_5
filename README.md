# Wireshark Packet Capture README

## Steps

1. **Install Wireshark** on your machine from [wireshark.org](https://www.wireshark.org/).
2. **Start capturing** on your active network interface (e.g., Wi-Fi).
3. **Generate traffic** by browsing websites or using `ping` in terminal/command prompt.
4. **Stop capture** after about a minute.
5. **Filter packets** using protocols like `http`, `dns`, or `tcp` in Wireshark's filter bar.
6. **Identify protocols** in the capture (at least 3 different protocols).
7. **Export capture** as `.pcap` file via `File > Save As`.
8. **Summarize findings**:

   * Total packets captured: 74
   * Protocols found: TCP, HTTP, DNS, TLSv1.2
   * Observations: Traffic included web browsing and DNS queries.

## Notes

Use this file as reference to repeat or explain the procedure. Save your `.pcap` file along with this README for records.

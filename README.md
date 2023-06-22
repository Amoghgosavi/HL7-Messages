# HL7-Messages
HL7 messages facilitate the electronic exchange of healthcare data, defining its structure and content for seamless integration between systems. A GitHub repo on HL7 messages offers resources, docs, and code for healthcare software development. Enables interoperability and patient data transmission.

# Code Workflow:
To run these files in sequence, follow the steps below:

1. Start the TCP Listener file: Open the TCP Listener file and run it to initiate the listener. It will start listening for incoming HL7 data.

2. Send HL7 data to the TCP Listener: Use a client or another application to send HL7 data to the TCP Listener's designated port. The TCP Listener will receive and process the incoming data.

3. HL7 to XML Conversion: Once the TCP Listener receives the HL7 data, it will automatically trigger the HL7 to XML Converter file. This file will convert the received HL7 messages into XML format.

4. XML to Normal Form Conversion: After completing the HL7 to XML conversion, run the XML to Normal Form Converter file. It will input the generated XML files and convert them into a normalized representation for further processing.

Note: Please make sure to change the folder locations in the code according to your system. Update the file paths to match the actual locations on your machine. This ensures that the files are accessed correctly during the execution process.

By following these steps and adjusting the folder locations as per your system, you can successfully process HL7 data, convert it to XML, and then transform it into a normalized format.

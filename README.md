# Local Network Scan

Analyze the local network to search for devices with open and remotely accessible services (e.g., IP cameras, routers, etc.).

* Retrieve the local network triplet based on the gateway's IP on the network interface card (by default).
* Scan the entire triplet (0/255) while searching for IPs with port 80 open.
* For each IP found from the previous steps, perform a port scan within the range 0/9999.
* Verify accessibility on HTTP and RTSP ports.
* Recognize TCP service names.

Very fast scanning thanks to multi-threading, able to scan 2,549,745 ports divided among 255 IPs in less than 30 seconds. All within a single Python script or Windows executable file.

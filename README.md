# 2024 Take Your Child to Work Day Network CTF



# Chromebook Setup

1. Install the penguin (Linux) environment on your Chromebook
    1. Press the search (circle) key
    2. Search for the ```Terminal``` app
    3. Open ```Terminal```
    4. If not already setup click on the ```Set up``` button
    5. In the ```Settings``` menu that opens click ```Turn on```
    6. Pick all of the defaults in the wizard (click next until it finishes)

2. Open the Linux terminal environment
    1. Open the ```Terminal``` app
    2. Click on ```penguin```

3. Install wireshark
    ```
    sudo apt install -y wireshark
    ```
4. Download pcap files
    ```
    git clone https://github.com/rampartcommunications/2024tyctwdCTF.git
    ```

# Questions


## 1 - ARP

1. What Ethernet (MAC) addresses are exchanging packets?


2. What IP address is requesting MAC addresses?


3. Did 10.10.8.12 answer, if so what Ethernet (MAC) address is it using?


4. Did 10.10.8.61 answer, if so what Ethernet (MAC) address is it using?


## 2 - ICMP


### 2.1

1. What IP address is sending the PING requests?


2. What IP address is replying?


3. What is the Ethernet (MAC) address for 10.10.8.1?


4. How long does it take for the reply to get back to the sender?


### 2.2

1. What IP address is sending the PING requests?


2. What IP address is replying?


3. What is the Ethernet (MAC) address for the host that's replying?

    - Is this MAC the same or different than the MAC from 2.1 question 3?  What does this tell you?


4. How long does it take for the reply to get back to the sender?

    - Is this longer or shorter than from 2.1?  What does this tell you?


## 3 - DNS

1. What is the IP address for the DNS server we're querying?


2. What protocols are being used in packet 1?


3. What port is the DNS server on?


4. What IP address(es) can you find google.com at?


5. What IP address(es) can you find snapchat.com at?


## 4 - TCP

1. What protocol are being used in packet 5?


2. What port number is the packet coming from in packet 5?


3. What date and time was packet 5 sent?



## 5 - HTTP

### 5.1 - Download

1. What is the IP address for the web (HTTP) client and server?  Do you notice anything odd about them?


2. What port number is the web (HTTP) server using?


3. What is the name of the file being downloaded?


4. What is the name of the person in the picture?


### 5.2 - Upload


1. What is the IP address for the web (HTTP) client and server? 


2. What port number is the web (HTTP) server using?  Is it the same or differet as the one from 4.1?


3. What is the name of the file being uploaded?


4. What is the secret message in the uploaded file?

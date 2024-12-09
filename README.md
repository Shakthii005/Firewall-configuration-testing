# Firewall Configuration and Testing

This project demonstrates firewall configuration and testing using `iptables` on an Kali Linux server. It involves configuring the firewall to secure a web server and testing the setup by simulating attacks from a client machine.

## Technologies Used:
- Kali Linux Server
- `iptables`
- Apache Web Server
- `nmap`, `curl`, `hping3`, `hydra` (testing tools)

## Setup Instructions:
1. Set up a web server (Apache) on the server machine.
2. Apply the `iptables` rules to secure the server.
3. Use `nmap` and `curl` to test connectivity and services.

## Screenshots:
1. iptables_rules:
   
![Screenshot (3)](https://github.com/user-attachments/assets/788b7b94-58f4-4f52-9a87-38abfe0f0856)
![Screenshot (2)](https://github.com/user-attachments/assets/85709dd5-11e2-4735-880e-073d4e0bd0d7)

2.Nmap result

 ![Screenshot (4)](https://github.com/user-attachments/assets/f60707f3-461e-469c-8adb-190da68683b6)

3. ssh connection result:
   
![Screenshot (5)](https://github.com/user-attachments/assets/cc4cd34a-b25a-4cd4-bcce-0c22777b57f0)

4. hping3 result:

![Screenshot (7)](https://github.com/user-attachments/assets/cdd7f0b1-efa1-4606-a0a6-56a02f96b903)

5. curl of server result;

![Screenshot (8)](https://github.com/user-attachments/assets/eda1b935-62f6-454a-97f2-ca5e936ffd6d)



## License:
This project is open-source and available under the MIT License.

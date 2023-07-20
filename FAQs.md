## Frequently Asked Question

**What is the solution architecture?**

In our system, all DVRs, NVRs, and IP cameras belonging to clients will establish a secure VPN tunnel to our servers. The recorded footage will be stored in Google Cloud Storage, ensuring reliable and scalable storage capabilities. To access the footage and utilize various services, client users will interact with our web application. They will have the ability to perform tasks such as live streaming, playback, and leverage additional functionalities provided by our application.

![Technical Architecture](tech_arch.png)

**How secure is the data stored in the cloud?**

We use Google Cloud Platform (GCP) as our cloud infrastructure. GCP has implemented numerous security measures to ensure the protection of data stored on their platform.
Here are some key security features and practices that Google Cloud Platform typically employs:
- Physical Security: Google maintains highly secure data centers with multiple layers of physical security controls, including strict access controls, video monitoring, and 24/7 security personnel.
- Data Encryption: Google encrypts data at rest by default using industry-standard AES-256 encryption.
- Network Security: GCP utilizes Google's private global fiber network, which is designed to keep customer data safe from unauthorized access. They employ robust network security measures, such as distributed denial-of-service (DDoS) protection, firewall policies, and Virtual Private Cloud (VPC) for isolating and securing resources.
- Security Audits and Compliance: Google Cloud undergoes regular independent third-party audits to validate its security controls and compliance with industry standards and regulations. They also offer various compliance certifications, such as ISO 27001, SOC 2, and HIPAA, which may be relevant depending on your specific requirements.
- Incident Response and Monitoring: Google employs advanced monitoring and detection systems to identify and respond to potential security threats in real-time. They have dedicated security teams that work to mitigate and respond to security incidents promptly.

**What measures are in place to protect the privacy of our surveillance footage?**

The privacy of your surveillance footage is of utmost importance to us, and we have implemented robust measures to ensure its protection within our cloud infrastructure. Access to the footage is strictly controlled and requires user credentials for login. By providing secure user authentication, we ensure that only authorized individuals can access the surveillance footage through our web application. This helps safeguard the privacy and confidentiality of the data, ensuring that it remains accessible only to those with proper authorization. Rest assured that we prioritize privacy as a fundamental aspect of our solution and take appropriate steps to protect the sensitive nature of surveillance footage.

**Are there any encryption protocols in place for data transmission?**

To ensure secure data transmission between client endpoints and our cloud infrastructure, we employ a highly reliable VPN tunnel. This tunnel incorporates top-tier encryption protocols, prioritizing simplicity, performance, and strong cryptography. Notably, it utilizes Curve25519 to establish a secure session key, ChaCha20 with Poly1305 for data encryption and message authentication, and Blake2s hash function for key derivation, integrity checks, and packet authentication. By leveraging these encryption protocols, we ensure the confidentiality and integrity of data transmitted within the VPN tunnel, providing efficient and secure communication with minimal overhead.

**How scalable is the solution? Can it handle a large number of cameras and devices?**

The solution we have developed on the Google Cloud Platform is highly scalable, allowing us to handle a virtually unlimited number of cameras or devices. With our robust infrastructure and architecture, scalability is not a concern. This scalability capability empowers us to meet the needs of any size deployment, making our solution flexible and adaptable to various requirements.

**What is the system's performance like during peak usage times?**

During peak usage times, our systems exhibit exceptional performance and responsiveness. Our software is meticulously crafted using cutting-edge tools that are tailored to their specific purpose, allowing us to achieve optimal performance levels. We have dedicated significant effort to fine-tuning our systems to ensure they can seamlessly handle high loads and efficiently process requests, even during periods of intense usage. As a result, you can expect our system to consistently deliver a smooth and reliable experience, regardless of the volume of users or demands placed upon it.

**Are there any limitations in terms of bandwidth or storage capacity?**

Since our solution is built on the robust foundation of the GCP, clients can enjoy the benefits of virtually unlimited bandwidth and storage capacity. We leverage the scalable infrastructure provided by Google, allowing us to seamlessly accommodate clients requirements without encountering any limitations in terms of bandwidth or storage. Whether clients need to handle large amounts of data or support high-volume traffic, our solution is designed to scale effortlessly, ensuring that your operations run smoothly and efficiently. Rest assured that with our system, you have the flexibility and capacity to meet your growing needs without any concerns about bandwidth or storage limitations.

**Can the solution integrate with existing surveillance systems or hardware?**

Yes! Our solution is designed to seamlessly integrate with existing surveillance systems or hardware that have network capabilities. This means that you can leverage our solution without the need for extensive hardware upgrades or replacements. Whether you have IP cameras, video recorders (NVRs / DVRs), or other compatible surveillance devices, our solution can efficiently work with them to enhance your overall surveillance capabilities. By leveraging the network connectivity of your existing devices, we can provide a seamless integration experience, ensuring that you can easily incorporate our solution into your current surveillance infrastructure.

**What protocols or standards does the solution support for seamless integration?**

For seamless integration, our solution supports the widely adopted ONVIF protocols. These protocols enable smooth communication and interoperability between our solution and a variety of surveillance devices. By leveraging ONVIF support, you can easily connect your compatible cameras, video recorders, and other surveillance hardware to our solution without compatibility issues.
By incorporating these protocols and standards into our solution, we ensure that your existing surveillance infrastructure can seamlessly integrate with our system, enabling you to maximize the benefits of our solution without disruptions or limitations.

**Are there any specific requirements for the devices or cameras that can be connected to the system?**

To connect devices or cameras to our system, the primary requirement is that they support the ONVIF protocol. This ensures compatibility and smooth integration with our solution. Additionally, as we utilize VPN tunnels for data transfer, it is beneficial to use VPN-enabled routers for seamless connectivity. In particular, **Mikrotik Routers** are an excellent choice for this purpose.
By meeting these requirements, clients devices and cameras can easily integrate with our system, enabling you to leverage the full capabilities and benefits of our solution.

**How long is the surveillance footage retained in the cloud?**

The retention period for surveillance footage in the cloud is entirely customizable based on the specific requirements of our clients. We offer flexible plans that allow clients to choose the duration for which they want to retain their footage. While we provide options ranging from short-term to long-term retention, it is worth noting that our most popular plans include a three-month retention period. However, we also offer more cost-effective options with a minimum retention period of one year. Ultimately, the choice of retention duration is in the hands of the client, ensuring that it aligns with their individual needs and preferences.
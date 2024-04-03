<h1 align="center">AWS-Ethical Hacking Lab.</h1>

As part of my learning experience at TKH, we Have to working-team where participants can simulate real-world scenarios, fostering collaboration and problem-solving skills. The lab provides an opportunity to work with AWS's native security services, such as AWS Identity and Access Management (IAM), AWS Shield, and AWS WAF (Web Application Firewall). Our team aspires to create a website that showcases our home lab and documents our process of establishing it in the cloud.  

![Screenshot 2024-03-29 011858](https://github.com/luzritacco/AWS-Ethical-Hacking-lab/assets/151267325/021b676d-0d8a-4271-9e92-b270465503a7)


###
<h1 align="center">AWS Ethical Lab Components.</h1>



- AWS account
- Amazon Virtual Private Cloud (Amazon VPC)
- EC2 (Elastic Compute Cloud)
- Networking components like NAT gateways, internet gateways, route tables, security groups and users.
- Amazon Guard Duty
- Amazon CloudWatch 
 ##

 - **Project Visual workflow :**
   ![Screenshot 2024-03-25 005908](https://github.com/Quatecha/Phase-2-Final-Project_TKH-/assets/151267325/3b423c17-46ea-41ac-bee3-f5f5534003dc)
##


**Click here to have a visual workflow by stages**
  
- https://1drv.ms/w/s!ALrXxP7mFzWXjwg?e=IsZIoG
 ##
 <h1 align="center"> Our AWS Home Lab.</h1>

   Setting up a bastion host can indeed be challenging, especially when it comes to ensuring secure access to EC2 instances within a private subnet. It's crucial to have the correct configurations in place, as the bastion host acts as a gateway to your private resources, enforcing strict access control and monitoring. When creating a new VPC, it's important to carefully plan the architecture, considering how the public and private subnets will interact, and how security measures like NACLs and security groups will be implemented.

  We were trying to set up a bastion host in our first public subnet so that we could allow internet traffic to ourEC2 instances on our private subnet. We ran into issues with the configurations of our bastion host which forced us to have to create an entirely new environment with a new VPC. On this VPC, we create one private and one public subnet and instead of using a bastion host we will have out attack machine on the public subnet and our target machine on our private subnet.
For our team, encountering this issues that demand significant time to resolve can be frustrating, especially when it impacts the project timeline and workflow. The situation becomes even more challenging when there's a need to start from scratch or seek external assistance.


 However, these moments of frustration can also be transformed into opportunities for growth and learning. Troubleshooting can foster a deeper understanding of the system, enhance problem-solving skills, and strengthen team collaboration. When a team faces a complex issue, it's an invitation to come together, pool knowledge, and find innovative solutions.

##
 <h1 align="center">  Issues and learning Experience on this process.</h1>

Creating an ethical hacking lab in Amazon Web Services (AWS) can be both exciting and challenging. Here are some experiences and insights that our team encounter during the process.


|    Challenge | Learning Experience |
| ------------- | ------------- |
 -Setting Up the Lab Environment- Configuring the lab environment correctly can be tricky. we’ll need to create instances, set up networking, and ensure proper security.  | ☑Take our time to follow step-by-step or instructions. Double-check configurations to avoid mistakes.|
| - Selecting the appropriate EC2 instance types for your lab can be overwhelming. Different use cases require different resources. | ☑ Understand your lab’s requirements and choose instances accordingly.|
|-Properly configuring security groups and network settings is crucial. Misconfigurations can lead to   connectivity issues or security vulnerabilities. |☑Test connectivity thoroughly to ensure proper communication between instances. Refer to AWS documentation and best practices. |
|-Managing access control using key pairs can be confusing, especially if you’re new to AWS |☑Create and securely store your key pairs. Understand how SSH or RDP connections work with these keys.|
|-Setting up Kali Linux correctly is essential for ethical hacking. Installing tools, updating repositories, and configuring network interfaces can be complex.|☑Take the time to follow step-by-step instructions. Double-check configurations to avoid mistakes.|
|-Keeping track of your findings, vulnerabilities, and successful exploits is crucial.|☑Use tools like Keep Note or a simple text file to document your progress. Include details, screenshots, and steps taken.|


##
<h1 align="center">Conclusion</h1>

 Implementing a cybersecurity lab within a collaborative team on AWS is a strategic move towards developing a deeper understanding of cybersecurity measures. AWS provides a practical platform for teams to learn, experiment, and prepare for real-world cyber threats, ensuring that their home lab is a fortress against digital adversaries. AWS tools and services offer the necessary resources to build a sophisticated and secure cybersecurity lab for us as a professional in cybersecurity who wants to keep learning and improving our professional skills. Whether you are a beginner or an experienced professional.

##

 **Click here to have more details**

- **Project Notes:**
     - https://1drv.ms/w/s!ArrXxP7mFzWXjmzPPn-VSxdU43di?e=JYUBsc
  
- **Lab Report-Layout:**
     - https://docs.google.com/document/d/13MJtSPFCy_h2RG4m-nulJuCKO9qzSU3AWsC5mxF-_WE/edit?usp=sharing
- **Presentation:**
    - https://docs.google.com/presentation/d/1hJu1IpRhxcFIrRHTQg8eLtWdwxg3pfIRpGqj-mm8ayU/edit?usp=sharing
    - https://docs.google.com/presentation/d/1tf_wxw4TL_7j4R_qoHTwvqy17t22BdTtfls81D6gIlQ/edit?usp=sharing
- **Final Paper**

   - [ -https://1drv.ms/w/s!ArrXxP7mFzWXjn6V8wK0WUPe1hjd?e=ohAu67 ](https://1drv.ms/w/s!ArrXxP7mFzWXjn6V8wK0WUPe1hjd?e=ohAu67)
 - **Detail Paper**
   -  https://docs.google.com/document/d/1EA_dVf7KVaGYp0jS5BvDBONYGzRPB0P7iALVcPyaqY0/edit
   -  https://docs.google.com/document/d/13sIidHHO997VYtuUIkW6jyv7qrFU4bDyQ34OFRcVJSc/edit

#### Here's a link for the group repository:
- https://github.com/Quatecha/Phase-2-Final-Project_TKH-/blob/main/README.md

##

> _**Team-2 Members: D'andre W,  Jose R, Luz R, Luis V, Quatecha C, Margaret E, Mathew E.**_
 

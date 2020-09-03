# **About This Lab**

This lab walks end users through the process of configuring Venafi Trust Protection Platform and F5's BIG-IP and BIG-IQ devices to completely automate machine identities in use throughout an organization's F5 infrastructure.

### **Background**

Issuing a machine identity today, in many organizations, can take DAYS and is often a very manual process involving change requests, tickets and lots of hands on keyboards. Naturally, that can create bottlenecks for security or PKI teams that are typically dealing with multiple product and/or application developer teams. Manual processes are also prone to human error that could otherwise be avoided by introducing some form of automation. These problems are exacerbated when organizations are using DevOps practices.

Application teams are used to speed and automation, and for good reason. They adopt tools like BIG-IQ and BIG-IP to help them deliver, secure and monitor business applications. Introducing Venafi allows administrators to get the machine identities they need to secure their applications as quickly as possible. Security teams get the visibility to see ALL the machine identities throughout the organization, and the capability to enforce standard policy over the machine identities that application teams are requesting. Application teams get to use a simple process inside their native tools. It's a win-win.

### **BIG-IP vs. BIG-IQ - Which should you choose?**

At this point, you're probably wondering which integration makes sense for your organization. Both achieve better control and visibility of machine identities used withn F5 infrastructures, but there are a few differences to be aware of. Perhaps the number one question to ask yourself is "Which team needs to be in control of machine identities for the F5 infrastructre?"

**If the answer to that question is the F5 team**, then the best option is going to be BIG-IQ, because it allows F5 administrators to renew, revoke, and obtain new machine identities directly from the BIG-IQ interface, while still providing the visibility and policy controls to the security or PKI team. F5 administrators can see available Policy folders from Venafi and choose the corresponding container that makes sense for their specific application.

**If the answer is the Security or PKI team**, then the BIG-IP integration is able to provide that control without adding any additional burdens to the F5 admins. Tasks related to the machine identity lifecycle are all initiated automatically from Venafi. This means that Venafi Trust Protection Platform will recognize that a certificate is coming up for expiration. It will reach out to the corresponding Certificate Authority and renew the certificate. And finally, it will push the renewed certificate to the BIG-IP device and associate it with the correct profile...all without human interaction.

### **Accessing the Lab Environment**

You should have received lab access directly from the CloudShare platform. The lab environment will be valid for two weeks and will automatically be shut down after that time. If you require additional lab time, please reach out to paul.cleary@venafi.com.

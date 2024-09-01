---
title: How Microsoft's Zero Trust Data System (ZTDS) Enhances Windows Cybersecurity
date: 2024-08-27 21:41:11
updated: 2024-08-29 12:22:30
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/windows-11-logo.jpg
---

## How Microsoft's Zero Trust Data System (ZTDS) Enhances Windows Cybersecurity

DNS is one of the biggest weak points in our devices' networking. It's often used without encryption, which is a problem when DNS is responsible for convering web addresses into the required server IP addresses. Microsoft is now planning some changes to Windows that could make DNS more secure and less vulnerable to tampering.

 Microsoft has revealed a comprehensive new security system, called Zero Trust DNS (ZTDNS for short), aimed at significantly bolstering the security of the Domain Name System (DNS) within Windows networks. [DNS](https://instagram-clips.techidaily.com/new-2024-approved-revealing-the-top-10-hidden-story-supporters/), essential for translating human-friendly website names into numerical IP addresses, has long been plagued by security risks. ZTDNS promises to resolve this by providing encrypted and authenticated communication channels between client devices and DNS servers, while also empowering administrators to tightly control which domains those servers can resolve.

 Historically, enhancing DNS security has often meant sacrificing administrative visibility into network traffic. This forces admins to choose between unencrypted DNS with monitoring capability but lacking protection, or encrypted DNS that blinds monitoring and control. Microsoft's ZTDNS integrates the Windows DNS engine and Windows Firewall directly into client devices to overcome this problem.

 The ZTDNS system blocks client devices from connecting to any IP address except for those of designated "protective DNS servers." When a client device needs to resolve a domain name, it communicates with a protective DNS server, which can optionally use client certificates for fine-grained policy control. Upon resolution, ZTDNS dynamically updates the Windows Firewall to allow connections to the newly resolved IP addresses, while blocking all other traffic by default. This creates a powerful domain-name-based lockdown tool.

 You can think of this as a series of processes where the ultimate result is that you can only visit websites that have been specifically approved, creating a super-secure environment. This differs from regular DNS resolving in a few ways—namely, the way your DNS is currently set up means that it can resolve any URL into an IP address, even if it's known to be malicious (with possible consequences ranging from malware downloading to even a potential entry point for a malicious actor).

 There are also potential concerns about what might happen when this technology is actually deployed. Although it's a promising thing for your online safety, it will also probably require careful planning and configuration by administrators to avoid accidental disruption of normal network functions. After all, DNS is a core feature needed for Internet access, and the new system could overreach and block actually non-harmful things that you might need to use. The good thing is that this won't be rolled out just yet, so there's still a bit of time to figure out how to properly set up things so that your Internet experience won't be accidentally broken or disrupted in the process.

 ZTDNS requires that DNS servers support encryption protocols like DNS over HTTPS (DoH) or DNS over TLS (DoT). Microsoft highlights that ZTDNS does not introduce any new network protocols, which helps in making it broadly compatible. ZTDNS is currently in "private preview," according to Microsoft—it's not immediately clear if it's only being internally tested by the company at the moment or whether a few select users are/will be getting access to it. Microsoft has not given any indication of when ZTDNS might become publicly available, and for now, the company has just said that Windows Insiders will get access to it at their own time, with a separate announcement planned when the time comes.

 For now, if you want to read more about ZTDNS and what to take into account when the time for a real-life deployment comes, you can [check out Microsoft's blog post](https://techcommunity.microsoft.com/t5/networking-blog/deployment-considerations-for-windows-ztdns-client/ba-p/4113372) with all the details.

 Source: [Microsoft](https://techcommunity.microsoft.com/t5/networking-blog/announcing-zero-trust-dns-private-preview/ba-p/4110366) via [Ars Technica](https://arstechnica.com/security/2024/05/microsoft-plans-to-lock-down-windows-dns-like-never-before-heres-how/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

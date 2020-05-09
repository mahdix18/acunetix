### Introduction to Acunetix
#### Why You Need To Secure Your Web Applications
Website security is today's most overlooked aspect of securing an enterprise and should be a priority in any organization. Increasingly, hackers are concentrating their efforts on web-based applications – shopping carts, forms, login pages, dynamic content, etc. Accessible 24/7 from anywhere in the world, insecure web applications provide easy access to backend corporate databases and also allow hackers to perform illegal activities using the attacked sites. A victim’s website can be used to launch criminal activities such as hosting phishing sites or to transfer illicit content, while abusing the website’s bandwidth and making its owner liable for these unlawful acts.


Hackers already have a wide repertoire of attacks that they regularly launch against organizations including SQL Injection, Cross Site Scripting, Directory Traversal Attacks, Parameter Manipulation (e.g., URL, Cookie, HTTP headers, web forms), Authentication Attacks, Directory Enumeration and other exploits.

The hacking community is also very close-knit; newly discovered web application intrusions, known as Zero Day exploits, are posted on a number of forums and websites known only to members of that exclusive underground group. Postings are updated daily and are used to propagate and facilitate further hacking.


Web applications – shopping carts, forms, login pages, dynamic content, and other bespoke applications – are designed to allow your website visitors to retrieve and submit dynamic content including varying levels of personal and sensitive data.

If these web applications are not secure, then your entire database of sensitive information is at serious risk.  A Gartner Group study reveals that 75% of cyber-attacks are done at the web application level.


### Why are web applications vulnerable?

Websites and web applications are easily available via the internet 24 hours a day, 7 days a week to customers, employees, suppliers and therefore also hackers.
Firewalls and SSL provide no protection against web application hacking, simply because access to the website has to be made public.
Web applications often have direct access to backend data such as customer databases.
Most web applications are custom-made and, therefore, involve a lesser degree of testing than off-the-shelf software.  Consequently, custom applications are more susceptible to attack.
Various high-profile hacking attacks have proven that web application security remains the most critical.  If your web applications are compromised, hackers will have complete access to your backend data even though your firewall is configured correctly and your operating system and applications are patched repeatedly.
Network security defense provides no protection against web application attacks since these are launched on port 80 which has to remain open to allow regular operation of the business. It is therefore imperative that you regularly and consistently audit your web applications for exploitable vulnerabilities.
The need for automated web application security scanning
Manual vulnerability auditing of all your web applications is complex and time-consuming, since it generally involves processing a large volume of data. It also demands a high level of expertise and the ability to keep track of considerable volumes of code used in a web application. In addition, hackers are constantly finding new ways to exploit your web application, which means that you would have to constantly monitor the security communities, and find new vulnerabilities in your web application code before hackers discover them.


Automated vulnerability scanning allows you to focus on the already challenging task of building a web application. An automated web application scanner is always on the lookout for new attack paths that hackers can use to access your web application or the data behind it.

Within minutes, an automated web application scanner can scan your web application, identify all the files accessible from the internet and simulate hacker activity in order to identify vulnerable components.


In addition, an automated vulnerability scanner can also be used to assess the code which makes up a web application, allowing it to identify potential vulnerabilities which might not be obvious from the internet, but still exist in the web application, and can thus still be exploited.

### Acunetix Vulnerability Management
Acunetix is an automated web application security testing tool that audits your web applications by checking for vulnerabilities like SQL Injection, Cross site scripting and other exploitable vulnerabilities. In general, Acunetix scans any website or web application that is accessible via a web browser and uses the HTTP/HTTPS protocol.


Acunetix offers a strong and unique solution for analyzing off-the-shelf and custom web applications including those utilizing JavaScript, AJAX and Web 2.0 web applications. Acunetix has an advanced crawler that can find almost any file. This is important since what is not found cannot be checked.

### Install Docker For Acunetix
Run: 

```docker build .```

hub and docker: https://hub.docker.com/r/vouu/acu

Run `dokcer run -it -d -p 443:3443 vouu/acu`

Login Info

```
login: https://localhost

Email: contact@manhtuong.net

Password: Abcd1234
```
Limit Upload:
edit file: /home/acunetix/.acunetix/data/general/settings.xml

```
                <ContentTypeSettings>
                        <ContentType Kind="text/*" Fetch="1" Parser=""></ContentType>
                        <ContentType Kind="application/json" Fetch="1" Parser="JSON"></ContentType>
                        <ContentType Kind="application/vnd.msword" Fetch="1" Parser=""></ContentType>
                        <ContentType Kind="application/msword" Fetch="1" Parser=""></ContentType>
                        <ContentType Kind="application/vnd.ms-excel" Fetch="1" Parser=""></ContentType>
                        <ContentType Kind="application/ms-excel" Fetch="1" Parser=""></ContentType>
                        <ContentType Kind="application/vnd.sun.wadl+xml" Fetch="1" Parser=""></ContentType>
                        <ContentType Kind="text/html" Fetch="1" Parser="HTML"></ContentType>
                        <ContentType Kind="text/xhtml" Fetch="1" Parser="HTML"></ContentType>
                        <ContentType Kind="text/vnd.wap.wml" Fetch="1" Parser="HTML"></ContentType>
                        <ContentType Kind="application/xhtml+xml" Fetch="1" Parser="HTML"></ContentType>
                        <ContentType Kind="application/x-shockwave-flash" Fetch="1" Parser="Flash"></ContentType>
                        <ContentType Kind="application/x-javascript" Fetch="1" Parser="JS"></ContentType>
                        <ContentType Kind="javascript/x-javascript" Fetch="1" Parser="JS"></ContentType>
                        <ContentType Kind="application/javascript" Fetch="1" Parser="JS"></ContentType>
                        <ContentType Kind="text/css" Fetch="1" Parser="CSS"></ContentType>
                        <ContentType Kind="text/xml" Fetch="1" Parser="RSS"></ContentType>
                        <ContentType Kind="application/xml" Fetch="1" Parser="XML"></ContentType>
                        <ContentType Kind="application/atom+xml" Fetch="1" Parser="XML"></ContentType>
                        <ContentType Kind="application/rss+xml" Fetch="1" Parser="RSS"></ContentType>
                        <ContentType Kind="application/rdf+xml" Fetch="1" Parser="RSS"></ContentType>
                        <ContentType Kind="application/soap+xml" Fetch="1" Parser="XML"></ContentType>
                </ContentTypeSettings>

```

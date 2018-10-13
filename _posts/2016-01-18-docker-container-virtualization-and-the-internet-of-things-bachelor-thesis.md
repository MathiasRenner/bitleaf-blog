---
ID: 1718
post_title: >
  Docker/Container Virtualization and the
  Internet of Things (Bachelor thesis)
author: Mathias Renner
post_excerpt: >
  Today, I publish my Bachelor thesis that
  examined if and how Container
  Virtualization can be useful for the
  IoT.
layout: post
permalink: >
  https://bitleaf.de/2016/01/18/docker-container-virtualization-and-the-internet-of-things-bachelor-thesis/
published: true
post_date: 2016-01-18 12:46:53
---
<!-- wp:paragraph -->
<p>Today, I publish my Bachelor thesis that examined if and how Container Virtualization can be useful for the IoT.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>In
 this post I will paste the first and last chapter – introduction and 
summary – which give a good overview about the details to expect in 
between.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>You find the PDF including footnotes and references <a href="http://mathias-renner.de/thesis.pdf" rel="noreferrer noopener" target="_blank">here</a>.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 id="88d8">Indroduction: New Challenges in the Internet of Things</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In
 2015, the Internet of Things (IoT) received much attention. While the 
term roots back to 1991 (presented in section 2.1) IoT has become one of
 the most often discussed and most promising topics in the IT industry. 
For instance, Gartner — a major IT research firm specialized on market 
analysis — put IoT on the peak position of 37 emerging computing 
technologies in a recently published report. Some say that the IoT is 
the next industrial<br/>revolution.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The
 concept of IoT denotes an infrastructure that allows many devices to 
communicate with one another. Moreover, the IoT focuses on transforming 
tiny devices into computing objects, which are then called IoT devices. 
Doing so, a tooth brush, a coffee machine, or air quality sensors in 
commercial buildings provide capabilities to retrieve and distribute 
information. As a result, information technology becomes pervasive: both
 in private life and in enterprises.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The
 number of IoT devices is already high. Several companies and research 
institutions have published numbers on present and forecasted future use
 of IoT devices. One recent study published in July of 2015 estimated 
the number of connected devices at 13.4 billion, which is nearly twice 
the entire human population. Despite differing forecasts, the estimated 
number of devices in 2020 ranges from 26 to 200 billion, greatly 
exceeding present day numbers. <br/>These 200 billion devices divided by 
every of the 7 billion humans on earth is equal to around 28 devices per
 person. Assuming a majority of the people able to buy such devices live
 in developed countries, the average number of devices in developed 
countries is expected to be much higher.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Despite
 the popularity of IoT, critics have emerged and spoken against IoT. Its
 ubiquity in private life offers the opportunity to gather more data 
about people’s lives than is already done today. Across enterprises 
harvesting such data, security leaks are expected to arise more often. 
The IoT’s pervasiveness in an enterprise might simplify industrial 
espionage, due to the plethora of information retrieved by IoT devices. 
Thus, it is required to emphasize solutions that are capable of 
minimizing the risk this incurs.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>An
 IoT infrastructure requires a different design than today’s Internet 
infrastructure. The central issue is related to security: How can we 
isolate software on an IoT device from its environment in order to 
restrict its access to information it should not handle? Furthermore, 
how can devices be updated in a secure way? Applications frequently need
 security updates in order to fix loopholes and software issues. This is
 especially important to IoT applications on devices that are 
permanently connected to the Internet. The process of updating an 
application sometimes requires the user to completely reinstall the 
application. The question arises: how can applications be installed and 
updated in a secure way? Maintaining a fleet of IoT devices needs to be 
done automatically to gain a high level of efficiency. How can this be 
achieved? Next, how can we deal with configurations that are initialized
 when an application is deployed? How can applications be securely 
reconfigured? Finally, an important issue is limited availability of 
resources of IoT devices because many of them are equipped with little 
computing capabilities. Thus, solutions need to be applicable for these 
resource-poor devices as well.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Potential
 solutions need to address IoT’s architecture by design instead of a 
feature built on top. Doing so will further minimize risks because 
problems are already addressed in the IoT’s core functions. For 
instance, a core function could be the isolation of any application 
running on IoT devices. This limits the application to accessing only 
the information it is told to deal with. By isolating an application 
running on an IoT device, it cannot cause further problems due to its 
isolated environment and access restrictions.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>This
 work focuses on the design of application deployment in an IoT 
infrastructure in order to offer solutions to solve the aforementioned 
issues. Potential solutions will be evaluated. The objective is to 
identify an optimal way to distribute, deploy and integrate applications
 into IoT’s infrastructure. Thereby, any evaluation will be performed 
against requirements of the IoT in order to retain results that make 
this work useful in practice.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The
 research evaluates container technology as a promising solution for the
 deployment of IoT applications. Container technology offers multiple 
features that address the presented challenges, including: isolation of 
applications from their surrounding area, resource restrictions against 
applications, and a standardized method to package, distribute, and 
deploy applications onto devices.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 id="6cbd">Procedure Model and Structure of this Thesis</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>The
 objective of this thesis is to identify challenges induced by the IoT 
that are different from contemporary, common IT infrastructures. Based 
on these results, container technology as a potential solution is 
evaluated, which can deal with the majority of new challenges. The 
proposed solution will be implemented in a test environment.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The
 procedure model this work follows can be described as a stepwise 
identification, evaluation, and implementation. First, basic concepts of
 the IoT will be presented to describe common terminology to the reader.
 Next, central requirements in an IoT infrastructure will be identified,
 including those for hardware and software. Also, a concept to reach a 
high level of standardization will be established, which together with 
container technology will simplify deployment of any application on 
almost any IoT device that can run container technology. In subsequent 
chapters, different container technologies will be compared in order to 
select one that is most suitable for an IoT infrastructure.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>In
 the final chapter, the results of all preceding chapters will be used 
to build an IoT infrastructure in a test environment using container 
technology.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 id="79ee">Main Part</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>To read the main part of the thesis, <a href="http://mathias-renner.de/thesis.pdf" rel="noreferrer noopener" target="_blank">download the PDF.</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3 id="05f6">Summary and Outlook</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>The
 objective of this thesis was to evaluate, whether Linux container 
technology (LCT) satisfies challenges and requirements set in place by 
IoT’s infrastructure. Therefore, IoT’s requirements were discussed in 
order to form the basis for subsequent evaluations and tests. Extensive 
comparisons were conducted to identify concepts with potential benefits 
from the use of LCT over the classical Full Virtualization (FV). Upon 
finding extraordinary advantages of concepts used by LCT compared to FV,
 the most appropriate implementation of LCT was identified. Comparing 15
 solutions demonstrated that only four solutions meet IoT’s 
requirements: LXC, LXD, Docker and rkt. Subsequently, detailed 
comparisons suggested that even if LXC and LXD were considered as LCT 
solutions, they do not offer reasonable advantages for use in the IoT. 
While Docker technology is currently the only solution that meet IoT’s 
requirements, rkt is anticipated to do so in the near future. Between 
Docker and rkt, rkt exhibited better security and higher levels of 
standardization than Docker. However, because Docker was production 
ready, it was selected for practical evaluation in a test environment 
similar to that of an IoT infrastructure.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The
 test results have indicated that Docker meets central IoT requirements 
through a rich set of features. Through such features (detailed in the 
preceding sections) it is capable of handling all major challenges of 
the IoT including high levels of automation and manageability, support 
for a wide range of hardware and software platforms, and the ability to 
maintain safety of multiple IoT devices.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Even
 though there is still potential for improvements. Docker’s developers 
have not recognized its potential as middleware for the IoT, which has 
been identified in this work. Docker is encouraged to publish the latest
 version of the precompiled binary for ARM rather than having users 
download it from other websites.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Furthermore,
 Docker needs to extend its security features. Presently, the defaults 
do not support digital signing or container encryption, nor does it 
fully implement user namespaces. The last of which is a Linux OS feature
 that is required to harden Docker onto a similar level of that of VMs.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Apart
 from security topics in LCT, software defined networking (SDN) has been
 presented as a technology with tremendous potential to secure IoT 
networks. Open vSwitch (OVS) is a high performance SDN software proven 
to successfully separate network traffic using tunnels. In addition, OVS
 provides a level of flexibility for configuring networks that surpasses
 capabilities offered by those of classical managed switches. Despite 
these positive results, enabled encryption does not offer reasonable 
network performance. This could only be achieved with hardware support 
in the form of an encryption accelerator. Because network performance 
and levels of security are particularly important in the IoT, more 
research should be conducted in this field.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>New
 network topologies are expected to evolve that extend today’s concepts 
of cloud computing. Cloud computing 2 is necessary for processing data 
gathered in IoT networks. Cloud computing instances are part of the 
wider communication network and are often far away from local IoT 
networks due to high levels of centralization. Therefore the bandwidth 
between an IoT network and the cloud is not sufficient of delaying 
sensitive services, such as health care. The new concept of Fog 
Computing addresses low bandwidth by colocating cloud computing clusters
 next to the IoT networks from which they receive data. Interest in Fog 
Computing is expected to rise proportionally with that for IoT. 
Therefore, further research is expected in the near future.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>As
 shown in section 1.1, the IoT receives much attention from major 
companies and research institutions worldwide, not only in the field of 
IT. Some even speak of a fourth industrial revolution to follow, after 
innovations such as the steam engine, mass production, and the World 
Wide Web. All of these preceding revolutions changed fundamental 
paradigms in the societies’ infrastructure, which hold for IoT as well. 
Furthermore, the IoT changes information infrastructures, allowing 
today’s information society to apply it at a much faster rate than 
preceding revolutions. Because each human being is expected to own 
dozens of IoT devices in the near future, new physical infrastructures 
are also required to provide energy for all these devices. Communication
 networks that ensure Internet connectivity for each device — regardless
 of location — will also induce an extraordinary expansion of 
communication infrastructures compared to those found today.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>In
 summary, the IoT has the potential to provide tremendous transformation
 for many industries. Because the IoT is agnostic to its application 
domains, any industry may make use of and benefit from a communication 
based infrastructure of it. The IoT is like the network of public roads:
 although everyone can use the network — the individual can specify the 
make and model of vehicle they choose to drive and utilize within the 
infrastructure. A wide range of industries, including that of 
automobiles, health care, and energy have already started to take part 
in this revolution. At the least, we can conclude without doubt, that in
 the long run, IoT influences everyone’s life in some way or another.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The
 present influences on the IoT are just the beginning. Technology, which
 powers IoT infrastructures still has much potential for improvements as
 identified in this work. A potential solution has been identified in 
this thesis: Linux container technology addresses all major challenges 
in the IoT and is therefore proposed as the optimal middleware 
technology as we move into the future.</p>
<!-- /wp:paragraph -->
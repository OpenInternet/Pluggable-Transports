---
layout: single
title: "Measuring Censorship"
permalink: /measuring/

excerpt: ""
header:
  overlay_image: /assets/images/max-vertsanov-683738-unsplash.jpg
  caption: "Photo credit: [**CC0 Unsplash / Max Vertsanov**](https://unsplash.com/@make_it)"
#  cta_label: "More Info"
#  cta_url: "https://unsplash.com"

sidebar:
    nav: "aboutnav"
---

Censorship of Internet content is increasing, as more regimes seek to restrict the flow of information to and between their citizens. Pluggable Transports can help keep people connected, by hiding (obfuscating) network traffic and routing it between devices in ways that make it more difficult to block.

You can see from our [overview](/how) that there are several methods censors can use to obstruct the Internet, and how there are different ways people can get past these restrictions. But how do we know what's really happening around the world, and how do we decide where our attention is needed the most?

Below is a collection of resources that may help you find out some of this information. These are projects that do ongoing monitoring of network outages, and report them to the [community](/community). If you know of a resource we should be including here, let us know via [email](mailto:feedback@pluggabletransports.info)

* **[OONI](https://explorer.ooni.torproject.org)** - The Open Observatory of Network Interference is part of the [Tor Project](https://www.torporject.org), aiming to collect information related to network interference around the world. They have been operational for over 5 years, and have [a collection of apps](https://ooni.torproject.org/install/) run by volunteers to test network conditions where they are.<br /><br />OONI's raw data is often combined with research from leading academics and practitioners to build up a picture of censorship at specific times, such as [this example from August 2018](https://ooni.torproject.org/post/south-sudan-censorship/) that provides some detail about South Sudan's blocking of independent news organizations.

* **[Censored Planet](https://censoredplanet.org)** - The Censored Planet Observatory uses remote measurement techniques to run remote censorship measurements for thousands of websites. Censored Planet continously measures reachability to 2,000 websites from more than 95,000 vantage points in 221 countries (a 42-360% increase compared to other measurement platforms).

* **[IODA](https://ioda.caida.org)** - IODA stands for Internet Outage Detection and Analysis, a project from CAIDA, the Center for Applied Internet Data Analysis. IODA's visualizations are considered "experimental", and the site urges people to use it with caution. Along with a high-level [dashboard](https://ioda.caida.org/ioda/dashboard) showing outages according to their severity, IODA also has an [Alert Feed](https://ioda.caida.org/ioda/dashboard) for outages, and a comprehensive [API](https://ioda.caida.org/ioda/api) for researchers to use with their own dta.

* **[MLab](https://measurementlab.net)** - The Measurement Lab is an open source project, hosting [tests](https://www.measurementlab.net/tests/) that individual users can access to verify their own connections. The data is collected according to a strict [Privacy Policy](https://www.measurementlab.net/privacy), and the project publishes all data in an open format, as well as providing its own [visualizations](https://www.measurementlab.net/visualizations/) and [publications](https://www.measurementlab.net/publications/)

* **[RIPE NCC](https://stat.ripe.net)** - Operating at the routing level of the Internet, RIPE measures the performance of the Internet's backbone. Using data from [RIPE Atlas devices](https://atlas.ripe.net/) used by thousands of organizations around the world, RIPE able to provide a snapshot of Internet performance from a number of different perspectives.

* **[Canary](https://github.com/OperatorFoundation/Canary)** - Operator Foundation's Canary platform is a server-based tool for assessing the efficacy of pluggable transports, working in conjunction with their [Adversary Lab](https://github.com/OperatorFoundation/AdversaryLabClientSwift) client. As a privately-run tool, tests can be run on all pluggable transports that work with Operator's [Shapeshifter](https://github.com/OperatorFoundation/shapeshifter-dispatcher) library.

* **[Psiphon Data Engine](https://psix.ca)** - Launched in 2020, the Psiphon Data Engine \(PDE\) is a central repository for visualizing and analyzing open network measurements, with the aim of providing actionable insights for researchers and security trainers. \(PDE\) has a number of [partners](https://psix.ca/d/IvwsRueWz/partners?orgId=2) and is actively soliciting for more engagement from across the Internet Freedom community.

* **[Tor Metrics](https://metrics.torproject.org)** - Tor already has support for Pluggable Transports, deployed through obfuscated bridges. Their metrics page can give a good indication of where network blocking takes place. On the metrics page, you can see where direct connections are working, and also where different types of bridge connections are taking place. This data is supplemented by a manual collection of known events that might be related to the graphs. Also worth looking at is Torsten Grote's visualization of data collected by OONI, and showing where [Tor may be being blocked](https://grobox.de/tor/).

* **[Google Transparency Report](https://transparencyreport.google.com/traffic/overview)** - Originally launched as far back as 2010 during Google's conference [Internet at Liberty](https://sites.google.com/a/pressatgoogle.com/internet-at-liberty-2010/), the Transparency Report documents a number of ways in which Google's services are restricted internationally. Sometimes that can be via [government demands for content takedown](https://transparencyreport.google.com/government-removals/overview), but other times it can be due to interference at the network level. The [Global Disruptions](https://transparencyreport.google.com/traffic/overview) map shows a near-live, aggregated view of what they are seeing on their network, along with links to verified reports that the data illustrates.

* **[Netblocks](https://netblocks.org)** - Netblocks operate at the intersection of cybersecurity, Internet governance, and digital rights. The organization was originally formed as [Turkeyblocks](https://www.turkeyblocks.org) when Turkey blocked access to social media in the wake of a bombing attack in Ankara. They have since moved on to test conditions in many other countries, collecting data via a network of volunteers in countries such as Iraq, Nicaragua and Pakistan. In August 2018, they wrote about the restriction of mobile Internet speeds in [Bangladesh](https://netblocks.org/reports/bangladesh-internet-shutdown-student-protests-jDA37KAW), and at the time of writing are due to launch COST, their collaboration with the [Internet Society](https://www.internetsociety.org/) to measure the cost of shutting down the Internet, at the [2018 Forum on Internet Freedom in Africa](https://cipesa.org/2018/06/2018-edition-of-the-forum-on-internet-freedom-in-africa-fifafrica-set-to-take-place-in-ghana/).


* **[Freedom on the Net](https://freedomhouse.org/report/freedom-net/)** - If you're looking at how Internet Freedom has been impacted over the past six years, you can read through the archive of reports produced by Freedom House since 2012. Using networks of trusted reporters, Freedom House have amassed a wealth of information and detailed reports, showing a year-on-year decline of overall freedom on the net. For up-to-date reports since the [latest edition](https://freedomhouse.org/report/freedom-net), you can also follow them on [Twitter](https://twitter.com/freedomonthenet).


<p style="text-align:left;"><a href="/about/">&lt; Previous</a>
</p>

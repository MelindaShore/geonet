Internet-Wide GeoNetworking (geonet)
====================================

Chairs:
  Melinda Shore (melinda.shore@gmail.com)
  Alexandru Petrescu (alexandru.petrescu@gmail.com)

Assigned Area Director:
  Ted Lemon

Mailing list
   Address: its@ietf.org  
   To subscribe: https://www.ietf.org/mailman/listinfo/its  
   Archive: http://www.ietf.org/mail-archive/web/its/current/maillist.html  

Previous web page: http://www.lara.prd.fr/ietf-its

Charter Proposal
----------------

The group is concerned with Internet-wide geonetworking.

IP routing and addressing are completely unaware of
geography.  Mechanisms and IETF protocols are needed for
authorized source nodes anywhere in the Internet to
disseminate packets to other nodes in areas described by
geographic parameters, while respecting the privacy concerns
of sender and receiver.  Parameters such as geographical
coordinates and other geo-locators such as civic addresses
should be usable.
In particular, mechanisms and protocol solutions are needed:

* for the accurate representation of geographic areas using
  (1) geolocators such as names and (2) physical geographic
  coordinates.

* to ensure that geographical area information (for example,
  geolocators, names, and physical geographic coordinates)
  is accurately mapped to an IP address.  Mapping data bases
  can be maintained at the source nodes, intermediate or
  edge nodes, and at specific IP locator nodes.

* to ensure that an IP address can be accurately mapped to a
  geographic area information (geo-locators, names, and
  geographic physical coordinates).  Note that this refers
  to the addresses of access routers, roadside units (RSUs),
  and so on, and not end nodes.  Mapping data bases can be
  maintained at the source nodes, intermediate or edge
  nodes, and at specific IP locator nodes.

* to ensure that data packets generated by source nodes
  placed arbitrarily in the Internet can be forwarded over
  multiple hops by using, where possible, geographic
  physical coordinates of (1) the destination node(s) and/or
  (2) the intermediate nodes for the routing decisions,
  instead of using their IP addresses.  Note that in order
  to solve the above challenge it is NOT mandated that all
  nodes located on the path from source to destination nodes
  are able to forward packets using the geo-coordinates of
  (1) the destination node(s) and/or (2) the intermediate
  nodes for the routing decisions. This is emphasized by
  using the words "where possible".

The main use-cases are:
* dissemination to a geographical area
* goods tracking
* vehicular traffic safety, efficiency, management and infotainment
* mobile road-side unit
* identification of originating area
* geolocation of instrumented ambulance

Protocol work would begin after completion of these work items listed
below, and upon rechartering.

Work Items
----------
* Problem Statement I-D (informational)
* geonet Terminology I-D (informational)
* Description of Geospatial Locators I-D (informational)
* geonet Framework  (informational)
* Mapping Between IP Locators and Geospatial Locators (informational)

Milestones:
----------
  Jul 2014 -

  Oct 2014 -

  Mar 2015 -


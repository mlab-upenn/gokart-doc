.. _doc_gnss:

GNSS
=========================

Global navigation satellite system (GNSS) is the system used for obtaining the current position. We use the Sepntrio `Mosaic-H dev kit <https://shop.septentrio.com/en/shop/mosaic-h-gnss-heading-module-development-kit-2-gnss-antennae?utm_medium=website&utm_source=GNSS%20receivers%20or%20modules%20%20Page%20mosaic-H%20-%20CTA%20to%20webshop>`_
The dual antenna setup improves functionality as we also obtain heading (`True North heading <https://airplaneacademy.com/whats-the-difference-between-true-and-magnetic-heading-explained/#:~:text=True%20heading%20is%20your%20direction,being%20hundreds%20of%20miles%20apart.>`_) from the system.

RTK correction services:
Point One Polaris '<https://pointonenav.com/polaris>'_
'<https://github.com/PointOneNav/polaris>'_
need to request early access

u-blox PointPerfect
SSR, i.e. PPP-RTK
https://portal.thingstream.io/pricing
3-6 cm, < 30 s
SPARTN format, not supported by Septentrio mosaic-H
Supported natively only by u-blox receivers with an up-to-date firmware (and maybe only on the latest revisions)
https://www.u-blox.com/en/technologies/ppp-rtk-gnss-correction-services-pointperfect
http://rtcm-ntrip.org/home.html
free, but only a few available
RTK2GO
http://rtk2go.com/
See map – RTK2GO public base stations
RTK2GO public base stations
Skylark
$49 per month per client
Coverage in US
RTCM over NTRIP
Trimble RTX
$400 per year
https://incors.in.gov/rtk.aspx
RTk service in Indiana
KeyNet
RTK service in PA, works in Philly
$375 for 30 days; $3135 annually

RTK basestation:

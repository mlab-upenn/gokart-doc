.. _doc_gnss:

GNSS
=========================

Global navigation satellite system (GNSS) is the system used for obtaining the current position. We use the Sepntrio `Mosaic-H dev kit <https://shop.septentrio.com/en/shop/mosaic-h-gnss-heading-module-development-kit-2-gnss-antennae?utm_medium=website&utm_source=GNSS%20receivers%20or%20modules%20%20Page%20mosaic-H%20-%20CTA%20to%20webshop>`_
The dual antenna setup improves functionality as we also obtain heading (`True North heading <https://airplaneacademy.com/whats-the-difference-between-true-and-magnetic-heading-explained/#:~:text=True%20heading%20is%20your%20direction,being%20hundreds%20of%20miles%20apart.>`_) from the system.

=========================
RTK correction services:
=========================

#.Point One Polaris-
  * 'polaris'_
  * 'polaris_git'_

.. polaris: https://pointonenav.com/polaris
.. polaris_git: https://github.com/PointOneNav/polaris

#. u-blox PointPerfect
  * SSR, i.e. PPP-RTK
  * https://portal.thingstream.io/pricing
  * 3-6 cm, < 30 s
  * SPARTN format, not supported by Septentrio mosaic-H
  * Supported natively only by u-blox receivers with an up-to-date firmware (and maybe only on the latest revisions)
  * https://www.u-blox.com/en/technologies/ppp-rtk-gnss-correction-services-pointperfect
  * http://rtcm-ntrip.org/home.html
  * free, but only a few available

#. RTK2GO
  * http://rtk2go.com/
  * 'RTK2GO public base stations map <https://www.google.com/maps/d/u/0/edit?mid=1IMrStJfvUROGhlZtQzr1fDgeN-hBom6i&usp=sharing>'_
  * 'RTK2GO public base stations <https://docs.google.com/spreadsheets/d/19LGGK_gizAD02vjECt7P1b4enX6-dsjAkxU3BNMIU9Q/edit?usp=sharing>'_

#. Skylark
  * $49 per month per client
  *  https://www.swiftnav.com/skylark
  * Coverage in US
  * RTCM over NTRIP

#. Trimble RTX
  *  https://positioningservices.trimble.com/services/rtx/
  * $400 per year

#. RTK service in Indiana
  * https://incors.in.gov/rtk.aspx

#. KeyNet
  * RTK service in PA, works in Philly
  * http://www.keynetgps.com/
  * $375 for 30 days; $3135 annually

=========================
RTK basestation:
=========================
* https://learn.sparkfun.com/tutorials/how-to-build-a-diy-gnss-reference-station/all
* https://learn.sparkfun.com/tutorials/setting-up-a-rover-base-rtk-system
* https://learn.sparkfun.com/tutorials/gps-rtk2-hookup-guide

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

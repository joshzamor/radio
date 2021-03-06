# radio
Currated Links, a work in progress

## General
- [Antenna Theory](http://www.antenna-theory.com/): Bunch of information on antennas.
- [RepeaterBook](https://repeaterbook.com): Online listing of repeaters

## Digital - Packet
Packet transmissions generally require a transciver (or just resceiver if skipping sending), a computer,
a Terminal Node Controller (TNC) for converting to/from serial for the computer and analog for the transciever.
More recently software and faster computers have made it possible to replace the TNC with an adequate sound card
and the right software, saving on the cost/bulk of the TNC and associated cabling.  Software TNC running on a
Raspberry Pi appears to be a good fit.

- [Ubiquiti](https://www.ubnt.com/): Company selling WiFI (not ham radio) equipment for long range links
  and mesh networking.
- [HamWan](https://hamwan.org/): Pugent Sound Data Ring
- [aprs](http://aprs.fi): Packet network for reporting position and small messages
- [TNC-x](http://tnc-x.com/): TNC in a box and for RaspberryPi

## Outernet
Digital data streaming from satelites.
- [Outernet](http://outernet.is/): project site and store
- [Lighthouse article at RTLSDR](https://www.rtl-sdr.com/outernet-lighthouse-receiver-now-for-sale/): On Outernet and the Lighthouse
- [Lantern Indegogo](https://www.indiegogo.com/projects/lantern-a-global-satellite-data-radio#/): Project description
- [Malawi National Library Install](https://youtu.be/RhTdkI9yXXA):  Video of installation

## Orgs
- [ARRL](http://arrl.org): US org Amateur Radio Relay League
- [RACES](http://www.usraces.org/): US emergency civil radio group

## SDR
- [OpenWebRX](SDR.hu): Open source web spectrum analysis
- [RTL-SDR](https://www.rtl-sdr.com/):  Software Defined Radio (SDR)
- [WebSDR](http://websdr.org): Web-based SDR broadcasts

## Software
- [CHIRP](http://chirp.danplanet.com/projects/chirp/wiki/Home): Open source software for programming.
  (frequencys and the like by location) radios.
- [Dire Wolf](https://github.com/wb2osz/direwolf) Software "soundcard" modem/TNC for AX.25 encoding/decoding.
  Popular software to use in conjunction with a Raspberry Pi, soundcard, and radio for a software based TNC setup.
  [Example](https://github.com/wb2osz/direwolf/blob/master/doc/Raspberry-Pi-APRS.pdf) for that rig included.
- [GNURadio](https://www.gnuradio.org/): SDK (Software Development Kit) for SDR.

## Protocols & Formats
- [AX.25](https://en.wikipedia.org/wiki/AX.25): Wiki entry on the AX.25 protocol at the heart of many packet radio
  communications.
- [Codec 2](http://www.rowetel.com/?page_id=452): Codec for quality voice audio over low baud.

## Baofeng
Cheap radios which people have made work for cheap packet communications.
- [Baofeng Carrier Detect](http://larr-project.blogspot.com/2014/01/elegant-solution-for-carrier-detect-in.html): To better
  detect when a transmission is being received.
- [Baofeng Packet blog](https://illruminations.com/2014/01/15/baofeng-packet-radio-adventures/): more on packet radio and 
  baofengs.
- [Baofeng hacks](https://w7apk.com/): More info on using Baofengs for packet.

# M475A Stereo Monitor Module · Monitoring

Ward-Beck Systems M475A, 1986|19. Wiki page: [M475A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M475A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 33 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 215 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 13 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 38 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [4 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1986 - M475A - P004 - 1-1.jpg](MANUALS/1986%20-%20M475A%20-%20P004%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;Monitor solo | dB +/-0.5 dB _ dB +/-0.5 dB |
| **Frequency response** | +/-0.15 dB from kHz |
| **Noise** | dB below nominal output measured over Hz dBm kHz bandwidth) |
| **Harmonic distortion** | Less than 0.159 from Hz +24 dBm output less Less than 0.059 at kHz +24 dBm output. |
| **Source impedance** | Monitor Solo 600 ohms less balanced/unbalanced. 30k ohms balanced |
| **Input impedance monitor solo talk back** | 30k ohms balanced_ Less than ohms summing input) _ 78K ohms balanced |
| **Input level** | dBm nominal |
| **Output impedance** | 50 ohms balanced |
| **Load impedance** | 600 ohms balanced |
| **Output levels** | dBm nominal +26 dBm maximum |
| **Channel separation** | Phasing: dB _ Low number the input pair in phase with the low number the output pair. |
| **Power requirements** | 25V MA nominal, +24 dc 120 mA _ MA maximum. |
| **Ambient temperature** | degrees Celsius |
| **Dimensions** | 60&quot; (41 mm 7.00&quot; high 178 mm 165 Mm 50&quot; deep |
| **Weight** | (0.538 kg) |

## Circuit description

From [1986 - M475A - Stereo Monitor Module (2).pdf](MANUALS/1986%20-%20M475A%20-%20Stereo%20Monitor%20Module%20(2).pdf) pages 8-13 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The mono control signal appearing at J2 pin I of the SA14_ 140 assembly and derived f...om U48 pin 10, del ermines whether the solids tate switch ing on the SA14_ 14 0 combines the le I! and...igh t channel signals to a n L+R (mo no) signal. This OCCurS forth eco ndHion of SW6 op e...a le Clan d the program signal palh selected (n o closure to control Common at module Connector pin W).

Transistors 04 and 05 drive the su lo.. n d mono LEO indlc a to...s respectively.

Monitor Outputs

Two Se lS of left and right channel mo r,;lor ing out p U15 a &quot;'e provided. On&quot; is di...ec t and the other is through mute relays K I lind K2.

With the muter el a y s K l lind K2 int her el axed po s il ion the full +8 dBm signal output IIp pears atp ins 17&amp;U and 18&amp;U of the module conn eclo r. When the mUle control function is activated the signals are derive d through loss n el works R 17, R 18 &amp; R2 1 (f or the ie ftc hannel) and R19, R20 &amp; R2 2 l forth e right c h&quot; n nel). R21 and R22 maybe adjusted to give the degree of muting desired (f ull or partial).

Transistors 0 1 and 02 drive muter e lays Kl, K2 and the mute LEO indicator 051 (Which is i nlegra l to mUles witch SW7).

Mute cont...ol maybe from a next erna l source, wll h a closure of connector pin X to pin Z by a n e x tern a l SOurce or o nth e module by operating alternate &quot; c t lon s wllch SW7.

Power fort he mule control circuitry is der lve d from.. n external 24 volt sc c c e applied between pins Y and Z of the module connector.

Twelve volts to operate the s olo/ l a lkba ck control circuitry through dec o u p l er 0 3.

Power Supply Oecoupling

The +/-25 volts u p ply voltage applied 10 pins 21 and 19 of I h e

module c onneclo... is...e gul at ed down to +/ _18 volts by ana ctiv e

decoupl er consisting of 0 6 through 0 9 wll h their associated components.

**M4 7 SA STEREO MONITOR MOOUL E**

The d ~oup led +/ ~18 II olt supply IIol t age powers t h., audio c i n:u itry of the M47SA.

The common return fort he + / ~2S IIo l t supplies i sat pin 20 o f the module connector, while them ain f r...me c h...s sis con ne c tio n appears atp i n 22.

WA;:; C · = = C l&lt; SYS,&quot;E M S L.TC,

&quot;'''15''' ST ~ i'l: EO MONITOR MODUL!::

MFG PART NUMBE1'l

cr Caoac; llor 4..7 uF /to V Kernel T3908 475&quot;'0 IOAS C2 4.7 v F/lO V ca 22 pF Ph~lips CO 22pF cs 220 pF 2222 -6~O-O.l2: 1

ce 33 uFjlO V Kernel TJ90 D3J6MOIOAS C1 4.7 vF /to V T39OB47 5MOIOAS C' 4.7 uF / to V C' 22p F Philips COO 22 pF

220 pF 33 uF / to V 68 uF jlO V,-, 2222-63 ~3 22 1 T3900 336MOlOAS T390 0686 MQl OAS ca 68 u F/ to V cis 470 pF

m 4?O pF ctz 22 pF 2Z22-6 U1_I0229 C&gt;8 22 pF CO? l OO pF 22 22~30-58 l 0 1 C20 33 u F/ to V T390 0336MOIOAS

C&quot; 22 vF /25 V en 22 uF j 25 V C2J 10 vF / 25 V C,. 10 u F/2S V cas 0.' uFj lOOV Spra g ue lCl OX7RlO4M05 08

C26 22 uF/25 V Philips C21 22 uFj 25 V C28 22 uF /2 5 V C,&quot; 22 uF / 25 V C&quot; 22 u F/2 5 V

C&quot; 22 uF/2 5 V caz 0.' uFj

l OO V Sp ~,ague lClOX7R1C4M050 B C3J 0.' uF/l OO V

C'&quot; 0.' uFj lOO V cas 0.' uFj l OO V

WA~ D - BECK SYSTEMS L.TD.

**MFG PART HUMBER**

CJ8 0.1 uF! IOO v Sp,;:ag ue CJ1 0.1 uF ! lC)O v

0.1 uF ! IOO v 0.1 uF ! IOO v

CRI DIode I H4 ' 48 CR2 R, Zen e.. 6.2V IH153A

CR. 'N&quot;&quot;&quot;

,R,, Zen... l. W IH146A m l H4003

**CRIO**

051 LEO, V.llaw H. P. HLMP_, 40 1 VI,. OS2 LEO, Red Fa fn: hlld FLlJl 10 RD DSJ LEO, R. d H.P. HLM P_ 1JOI RD

QI T..a n. l.lar PN3 569

**TN21 02**

00 1' PNl 569

**PNJ645**

ce T N2 102 09 T N4OJ6

R,R' Resl$lar&quot; 1! 4W 5'; 41K

Philips

**'9 ' OK**

W A J10 - B e Cl&lt; S Y9Tl:: MS LT C.

MI&amp;75A STEREO MONITOR MOOut.E

DESCRIPTION MFG PMn NUMBE;!;

Res l,~tor lf4 W 5S,2&lt;

**R15 1**

Potent Iometer

1/ I&amp;W 5~ Philips

Resistor

&quot; P i her PT1 0 VSK '&quot; Potenl lomet er

eza Re s',:lIo r 1/4W 5S &quot;&quot;&quot;zs Philips

,n J9K '&quot;

22 0

&quot; 0 Potent iometer

Resistor 1/4W 51 JOK

IoI47S A S'~RE O MONITOR MoaUL::

**,. '&quot; M' G &quot;'ART NUMBER**

Resistor 1/ 4W

**1/ 4 W**

P&quot;,i,liPS

RS&gt; l / ZW 5~ 'AS AS' 1/ 4W roc R5S oaK AS. oaK

**S'NI**

7.4c AlA. Pusl'lb ullon Assembly

SW' SW if,~h, Lighted L icon 39-23 100 S..n

n Con~ec (o,., 12 Pin e..... g 5 lik 8:;'-9 65780-0 12 J2 e Pine.....gsti k 6 578 ()..()06

Relay rr r RZ. 24W-C

I n l.,~..e tee

U' Cil&quot;(;ul t National LM8J 3N

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY2p3cWdkc2sxLW8/view?resourcekey=0-OM-lCjn0SVC8Sy7VutO-9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY2p3cWdkc2sxLW8&resourcekey=0-OM-lCjn0SVC8Sy7VutO-9A" width="240" alt="1986 - M475A - 475-04-004 - STEREO MONITOR MODULE MODULE LAYOUT.jpg"></a><br><sub>1986|19 · 475-04-004 - STEREO MONITOR MODULE MODULE LAYOUT · <a href="MECHANICAL/1986%20-%20M475A%20-%20475-04-004%20-%20STEREO%20MONITOR%20MODULE%20MODULE%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcmJySGt4ZS1lYms/view?resourcekey=0-lJNpiLmsMpJ6tRHdZnDohA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcmJySGt4ZS1lYms&resourcekey=0-lJNpiLmsMpJ6tRHdZnDohA" width="240" alt="1986 - M475A - 475-04-004.jpg"></a><br><sub>1986|19 · 475-04-004 · <a href="MECHANICAL/1986%20-%20M475A%20-%20475-04-004%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M475A.stl`](MECHANICAL/M475A.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M475A)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 60" (41 mm 7.00" high 178 mm 165 Mm 50" deep)
- **From the drawing:** 11 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M475A - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M475A.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU3U2bVl4amF2SW8/view?resourcekey=0-NdkWkx-foIz0Myn27DooOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU3U2bVl4amF2SW8&resourcekey=0-NdkWkx-foIz0Myn27DooOw" width="240" alt="1986 - M475A - 14-140-02-001 - ALL CAPCITORS ARE.jpg"></a><br><sub>1986|19 · 14-140-02-001 - ALL CAPCITORS ARE · <a href="SCHEMATICS/1986%20-%20M475A%20-%2014-140-02-001%20-%20ALL%20CAPCITORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGtRWmRVQXMtMHM/view?resourcekey=0-dgQMOgC1RN8QCW0PVczBoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGtRWmRVQXMtMHM&resourcekey=0-dgQMOgC1RN8QCW0PVczBoA" width="240" alt="1986 - M475A - 14-140-02-001 - NOTES ALL RESISTORS ARE.jpg"></a><br><sub>1986|19 · 14-140-02-001 - NOTES ALL RESISTORS ARE · <a href="SCHEMATICS/1986%20-%20M475A%20-%2014-140-02-001%20-%20NOTES%20ALL%20RESISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeGNfZGFCMHUwdUk/view?resourcekey=0-GJspUEIn7ZeKohZpXViKAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeGNfZGFCMHUwdUk&resourcekey=0-GJspUEIn7ZeKohZpXViKAg" width="240" alt="1986 - M475A - 14-140-06-001 - DUAL BOOSTER AMPLIFIER COMPONENT LAYOUT.jpg"></a><br><sub>1986|19 · 14-140-06-001 - DUAL BOOSTER AMPLIFIER COMPONENT LAYOUT · <a href="SCHEMATICS/1986%20-%20M475A%20-%2014-140-06-001%20-%20DUAL%20BOOSTER%20AMPLIFIER%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdzdZMHVwTWhnbmc/view?resourcekey=0-lf6lD7LrnA3_7cpFHcicLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdzdZMHVwTWhnbmc&resourcekey=0-lf6lD7LrnA3_7cpFHcicLg" width="240" alt="1986 - M475A - 475-01-002 - SOLO INPUT MUTE SOLO CONTROL PLIFIER MON TOR.jpg"></a><br><sub>1986|19 · 475-01-002 - SOLO INPUT MUTE SOLO CONTROL PLIFIER MON TOR · <a href="SCHEMATICS/1986%20-%20M475A%20-%20475-01-002%20-%20SOLO%20INPUT%20MUTE%20SOLO%20CONTROL%20PLIFIER%20MON%20TOR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVpEemlDdVEzU28/view?resourcekey=0-5R7OZ_BYCavlKibVToK06Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVpEemlDdVEzU28&resourcekey=0-5R7OZ_BYCavlKibVToK06Q" width="240" alt="1986 - M475A - 475-01-002 - STEREO MONITOR MODULE FUNC TIONAL.jpg"></a><br><sub>1986|19 · 475-01-002 - STEREO MONITOR MODULE FUNC TIONAL · <a href="SCHEMATICS/1986%20-%20M475A%20-%20475-01-002%20-%20STEREO%20MONITOR%20MODULE%20FUNC%20TIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQm9Gd2RrNEg4LU0/view?resourcekey=0-bYQrWOYML-PRuJvF7C04wg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQm9Gd2RrNEg4LU0&resourcekey=0-bYQrWOYML-PRuJvF7C04wg" width="240" alt="1986 - M475A - 475-02-002 - NOTES ALL RESISTORS ARE.jpg"></a><br><sub>1986|19 · 475-02-002 - NOTES ALL RESISTORS ARE · <a href="SCHEMATICS/1986%20-%20M475A%20-%20475-02-002%20-%20NOTES%20ALL%20RESISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSXNVdHRJVll5dVU/view?resourcekey=0-HQWpLypeSVNeW5dQabCCxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSXNVdHRJVll5dVU&resourcekey=0-HQWpLypeSVNeW5dQabCCxw" width="240" alt="1986 - M475A - 475-02-002 - STEREO MONITOR MODULE SCHEMATIC.jpg"></a><br><sub>1986|19 · 475-02-002 - STEREO MONITOR MODULE SCHEMATIC · <a href="SCHEMATICS/1986%20-%20M475A%20-%20475-02-002%20-%20STEREO%20MONITOR%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHZnOEU0U0VKSE0/view?resourcekey=0-SBbJavgF_auT-6_I92Mvew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHZnOEU0U0VKSE0&resourcekey=0-SBbJavgF_auT-6_I92Mvew" width="240" alt="1986 - M475A - 475-06-002 - STEREO MONITOR MODULE COMPONENT.jpg"></a><br><sub>1986|19 · 475-06-002 - STEREO MONITOR MODULE COMPONENT · <a href="SCHEMATICS/1986%20-%20M475A%20-%20475-06-002%20-%20STEREO%20MONITOR%20MODULE%20COMPONENT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M475A - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts, 1 contacts (J1), 1 contacts (J2), 1 contacts (P1), 1 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 |  | unread |  | low |
| 1 |  | unread |  | low |
| 1 |  | unread |  | low |
| 1 |  | unread |  | low |
| Z | MUTE CO N T ...OL | control |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMjBpVXhQellJdTA/view?resourcekey=0-zT0vgE872VGP3LjrEbyC0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMjBpVXhQellJdTA&resourcekey=0-zT0vgE872VGP3LjrEbyC0Q" width="240" alt="1986 - M475A - P001 - Title Page.jpg"></a><br><sub>1986|19 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMzZaT2Iya2o3MWc/view?resourcekey=0-K2brKPtNoV9FER_Gp5Q1aA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMzZaT2Iya2o3MWc&resourcekey=0-K2brKPtNoV9FER_Gp5Q1aA" width="240" alt="1986 - M475A - P002.jpg"></a><br><sub>1986|19 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcDlCMGZHZ2Y4ckE/view?resourcekey=0-nxKaY_hxuIh-VwLwI5fFag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcDlCMGZHZ2Y4ckE&resourcekey=0-nxKaY_hxuIh-VwLwI5fFag" width="240" alt="1986 - M475A - P003.jpg"></a><br><sub>1986|19 · P003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTI4WXF4Y1Z0ZE0/view?resourcekey=0-3XYIaf_5j3v8lqCOhcDZgQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTI4WXF4Y1Z0ZE0&resourcekey=0-3XYIaf_5j3v8lqCOhcDZgQ" width="240" alt="1986 - M475A - P004 - 1-1.jpg"></a><br><sub>1986|19 · P004 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnZjWVh4cThSODQ/view?resourcekey=0-m4mOIm3yfrdtCDG-Ldse3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnZjWVh4cThSODQ&resourcekey=0-m4mOIm3yfrdtCDG-Ldse3g" width="240" alt="1986 - M475A - P005 - 2-1.jpg"></a><br><sub>1986|19 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNldjUUdTUGtJOFE/view?resourcekey=0-e1gO9TAZZ6acmxNNhm9X7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNldjUUdTUGtJOFE&resourcekey=0-e1gO9TAZZ6acmxNNhm9X7w" width="240" alt="1986 - M475A - P006 - 3-1.jpg"></a><br><sub>1986|19 · P006 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVnp2NjlseE9zRGM/view?resourcekey=0-_ELLvmLdNDHB77sPDDBgjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVnp2NjlseE9zRGM&resourcekey=0-_ELLvmLdNDHB77sPDDBgjg" width="240" alt="1986 - M475A - P007 - 4-1.jpg"></a><br><sub>1986|19 · P007 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKelFESG1DUkp1T0U/view?resourcekey=0-SZLgnLFt6x6WujnDrh_YHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKelFESG1DUkp1T0U&resourcekey=0-SZLgnLFt6x6WujnDrh_YHw" width="240" alt="1986 - M475A - P008 - 4-2.jpg"></a><br><sub>1986|19 · P008 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3M0TVRCcVpvQ3c/view?resourcekey=0-h1JjIlbm-hQjtMsPh8Cn2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3M0TVRCcVpvQ3c&resourcekey=0-h1JjIlbm-hQjtMsPh8Cn2g" width="240" alt="1986 - M475A - P009 - 4-3.jpg"></a><br><sub>1986|19 · P009 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNFJwTG9hdEowMGs/view?resourcekey=0-W9OP1K3nw18SgOaEXFqGbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNFJwTG9hdEowMGs&resourcekey=0-W9OP1K3nw18SgOaEXFqGbw" width="240" alt="1986 - M475A - P010 - 5-1.jpg"></a><br><sub>1986|19 · P010 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTnFieG8zMjU0NXc/view?resourcekey=0-JrWI9ldzhNAoD1jg4yNTlw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTnFieG8zMjU0NXc&resourcekey=0-JrWI9ldzhNAoD1jg4yNTlw" width="240" alt="1986 - M475A - P011 - 5-2.jpg"></a><br><sub>1986|19 · P011 - 5-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaVlwMG1hQk9FOGM/view?resourcekey=0--feYdHVLRnOVeyrHOhx88g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaVlwMG1hQk9FOGM&resourcekey=0--feYdHVLRnOVeyrHOhx88g" width="240" alt="1986 - M475A - P012 - 5-3.jpg"></a><br><sub>1986|19 · P012 - 5-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDVoUzVKNnN2bW8/view?resourcekey=0-cQnovpEC4d2MamYLhQHByA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDVoUzVKNnN2bW8&resourcekey=0-cQnovpEC4d2MamYLhQHByA" width="240" alt="1986 - M475A - P013 - 5-4.jpg"></a><br><sub>1986|19 · P013 - 5-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlZXVEUxVmdHMUU/view?resourcekey=0-fSQGuVbWWyLQ5RD-a2OCvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlZXVEUxVmdHMUU&resourcekey=0-fSQGuVbWWyLQ5RD-a2OCvg" width="240" alt="1986 - M475A - P014 - 5-5.jpg"></a><br><sub>1986|19 · P014 - 5-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZi1zWEs3MDY5X1U/view?resourcekey=0-sXU4IuOBWK1Nz19Cb616vQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZi1zWEs3MDY5X1U&resourcekey=0-sXU4IuOBWK1Nz19Cb616vQ" width="240" alt="1986 - M475A - P015 - 6-1.jpg"></a><br><sub>1986|19 · P015 - 6-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlJnZ1Vab25vdGM/view?resourcekey=0-xqI-M0YccTWYDfC_uQbVgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlJnZ1Vab25vdGM&resourcekey=0-xqI-M0YccTWYDfC_uQbVgg" width="240" alt="1986 - M475A - P020.jpg"></a><br><sub>1986|19 · P020</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWDFORDdJVWRubVE/view?resourcekey=0-PMvObeKVOaYNX4Okn0LcjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWDFORDdJVWRubVE&resourcekey=0-PMvObeKVOaYNX4Okn0LcjA" width="240" alt="1986 - M475A - P021 - SA14-140.jpg"></a><br><sub>1986|19 · P021 - SA14-140</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjdDZWliZDZtOFE/view?resourcekey=0-3Iv_o4oi_nPnCvGZZHnRQQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjdDZWliZDZtOFE&resourcekey=0-3Iv_o4oi_nPnCvGZZHnRQQ" width="240" alt="1986 - M475A - P022 - SA14-140 - 1-1.jpg"></a><br><sub>1986|19 · P022 - SA14-140 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUpFOVlDUGZ5QzA/view?resourcekey=0-1T9mivBrBnzyvOCbDJE_Yw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUpFOVlDUGZ5QzA&resourcekey=0-1T9mivBrBnzyvOCbDJE_Yw" width="240" alt="1986 - M475A - P023 - SA14-140 - 2-1.jpg"></a><br><sub>1986|19 · P023 - SA14-140 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHZuUUlMTHJaT3c/view?resourcekey=0--lnh20sNIBxhxzfZPDO2yA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHZuUUlMTHJaT3c&resourcekey=0--lnh20sNIBxhxzfZPDO2yA" width="240" alt="1986 - M475A - P024 - SA14-140 - 2-2.jpg"></a><br><sub>1986|19 · P024 - SA14-140 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3JIX3ZOVzE5SWM/view?resourcekey=0-WP4j-2T5DbWllne5eIt5OQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3JIX3ZOVzE5SWM&resourcekey=0-WP4j-2T5DbWllne5eIt5OQ" width="240" alt="1986 - M475A - P025 - SA14-140 - 2-3.jpg"></a><br><sub>1986|19 · P025 - SA14-140 - 2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHJFRDhiRlA5eWM/view?resourcekey=0-NAmfidTvP00q46DSyvdiOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHJFRDhiRlA5eWM&resourcekey=0-NAmfidTvP00q46DSyvdiOw" width="240" alt="1986 - M475A - Stereo Monitor Module (2).pdf"></a><br><sub>1986|19 · Stereo Monitor Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWgxaWNqZHJocWc/view?resourcekey=0-yCWtY3Vd2foTDcsvxSngbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWgxaWNqZHJocWc&resourcekey=0-yCWtY3Vd2foTDcsvxSngbQ" width="240" alt="1986 - M475A - Stereo Monitor Module.pdf"></a><br><sub>1986|19 · Stereo Monitor Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYjgzZm4tc2g2MmM/view?resourcekey=0-Bry_NZi2O3fUD5ZPmwVIhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYjgzZm4tc2g2MmM&resourcekey=0-Bry_NZi2O3fUD5ZPmwVIhA" width="240" alt="19xx - M475A - DOC - STEREO L SERIES - P006.jpg"></a><br><sub>19xx - M475A - DOC - STEREO L SERIES - P006</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQTJ6c0JaSklnaEk/view?resourcekey=0-XM7munndTr4kWzum7sbPXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQTJ6c0JaSklnaEk&resourcekey=0-XM7munndTr4kWzum7sbPXg" width="240" alt="19xx - M475A - DOC - STEREO L SERIES - P007.jpg"></a><br><sub>19xx - M475A - DOC - STEREO L SERIES - P007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHZfR0RiYlJNU00/view?resourcekey=0-dNHJAnYWsZsGvNn5IbiR-Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHZfR0RiYlJNU00&resourcekey=0-dNHJAnYWsZsGvNn5IbiR-Q" width="240" alt="19xx - M475A - DOC - STEREO L SERIES - P016.jpg"></a><br><sub>19xx - M475A - DOC - STEREO L SERIES - P016</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa2Nsc1ZLQXE0eDA/view?resourcekey=0-Ex-_y4TUXDD3Yl3WOsgJuw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa2Nsc1ZLQXE0eDA&resourcekey=0-Ex-_y4TUXDD3Yl3WOsgJuw" width="240" alt="19xx - M475A - DOC - STEREO L SERIES - P017.jpg"></a><br><sub>19xx - M475A - DOC - STEREO L SERIES - P017</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2" width="240" alt="19xx - M475A - DOC - WILMA - Aux and main summing.jpg"></a><br><sub>19xx - M475A - DOC - WILMA - Aux and main summing</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1986 - M475A - 14-140-02-001 - ALL CAPCITORS ARE.kicad_sch](KICAD/1986%20-%20M475A%20-%2014-140-02-001%20-%20ALL%20CAPCITORS%20ARE.kicad_sch)
- [1986 - M475A - 14-140-02-001 - NOTES ALL RESISTORS ARE.kicad_sch](KICAD/1986%20-%20M475A%20-%2014-140-02-001%20-%20NOTES%20ALL%20RESISTORS%20ARE.kicad_sch)
- [1986 - M475A - 475-01-002 - SOLO INPUT MUTE SOLO CONTROL PLIFIER MON TOR.kicad_sch](KICAD/1986%20-%20M475A%20-%20475-01-002%20-%20SOLO%20INPUT%20MUTE%20SOLO%20CONTROL%20PLIFIER%20MON%20TOR.kicad_sch)
- [1986 - M475A - 475-01-002 - STEREO MONITOR MODULE FUNC TIONAL.kicad_sch](KICAD/1986%20-%20M475A%20-%20475-01-002%20-%20STEREO%20MONITOR%20MODULE%20FUNC%20TIONAL.kicad_sch)
- [1986 - M475A - 475-02-002 - NOTES ALL RESISTORS ARE.kicad_sch](KICAD/1986%20-%20M475A%20-%20475-02-002%20-%20NOTES%20ALL%20RESISTORS%20ARE.kicad_sch)
- [1986 - M475A - 475-02-002 - STEREO MONITOR MODULE SCHEMATIC.kicad_sch](KICAD/1986%20-%20M475A%20-%20475-02-002%20-%20STEREO%20MONITOR%20MODULE%20SCHEMATIC.kicad_sch)
- [1986 - M475A - Stereo Monitor Module (2) p21.kicad_sch](KICAD/1986%20-%20M475A%20-%20Stereo%20Monitor%20Module%20(2)%20p21.kicad_sch)
- [1986 - M475A - Stereo Monitor Module (2) p30.kicad_sch](KICAD/1986%20-%20M475A%20-%20Stereo%20Monitor%20Module%20(2)%20p30.kicad_sch)
- [1986 - M475A - Stereo Monitor Module p19.kicad_sch](KICAD/1986%20-%20M475A%20-%20Stereo%20Monitor%20Module%20p19.kicad_sch)
- [1986 - M475A - Stereo Monitor Module p21.kicad_sch](KICAD/1986%20-%20M475A%20-%20Stereo%20Monitor%20Module%20p21.kicad_sch)
- [1986 - M475A - Stereo Monitor Module p30.kicad_sch](KICAD/1986%20-%20M475A%20-%20Stereo%20Monitor%20Module%20p30.kicad_sch)
- [M475A.kicad_sym](KICAD/M475A.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

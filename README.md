# Artificial brain
This repository describes the architecture of an **Autonomous Intelligent Agent**. The architecure was designed using the [Eclipse Capella](https://www.eclipse.org/capella/) tool (version 5.2.0) following the [Arcadia](https://www.eclipse.org/capella/arcadia.html) systems engineering methodology.

## Goal
Design an experimental setup to develop and evaluate basic capabilities of an **Autonomous Computational Intelligence** through interactions with a *Human Interlocutor* and an *Unstructured Indoor Environment*.

## High-level requirements
In this section, we list some high-level requirements describing mainly the interactions between the *Human Interlocutor* with the system, i.e. the **Autonomous Intelligent Agent**:
1. The system shall be able receive high-level voice commands from a human interlocutor;
2. The system shall provide voice feedback to the human interlocutor;
3. The system shall learn *scripts* describing how to perform simple tasks in the unstructured indoor environment, e.g. go get an object at a given room;
4. The system shall recall the appropriate *scripts* upon high-level human voice commands;
5. The system shall execute *scripts* to perform learned tasks in the unstructured indoor environment;
6. ...

## Logical architecture
As depicted in the figure below, the **Autonomous Intelliget Agent** includes both an **Autonomous Computational Intelligence** and a **Semi-Autonomous Experimental Robotic Platform**. The **Autonomous Computational Intelligence** corresponds to an *Artificial Brain* in which the high-level voice commands are recognized, translated into *scripts* and them prepared / adapted for execution according to the feedback from the *Unstructured Indoor Environment*. On the other hand, the **Semi-Autonomous Experimental Robotic Platform** corresponds to an *Artificial Body* by which the *Artificial Brain* executes its tasks and collect feedback from the *Unstructured Indoor Environment*.

![Logical Architecture](https://github.com/LCAD-UFES/artificial_brain/blob/main/docs/%5BLCBD%5D%20Structure.png)

## Low-level requirements
This section describes the low-level requirements for the system components, i.e. the **Autonomous Intelligent Agent**:
1. The semi-autonomous experimental robotic platform shall be remotely controlled by the artificial brain via a high-speed Wi-Fi link;
2. ...

## Physical architecture
Figure below illustrates the main components of the physical architecture of the **Autonomous Intelligent Agent** highlighting both the allocation of physical functions (green boxes) into software components (blue boxes) and the allocation of software components (blue boxes) into hardware components (yellow boxes). The architecture also indicates the main physical interfaces between the hardware components.
![Physical Architecture](https://github.com/LCAD-UFES/artificial_brain/blob/main/docs/%5BPAB%5D%20Physical%20Architecture%202.png)

## Configuration items breakdown
Figure below indicates the breakdown of the configuration items into COTS equipments and miscellaneous hardware components for being purchased and software components to be either developed or integrated.
![Configuration Items](https://github.com/LCAD-UFES/artificial_brain/blob/main/docs/%5BCIBD%5D%20Configuration%20Items%202.png)

## List of material
Imported equipments:
| Item | Description | ROM Price (USD) | Quantity | Freight (USD) | Total (USD) | 
| --- | --- | --- | --- | --- | --- |
| 1 | [PincherX 100 Robotic Arm](https://www.trossenrobotics.com/pincherx-100-robot-arm.aspx) | 550 | 1 | ? | 550 |
| 2 | [Acherman Robot Car](https://wheeltec.net/product/class/?115.html) | [477](https://www.thanksbuyer.com/ackerman-robot-car-smart-ros-car-assembled-top-version-with-front-wheel-steering-mechanism-71306?search=ackerman%20robot%20top%20) | 1 | ? | 477 |
| 3 | [LABISTS Raspberry Pi 4 8GB RAM Starter Kit](https://labists.com/products/raspberry-pi-4-8gb-ram-starter-kit-with-64gb) | 140 | 2 | ? | 280 |
| 4 | [Pre-Assembled 2 DoF Pan Tilt Digital Servo Kit](https://www.uctronics.com/uctronics-pre-assembled-2-dof-pan-tilt-digital-servo-kit-full-metal-bracket-for-building-robotic-arms-ptz-cameras-and-more.html) | 90 | 1 | ? | 90 |
| 5 | [LY-KREE DC-DC 12V to 5V/15A 75W Converter](https://www.amazon.com/Adapter-Voltage-Converter-Regulator-Electronics/dp/B07Q71LQGS/ref=psdc_10967761_t2_B07VGN79X5?th=1) | 23 | 1 | ? | 23 |
| 6 | [Cllena DC 8V-40V to 12V/10A 120W Regulator](https://www.amazon.com/Cllena-Automatic-Converter-Regulator-Waterproof/dp/B08KZPXK63) | 30 | 1 | ? | 30 |

National equipments:
| Item | Description | ROM Price (BRL) | Quantity | Freight (BRL) | Total (BRL) | 
| --- | --- | --- | --- | --- | --- |
| 1 | [Omni Mic](https://produto.mercadolivre.com.br/MLB-1681272341-microfone-de-mesa-omnidirecional-com-mudo-usb-home-office-_JM#position=43&search_layout=stack&type=item&tracking_id=bef4a4fe-736d-4d0e-b97b-3a9fc6daa799) | 210 | 1 | ? | 210 |
| 2 | [Speakers](https://www.americanas.com.br/produto/1735304195?pfm_carac=caixa-de-som-pc-p2&pfm_page=search&pfm_pos=grid&pfm_type=search_page&offerId=60e75aac52131c3c81df32c0&buyboxToken=smartbuybox-acom-v2-06dc7cd9-a7e3-4bfe-8288-f81673ea0c88-2022-01-16%2017%3A54%3A16-0300&voltagem=220V) | 30 | 1 | ? | 30 |
| 3 | [Dual-band Wi-Fi Router GI Inet GL-AR750](https://www.gl-inet.com/products/gl-ar750s/) | 750 | 1 | ? | 750 |
| 4 | [Skyrich Lithium Battery Lix14 12V 12/14Ah](https://produto.mercadolivre.com.br/MLB-1507427330-bate-lithium-lix14-vulcan-750-1-ano-de-garantia-_JM#position=6&search_layout=stack&type=item&tracking_id=f606c4c4-1f0a-4bde-8ce4-40e22f91b49b) | 690 | 1 | ? | 690 |


## Action list
- [ ] Close the arquitecture (Stiven - 23/01)
- [ ] Review the arquitecture (Rafael - 31/01)
- [ ] Indicate at least 3 suplliers for each item (Rafael - 06/02)
- [ ] Prepare/start the purchase process (Manoel - 13/02)


⚠️ *This and all associated organisational repositories are a part of the Ecosystem of Trust pilots initiative at this time and as such this is all innovation based work and thinking. This is a 📢 **public** repository - viewable by all and editable by those who have been invited in. Sensitive documents and information must not be added to the repositories within this Github organisation.*

# Information Sharing Networks

ISNs are networks that enable interested parties to share information between each other. The information is shared by way of signals. 

Each participant in a network has a site where they can publish and receive signals. The signals are flexible and allow parties to reply or contribute to a signal thus enriching the information for the parties in the network.  

[Introduction to Information Sharing Networks](https://github.com/information-sharing-networks/.github)

## Establishing an ISN
In order to establish an ISN parties need to sign a Information Sharing Network Framework Agreement to share the information and manage the ISN.

The next dependency is for network participants to have a site for each of the members in the network. The sites will enable the exchange of the signals to take place. (see Technology dependencies section below)


## Information Sharing Network Framework Agreement
The [Framework Agreement](https://github.com/information-sharing-networks/Framework) is a multi-party sharing instrument that allows information to be shared between groups of public and private bodies with a shared interest or objective. It reduces the reliance on traditional point-to-point agreements between individual actors.

The Framework Agreement makes it easier for organisations to cooperate by minimising the paperwork needed when a new information sharing requirement is identified.

The Framework Agreement comprises: 
- a Memorandum of Understanding (MOU)
- a Network Establishment Agreement (NEA)

The MOU is signed by organisations wishing to cooperate in order to improve information sharing.  It establishes the roles and responsibilities for members, and the principles for cooperation between the participating organisations.

The Standard Network Establishment Agreement includes principles for operating a committee to manage the network.  

The simpler Accelerated Network Establishment Agreement can be used where a lighter-touch governance arrangement is appropriate.

## Technology dependencies to set up ISN
Every organisation participating in an ISN has a site (with their own URL) to which they can publish signals on to. 

Participants of the sites can also grant permissions to one another so that signals can be exchanged between the sites. 

For detailed instructions on how to set up a site please see link: https://github.com/information-sharing-networks/isn-ref-impl

## Signals
Signals are created using an Indieweb Microformat 2 'event' post type by calling the ISN site 'micropub' endpoint, internally this creates a 'signal' compliant with the information-sharing-network signals protocol.

- Details on the signals and protocols can be found here: [Signal protocol](https://github.com/information-sharing-networks/signals)

## BTD Signal Definitions
We are running a number of Border Trade Demonstrators (BTDs) sites where signals are being received. 

-  Details on the signal definition for the BTDs can be found here:
https://github.com/border-trade-demonstrators/btd-1/blob/main/isn-btd-1.edn




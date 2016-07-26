# RandomTP
RandomTP is a DragonMiner plugin created by Mafrans.
The purpose of this plugin is to randomly teleport players within a radius.

commands:
  randomtp:
    description: The main command of RandomTP.
    usage: /<command> <player>
    aliases: [rtp]
    permission: rtp.self
  rtpportal:
    description: Add or remove portals;
    usage: /<command> <add|remove> <portalName>
    permission: rtp.portals

permissions:
  rtp.self:
    description: Allows using /randomtp.
    default: op
  rtp.others:
    description: Allows using /randomtp on others.
    default: op
  rtp.portals:
    description: Allows using /rtpportal.
    default: op

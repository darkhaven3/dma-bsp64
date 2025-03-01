A new node builder for Doom 64.

This is based on D64BSP, which in turn is based on GLBSP ... which is then based on BSP.

New features:
- Lines can be omitted from the blockmap by providing a negative tag, OR by combining the "Always show on automap" AND "Never shown on automap" linedef flags.
      - Note that in practice in DB64, this means setting a tag greater than 32767.

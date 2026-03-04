# ChargeBridge Design Files

This repository contains the design files for the Pionix ChargeBridge.

The KiCAD component is a multi unit part to simplify the schematics.

The KiCAD Footprints contain the 3D models as embedded files, so if you use them there is no need
to download the separate STEP files.

There are two components, one for the M.2 Connector and one for the standoff. Use both. The reason it is split up is that it appears as 
two items in the BOM with correct pick and place positions. Note that the ChargeBridge itself will not automatically be part of the BOM.

Note that the Footprint for the metal standoff (Würth 9774067243R) contains a 3D model from a part that
is slightly shorter, so it will look like as it does not fit in height. 9774067243R is a custom height part
that fits exactly to the M.2 connector being used in the component. If you use a different M.2 connector, adjust
height of the stand off accordingly.

The custom height is in stock at Würth at the time of writing and can be ordered via Würth directly. Alternatively,
contact Pionix for parts.


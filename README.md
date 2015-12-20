# Kha-InstancedExample
Simpel example for instanced rendering in kha. Preview: http://www.aoe-maniac.de/instances/

Instanced rendering allows you to render an object multiple times with some variations, but in a singe drawcall. An example for this are lots of identical blocks with different positions. Rendering them individually there is lots of communication overhead between CPU and GPU. But please keep in mind that this only makes sense if you are drawing many instances of a single model.
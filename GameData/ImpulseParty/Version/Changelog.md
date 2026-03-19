# Impulse Party

## 0.6.1
* Fixed bulkheadProfile values in some parts.
* Updated dependency from WildBlueTools to WBIResources.
* Updated files for the part upgrades. Those work properly again.
* Updated minimal state fusion reactor characteristics:
  * If Sterling style or WBI style not activated, default to this.
  * Will require FusionPellets and produce ElectricCharge, scaled by part volume vs FFT 2.5m fusion reactor.
  * Reduced ElectroPlasma (updated to wbiElectroPlasma) storage. This fixes the issue of the reactors generating a huge mass while running and defeating a warp ship's WarpCapacity.
* Updated WBI style fusion reactor characteristics:
  * They primarily produce only ElectroPlasma now and have additional converters for ElectroPlasma Decay and ElectricCharge extration, known as EPS Transformer.
  * EPS Transformer is superior to WBI fusion's ElectricCharge byproduct rate, very useful for folks who need the extra ElectricCharge and don't care much about the WBI plasma RCS.
  * Removed FusionPellets storage to accomodate the EPS aspects.

## 0.6
* Added and fixed Tweakscale for nav dishes.
* Fixed attachment symmetry problems which leads to undesired reverse thrust situations and one or more engines burning off the part they are attached to. This may cause invalid orientation of some attachments of the engine on some crafts.
* Fixed StoredCharge conversion ratio in Mk2 NF-alike capacitors.
* Updated shields config to not cause the multiple ModuleAblator issue with OPT.

## 0.5
* Added Nav Deflector parts, including separate models for the shield projection standalone.
* Raise heat tolerances for fusion reactors, Mk1 warp core and Mk2 batteries.

## 0.4
* Added 0.625m parts: Priax series warp nacelles and Kelvin series scoop.
* Added Extras:
  * Hard Balance (when WBI mods absent) tunes impulse rockets to feel like Nertea's mods.
  * Moved warp coils upgrade patch here.
  * Moved harvesters free animation patch here.
* Added Impulse 3.75m rocket.
* Added Kelvin series warp nacelle parts with 2.5m tails.
* Added Mk2 batteries and Mk2 capacitors (pending external emissive for use by NFE).
  * Capacitors have distinct accent color for KSPIE and NFE.
  * Included complete patches for them.
* Revised warp coils upgrade patch.

## 0.3
* Added red color variant for scoops.
* Added Extras:
  * Aesthetics patch for harvesters so they always spin and can toggle lights (not action-grouped) unlinked from harvester functions.
* Changed mesh switching on scoops to only use stock variants, no longe ruse B9PS.
* Perfected plume switching for impulse engines when using UFO engine module.
* Updated scoop textures.
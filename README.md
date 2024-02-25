# FS22_stoppelfahrspur
# ACHTUNG! DIES IST KEIN MOD! 
benötigte Dateien für Stoppelfahrspuren im LS22

Die Dateien sind momentan so angeordnet, daß die Ordner **foliage** und **xml** direkt in das Verzeichnis der map.i3d eingefügt werden können, ohne weitere Änderungen an den Dateien vornehmen zu müssen.


## map.i3d

die xml Dateien der Früchte müssen in der map.i3d auf den neuen Pfad aktualisiert werden

Bsp. 

```xml
<File fileId="226" filename="foliage/barley/barley.xml"/>
<File fileId="225" filename="foliage/canola/canola.xml"/>
```

## map.xml

Der Pfad zur fruittypes.xml und zur maps_growth.xml muß in der map.xml aktualisiert werden (oder stattdessen die vorhandene ersetzen)

```xml
<fruitTypes filename="xml/maps_fruitTypes.xml" />
<growth filename="xml/maps_growth.xml" />
```

---

# CAUTION! THIS IS NOT A MOD!
Required files for stubble tracks in FS22

The files are currently arranged so that the folders **foliage** and **xml** can be inserted directly into the directory of the map.i3d, without any further changes needing to be made to the files.

## map.i3d

The XML files of the crops must be updated in the map.i3d to the new path

Example:

```xml
<File fileId="226" filename="foliage/barley/barley.xml"/>
<File fileId="225" filename="foliage/canola/canola.xml"/>
```

## map.xml

The path to fruittypes.xml and maps_growth.xml must be updated in the map.xml (or instead, replace the existing one)

```xml
<fruitTypes filename="xml/maps_fruitTypes.xml" />
<growth filename="xml/maps_growth.xml" />
```

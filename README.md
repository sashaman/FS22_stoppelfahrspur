# FS22_stoppelfahrspur
benötigte Dateien für Stoppelfahrspuren im LS22

Die Dateien sind momentan so angeordnet, daß die Ordner **foliage** und **xml** direkt in das Verzeichnis der map.i3d eingefügt werden können, ohne weitere Änderungen vornehmen zu müssen.



## map.i3d

die xml Dateien der Früchte müssen in der map.i3d auf den neuen Pfad aktualisiert werden

Bsp. 

```xml
<File fileId="226" filename="foliage/barley/barley.xml"/>
<File fileId="225" filename="foliage/canola/canola.xml"/>
```



## map.xml

Der Pfad zur fruittypes.xml muß in der map.xml aktualisiert werden (oder stattdessen die vorhandene ersetzen)

```xml
<fruitTypes filename="xml/maps_fruitTypes.xml" />
```

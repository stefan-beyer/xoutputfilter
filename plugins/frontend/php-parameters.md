## PHP mit Parameter

### Beispiel

 1. Wähle _PHP mit Parametern_ als Ersetzungstyp
 2. Verwende `date` als Marker (es ist nur ein Wert möglich)
 3. als Ersetzung / PHP-Code: `<?php echo date($params['format']); ?>`
 4. Als Marker kann man nun verwenden `[[date format="d.m.Y"]]`
 5. Freuen, wenn das aktuelle Datum richtig formatiert ausgegeben wird.

 
__Achtung:__ Manchmal werden die Anführungszeichen automatisch in andere Zeichn umgewandelt und die Parameter werde nnicht erkannt. In solch einem Fall kann auch `param=|wert|` verwendet werden.
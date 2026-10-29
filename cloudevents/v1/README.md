Specificatie data onderdeel in CloudEvent netwerkmodel

JSON Schema voor Notificatie en Melding. Beide types delen de Message-definitie; Duiding verloopt via oneOf op het id-veld. 

> [!WARNING]
> LET OP: De 'id' in de CloudEvent context is een random UUID en verwijst NIET naar een record in een register. Gebruik daarvoor de waarde onder recordID.

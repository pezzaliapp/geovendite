# GeoVendite

PWA commerciale locale per importare file Excel di clienti, vendite e ordini, analizzare fatturato, ordinato/inevaso, trasporti addebitati, agenti, macchine e mappa clienti.

## Pubblicazione su GitHub

```bash
git clone https://github.com/pezzaliapp/geovendite.git
cd geovendite
cp -R /percorso/della/cartella/geovendite-pwa/* .
git add .
git commit -m "Prima versione PWA GeoVendite"
git push origin main
```

Poi abilita GitHub Pages da **Settings > Pages > Deploy from branch > main / root**.

## File richiesti dall'app

- ordini Excel
- vendite Excel
- clienti Excel

I dati restano nel browser. La georeferenziazione usa OpenStreetMap/Nominatim solo quando premi il pulsante dedicato.


## Aggiornamento v16
- Marker ordinato in rosso per maggiore leggibilità.
- Andamento mese su mese per cliente.
- Comparazione con anno precedente o con anno selezionato.


## v16
- Confronto mese su mese selezionabile per Venduto + Ordinato, Solo Venduto, Solo Ordinato e Trasporti.
- La comparazione può usare la selezione principale oppure una modalità dedicata nel riquadro andamento cliente.


## v16
- Corretto confronto mese su mese: venduto + ordinato, solo venduto, solo ordinato e trasporti.
- Aggiunta riga Totale anno nella comparazione.

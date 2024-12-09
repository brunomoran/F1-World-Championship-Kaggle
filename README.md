## F1 World Championship (1950 - 2024)

Aquest projecte del cas Kaggle de l'assignatura APC analitza els campionats del món de Fórmula 1 des de 1950 fins a 2024 utilitzant dades històriques. L'objectiu és avaluar el rendiment dels pilots i equips, identificar tendències històriques i predir resultats futurs.

### Autors i repositori

- [Bruno Morán Vivanco](https://github.com/brunomoran)
- [Roger Sala Mimó](https://github.com/Salaeones)
- [Repositori GitHub](https://github.com/brunomoran/F1-World-Championship-Kaggle)

### Introducció

Aquest repositori conté informació detallada sobre el campionat del món de F1. Les dades estan organitzades en diferents arxius CSV dins de la carpeta 

data

, cadascun proporcionant informació específica sobre diferents aspectes del campionat.

Les dades són obtingudes de [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020) i inclouen informació sobre els circuits, equips, pilots, resultats de curses, classificacions finals, temps de voltes, parades a boxes, classificacions de classificació, temporades, curses sprint i estats dels pilots.

### Estructura de les dades

- `circuits.csv`: Informació sobre els circuits on s'han celebrat curses de F1.
- `constructor_results.csv`: Resultats de cada equip (constructor) en cada cursa.
- `constructor_standings.csv`: Classificació final de cada equip (constructor) al final de cada temporada.
- 

constructors.csv

: Informació sobre els equips (constructors) que han participat en temporades de F1.
- `driver_standings.csv`: Classificació final de cada pilot al final de cada temporada.
- 

drivers.csv

: Informació sobre els pilots que han participat en temporades de F1.
- `lap_times.csv`: Temps de cada volta de cada cursa.
- `pit_stops.csv`: Informació sobre les parades a boxes de cada cursa.
- `qualifying.csv`: Resultats de la sessió de classificació de cada cursa.
- `races.csv`: Informació sobre cada cursa, inclòs dates i ubicacions.
- `results.csv`: Resultats detallats de cada cursa.
- `seasons.csv`: Informació sobre cada temporada del campionat.
- `sprint_results.csv`: Resultats de les curses sprint.
- `status.csv`: Informació sobre l'estat dels pilots durant les curses (per exemple, si han abandonat o han estat desqualificats).

### Objectius

1. **Anàlisis de rendiment dels pilots i equips**: Evaluar el rendiment dels pilots i equips al llarg dels anys. Identificar els pilots i equips més exitosos de la història de la F1.
2. **Anàlisis de circuits**: Analitzar el rendiment dels pilots i equips en diferents circuits. Identificar els circuits més desafiants i aquells on s'han produït més accidents.
3. **Tendències històriques**: Identificar tendències i canvis en el campionat de F1 al llarg del temps. Analitzar l'evolució de la tecnologia i el seu impacte en el rendiment dels equips.
4. **Predicció de resultats**: Utilitzar tècniques d'aprenentatge automàtic per predir els resultats de temporades futures. Identificar els pilots i equips amb més probabilitats de guanyar el campionat.

### Requisits

- Python 3.9
- Llibreries: pandas, matplotlib, numpy, seaborn, scikit-learn

### Ús

1. Cloneu el repositori:
   ```sh
   git clone https://github.com/brunomoran/F1-World-Championship-Kaggle.git
   cd F1-World-Championship-Kaggle
   ```

2. Instal·leu les dependències:
   ```sh
   pip install -r requirements.txt
   ```

3. Executeu el notebook 

f1.ipynb

 per veure les anàlisis i prediccions.

### Conclusions

- Els pilots i equips més exitosos de la història de la F1 han estat identificats basant-nos en les seves posicions finals i punts totals.
- Els circuits es poden agrupar en tres clústers principals basats en la seva ubicació geogràfica i altitud.
- Els circuits més desafiants i amb més accidents han estat identificats.
- L'impacte de la tecnologia en el rendiment dels equips ha estat significatiu, especialment amb el canvi al motor híbrid.
- Prediccions sobre la millor combinació de pilot i equip per a la temporada 2025 i l'impacte de Hamilton a Ferrari han estat realitzades.

### Contribucions

Les contribucions són benvingudes. Si voleu contribuir, si us plau, feu un fork del repositori, creeu una branca amb les vostres modificacions i envieu un pull request.

### Llicència

Aquest projecte està llicenciat sota la llicència MIT. Vegeu el fitxer `LICENSE` per a més detalls.

# Kunskapskontroll3-datascience

# Spotify Analysis: Jämförande analys av personliga Spotify-data

Detta projekt genomför en jämförande analys av två personers personliga Spotify-data. Analysen syftar till att visualisera och jämföra olika musikpreferenser baserat på användarnas streaminghistorik. Data från två individuella CSV-filer har sammanslagits för att skapa en gemensam fil som sedan analyseras och visualiseras.

# Struktur i projektet

**Images:** Denna mapp innehåller bilder som representerar varje artist, kopplade till rätt syntax och attribut i databasen.
**app.py (Streamlit):** Innehåller koden för alla analyser och deras visualiseringar.
**merged_data.ipynb:** Här slår jag samman de två individuella CSV-filerna till en gemensam fil och gör några tester innan jag genomför de slutgiltiga analyserna.
**spotify.db:** En SQLite-databas skapad från den gemensamma CSV-filen, som används för att lagra och hantera data.
**CSV-filer:** Tre CSV-filer finns med. Två av dem är personliga Spotify-streaminghistorikfiler och en är den sammanslagna versionen av dessa.

# För att köra detta projekt behöver följande bibliotek installeras:

**Visualiseringar:** 
Matplotlib
Plotly
PIL
Seaborn
Streamlit

**Datahantering:**
Pandas
Sqlite3
Numpy

**Programmeringsspråk:**
Python

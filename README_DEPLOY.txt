Hazra Bari Virtual Dual Temple — Revised Timetable

Files:
- 11111.py — deployment entrypoint for the existing Streamlit project
- app2.py — same revised source under the requested app2.py filename
- requirements.txt — dependencies

Deployment: keep the existing Streamlit Main file path (11111.py) unless you also change the Streamlit app settings to app2.py. Upload the source and requirements.txt to the repository.

Revised IST schedule:
05:00–05:30 Mangal Aarti • Darshan
05:30–06:30 Japa • Darshan
06:30–07:00 Shringaar Aarti • Darshan
07:00–10:00 Chadhawa • Darshan
10:00–10:30 Morning Aarti • Darshan
10:30–12:15 Bhog Seva • Darshan
12:15–12:45 Bhog Aarti
12:45–16:45 Mid Day Japa
16:45–17:15 Afternoon Shringaar Aarti • Darshan
17:15–19:00 Chadhawa • Darshan
19:00–19:30 Evening Aarti • Darshan
19:30–21:00 Bhog Seva • Darshan
21:00–21:30 Shital Aarti • Darshan
21:30–22:00 Night Japa • Darshan
22:00–22:30 Sayan Aarti • Darshan
22:30–22:45 Mandir Closing Preparation; temple closes at 22:45.

Darshan rule: both Maa Durga and Mahadev Shiva are visible and Darshan can be recorded at any time while the temple is open, including during Aarti, Japa, Chadhawa and Bhog Seva. Each deity has a separate counter. Only signed-in devotee button actions are counted.

Preservation note: this package is based on the uploaded prior source and retains its other existing features. The source passed Python syntax compilation and schedule assertions. Live Streamlit hosting, account flows, database persistence and Panchang API behavior were not exercised here. The app's existing database remains SQLite; this update does not migrate it to PostgreSQL/Supabase.

Panchang secrets (if used by this source) must be configured in Streamlit Secrets; never commit API keys to GitHub.

About Dataset:
This dataset contains detailed Spotify listening history of a user. Each record captures information about a specific track played on Spotify, including metadata about the track, playback behavior, and the user's interaction with the platform. It spans multiple years and provides insights into user behavior, track preferences, and session dynamics.

Columns/Features Descriptions:


Date_Played – The timestamp when the track playback started.

platform – The platform or device used for playback (e.g., web player).

minutes_played – Number of minutes the track was played before being stopped or skipped.

track_name – The name/title of the track.

artist_name – The artist or band who performed the track.

album_name – The album the track belongs to.

reason_start – Indicates what triggered the playback (e.g., autoplay, user click).

reason_end – Describes how the playback ended (e.g., track completed, skipped).

shuffle – A boolean field indicating if shuffle mode was enabled during playback.

skipped – A boolean field indicating whether the track was skipped (True) or played fully (False).



KPI & Insights:

 4 KPIs

 - Top Artist Listening Share — The Beatles hold ~32.17% of all minutes played among Android users.

 - Second Artist Share — The Killers capture ~25.69% of minutes played.

 - Top Reason for Track Start — trackdone with ~68K occurrences.

 - Top Reason for Track End — trackdone with ~71K occurrences.

📌 3 Insights & Actions
 - Platform Loyalty to Few Artists — Android listeners are heavily concentrated on top 2 artists (>57% combined). Suggest creating recommendations to diversify exposure to other artists.

 - High ‘Trackdone’ Events — Majority of starts and ends are triggered by natural completion, indicating full-track engagement. This can be leveraged in playlist algorithms to maintain listener retention.

 - Low App Interruptions — Minimal appload, backbtn, and logout events suggest stable app performance with low forced-exit rates; maintain current technical stability while focusing on skip reduction.

🖥️ Dashboard Architecture & Views
The dashboard is structured into four distinct focus areas to provide granular and macro views of the music ecosystem:

1. Global Performance Overview
File Reference: overview.png

Focus: Core streaming KPIs and high-level performance tracking.

Key Features: Tracks 526 billion total streams across 20 markets. Includes dynamic visual matrixes highlighting a 5bn monthly stream average, album type distribution (Albums vs. EPs vs. Singles), top-streamed languages (led by Japanese), and macro genre trends dominated by Soul and Electronic music.

2. Artists & Record Labels Insight
File Reference: Artist & Labels.png

Focus: B2B market share analysis and corporate revenue distribution.

Key Features: Breakdowns of market share revenue among major labels (Sony, Def Jam, Atlantic, Universal) versus Independent creators. Tracks complex financial splits across streaming revenue, synchronization rights (Srevenue_sync), and merchandising (revenue_merch).

3. Global Streaming Geography
File Reference: Geography.jpg

Focus: Geospatial audience density and localization strategy.

Key Features: Features an interactive World Choropleth Map visualizing monthly stream distributions globally. Isolates high-performing regional target markets, identifying Germany, France, and the United Kingdom as top revenue-generating hubs.

4. Social Buzz & Mood Vibes
File Reference: Social & Vibes.png

Focus: Cross-platform marketing attribution and psychological listener trends.

Key Features: Correlates platform-specific impressions (TikTok, Instagram Reels, YouTube Shorts, Reddit) to streaming surges. Tracks a unique "Mood Distribution" metric (Happy, Melancholic, Romantic, Energetic, Calm) alongside device-usage segmentations (Mobile, Desktop, Smart Speaker) to map listener psychological profiles.

🛠️ Tech Stack & Skills Demonstrated
BI Tool: Power BI Desktop

Data Modelling: Star Schema layout linking dimension tables (Artists, Geography, Platforms) with core Fact tables (Streams, Social Engagement, Revenue).

Data Transformation (Power Query / M): Handled dirty strings, structural null values, platform-specific date formats, and normalization of cross-platform social metrics.

DAX (Data Analysis Expressions): Engineered custom time-intelligence metrics, dynamic market share percentages, and custom average calculations.

UI/UX Design: Implemented a highly optimized, custom Spotify dark-mode aesthetic utilizing intentional data color theory (Spotify green for streaming focus, distinct branding colors for multi-social analysis).

📈 Key Insights & Business Value
1.Social-to-Stream Correlative Mapping: Demonstrates how viral short-form video metrics (e.g., Instagram Reels driving 108M impressions) directly impact a track's immediate global performance tier.

2.Emotional Data Tailoring: By identifying that ~52% of tracks hold a "Melancholic" mood profile while maintaining a high stream rate, labels can optimize playlist curation algorithms and hyper-target regional ad campaigns.

3.Revenue Split Optimization: Highlights where independent artists are competing successfully against major labels in merch vs. direct digital streaming revenue splits.

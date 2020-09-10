# Billboard-Artist-Frequency

Analysis covering the Billboard Top 100, each week, from 1958-08-09 to 2020-06-27, to highlight artists who frequent said lists more commonly as supporting artists. Historical song data was scraped from Billboard.com then parsed into multiple dataframes for later analysis and data visualization.

Note that 'df_unique.zip' will need to be extracted to be run. The notebook has been structured so as to replace the most time-consuming steps with imports of previously created dataframe / Excel files. Manual, execution of the entire notebook (re-execution of all steps, i.e. no relying on provided dataframe / Excel files), will require switching certain cells from 'raw' to 'code'. Above mentioned full execution time takes multiple hours, so buckle in and bring some popcorn.

The included infographic 'Billboard Artist Frequency.png' is composed of three key elements: a bar chart of most frequent supporting artists ranked in order of total main artist songs (top left), a treemap highlighting the delta between an artist's frequency as main and supporting artist (top right), and supporting artist frequency as a percentage of combined supporting and main artist frequency (bottom).

# us_debate_word_frequency_analysis
Python code for bigram frequency analysis using text transcript

**Word Frequency Analysis of 2024 Presidential Debate
This project conducts a word frequency analysis on the transcript of the 2024 U.S. presidential debate between Kamala Harris and Donald Trump. By analyzing bigram frequencies, we can gain insights into the primary topics and messaging strategies of each candidate.

**Project Overview
Using Python, this analysis focuses on the most frequent phrases (bigrams) used by each candidate, excluding common and less informative phrases (e.g., "donald trump," "united states"). The cleaned data provides a clearer picture of each speaker's core themes and rhetoric during the debate.

**Key Features
Phrase Filtering: Excludes common and repetitive phrases that are not useful for analysis.
Customizable Parameters: Users can modify the number of phrases displayed or the n-gram range for more detailed exploration.
Visualization: Generates horizontal bar plots showing the top bigrams for each candidate.

**Installation
Install the required Python libraries using:
pip install pandas scikit-learn matplotlib

**File Structure

Output Images: The script saves two images of the top bigrams for each speaker in the format Kamala_Harris_top_5_bigrams.png and Donald_Trump_top_5_bigrams.png.

**Usage

Place the transcript CSV file in the same directory as the script.

Update the file_path variable in the script with the path to your CSV file.

The script will generate bar plots showing the most frequent phrases for each candidate and save them as PNG files.

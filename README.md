# Spotify 2023 Data Analysis

This project provides a comprehensive analysis of the Spotify 2023 dataset, exploring patterns in popular music across multiple dimensions.

## Overview

The analysis covers five key areas:

1. **🎵 Music Analysis**: Audio features and trends in popular songs
2. **📱 Platform Comparison**: Song popularity across different streaming services  
3. **👥 Artist Impact**: How artist involvement relates to song success
4. **📅 Temporal Trends**: Music preferences and characteristics over time
5. **🌐 Cross-Platform Presence**: Performance across different streaming platforms

## Dataset

The analysis uses the `spotify-2023.csv` dataset containing information about:
- Track and artist details
- Release information
- Platform presence (Spotify, Apple Music, Deezer, Shazam)
- Audio features (danceability, energy, valence, etc.)
- Streaming metrics

## Setup

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

3. **Open the analysis:**
   - Open `spotify_data_analysis.ipynb`
   - Ensure `spotify-2023.csv` is in the same directory
   - Run all cells to see the complete analysis

## Key Findings

**Music Characteristics:**
- Higher danceability and energy correlate with success
- Popular music averages ~128 BPM (typical pop tempo)
- Major keys dominate (~65% of successful songs)

**Platform Insights:**
- Spotify maintains strongest presence across all metrics
- Cross-platform presence is crucial for maximum impact
- Strong correlation between platform performances

**Artist Collaboration:**
- ~40% of popular songs feature multiple artists
- Collaborations are common but don't guarantee higher streams
- Solo tracks vs collaborations show varied success patterns

**Temporal Trends:**
- 2023 releases dominate the dataset
- Certain months show higher success rates
- Audio feature preferences evolve over time

## Analysis Structure

The notebook is organized into clear sections:

1. **Data Loading & Exploration** - Understanding the dataset
2. **Data Cleaning** - Preprocessing and validation
3. **Music Analysis** - Audio features exploration
4. **Platform Comparison** - Cross-platform performance
5. **Artist Impact** - Collaboration effects
6. **Temporal Trends** - Time-based patterns
7. **Cross-Platform Success** - Integrated success analysis
8. **Statistical Insights** - Advanced correlations and patterns
9. **Summary & Conclusions** - Key findings and recommendations

## Visualizations

The analysis includes comprehensive visualizations:
- Distribution plots for audio features
- Correlation heatmaps
- Platform comparison charts
- Temporal trend analysis
- Success factor breakdowns

## Usage

Simply run the notebook cells in order. The analysis is designed to be:
- **Self-contained**: All necessary code and explanations included
- **Well-documented**: Clear markdown explanations throughout
- **Comprehensive**: Covers all major aspects of the dataset
- **Actionable**: Provides practical insights and recommendations

## Requirements

- Python 3.8+
- Jupyter Notebook
- Required packages listed in `requirements.txt`

## Files

- `spotify_data_analysis.ipynb` - Main analysis notebook
- `spotify-2023.csv` - Dataset (should be provided)
- `requirements.txt` - Python dependencies
- `README.md` - This file

## Next Steps

This analysis provides a foundation for:
- Music recommendation systems
- Artist success prediction
- Platform strategy optimization
- Market trend analysis
- Audio feature engineering

---

## Summary and Conclusions

### COMPREHENSIVE SPOTIFY 2023 DATA ANALYSIS SUMMARY

**📈 DATASET OVERVIEW:**
- Total songs analyzed: 953
- Year range: 1930 - 2023
- Total unique artists: ~486
- Total streams (sum): 489,458,828,542
- Average streams per song: 513,312,423

**🎵 MUSIC CHARACTERISTICS:**
- Average danceability: 67.0% (moderately danceable)
- Average energy: 64.3% (high energy)
- Average valence: 51.0% (moderately positive)
- Average BPM: 123 (typical pop tempo)
- Most popular key: C#
- Major vs Minor: 65.1% Major, 34.9% Minor

**🤝 COLLABORATION INSIGHTS:**
- Collaboration rate: 38.4% of songs feature multiple artists
- Average artist count: 1.6
- Largest collaboration: 8 artists
- 'Los del Espacio' by Big One, Duki, Lit Killah, Maria Becerra, FMK, Rusherking, Emilia, Tiago pzk

**📱 PLATFORM DOMINANCE:**
- Platform leader (playlists): Spotify
- Average playlist presence: Spotify 5200, Apple 68, Deezer 91
- Cross-platform correlation: 0.512 (Spotify-Apple)

**⭐ SUCCESS FACTORS:**
- High-success songs: 318 (33.4%)
- Key success characteristics:
  - Higher danceability: 69.9% vs 67.0%
  - Higher energy: 68.9% vs 64.3%
  - Average BPM: 125

**📅 TEMPORAL TRENDS:**
- 2023 dominance: 175 songs (18.4% of dataset)
- Vintage hits: 258 songs from before 2020 still popular
- 2023 songs avg streams: 147,477,052
- Pre-2020 songs avg streams: 1,090,119,322

**🎯 KEY FINDINGS:**
- ✓ Higher danceability and energy correlate with success
- ✓ Cross-platform presence is crucial for maximum impact
- ✓ 2023 releases dominate the popular music landscape
- ✓ Spotify maintains strongest presence across all metrics
- ✓ Artist collaborations are common but don't guarantee higher streams
- ✓ Popular music tends toward major keys and moderate-to-high BPM
- ✓ Successful songs balance energy with accessibility

**🚀 RECOMMENDATIONS:**
- Focus on creating energetic, danceable tracks
- Aim for cross-platform distribution strategies
- Consider timing releases strategically
- Balance audio features for broad appeal
- Leverage Spotify's platform dominance while maintaining presence on other services

---

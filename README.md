# Twentieth-Century Geopolitical Network Analysis

## Mapping Relationships

## Description

The Institute for Public Policy commissioned this project to examine how twentieth-century historical events shaped today’s geopolitical climate. The Institute seeks to uncover the web of interrelations between countries, using data-driven visualizations to reveal how past ties, alliances, and conflicts continue to influence current global dynamics.

The ultimate aim is to create a clear, research-ready visualization of international relations during this turbulent century, supporting broader policy research initiatives.

## Project Goal

● Perform an analytical overview and visualization of twentieth-century country-to-country relationships to:

● Extract and map historical ties between nations

● Analyze major global events through network metrics

● Highlight patterns in international influence and alliances

● Provide visual insights for researchers and policymakers

## Key Research Questions

_● Which countries were most interconnected during major global events?

_● Which nations held central positions in the twentieth-century network (degree, closeness, betweenness)?

_● What patterns emerge when analyzing inter-country relationships as a network?

## 🚀 Fast Facts

Tools: Python (Pandas, BeautifulSoup, NetworkX, spaCy/NLTK, Matplotlib)
Focus: Web scraping, text mining, NLP, network analysis, visualization
Data: Wikipedia page on 20th-century history

## 🧼 Data & Preprocessing

● Scraped lists of countries and historical content from Wikipedia

● Preprocessed text for named entity recognition (NER) of country mentions

● Applied NLP techniques to extract co-occurrence relationships

● Built a country–country interaction graph

● Engineered features: degree centrality, closeness, betweenness

● Validated graph structure to ensure consistency with historical context

## 📊 Visualization

● Dynamic network chart showing interrelations between countries

● Distinct communities highlighted with clustering algorithms

● Edge thickness reflects strength/frequency of interactions

● Interactive layout for exploring historical ties

## 🔑 Key Findings

## Strongest Connections:

● Germany shows thick edges with Japan, Italy, and Poland

● Japan is strongly connected with China

## Degree Centrality (Most Connected Countries):

● Germany has the highest number of connections in the 20th-century network

● Japan ranks second, followed by France

● Lebanon, Solomon Islands, Guinea, and Iraq have the fewest connections

## Closeness Centrality:

● Many countries rank highly, showing a broad spread of accessibility in the network

## Betweenness Centrality (Influence):

● Germany is the most influential country, followed by Japan

● Most other countries score relatively low on this scale

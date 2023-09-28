# Dune Series Network Analysis

![Project Preview](https://github.com/kirudang/Network_analysis_Dune/assets/91911269/afeee41c-1229-4e4f-9616-1ddfc175060e)

This project explores the "Dune" book series by Frank Herbert through network analysis and community detection. It leverages advanced tools and techniques from natural language processing and network science to gain new insights into the complex web of relationships among characters in this seminal work of science fiction.

## Table of Contents
- [Introduction](#Introduction)
- [Project Structure](#Project-Structure)
- [Data Manipulation and Relationship Extraction](#Data-Manipulation-and-Relationship-Extraction)
- [Network Analysis and Community Detection](#Network-Analysis-and-Community-Detection)
- [Modularity Analysis](#Modularity-Analysis)
- [Centrality Measures](#Centrality-Measures)
- [Getting Started](#Getting-Started)
- [Dependencies](#Dependencies)
- [Contributing](#Contributing)
- [License](#License)

## Introduction

The "Dune" book series is a masterpiece of science fiction literature, known for its rich narrative, intricate character relationships, and complex political intrigue set in a vast interstellar empire. In this project, we dive into the world of "Dune" and uncover hidden patterns and insights by analyzing the relationships between its characters.

## Project Structure

The project is structured into multiple phases:

1. **Data Manipulation and Relationship Extraction**: In this phase, we explore the textual corpus of the "Dune" series and extract the names of characters and locations using spaCy's Named Entity Recognition (NER). This results in a structured representation of the narrative's entities.

2. **Network Analysis and Community Detection**: With the character relationship graph in place, we shift our focus to network analysis. Using NetworkX and the Louvain Algorithm, we uncover the structural properties of the "Dune" universe.

3. **Modularity Analysis**: We assess the quality of the community structure within the graph by calculating modularity, a measure that quantifies the richness of character relationships.

4. **Centrality Measures**: To identify the most influential characters, we calculate centrality measures such as betweenness centrality and closeness centrality.

## Data Manipulation and Relationship Extraction

In this phase, we extract character relationships from the text by:

- Utilizing Named Entity Recognition (NER) to identify character and location names.
- Creating a structured representation of the narrative's entities.
- Building the direction of relationships between characters.

## Network Analysis and Community Detection

In this phase, we:

- Construct a character relationship graph.
- Use the Louvain Algorithm for community detection, revealing hidden communities within the narrative.

## Modularity Analysis

We evaluate the quality of the community structure within the graph by calculating modularity, which quantifies the richness of character relationships.

## Centrality Measures

We identify the top 10 most influential characters using centrality measures, shedding light on the story's protagonists.

## Getting Started

To explore the "Dune" Series Network Analysis project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/kirudang/Network_analysis_Dune.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Network_analysis_Dune
   ```

3. Install the required Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook to explore the project phases.

## Dependencies

The project relies on the following Python libraries:

- spaCy
- NetworkX
- Pyvis
- Louvain Algorithm
- Pandas
- Matplotlib

These dependencies are listed in the `requirements.txt` file.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. We appreciate your help in improving this analysis.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

# Share of Voice Analysis for Atomberg

This project analyzes Atomberg’s Share of Voice (SoV) in the "smart fan" category across platforms like Google, YouTube, Instagram, and X. It quantifies brand visibility using keyword-based search results, combining mentions, sentiment, and relevance scores.

## Tech Stack

- Python for scripting and data analysis
- BeautifulSoup and Selenium for scraping
- VADER for sentiment analysis
- OpenAI GPT-4 for content categorization
- Pandas and Matplotlib for computation and visualization

## Project Structure
'''
├── data/                    # Raw and cached search results\
├── utils/                   # Scraping, scoring, and SoV modules\
├── results/                 # Final SoV outputs and plots\
├── findings_report.pdf      # Final two-page report\
└── main.ipynb               # End-to-end analysis notebook
'''
## Key Features

- Platform-specific scraping for top-N search results
- Weighted SoV scoring based on mentions, sentiment, and relevance
- Modular design for easy extension or platform updates

## Links

- Full Report: [findings_report.pdf](https://github.com/Tejaswini170104/atomberg.pdf)
- Codebase: [GitHub Repository](https://github.com/Tejaswini170104/atomberg_asg)

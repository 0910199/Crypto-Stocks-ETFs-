![Screenshot (40)](https://github.com/user-attachments/assets/6d124480-3f12-43db-bf14-39ddce902a49)
![Screenshot (41)](https://github.com/user-attachments/assets/7e6bf379-af2d-4262-876c-b8a3c352e2a1)
![Screenshot (42)](https://github.com/user-attachments/assets/29193b38-bd7d-4ed0-bc59-d5d94b3fdbc0)


---
# Market Data Analysis (2019 - 2024)

This repository contains datasets and analysis related to market data from 2019 to 2024. The primary focus is on ETFs and stock symbols, covering various market metrics. The data is segmented by date, with additional insights provided through color coding and tracker symbols.

## Dashboard Link - https://app.powerbi.com/reportEmbed?reportId=7dc2a0e0-c3a9-4ef6-8f2d-4651af947f3b&autoAuth=true&ctid=0641ba0f-2be1-47b8-b8c8-c91781ed63e0

## Data Files

### 1. **2019 - 2024 Market Data.xlsx**
- **Description**: Contains market data for various ETFs.
- **Structure**: 
  - Columns include `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`, `Symbol`, `Year`, `Category`, `Formatted Date`, `New_Date`, `Type`, and `Logo`.
  - Example rows:
    | Date       | Open  | High  | Low   | Close | Adj Close | Volume | Symbol | Year | Category | Formatted Date | New_Date   | Type | Logo |
    |------------|-------|-------|-------|-------|-----------|--------|--------|------|----------|----------------|------------|------|------|
    | 2018-12-31 | 1662.0| 1723.0| 1647.0| 1676.0| 1488.77   | 383424 | SQQQ   | 2018 | Max      | 2018           | 2018-12-31 | ETFs | NaN  |

### 2. **ColorCodes.xlsx**
- **Description**: Provides color coding for different visual themes.
- **Structure**:
  - Columns include `Mode`, `bg`, `bg-visual`, `bg-2`, `text`, `text-2`, `red-txt`, `red-bg`, `green-txt`, `green-bg`, `check icon`, `Icon`.
  - Example rows:
    | Mode | bg      | bg-visual | bg-2    | text    | text-2  | red-txt | red-bg  | green-txt | green-bg | check icon                                       | Icon |
    |------|---------|-----------|---------|---------|---------|---------|---------|-----------|----------|-------------------------------------------------|------|
    | Dark | #181818 | #1d1d1f   | #393a3e | #FFFFFF | #F3F3F3 | #FF4242 | #FFBABA | #30DA38   | #C9FFCC  | https://i.postimg.cc/3JQzpkWZ/check-3.png       | 🌙    |
    | Light| #FFFFFF | #F7F7F7   | #DBDBDB | #000000 | #2F2F2F | #FF4242 | #FFBABA | #30DA38   | #C9FFCC  | https://i.postimg.cc/jdDLtvJ3/check-2.png       | ⛅    |

### 3. **trackers.csv**
- **Description**: Contains symbols, types, and logos for various stocks.
- **Structure**:
  - Columns include `Symbol`, `Type`, `Logo`.
  - Example rows:
    | Symbol | Type  | Logo                                            |
    |--------|-------|-------------------------------------------------|
    | AAPL   | Stock | https://i.postimg.cc/zfTYDYxX/pngwing-com-4.png |
    | GOOGL  | Stock | https://i.postimg.cc/15W9bSjk/pngwing-com-9.png |

## Usage

1. **Data Analysis**: Use these datasets to analyze market trends over the years 2019 to 2024.
2. **Visualization**: Utilize the color codes provided to maintain consistency across visual themes when presenting data.
3. **Tracking Symbols**: Reference the `trackers.csv` file for visual logos and types of stocks to enhance data presentation.

## Requirements

- Python 3.x
- Pandas

## Getting Started

1. Clone this repository.
2. Install the required dependencies using `pip install pandas`.
3. Load and analyze the datasets using Python or any preferred data analysis tool.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Market data provided from various sources.
- Icons sourced from postimg.cc.

---



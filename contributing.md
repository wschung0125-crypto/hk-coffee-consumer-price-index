Contributing to HK Coffee Price Index ☕️📈
First off, thank you for considering contributing! Whether you are a fellow Gen Z coffee lover, a data enthusiast, or an economist, your help makes this index more accurate for all Hongkongers.

How You Can Help
1. Adding New Price Data (Most Needed!)
The heart of this project is the data.json file. If you visit a cafe and notice a price change, or find a receipt from a few years ago, please add it!

    Data Requirements:
    
    Item: Must be a "Standard Latte" (Hot, regular size) to keep the index consistent.
    
    Price: The price in HKD (including service charge if applicable).
    
    Location: The district (e.g., Causeway Bay, TST, Tsuen Wan).
    
    Proof: If possible, include a link to a photo of the menu or receipt in your Pull Request description.

2. Refining the Index Calculation
    If you have a background in statistics or economics, we are looking for advice on:
    
    How to weight different districts (e.g., should Central carry more weight than North District?).
    
    How to account for "Shrinkflation" (e.g., if the cup size gets smaller but the price stays the same).

3. Improving the Website
    If you know HTML, CSS, or JavaScript, feel free to help us improve the GitHub Pages visualization. We want the charts to be easy to read on mobile!
    
    The Process
    Fork the repository.
    
    Create a new branch for your changes (e.g., git checkout -b add-2023-tst-prices).

Update data.json following the existing format:

    JSON
    {
      "date": "YYYY-MM",
      "cafe_name": "Name",
      "district": "District",
      "price_hkd": 42,
      "source": "Receipt/Menu Photo"
    }
    Commit your changes with a clear message (e.g., "Add May 2023 prices for Sheung Wan").
    
    Submit a Pull Request (PR) and wait for review!

Code of Conduct
This is a community project. Please be respectful, helpful, and patient with others. We are all here to learn and track our disappearing coffee money together!

## Tax Calculator

### About
This Python library provides a comprehensive solution for calculating federal and state/provincial taxes for various countries. It simplifies the process of determining your federal and state tax liability based on your income and residence.

### Class Structure
**Federal:**
- This class serves as the foundation for tax calculations. It takes the country and income as input and provides methods for calculating standard deduction, taxable income, base tax, additional taxes, and total tax.
- Additional taxes include:
  - CPP and EI
  - Social Security and Medicare

**State:**
- This class inherits from Federal and adds functionalities specific to state/provincial tax calculations. It considers the state/province of residence and incorporates its tax brackets.
- Compatible states include:
  - British Columbia, Ontario
  - California, Florida, New York, Texas
 
### Data Files

The code relies on two CSV files containing tax bracket data for different countries and states/provinces. These files need to be structured appropriately to ensure accurate tax calculations.

The files are:
- `federal_brackets.csv`
- `state_brackets.csv`

### Future Enhancements

1. Integration with external APIs for real-time tax data.
2. Support for a wider range of countries, states, and provinces.
3. Graphical user interface for user-friendly tax estimation.
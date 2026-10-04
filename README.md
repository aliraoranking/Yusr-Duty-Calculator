# Yusr Duty/Taxes Calculator By ALiRao

A browser calculator for Pakistan Customs core assessment. It works out import value, duties and taxes, then compares the paid assessment with an audited assessment.

Developed by ALiRao, Appraising Officer (muhammadalicustoms@gmail.com).

## How to use

1. Open `Yusr-Duty-Taxes-Calculator.html` in a browser, or use the GitHub Pages link.
2. Enter the invoice or assessed value. Freight is already included and is not added again.
3. Choose insurance: 1% of the invoice value, or a fixed foreign-currency amount.
4. Choose landing charges: 1% of (invoice + insurance), or a fixed foreign-currency amount.
5. Enter the exchange rate and the duty and tax rates.
6. Click a zero to clear it. Press Enter to move to the next rate.

## Calculation

- Import value (FC) = invoice or assessed value + insurance + landing charges
- Import value (PKR) = import value (FC) × exchange rate
- Customs duty, additional customs duty, regulatory duty and federal excise duty are charged on the import value in PKR
- Anti-dumping duty is charged on the import value and added to the total, but it is not included in sales tax or income tax
- Sales tax and additional sales tax = (import value + customs duty + additional customs duty + regulatory duty + federal excise duty) × rate
- Income tax = (import value + those duties + sales tax + additional sales tax) × rate
- Other can be named and charged on the duty base, the sales-tax base, or the income-tax base

## Audit

Tick **Audit** to lock the paid duty and taxes.

- Tab 2 keeps the paid figures
- Tab 3 recalculates with the revised rates and shows them beside the paid amounts
- Tab 4 shows the levy-wise difference: short levy or excess paid

Print produces one A4 sheet.

## Not included

CESS, stamp duty and other provincial charges are outside this core assessment.

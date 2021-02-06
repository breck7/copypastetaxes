# CopyPasteTaxes

Your taxes should be a single text file that is easy
to read. You should be able to use a nice spreadsheet
to do it or a plain old notepad. Filling out your taxes
each year should mostly just be updating a few lines in
that text/file, and copy pasting the whole thing into IRS.gov.
Experts who understand the deductions should be able to provide
snippets that you can copy/paste into your taxes.

The whole thing should take just a few minutes per
year, and you should be able to do it yourself, for
free, if you so choose.

## Support the Crowdfunding campaign!

[If we get to $50,000, this will become a real thing](https://www.indiegogo.com/projects/copypastetaxes/#/)

## Community

- Twitter: https://twitter.com/copypastetaxes
- Subreddit: https://www.reddit.com/r/CopyPasteTaxes

## Proof of Concept

[This will work](https://jtree.treenotation.org/designer/#grammar%0A%20copyPasteTaxesNode%0A%20%20description%20An%20open%20source%20language%20to%20allow%20Americans%20to%20do%20their%20taxes%20using%20simple%20copy%20and%20paste.%20A%20simple%20language%20that%20compiles%20into%20the%20proper%20tax%20forms%20for%20the%20IRS.%0A%20%20root%0A%20%20inScope%20taxReturnNode%0A%20keywordCell%0A%20intCell%0A%20anyCell%0A%20taxReturnNode%0A%20%20inScope%20yearNode%20taxpayerNode%20dependentNode%20w2Node%20childCardCreditNode%20homeOfficeDeductionNode%0A%20%20crux%20taxReturn%0A%20%20cells%20keywordCell%0A%20yearNode%0A%20%20crux%20year%0A%20%20cells%20keywordCell%20intCell%0A%20taxpayerNode%0A%20%20inScope%20nameNode%20cityNode%20stateNode%20ssnNode%0A%20%20crux%20taxpayer%0A%20%20cells%20keywordCell%0A%20nameNode%0A%20%20crux%20name%0A%20%20catchAllCellType%20anyCell%0A%20%20cells%20keywordCell%0A%20cityNode%0A%20%20crux%20city%0A%20%20cells%20keywordCell%20anyCell%0A%20stateNode%0A%20%20crux%20state%0A%20%20cells%20keywordCell%20anyCell%0A%20ssnNode%0A%20%20crux%20ssn%0A%20%20cells%20keywordCell%20anyCell%0A%20dependentNode%0A%20%20inScope%20nameNode%0A%20%20crux%20dependent%0A%20%20cells%20keywordCell%0A%20w2Node%0A%20%20inScope%20nameNode%20totalIncomeNode%0A%20%20crux%20w2%0A%20%20cells%20keywordCell%0A%20totalIncomeNode%0A%20%20crux%20totalIncome%0A%20%20cells%20keywordCell%20intCell%0A%20childCardCreditNode%0A%20%20inScope%20amountNode%0A%20%20crux%20childCardCredit%0A%20%20cells%20keywordCell%0A%20amountNode%0A%20%20crux%20amount%0A%20%20cells%20keywordCell%20intCell%0A%20homeOfficeDeductionNode%0A%20%20inScope%20amountNode%20Node%0A%20%20crux%20homeOfficeDeduction%0A%20%20cells%20keywordCell%0Asample%0A%20taxReturn%0A%20%20year%202020%0A%20%20taxpayer%0A%20%20%20name%20Breck%20Yunits%0A%20%20%20city%20Honolulu%0A%20%20%20state%20Hawaii%0A%20%20%20ssn%20***-***-****%0A%20%20dependent%0A%20%20%20name%20Little%20Yunits%0A%20%20w2%0A%20%20%20name%20Bluth%20Banana%20Company%0A%20%20%20totalIncome%2045000%0A%20%20childCardCredit%0A%20%20%20amount%201200%0A%20%20homeOfficeDeduction%0A%20%20%20amount%2020000%0A%20%20%20)

## The Plan

Here's the plan.

[x] Start the community

[x] Build a dumb little working demo

[x] Make a screencast

[x] Launch a $50K crowdfunding campaign to see if people care

[] If enough people care, build the thing.

[] If not, return to other things.

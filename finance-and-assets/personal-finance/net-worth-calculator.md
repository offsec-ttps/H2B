---
description: Automatically calculate net worth based on assets and liabilities.
---

# Net Worth Calculator

## bolt.dev prompt

```
Build a separate page: "Net Worth Calculator"

Features:

Dropdown menu to add asset types, each with an input field for estimated value.

Asset Types (select one or more):

Real Estate

Family Property

Investments (Stocks, Mutual Funds)

Cash & Bank Savings

Business Ownership

Vehicles (Cars, Bikes, Boats, etc.)

Jewelry & Valuables

Insurance (Surrender Value)

Land

Retirement Funds (EPF, PPF, 401k, etc.)

Digital Assets (Crypto, Domains)

Others (Custom Entry)

Allow users to assign category for each asset:

Liquid

Saving

Long-Term

Show 3 donut charts based on categorization:

Liquid Net Worth

Saving Net Worth

Long-Term Net Worth

Add checkboxes to include/exclude assets from final Total Net Worth calculation.

Display Total Net Worth summary dynamically below charts.
```

<div><figure><img src="../../.gitbook/assets/Screenshot from 2025-05-04 15-54-29.png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot from 2025-05-04 15-53-34.png" alt=""><figcaption><p>Drop down menu showing all the options for networth calcullator</p></figcaption></figure></div>

The replit AI prompt

```
Implement a new web page under Finance > Financial Health for the "Net Worth Calculator".

When the user clicks the "Calculate Net Worth" button in the "Net Worth Calculator" section, open this new page.

Page Title: Net Worth Calculator

Features:

Asset Input Section:

Create a dynamic form to let users add multiple assets.

For each added asset, include:

Dropdown Menu to select Asset Type (support multiple entries).

Input field labeled "Estimated Value" for numerical input.

Asset Types Dropdown Options:

Real Estate

Family Property

Investments (Stocks, Mutual Funds)

Cash & Bank Savings

Business Ownership

Vehicles (Cars, Bikes, Boats, etc.)

Jewelry & Valuables

Insurance (Surrender Value)

Land

Retirement Funds (EPF, PPF, 401k, etc.)

Digital Assets (Crypto, Domains)

Others (custom text field if selected)

Asset Category Assignment:

For each asset, add category selection (dropdown or radio buttons):

Liquid

Saving

Long-Term

Include/Exclude Checkbox:

Add a checkbox labeled "Include in Total" for each asset to control if it's included in the total net worth calculation.

Donut Charts Visualization:

Show 3 donut charts dynamically:

Liquid Net Worth: sum of included assets categorized as Liquid.

Saving Net Worth: sum of included assets categorized as Saving.

Long-Term Net Worth: sum of included assets categorized as Long-Term.

Charts must auto-update on any change in asset values, categories, or inclusion status.

Use any JS charting library like Chart.js.

Total Net Worth Summary:

Below the charts, show dynamic Total Net Worth.

This value is the sum of all assets with "Include in Total" checked.
```

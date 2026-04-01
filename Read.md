# TaxRoot: Income Tax Calculator (India)

TaxRoot is a client-side, interactive web application designed to help users estimate their income tax liability under both the Old and New Tax Regimes in India. It provides a comprehensive set of input fields for various income sources, exemptions, and deductions, offering a clear comparison and a downloadable report.

## Features

- **Dual Regime Comparison:** Easily compare tax liabilities under the Old and New Tax Regimes for the Financial Year.
- **Comprehensive Input Fields:**
  - Income details (Gross Salary, Bonus, Rental Income, Other Income).
  - Exemptions (Professional Tax, HRA, LTA).
  - Detailed **Section 80C** subcategories (PPF, LIC, ELSS, Tuition Fees, Housing Loan Principal, etc.).
  - Other common deductions like **80D** (Medical Insurance), **80CCD(1B)** (NPS), **80G** (Donations with subcategories for 100%, 50%, Children Education, Political Parties).
  - Specialized deductions including **80EE**, **80EEA** (Housing Loan Interest), **80GGC**, **80GGA** (Donations), **80DD**, **80DDB**, **80U** (Disability/Medical Treatment).
  - Interest-related reliefs such as Home Loan Interest, EV Loan Interest (**80EEB**), Savings Interest (**80TTA**), and Senior Citizen Interest (**80TTB**).
  - Exemption for Retrenchment Compensation (**10(10B)**).
- **Real-time Validation:** Input fields include `data-max` attributes for statutory limits, providing immediate visual feedback and error messages if values exceed these limits.
- **Accordion UI:** Deductions and income sections are organized into collapsible accordions for a cleaner and more manageable user interface.
- **Interactive Results:** Displays a clear winner between the Old and New Regimes, estimated tax savings, and an interactive bar chart for visual comparison.
- **PDF Report Generation:** Users can download a detailed PDF report of their tax calculation, including input summaries and regime comparisons.
- **Client-Side Processing:** All calculations are performed directly in the user's browser, ensuring privacy as no personal financial data is sent to a server.
- **Responsive Design:** Optimized for seamless use across various devices, from desktops to mobile phones.
- **Informational Pages:** Includes dedicated pages for "About," "Privacy Policy," and "Tax Tips" to provide additional context and guidance.

## Technologies Used

- **HTML5:** Structure of the web pages.
- **CSS3:** Styling and responsive design.
- **JavaScript:** Core logic for calculations, UI interactions, and data validation.
- **jsPDF:** For generating PDF reports.
- **jsPDF-AutoTable:** Plugin for `jsPDF` to create structured tables in the PDF reports.
- **Chart.js:** For rendering interactive tax comparison charts.

## Getting Started

To use the TaxRoot Income Tax Calculator, simply open the `home.html` or `calculator.html` file in your web browser. No server-side setup or installation is required.

1. **Clone the repository (if applicable):**

    ```bash
    git clone <repository-url>
    cd TaxRoot
    ```

2. **Open in Browser:**
    Navigate to the project directory and open `home.html` or `calculator.html` using your preferred web browser.

## Usage

1. Enter your financial details in the respective input fields on the `calculator.html` page.
2. The calculator will automatically apply statutory caps and validate inputs in real-time.
3. Click "Calculate Now" to see the comparison between the Old and New Tax Regimes.
4. Review the results, including estimated tax liability, savings, and effective tax rate.
5. Optionally, click "Download Report" to save a PDF summary of your calculation.

## Disclaimer

This calculator is intended for estimation and planning purposes only. While efforts have been made to ensure accuracy based on the latest tax laws (FY 2XXX-XX / AY 2XXXX-XX), it should not be considered a substitute for professional tax advice or for official tax filing. Always verify your final tax return with current rules and consult a qualified tax professional.

### Print Formats

Nice print formats and layouts for ERPNext documents

## Print Formats

Print formats for commonly used ERPNext doctypes:

- Sales Invoice
- Purchase Invoice
- Sales Order
- Purchase Order
- Delivery Note
- Payment Entry
- Journal Entry
- Quotation
- Credit Note
- Purchase Receipt
- Sales Quotation

Repository: https://github.com/KiruiElisha/print_formats.git

Install (local bench):

```bash
cd /path/to/bench
bench get-app https://github.com/KiruiElisha/print_formats.git
bench --site <site-name> install-app print_formats
bench --site <site-name> migrate
bench build
bench --site <site-name> clear-cache
```

On Frappe Cloud: add this repo to your project and ensure a post-deploy step runs:

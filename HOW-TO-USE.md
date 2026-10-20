# Paid. — How to use (2 minutes)

**No install, no account, no internet needed.**

1. Save `Paid.html` (the single file) anywhere — Downloads, Desktop, phone.
2. **Double-click it.** It opens in your browser. That's the whole setup.
3. Fill in **Your details** (name, payment instructions, currency, late-fee %, tax %).
4. **New invoice:** invoice #, client, date, due date, then add line items and press **Save invoice**.
5. Your invoice appears under **Portfolio** with a live status: not due / N days late / PAID.

### To chase a late client
- Find the overdue invoice → click **Reminder**.
- The app picks the right stage (1–5) for how late it is and writes the email.
- Click **Copy email**, paste it into Gmail/Outlook, send. Done in 20 seconds.

### To record a payment
- Click **Mark paid** on that invoice. It leaves your open balance immediately.

### To make a PDF invoice
- In a terminal (or ask anyone technical): `node fatura_yazdir.js` creates `ornek_fatura.html`.
  Open it in your browser → **Print → Save as PDF**. A ready PDF is included as `ornek_fatura.pdf`.

### Is my data safe?
- Everything is stored in your own browser (localStorage). Nothing is uploaded. No servers.
- Clearing your browser data clears the list — so if you want a backup, keep the exported text
  of your reminders, or ask for the "export to file" build.

### Changing your price / currency
- Currency: dropdown (USD, EUR, GBP, TRY, AUD, CAD).
- Late fee: default 18%/year. Set **0** if your contracts don't allow late fees.
- Tax/VAT: default 0%. Set it if your country requires it (e.g. 20 for UK VAT).

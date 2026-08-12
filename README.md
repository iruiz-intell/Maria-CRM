# Vida Wellness — Lead Generation Dashboard

**What this is:** A browser-based lead tracker + CRM for managing therapy client acquisition. No login, no server, no fees. Everything stored locally on your computer.

**Who should use it:** Maria (Vida Wellness) + team members who book consultations and manage referral outreach.

---

## 🚀 Quick Start

1. **Open the dashboard:** Double-click `index.html` or open it in any web browser
2. **Add a lead:** Click "+ Add Lead" → fill in name, email, source (Zocdoc/Google/Referral/etc), status
3. **Track progress:** Update status as they move through (new → consult-scheduled → converted)
4. **View KPIs:** Dashboard tab shows total leads, conversion rate, which source is working best

---

## 📊 Dashboard Tabs Explained

### 1. **Dashboard** (Home)
- **KPI Cards:** Total leads this month, free consults scheduled, new clients booked, conversion rate
- **Leads by Source:** Visual breakdown (how many came from Zocdoc vs. referrals vs. Google, etc.)
- **Weekly Priority Checklist:** Tasks for Mon–Fri (Zocdoc update, referral emails, GBP post, etc.)

### 2. **Leads** (Lead Tracker)
- **Add new leads:** Name, email, phone, source (dropdown), status, consult date
- **Search & filter:** Find leads by name/email/phone or filter by status (new, scheduled, converted, no-show)
- **Edit/Delete:** Modify lead info or remove duplicates
- **Track conversion:** Update status as leads book consults or convert to clients

**Lead Status Options:**
- `New` — just added, haven't reached out yet
- `Consult Scheduled` — free 15-min call is on the calendar
- `Converted` — booked ongoing therapy sessions
- `No-Show` — scheduled but didn't attend

### 3. **Referral Partners** (Outreach Tracking)
- **Add referral targets:** Pre-loaded with 19 OB/GYNs, DV advocates, immigration attorneys, etc.
- **Track outreach status:** Pending Contact → Contacted → Meeting Scheduled → Active
- **Log last contact date:** Know when to follow up
- **Search by org/email/phone:** Find partners quickly

**Status Options:**
- `Pending Contact` — haven't reached out yet
- `Contacted` — sent intro email, awaiting response
- `Meeting Scheduled` — 15-min call booked
- `Active` — regular referral relationship, send monthly check-ins

### 4. **Weekly Tasks** (Checklist)
- Ready-to-copy checklist for your 2.5–3 hour/week lead gen routine
- **Monday (20 min):** Zocdoc update + review + verify active status
- **Tuesday (30 min):** Send/follow-up referral emails (6–7 per week)
- **Thursday (20 min):** Post Google Business Profile update
- **Friday (15 min):** Update lead tracker + check automation logs
- **End of month (15 min):** Calculate metrics, identify top source

### 5. **Settings** (Config & Export)
- **Practice Info:** Phone, email, Calendly URL (auto-populates CTA links)
- **Export Leads:** Download all leads as CSV (for backup or analysis)
- **Export Referral Partners:** Download all partners as CSV
- **Clear Data:** Nuclear option (⚠️ cannot undo — always export first)

---

## 💾 How Data Is Stored

**Everything lives in your browser's local storage** — no server, no cloud, no login:
- ✅ Fast (instant load)
- ✅ Private (stays on your computer)
- ✅ Works offline
- ⚠️ Only accessible on THIS browser/device
- ⚠️ Cleared if you uninstall the browser or clear browser cache

**Backup your data monthly:**
1. Go to Settings tab
2. Click "📥 Export Leads" → saves `vida-wellness-leads.csv`
3. Click "📥 Export Referral Partners" → saves `vida-wellness-referral-partners.csv`
4. Store CSVs in a folder or Google Drive (safety net if browser clears)

---

## 📝 Monthly Workflow

### Week 1–3: Active Outreach
1. **Monday:** Log into Zocdoc, post update, check reviews
2. **Tuesday:** Send 6–7 referral partner emails (use template from playbook)
3. **Thursday:** Write & post Google Business Profile update
4. **Friday:** Update dashboard with any new leads

### Week 4: Monthly Review
1. **Export lead data:** CSV backup
2. **Calculate KPIs:**
   - Total leads this month
   - Consults scheduled (% conversion from leads)
   - Actual conversions to clients
   - Which source brought most leads?
3. **Adjust plan:** Double down on top source, drop underperformers

---

## 🔍 Key Features

### Lead Tracking
- **Add unlimited leads** — name, email, phone, source, status, notes
- **Search/filter** — find leads by any field, filter by status
- **Bulk update** — edit status as they progress (consult → converted)
- **Notes field** — track why they didn't convert, follow-up date, preferences

### Referral Partner Management
- **19 pre-loaded targets** — OB/GYNs, DV/SA advocates, immigration attorneys (edit/delete/add)
- **Contact tracking** — log when you last reached out, next follow-up date
- **Category filter** — view only OB/GYNs or only attorneys, etc.
- **Active status** — once a partner starts referring, mark as "Active" for monthly check-ins

### Automation
- **KPI auto-calculation** — dashboard updates totals + conversion rate automatically
- **Source breakdown** — pie chart of which channels drive leads
- **CSV export** — download all data for reporting or backup

---

## ❓ FAQ

**Q: Can my team see the same dashboard?**  
A: Not with local storage. Each browser/device has its own copy. For shared access, you'd need to:
- Share one laptop/tablet in the office
- Or export/import CSVs weekly to sync
- Or upgrade to a cloud version (not included)

**Q: What if I clear my browser cache?**  
A: All data disappears. **Export CSVs monthly to back up.**

**Q: Can I import old leads from a spreadsheet?**  
A: Not directly. Copy/paste into the form or contact me to build an import tool.

**Q: How do I know if a referral partner booked a meeting?**  
A: Mark status as "Meeting Scheduled" and add the date + notes. Manually track in calendar or CRM.

**Q: Can I track which provider (Maria/Berline/etc.) each lead was matched to?**  
A: Not in the current version. Add it in the "Notes" field (e.g., "Maria-matched 8/15").

**Q: Does this integrate with Zocdoc/SimplePractice/Calendly?**  
A: Not yet. Manual entry for now. (Could be built as a future feature.)

---

## 🛠️ Troubleshooting

**Dashboard won't open:**
- Make sure you're opening `index.html` directly in a browser (not in a text editor)
- Try a different browser (Chrome, Safari, Firefox)

**Data disappeared:**
- Did you clear browser cache? Data is gone if you did.
- Check if you're in a different browser/device (each has its own storage)
- Check your CSV backups if you exported

**Export button doesn't work:**
- Make sure you have at least 1 lead or 1 referral partner entered
- Try a different browser
- Check if you have permission to download files

**Search/filter not working:**
- Refresh the page (F5)
- Make sure you're typing in the search box, not a filter dropdown

---

## 📱 Mobile Use

The dashboard works on phones/tablets but:
- Small screen = harder to see tables
- Better for adding quick entries than reviewing data
- **Recommended:** Use on desktop/laptop for monthly reviews

---

## 🎯 Best Practices

1. **Add leads same day** — capture info while fresh (source, how they found you, etc.)
2. **Update status weekly** — don't let leads stale in "new" status
3. **Follow up on referral partners within 10 days** — cold emails lose momentum
4. **Export CSVs monthly** — automatic backup, also good for reporting
5. **Review KPIs end of month** — identify what's working, adjust next month

---

## 🔐 Privacy & Security

- **All data stays on your device** — no data sent to servers
- **No login required** — but anyone with access to your browser can see leads
- **No encryption** — if you need encrypted access, use a different tool
- **CSV exports** — store in Google Drive or secure folder

---

## 📞 Questions?

- **How to use it?** See the walkthroughs above
- **Data lost?** Check your CSV backups
- **Want to add features?** (Import tool, cloud sync, Zocdoc integration) → contact me

---

**Dashboard ready to use. Start adding leads today.**

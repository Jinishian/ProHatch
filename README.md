# 🐔 Hatchery Manager

**Professional invoicing, bookkeeping, production tracking, and calendar management for poultry and small-scale hatcheries.**

**Free and Open Source Software (MIT License)**

---

## What is Hatchery Manager?

Hatchery Manager is a **free, open-source, single-file tool** designed specifically for hatchery owners and small poultry operations. Track your inventory, invoices, breeding cycles, production metrics, and financial performance—all without sending your data to external servers.

### Key Philosophy

✅ **100% Private** — All data stored locally on your device. No cloud accounts, no tracking, no data collection.

✅ **Open Source (MIT License)** — Complete source code visible and modifiable. Use, fork, modify, distribute freely.

✅ **Self-Contained** — Single HTML file. No installation, no dependencies, no subscriptions.

✅ **Cross-Platform** — Works on desktop, tablet, and mobile browsers.

✅ **Free Forever** — No ads, no premium tiers, no surprise charges.

---

## Features

### 📦 Inventory Management
- Track birds by breed, species, and quantity
- Automatic total value calculations
- Date-stamped inventory entries
- Search and filter by type

### 💰 Invoicing System
- Professional invoice generation
- Customer tracking and sales history
- Configurable tax rates
- Print-ready invoice formatting
- Automatic income recording

### 📊 Bookkeeping & Transactions
- Income and expense tracking by category
- Transaction history with date sorting
- Profit/Loss statement by category
- Real-time financial summaries

### 🐣 Production Tracking
- Hatch cycle management by breed
- Eggs set → chicks hatched tracking
- Automatic hatch success rate calculation
- Cost-per-chick analysis
- Feed cost and overhead tracking

### 📅 Calendar & Planning
- Visual monthly calendar
- Three event types: Hatch dates, Breeding cycles, Tasks
- Upcoming events list with details
- Perfect for planning seasonal operations

### 📈 Advanced Analytics
- Production metrics dashboard
- Hatch success rate by breed (charts)
- Cost-per-chick breakdowns (visual analysis)
- Revenue vs. costs comparison
- CSV export for all production data

### 🎨 Customizable Themes
- 7 pre-built color schemes (Earthy, Ocean, Forest, Sunset, Berry, Slate, Mint)
- Custom color picker for brand matching
- Theme preference saved to device

---

## Getting Started

### Installation

1. **Clone or download** this repository
2. **Open** `hatchery-manager.html` in any modern web browser
3. **Start using** — no setup, installation, or internet required!

### First Time Setup

1. Click through each tab to familiarize yourself
2. Start in the **Inventory** tab to log your current birds/stock
3. Use **Invoicing** to create your first customer invoice
4. Track **Production** cycles as you breed
5. Monitor **Analytics** for insights

### Data Backup

⚠️ **Important**: Regularly export your data using the **Reports** tab.
- Export as CSV for analysis in Excel/Sheets
- Keep backups on your computer or cloud storage you control

---

## How to Use

### Inventory Tab
1. Select item type (Chicks, Eggs, Feed, etc.)
2. Enter breed and quantity
3. Set unit cost
4. Click "Add to Inventory"
→ Automatic total value calculation

### Invoicing Tab
1. Enter customer name and date
2. Describe items (e.g., "10 Rhode Island Red Chicks")
3. Set quantity and unit price
4. Add tax if applicable
5. Click "Create Invoice"
→ Invoice saved + automatically recorded as income

### Production Tab
1. Log breed, species, eggs set, and expected hatch date
2. Once chicks hatch, enter number hatched
→ Hatch success rate calculated automatically
3. Record feed costs and other expenses
4. Set your sale price per chick
→ Cost-per-chick calculated

### Calendar Tab
1. Click a date or use "Add Event"
2. Choose event type (Hatch/Breed/Task)
3. Add title and optional notes
4. Click "Add Event"
→ Event appears on calendar and upcoming list

### Analytics Tab
- View production metrics and financial KPIs
- See hatch success rates by breed
- Analyze costs and profitability
- Export production data as CSV

---

## Privacy & Security

- ✅ **No servers** — data never leaves your device
- ✅ **No analytics** — no tracking, no pixels, no third-party services
- ✅ **No accounts** — no login, no passwords
- ✅ **Transparent** — all code visible for inspection
- ✅ **You own your data** — export anytime

---

## Data Storage

All data is stored in your browser's **localStorage** (a secure, local storage mechanism). To see your data:
1. Open browser DevTools (F12)
2. Go to Application → Local Storage
3. Look for entries labeled "hatcheryData" and "hatcheryTheme"

To back up your data:
- Use the **Reports** tab to export CSV files
- (v2 will include JSON export for easy cross-device sync)

---

## System Requirements

- **Browser**: Any modern browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Storage**: ~500 KB per year of data (typical operation)
- **Internet**: Not required (works entirely offline)

---

## License

This project is licensed under the **MIT License** - see the LICENSE file for details.

**In short**: You are free to use, modify, and distribute this software for any purpose, commercial or personal, as long as you include the license and copyright notice.

### MIT License Summary
- ✅ Use commercially
- ✅ Modify the code
- ✅ Distribute freely
- ✅ Use privately
- ⚠️ Include license notice
- ❌ No warranty provided

---

## Contributing

Found a bug? Have a feature request? Contributions are welcome!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

---

## Roadmap

### ✅ v1.0 (Current)
- Core invoicing and bookkeeping
- Inventory management
- Production tracking
- Calendar and event planning
- Analytics and charts
- Theme customization
- CSV data export

### 🔄 v2.0 (Planned)
- **Cross-device sync**: Export/import data as JSON
- **Batch operations**: Bulk invoice generation
- **Advanced reporting**: Custom date ranges, filtered reports
- **Photo documentation**: Attach images to production cycles
- **Notes & history**: Full audit trail of changes
- **Multi-user support**: Team access with change tracking

### 📋 Future Considerations
- Integrations with other farm management tools
- Mobile app wrapper for offline-first performance
- Template management for repeating invoices
- Health/genetics tracking for individual birds
- Community sharing of breed data
- Compliance helpers for agricultural licensing

---

## Troubleshooting

### Data is empty when I open the app
- Check that you're using the same browser and device
- Browser privacy mode clears localStorage—use normal browsing
- Try exporting/importing from a backup

### Dates not calculating correctly
- Ensure your computer date/time is accurate
- Expected hatch date is typically 21 days for chickens, 17 for quail

### Charts not showing in Analytics
- Try refreshing the page
- Ensure you have at least one production record with costs entered
- Check browser console (F12) for errors

### Can't export data
- Check that pop-ups aren't blocked in your browser
- Try a different browser if issues persist

---

## FAQ

**Q: Can I use this on my phone?**
A: Yes! Open the HTML file in your phone's web browser (Safari on iPhone, Chrome on Android). Data syncs on same device. Multi-device sync planned for v2.

**Q: What if I want to use this on multiple devices?**
A: Export your data from one device (as CSV), then manually re-enter or wait for v2 which will have JSON import/export for easy syncing.

**Q: Can I modify the code?**
A: Absolutely! It's open source under MIT license. You can customize colors, add fields, modify calculations—the code is readable and commented.

**Q: Is there a way to share data with team members?**
A: Not yet in v1. Planned for v2. For now, export and share CSV files.

**Q: How do I reset my data?**
A: Use the "Clear All Data" button in Reports (⚠️ this is permanent—export first!).

**Q: Can I sell birds using this?**
A: Yes! The Invoicing tab is designed exactly for that. Track customers, create professional invoices, and monitor revenue.

**Q: How much does this cost?**
A: **Nothing!** Hatchery Manager is completely free and open source. No subscriptions, no ads, no premium tiers.

---

## Support & Community

- **Issues**: Found a bug? Open an issue on GitHub
- **Feature requests**: Have an idea? Start a discussion
- **Contributions**: Want to help? Pull requests welcome!
- **Share**: If you find this useful, share it with other hatchery owners

---

## Credits

Built with ❤️ for poultry enthusiasts and small-scale hatchery operations.

**Author**: Derek Jinishian  
**Repository**: https://github.com/your-username/hatchery-manager

---

## Disclaimer

This software is provided "AS IS" without warranty of any kind. Use at your own risk. Always keep backups of your data. The author is not responsible for any data loss or issues arising from the use of this software.

---

**Made with ❤️ for the hatchery community. Free. Open. Forever.**

*Last updated: 2026*

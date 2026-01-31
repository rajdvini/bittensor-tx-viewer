# ⚡ Bittensor Transaction Viewer

A sleek, modern web application for viewing and exporting Bittensor blockchain transactions with Awaken CSV format support.

![Bittensor TX Viewer](https://img.shields.io/badge/Blockchain-Bittensor-00D4AA?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## 🚀 Features

- **Wallet Lookup**: Enter any Bittensor wallet address to fetch transactions
- **Real-time Data**: Uses official Bittensor Subscan API
- **Beautiful UI**: Cyberpunk-inspired design with smooth animations
- **CSV Export**: Download transactions in Awaken format for tax/accounting
- **Responsive**: Works perfectly on desktop, tablet, and mobile
- **Fast & Lightweight**: Single HTML file, no dependencies needed

## 📸 Preview

Live Demo: [Your GitHub Pages URL will be here]

## 🛠️ Tech Stack

- Pure HTML5, CSS3, and Vanilla JavaScript
- No frameworks or build tools required
- Bittensor Subscan API integration
- Google Fonts (JetBrains Mono, Space Mono)

## 📦 Installation & Deployment

### Option 1: GitHub Pages (Recommended)

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/bittensor-tx-viewer.git
   cd bittensor-tx-viewer
   ```

2. **Push to your GitHub repository**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Click "Save"
   - Your site will be live at: `https://YOUR-USERNAME.github.io/bittensor-tx-viewer/`

### Option 2: Local Development

Simply open `index.html` in your browser:
```bash
open index.html
# or
python -m http.server 8000
# then visit http://localhost:8000
```

### Option 3: Other Hosting Platforms

Deploy to any static hosting service:
- **Vercel**: `vercel --prod`
- **Netlify**: Drag and drop the folder
- **Cloudflare Pages**: Connect your GitHub repo
- **AWS S3**: Upload to S3 bucket with static hosting

## 💻 Usage

1. **Enter a Bittensor wallet address** (starts with `5...`)
   - Example: `5GrwvaEF5zXb26Fz9rcQpDWS57CtERHpNehXCPcNoHGKutQY`

2. **Click "Fetch Transactions"**
   - The app will retrieve up to 100 recent transactions

3. **View transaction details** in the table:
   - Transaction hash, block number, timestamp
   - From/To addresses
   - Amount in TAO with +/- indicators
   - Transaction fees
   - Success/Failed status

4. **Download CSV** for accounting:
   - Awaken format compatible
   - Includes all transaction metadata
   - Ready for import into tax software

## 📋 CSV Format (Awaken Compatible)

The exported CSV includes these fields:
- Date (ISO 8601)
- Type (deposit/withdrawal)
- Base Currency (TAO)
- Base Amount
- Fee Currency & Amount
- From/To Addresses
- Blockchain (Bittensor)
- Transaction ID (Hash)
- Description (Block number)

## 🔧 API Information

This application uses the **Bittensor Subscan API**:
- Endpoint: `https://bittensor.subscan.io/api/v2/scan/transfers`
- Method: POST
- No API key required
- Rate limits apply (standard Subscan limits)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

## 📄 License

MIT License - feel free to use this for commercial projects!

## 🎯 Roadmap

- [ ] Pagination for >100 transactions
- [ ] Filter by date range
- [ ] Multiple wallet comparison
- [ ] Balance tracking over time
- [ ] Export to other formats (JSON, Excel)
- [ ] Dark/Light theme toggle

## 👨‍💻 Developer

Built for the Bittensor community with ❤️

If you find this useful, consider:
- ⭐ Starring the repository
- 🔗 Sharing with others
- 💰 Tipping: [Your wallet address]

## 🐛 Known Issues

- Subscan API occasionally rate limits requests
- Historical data limited to last 100 transactions per query
- Some mobile browsers may have CSV download issues (use desktop)

## 📞 Support

For issues or questions:
- Open a GitHub issue
- Contact: [Your contact info]

---

**Note**: This is an independent project and is not affiliated with or endorsed by Bittensor or Opentensor Foundation.

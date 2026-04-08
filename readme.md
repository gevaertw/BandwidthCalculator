# Bandwidth Calculator

### AKA "How long until this massive file finishes transferring and I can go get coffee?"

Look, every bandwidth calculator on the internet is either:
- Covered in ads for VPNs you don't need
- Asking you to sign up for a newsletter about throughput optimization
- Built in Flash (rest in peace, old friend)

So I vibe-coded my own. One HTML file. No dependencies. No build step. No npm install that downloads half the internet. Just open it in your browser like it's 1999.

### What does it do?

It answers the three eternal questions of data transfer:
1. **"How long will this take?"** — Enter size + bandwidth, get time. Revolutionary.
2. **"How much can I transfer?"** — Enter bandwidth + time, get size. Groundbreaking.
3. **"How fast does my connection need to be?"** — Enter size + time, get bandwidth. Nobel Prize pending.

It even has an **efficiency slider** (default 80%) because let's be honest — your "1 Gbps" connection has never once in its life actually done 1 Gbps.

### Features

- Zero dependencies (the `node_modules` folder has hurt me for the last time)
- Works offline (perfect for when your bandwidth is... well... zero)
- Single HTML file (email it to your colleagues, they'll think you're a wizard)
- Auto-calculates as you type (because clicking a "Calculate" button is *so* 2005)
- Microsoft Fluent UI-inspired design (looks professional in screenshots for management)

### Disclaimer

I am absolutely, categorically, 100% **not responsible** if you:
- Underestimate a transfer and miss a deadline
- Overestimate your bandwidth and promise a client something impossible
- Get a surprise cloud egress bill that makes your CFO cry
- Discover your ISP has been lying to you this whole time

Use at your own risk. Math doesn't have feelings, but your wallet does.
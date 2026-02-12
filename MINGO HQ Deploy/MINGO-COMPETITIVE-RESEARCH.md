# MINGO Tickets — Competitive Research Document
## Last Updated: February 2026

---

# MINGO OVERVIEW (Reference Baseline)

- Founded: 2018
- Blockchain: Hedera Hashgraph
- Fee Structure: 3.5% flat
- Technology: PWA (Progressive Web App — no app download required)
- Geography: 54 countries
- Key Features: NFT tickets, anti-scalping via resale caps, artist royalties on resale, anti-fraud
- Partners: WBC, Fight Circus, African Boxing League, Comic-Con Ireland, Napster AI, Tyson Fury, Goldstar Promotions
- URLs: tickets.mingo.com, mingo.com
- Philosophy: "Hides the blockchain so well it seems Web2"

---

# WEB2 COMPETITORS

---

## 1. TICKETMASTER / LIVE NATION

**Overview:**
- The dominant global ticketing platform, founded 1976 (Ticketmaster), merged with Live Nation in 2010
- HQ: Beverly Hills, California
- Parent company Live Nation is also the world's largest concert promoter and venue operator
- Currently facing DOJ antitrust lawsuit seeking breakup

**Fee Structure:**
- Total fees to consumers average 24-44% of ticket face value
- Ticketmaster itself keeps approximately 5-7% of the all-in price
- Venues typically retain over two-thirds of the service fee
- Additional facility charge set by venues
- Order processing fee per order
- $16.4 billion in total fees charged (per lawsuit data)
- Fees are opaque and vary by event, venue, and promoter deal

**Features:**
- Primary ticket sales
- Secondary marketplace (fan-to-fan resale)
- Verified Fan presale system (demand-based access)
- Dynamic pricing
- Interactive seat maps / reserved seating
- Mobile ticketing via app
- Transfer and resale built-in
- Venue/promoter analytics dashboard
- Marketing tools and email campaigns
- API for third-party integrations
- White-label solutions for venues
- Box office / POS systems
- Season ticket management
- VIP and premium experience packages
- All-in pricing option (recently pushed)
- Accessibility features

**Geography:**
- Operates in 30+ countries
- Dominant in USA (63% of online ticket buyers, 84% market share by volume)
- Strong in Canada, UK, Europe, Australia
- Expanding in Latin America and Asia

**Technology:**
- Traditional Web2 infrastructure
- Native mobile apps (iOS, Android)
- Web platform
- SafeTix rotating barcode technology (anti-screenshot fraud)
- No blockchain

**Scale:**
- ~500 million tickets sold annually
- 400,000+ events per year
- Powers ticketing for most major venues in the US
- ~80% US primary ticketing market share

**Key Partnerships/Clients:**
- NFL, NBA, NHL, MLB venues
- Major concert venues and arenas globally
- AEG venues (formerly, now shifting to AXS)
- Coachella (some years), Bonnaroo, Lollapalooza

**Strengths:**
- Unmatched scale and market dominance
- Exclusive venue contracts lock in supply
- Integrated promoter + venue + ticketing ecosystem
- Brand recognition (everyone knows Ticketmaster)
- Sophisticated anti-fraud tech (SafeTix)
- Deep analytics and data capabilities

**Weaknesses:**
- Consumer hatred is near-universal due to fees
- Under active DOJ antitrust lawsuit
- Fees are opaque and perceived as exploitative
- Dynamic pricing controversy (surge pricing)
- Bot problems persist despite Verified Fan
- No blockchain verification
- Monopolistic practices alienate artists and fans
- Legacy tech stack in many areas
- Poor customer service reputation

---

## 2. EVENTBRITE

**Overview:**
- Self-service event management and ticketing platform, founded 2006
- HQ: San Francisco, California
- Acquired by Bending Spoons (December 2025)
- Strongest in mid-size and community events

**Fee Structure:**
- Essentials plan: 3.5% + $1.59 per ticket (US)
- Professional plan: 3.7% + $1.79 per ticket
- Payment processing: 2.9% additional
- Total effective fee: 6-8% plus fixed costs per ticket
- Free events: free to list (since September 2024)
- Organizer can absorb fees or pass to buyer

**Features:**
- Primary ticket sales
- Event page creation and hosting
- Promotional tools (social sharing, email marketing, discount codes)
- Attendee management and check-in
- Analytics and reporting dashboard
- API for integrations
- Embeddable widgets for external sites
- Multi-event management
- Reserved seating (limited)
- Mobile app for organizers and attendees
- Stripe/PayPal payment processing
- Waitlist functionality
- Virtual event support
- CRM-lite features (attendee data)
- No secondary marketplace (no resale)

**Geography:**
- Operates globally in 180+ countries
- Strongest in US, UK, Australia, Canada
- Multi-language, multi-currency support

**Technology:**
- Web platform
- Native mobile apps (iOS, Android)
- No blockchain
- Standard Web2 tech stack

**Scale:**
- 87 million average monthly active users (Q4 2024)
- 21.6 million paid tickets per quarter
- Second most-used ticketing platform in US (31% of online ticket buyers)
- Millions of events hosted annually

**Key Partnerships/Clients:**
- Primarily self-service (SMB and community organizers)
- TEDx events, charity runs, food festivals, conferences
- No major exclusive venue deals

**Strengths:**
- Extremely easy to use (self-service)
- Large organic audience / discovery marketplace
- Global reach (180+ countries)
- Strong for free and community events
- Good API and integrations
- Brand recognition in mid-market

**Weaknesses:**
- Total fees (6-8%) are significantly higher than MINGO's 3.5%
- No secondary market / resale
- No anti-scalping features
- No blockchain or NFT capabilities
- Limited reserved seating
- Not designed for large-scale venues
- Being acquired — future uncertain under Bending Spoons
- No anti-fraud beyond basic measures
- No artist royalties on resale

---

## 3. DICE (acquired by Fever, June 2025)

**Overview:**
- Fan-first mobile ticketing platform, founded 2014
- HQ: London, UK
- Acquired by Fever (live entertainment discovery platform) in June 2025
- Known for transparent pricing and anti-scalping stance

**Fee Structure:**
- All-in pricing model (fee included in displayed price)
- Booking fee split between DICE and event organizer
- Estimated ~10% platform fee (included in ticket price)
- No hidden fees at checkout

**Features:**
- Primary ticket sales (mobile-first)
- Built-in waiting list (returns tickets to queue, not resale)
- Anti-scalping (no resale at markup — returns go back to queue at face value)
- Discovery algorithm (social media-like recommendations)
- All-in transparent pricing
- Mobile-only ticketing (app required)
- Analytics for organizers
- Guest list management
- No secondary marketplace (anti-scalping by design)
- Push notifications and event recommendations
- Social features (see what friends are attending)

**Geography:**
- UK (primary), US, Europe (France, Germany, Italy, Spain)
- Expanding globally via Fever acquisition
- Strong in club/music scene in London and other major cities

**Technology:**
- Native mobile app (iOS, Android) — app-only, no web purchasing
- No blockchain
- Standard Web2 tech

**Scale:**
- Millions of users (exact numbers not public)
- Focused on music, clubs, cultural events
- Smaller than Ticketmaster but significant in indie/club scene

**Key Partnerships/Clients:**
- Major music venues, festivals, promoters
- Fabric (London), Brooklyn Steel, various independent venues
- Not tied to specific venue chains

**Strengths:**
- Fan-first philosophy (anti-scalping, transparent pricing)
- Excellent mobile UX
- Strong brand in indie/alternative music
- Discovery algorithm drives engagement
- Waiting list system is genuinely anti-scalp

**Weaknesses:**
- App-only (requires download — MINGO's PWA is more accessible)
- ~10% effective fee is much higher than MINGO's 3.5%
- No secondary market at all (some fans want fair resale)
- No blockchain or NFT features
- No artist royalties on resale
- No reserved seating
- Limited to music/culture events
- No white-label or API for organizers
- Now owned by Fever — strategy may shift

---

## 4. SEE TICKETS

**Overview:**
- Major UK and European ticketing platform, founded 1980s (as a division of various parent companies)
- Currently owned by Vivendi (See Tickets is part of See Group)
- HQ: Nottingham, UK
- Strong in UK festival and live event ticketing

**Fee Structure:**
- Service fees typically 10-15% of face value
- Additional delivery/booking fees
- Fees vary by event and promoter agreement
- Not publicly transparent about exact percentages

**Features:**
- Primary ticket sales
- Secondary ticket exchange (some events)
- Reserved seating and GA
- Analytics and reporting
- White-label solutions for promoters/festivals
- Box office and POS
- Access control and scanning
- Marketing tools
- API integrations
- Mobile-responsive web (no dedicated app)

**Geography:**
- UK (dominant for festivals), France, Germany, Netherlands, US (expanding)
- Key market is UK festival circuit

**Technology:**
- Web-based platform
- No blockchain
- Standard Web2 infrastructure
- No dedicated mobile app

**Scale:**
- One of the top 3 ticketing platforms in the UK
- Handles major UK festivals (Glastonbury, Download, etc.)
- Millions of tickets annually

**Key Partnerships/Clients:**
- Glastonbury Festival
- Download Festival
- Latitude, Reading & Leeds (historically)
- Various UK promoters and festivals

**Strengths:**
- Deep roots in UK festival market
- White-label capabilities
- Box office and on-site solutions
- Strong promoter relationships in UK

**Weaknesses:**
- Fees much higher than MINGO
- Outdated web interface compared to modern platforms
- No blockchain, NFT, or anti-scalping tech
- No artist royalties
- Limited geographic reach outside UK/Europe
- No mobile app
- Less innovative than newer platforms

---

## 5. AXS (AEG)

**Overview:**
- Ticketing platform owned by AEG (Anschutz Entertainment Group), launched 2014
- HQ: Los Angeles, California
- Second-largest ticketing company globally after Ticketmaster
- Built as AEG's alternative to Ticketmaster

**Fee Structure:**
- Fees vary by venue and event
- Typically 15-25% of face value (similar to Ticketmaster)
- All-in pricing promotions occasionally offered
- Not publicly transparent about exact fee structure

**Features:**
- Primary ticket sales
- Fan-to-fan resale marketplace (Flash Seats)
- Mobile ticketing (digital tickets)
- Reserved seating and interactive maps
- AXS Invite (social ticket distribution)
- Analytics and venue management
- Season ticket management
- VIP/premium packages
- API integrations
- White-label for venues
- Box office and POS
- Marketing tools
- Mobile app (iOS, Android)
- Fraud detection

**Geography:**
- US (primary), UK (The O2), Europe, Asia, Australia
- 1,300+ venue and brand partnerships globally
- Strong in AEG-owned and operated venues

**Technology:**
- Web and native mobile apps
- Flash Seats digital delivery
- No blockchain
- Standard Web2

**Scale:**
- 1,300+ venue/brand clients
- Millions of tickets sold annually
- Clients include LA28 Olympics, Coachella, Red Rocks, The O2, BNP Paribas Open

**Key Partnerships/Clients:**
- LA28 Olympic and Paralympic Games
- Coachella Music Festival
- Red Rocks Amphitheatre
- The O2 (London)
- Japan's B.League
- WM Phoenix Open

**Strengths:**
- Backed by AEG (massive resources and venues)
- Growing alternative to Ticketmaster
- Strong venue relationships
- Good mobile experience
- Flash Seats fan-to-fan resale

**Weaknesses:**
- Fees comparable to Ticketmaster (15-25%)
- Tied to AEG venues primarily
- Less market share than Ticketmaster
- No blockchain or NFT
- No anti-scalping beyond basic measures
- No artist royalties on resale
- Still perceived as "big ticketing"

---

## 6. UNIVERSE (formerly Ticketfly connection)

**Overview:**
- Event ticketing and management platform
- Originally independent, operated as self-service ticketing
- HQ: San Francisco area
- Positioned as simpler, lower-fee alternative to Eventbrite

**Fee Structure:**
- Service fee per paid ticket (varies by country)
- All-in pricing in countries outside US
- Generally lower than Eventbrite
- Uses Stripe for payment processing

**Features:**
- Primary ticket sales
- Embeddable ticket widgets
- Event page creation
- Promotional tools (discount codes, affiliates)
- Attendee management
- Check-in tools
- Analytics and reporting
- API
- Multi-event management
- Refund management
- Mobile-responsive web

**Geography:**
- Global (available in most countries)
- Primarily US-focused

**Technology:**
- Web-based
- No blockchain
- Standard Web2

**Scale:**
- Smaller than Eventbrite
- Used by food festivals, community events, mid-size events

**Key Partnerships/Clients:**
- Community organizers, nonprofits, mid-size events
- No major exclusive venue deals

**Strengths:**
- Simple to use
- Lower fees than Eventbrite
- Good embeddable widgets
- Stripe integration

**Weaknesses:**
- Small market presence
- No secondary market
- No blockchain/NFT
- No anti-scalping
- No reserved seating
- No artist royalties
- Limited scale and brand recognition

---

## 7. TICKET TAILOR

**Overview:**
- Independent, low-cost ticketing platform, founded 2012
- HQ: London, UK
- Positioned as the affordable alternative to Eventbrite
- Independent and bootstrapped

**Fee Structure:**
- Pay-as-you-go: £0.60 / $0.70 per ticket (flat, regardless of price)
- Subscription plans available (monthly fee + lower per-ticket)
- Free events: free (under 2,000 tickets/year)
- No percentage-based fees
- Payment processing separate (Stripe fees apply)

**Features:**
- Primary ticket sales
- Embeddable widgets (sell on your own site)
- Seating charts / reserved seating
- Check-in app
- Discount codes and promo tools
- Waitlists
- Custom questions on checkout
- Analytics
- Zapier integrations
- White-label (customers stay on your site)
- Multi-event management
- Refund management
- No secondary marketplace

**Geography:**
- Global (web-based, available anywhere)
- Strong in UK, US, Australia, Canada

**Technology:**
- Web-based platform
- Check-in mobile app
- No blockchain
- Standard Web2

**Scale:**
- Used by thousands of organizers
- Smaller than Eventbrite but growing
- Popular with small-to-mid-size events

**Key Partnerships/Clients:**
- Independent organizers, small businesses, nonprofits
- No major venue exclusives

**Strengths:**
- Extremely low fees (flat rate, not percentage-based)
- On cheaper events, can be more expensive than MINGO's 3.5%; on expensive events, much cheaper
- White-label (customers stay on organizer's domain)
- Simple and clean UX
- Data stays with the organizer
- Independent company (no VC pressure)
- Reserved seating capability

**Weaknesses:**
- No secondary market
- No blockchain/NFT
- No anti-scalping
- No artist royalties
- No discovery marketplace (no audience)
- Small brand awareness
- No box office/POS
- No marketing/CRM tools beyond basics

---

## 8. HUMANITIX

**Overview:**
- Not-for-profit ticketing platform, founded 2016
- HQ: Sydney, Australia
- 100% of profits donated to charity (children's education)
- B-Corp certified, social enterprise model

**Fee Structure:**
- Free events: completely free
- Paid events: ~5% booking fee (example: $5 on a $100 ticket)
- Nonprofits get reduced rates (cost price)
- Payment processing included in booking fee
- Fees competitive with Eventbrite

**Features:**
- Primary ticket sales
- Event page creation
- Check-in app
- Analytics and reporting
- Email marketing tools
- Embeddable widgets
- Discount codes and promo
- Seating charts (basic)
- Multi-event management
- Attendee data and CRM-lite
- Donation integration (charity upsell at checkout)
- Virtual event support
- No secondary marketplace

**Geography:**
- Australia (primary), US, UK, New Zealand, Canada
- Expanding globally

**Technology:**
- Web-based platform
- Mobile check-in app
- No blockchain
- Standard Web2

**Scale:**
- Growing rapidly, especially in Australia
- Used by universities, nonprofits, community events, and increasingly commercial events
- Millions raised for charity through booking fees

**Key Partnerships/Clients:**
- TEDx events, universities, charity organizations
- Australian government events
- Community and cultural organizations

**Strengths:**
- Social impact story (100% profits to charity)
- Competitive fees
- Good for nonprofit/charity events
- Growing brand awareness
- Feel-good factor for organizers and attendees

**Weaknesses:**
- Fees still higher than MINGO (5% vs 3.5%)
- No secondary market
- No blockchain/NFT
- No anti-scalping
- No artist royalties
- Limited geographic presence (mostly Aus/UK/US)
- Not designed for large-scale venues
- No white-label

---

## 9. TICKETSWAP (Secondary Market)

**Overview:**
- Fair-priced secondary ticket marketplace, founded 2012
- HQ: Amsterdam, Netherlands
- Anti-scalping secondary platform (cap at 20% above face value)

**Fee Structure:**
- Buyer pays: 7% service fee + 3% transaction fee (10% total)
- Seller pays: nothing (or minimal)
- Price cap: maximum 20% above original face value
- No hidden fees

**Features:**
- Secondary ticket marketplace only (no primary sales)
- Price cap at 20% above face value (anti-scalping)
- Barcode verification / fraud detection
- Secure payment processing
- Mobile app
- Social features
- Waiting list for sold-out events
- API for primary ticketing platform integration
- Organizer partnerships for official resale

**Geography:**
- Europe (Netherlands, UK, Germany, France, Belgium, etc.)
- Expanding to US, Australia, Brazil
- 40+ countries

**Technology:**
- Web and mobile apps
- No blockchain
- Barcode verification tech
- Standard Web2

**Scale:**
- 10+ million users
- Major presence in European festival/club scene

**Key Partnerships/Clients:**
- Partnerships with festivals and promoters for official resale
- Tomorrowland, Sonar, and other major European festivals

**Strengths:**
- Anti-scalping (20% price cap)
- Trusted in European festival scene
- Good UX
- Verified tickets reduce fraud
- Growing international presence

**Weaknesses:**
- Secondary only (no primary sales)
- 10% buyer fee is high vs MINGO's 3.5%
- No blockchain/NFT
- No artist royalties on resale
- Limited presence outside Europe
- 20% markup still allows some profiteering

---

## 10. STUBHUB / VIAGOGO (Secondary Market)

**Overview:**
- World's largest secondary ticket marketplace
- StubHub founded 2000, acquired by Viagogo in 2020
- HQ: Geneva (Viagogo), New York (StubHub operations)
- StubHub filed for IPO in 2024/2025

**Fee Structure:**
- Buyer fee: ~10% of purchase price
- Seller fee: ~15% of sale price
- Total platform take: ~25% across buyer and seller
- No price caps (market-driven pricing)
- Under regulatory investigation for hidden fees

**Features:**
- Secondary ticket marketplace
- Dynamic pricing (market-driven)
- FanProtect guarantee (buyer protection)
- Mobile app
- International marketplace
- Seller tools and analytics
- No primary sales (pure resale)
- Price alerts
- Event discovery

**Geography:**
- Global (US, UK, Europe, Asia, Australia)
- StubHub dominant in US
- Viagogo dominant in Europe, Australia, Asia

**Technology:**
- Web and native mobile apps
- No blockchain
- Standard Web2

**Scale:**
- Billions in gross merchandise value annually
- Tens of millions of users globally
- Largest secondary marketplace in the world

**Key Partnerships/Clients:**
- Official resale partner for some leagues/venues
- MLB, some NFL teams
- But many artists/venues actively oppose StubHub

**Strengths:**
- Massive liquidity (largest secondary marketplace)
- Global reach
- Strong buyer protection guarantee
- Brand recognition

**Weaknesses:**
- 25% total fees (buyer + seller) — astronomically higher than MINGO
- Enables and profits from scalping (no price caps)
- Under regulatory investigation in multiple countries
- No anti-scalping measures
- No artist royalties
- Artists and fans actively dislike the platform
- No blockchain/NFT
- Reputation for hidden fees and deceptive pricing

---

# WEB3 COMPETITORS

---

## 1. GET PROTOCOL / OPEN TICKETING ECOSYSTEM

**Overview:**
- Blockchain ticketing protocol (not a consumer-facing platform), founded 2016
- Rebranded to OPEN Ticketing Ecosystem in 2024
- HQ: Amsterdam, Netherlands
- Provides infrastructure for ticketing companies to issue on-chain tickets
- Token: $OPN (formerly $GET)

**Fee Structure:**
- Protocol fee per ticket (paid in $OPN token)
- Exact fee varies by integrator
- Integrators set their own consumer-facing fees
- Protocol fee is relatively small per ticket

**Features:**
- On-chain NFT ticket issuance
- White-label ticketing infrastructure
- Anti-scalping (configurable resale rules)
- Secondary market with rules
- Event financing tools
- Digital twin ticketing (existing tickets get on-chain counterpart)
- DeFi integration (event financing, staking)
- Open protocol (any ticketing company can integrate)
- Analytics for integrators
- Token staking rewards

**Geography:**
- Netherlands (primary via GUTS), expanding globally
- 20+ integrators worldwide
- South Korea, Italy, UK, others

**Technology:**
- Polygon blockchain (Ethereum L2)
- Protocol layer (not consumer-facing)
- Integrators build their own front-ends
- White-label approach

**Scale:**
- 5.5+ million on-chain NFT tickets sold (as of early 2024)
- 20+ integrators
- Growing but still small vs Web2 giants

**Key Partnerships/Clients:**
- GUTS Tickets (Netherlands)
- Various ticketing integrators globally
- Blockchain ecosystem partners

**Strengths:**
- Protocol approach (scalable — any company can integrate)
- Genuine anti-scalping with configurable rules
- On-chain transparency
- Event financing innovation
- Open ecosystem model
- Most tickets sold of any Web3 ticketing project

**Weaknesses:**
- Not consumer-facing (relies on integrators)
- Token dependency adds complexity
- Small scale compared to Web2
- Less control over end-user experience
- Protocol complexity may deter smaller organizers
- Token price volatility affects protocol economics

---

## 2. MOONGATE

**Overview:**
- Web3 engagement and ticketing platform, founded ~2022
- HQ: Asia (Hong Kong area)
- Raised $2.7M seed round
- Acquired by / integrated with Humanity Protocol (2025)
- Focus on "phygital" experiences and on-chain engagement

**Fee Structure:**
- Not publicly transparent
- Custom pricing for enterprise clients

**Features:**
- NFT ticket issuance
- On-chain engagement tracking
- "Phygital" passport (connecting physical and digital experiences)
- Rewards engine (MoonFarmer)
- Fiat and crypto payment support
- Email-based wallet creation (no crypto knowledge needed)
- Event check-in
- Post-event NFT collectibles
- Token-gated access

**Geography:**
- Asia-Pacific primary
- Web3 conference circuit globally
- ETHDenver, various blockchain events

**Technology:**
- Multi-chain (Ethereum ecosystem)
- Web-based
- Wallet abstraction (email login)

**Scale:**
- Small (primarily Web3 events and conferences)
- Limited mainstream adoption

**Key Partnerships/Clients:**
- ETHDenver
- Various Web3 conferences
- Humanity Protocol

**Strengths:**
- Good wallet abstraction (Web2-friendly UX)
- Engagement/rewards beyond just ticketing
- Multi-chain support

**Weaknesses:**
- Tiny scale
- Primarily serves Web3 community (echo chamber)
- No mainstream event adoption
- No anti-scalping features documented
- No artist royalties
- Acquired by Humanity — direction unclear
- No secondary marketplace

---

## 3. YELLOWHEART

**Overview:**
- NFT ticketing and digital collectibles platform, founded 2020
- HQ: New York, USA
- Built on Polygon (Ethereum sidechain)
- Focus on music industry and artist empowerment

**Fee Structure:**
- Not publicly transparent
- Custom deals with artists/venues

**Features:**
- NFT ticket issuance
- Controlled resale (artist-set parameters)
- Artist royalties on secondary sales
- Dynamic tickets (transform post-scan)
- Push notifications and NFT airdrops
- Digital collectibles and memberships
- Rotating barcode (anti-screenshot)
- Fiat and crypto payments
- Exclusive content access via NFT ownership
- Merchandise integration

**Geography:**
- US primary
- Limited international presence

**Technology:**
- Polygon blockchain
- Web and mobile app
- Rotating barcode technology

**Scale:**
- Small (niche NFT ticketing market)
- Notable partnerships but limited volume

**Key Partnerships/Clients:**
- Maroon 5
- Various music artists
- NFT.NYC

**Strengths:**
- Artist royalties on resale (similar to MINGO)
- Controlled resale parameters
- Dynamic tickets are innovative
- Music industry focus
- Collectible/membership utility beyond ticketing

**Weaknesses:**
- Very small scale
- Limited mainstream adoption
- US-only effectively
- Not transparent about fees
- App required (not PWA)
- Unclear financial sustainability
- Limited feature set for organizers

---

## 4. SEATLAB

**Overview:**
- NFT ticketing platform, founded ~2022
- Built originally on Solana, then pivoted to NEAR Protocol
- Focus on fan rewards and collectible tickets
- Has $SEAT token

**Fee Structure:**
- Holding $SEAT tokens reduces buyer fees
- Exact fees not publicly documented

**Features:**
- NFT ticket issuance
- Fan rewards center
- Digital collectibles (redeemable for merchandise, VIP, drinks)
- Scannable collectibles for in-venue verification
- Anti-fraud via blockchain
- Wallet abstraction (biometric login, username-based)
- Fiat payment support

**Geography:**
- UK-based
- Limited geographic reach

**Technology:**
- NEAR Protocol blockchain
- Web-based
- Wallet abstraction (no crypto knowledge needed)

**Scale:**
- Very small / early stage
- Limited events and users

**Key Partnerships/Clients:**
- No major partnerships publicly known

**Strengths:**
- Good UX abstraction (biometric wallets)
- Collectible rewards system is innovative
- Fiat-friendly

**Weaknesses:**
- Extremely small scale
- Token dependency ($SEAT)
- No major partnerships
- NEAR Protocol is less mainstream
- No documented anti-scalping
- No artist royalties documented
- Early stage / unclear viability

---

## 5. NFT TIX

**Overview:**
- NFT ticketing platform built on Solana
- Early-stage project
- Focus on event ticket minting and staking

**Fee Structure:**
- Not publicly documented

**Features:**
- NFT ticket creation
- Creator center for event organizers
- Staking rewards for holding limited edition tickets
- Solana blockchain for fast transactions

**Geography:**
- Global (Web3 native, no geographic focus)

**Technology:**
- Solana blockchain
- Web-based

**Scale:**
- Very small / niche
- Primarily crypto-native users

**Key Partnerships/Clients:**
- No major partnerships known

**Strengths:**
- Solana = fast and cheap transactions
- Staking/rewards model

**Weaknesses:**
- Minimal adoption
- Crypto-native only (not Web2-friendly)
- No wallet abstraction
- No anti-scalping
- No artist royalties
- No major features beyond basic NFT minting
- Likely inactive or dormant

---

## 6. CENTAURIFY

**Overview:**
- NFT ticketing platform for music events, founded 2021
- Built on Cardano blockchain
- Also building music streaming platform
- Has $CENT token

**Fee Structure:**
- Staked token holders earn 1-3% on every NFT ticket transaction
- Fiat on-ramp available
- Exact organizer fees not documented

**Features:**
- NFT ticket issuance
- Music streaming platform (planned)
- Token staking rewards
- Fiat on-ramp (automatic conversion to token)
- Artist-focused features

**Geography:**
- Norway-based
- Global Web3 audience

**Technology:**
- Cardano blockchain
- Web-based

**Scale:**
- Very small / early stage
- Limited real-world events

**Key Partnerships/Clients:**
- Cardano ecosystem
- No major mainstream partnerships

**Strengths:**
- Cardano ecosystem support
- Music + ticketing combo vision
- Artist-focused

**Weaknesses:**
- Very early stage
- Cardano has smaller DApp ecosystem
- Token dependency
- No mainstream adoption
- Music streaming + ticketing is ambitious and unfocused
- Unclear if still actively developing

---

## 7. TRUE TICKETS

**Overview:**
- Blockchain-powered ticket delivery for performing arts, founded ~2019
- HQ: Boston, Massachusetts
- Built on IBM Blockchain (Hyperledger Fabric)
- Focus on performing arts venues and Broadway

**Fee Structure:**
- B2B pricing (integrates with existing ticketing systems like Tessitura)
- Not consumer-facing pricing

**Features:**
- Secure digital ticket delivery via blockchain
- Dynamic QR codes (anti-fraud)
- CRM data capture (identify real attendees vs. ticket brokers)
- "Shadow audience" revelation (see who actually attends)
- Integration with Tessitura (performing arts CRM)
- Contactless entry
- Transfer tracking
- Not a full ticketing platform — a delivery layer

**Geography:**
- US (performing arts venues, Broadway)

**Technology:**
- IBM Blockchain (Hyperledger Fabric)
- Google Cloud deployment
- Integration layer (not standalone platform)

**Scale:**
- Small but notable clients
- Broadway productions
- Performing arts venues

**Key Partnerships/Clients:**
- Broadway productions
- Tessitura Network
- IBM
- Performing arts venues

**Strengths:**
- Enterprise-grade blockchain (IBM/Hyperledger)
- Excellent for performing arts niche
- Reveals shadow audience (powerful CRM data)
- Integrates with existing systems (doesn't require platform switch)
- Dynamic QR = strong anti-fraud

**Weaknesses:**
- Not a full ticketing platform (delivery layer only)
- Performing arts niche only
- No consumer-facing marketplace
- No secondary market features
- No anti-scalping
- No artist royalties
- Small scale
- Hyperledger is permissioned (not truly decentralized)

---

## 8. OVEIT

**Overview:**
- Event management and NFT ticketing platform, founded 2015
- HQ: Bucharest, Romania
- Hybrid platform (traditional + NFT ticketing)
- Also offers cashless payment solutions for events

**Fee Structure:**
- Freemium model
- Fees for paid events (not publicly specified exact percentages)
- Likely competitive with Eventbrite-level fees

**Features:**
- NFT ticket issuance (blockchain-based)
- Traditional ticket sales
- Cashless payment system for in-event spending
- Token-gated events
- Check-in and access control
- Event registration
- Virtual event support
- Livestream ticketing
- Analytics
- Custom branding
- NFC wristbands for cashless payments
- Multi-event management

**Geography:**
- Romania/Eastern Europe primary
- Global availability
- Small international presence

**Technology:**
- Blockchain for NFT tickets (chain not prominently specified)
- Web-based platform
- NFC/RFID for cashless

**Scale:**
- Small (thousands of events, not millions)
- Regional player

**Key Partnerships/Clients:**
- Romanian events and festivals
- European SMB events

**Strengths:**
- Hybrid model (traditional + NFT)
- Cashless payment integration (unique)
- Livestream/virtual event support
- More mature than most Web3 competitors (founded 2015)

**Weaknesses:**
- Small scale and limited brand recognition
- Unclear blockchain implementation details
- No anti-scalping
- No artist royalties
- Limited to SMB events
- Eastern European focus limits global appeal

---

# FEATURE COMPARISON MATRIX

(Plain text format — Y = Yes, N = No, P = Partial, ? = Unknown)

## PRIMARY SALES
- Ticketmaster: Y
- Eventbrite: Y
- DICE: Y
- See Tickets: Y
- AXS: Y
- Universe: Y
- Ticket Tailor: Y
- Humanitix: Y
- TicketSwap: N (secondary only)
- StubHub/Viagogo: N (secondary only)
- GET Protocol: Y (via integrators)
- Moongate: Y
- YellowHeart: Y
- Seatlab: Y
- NFT TiX: Y
- Centaurify: Y
- TrueTickets: N (delivery layer)
- Oveit: Y
- MINGO: Y

## SECONDARY MARKET / RESALE
- Ticketmaster: Y (fan-to-fan)
- Eventbrite: N
- DICE: N (returns to queue only)
- See Tickets: P (some events)
- AXS: Y (Flash Seats)
- Universe: N
- Ticket Tailor: N
- Humanitix: N
- TicketSwap: Y (core business)
- StubHub/Viagogo: Y (core business)
- GET Protocol: Y (configurable)
- Moongate: N
- YellowHeart: Y (controlled)
- Seatlab: P
- NFT TiX: P
- Centaurify: P
- TrueTickets: N
- Oveit: N
- MINGO: Y (with caps)

## ANTI-FRAUD / COUNTERFEIT PREVENTION
- Ticketmaster: Y (SafeTix rotating barcode)
- Eventbrite: P (basic)
- DICE: Y (mobile-only, no screenshots)
- See Tickets: P (basic)
- AXS: Y (digital tickets)
- Universe: P (basic)
- Ticket Tailor: P (basic)
- Humanitix: P (basic)
- TicketSwap: Y (barcode verification)
- StubHub/Viagogo: P (guarantee, not prevention)
- GET Protocol: Y (blockchain verification)
- Moongate: Y (NFT verification)
- YellowHeart: Y (rotating barcode + blockchain)
- Seatlab: Y (blockchain)
- NFT TiX: Y (blockchain)
- Centaurify: Y (blockchain)
- TrueTickets: Y (dynamic QR + blockchain)
- Oveit: Y (blockchain)
- MINGO: Y (Hedera blockchain + NFT)

## ANTI-SCALPING
- Ticketmaster: P (Verified Fan, but still allows resale at any price)
- Eventbrite: N
- DICE: Y (no resale, returns to queue at face value)
- See Tickets: N
- AXS: N
- Universe: N
- Ticket Tailor: N
- Humanitix: N
- TicketSwap: Y (20% cap above face value)
- StubHub/Viagogo: N (enables scalping)
- GET Protocol: Y (configurable resale caps)
- Moongate: N
- YellowHeart: Y (artist-set parameters)
- Seatlab: P
- NFT TiX: N
- Centaurify: N
- TrueTickets: N
- Oveit: N
- MINGO: Y (resale caps)

## ANALYTICS / REPORTING
- Ticketmaster: Y (comprehensive)
- Eventbrite: Y (good)
- DICE: Y
- See Tickets: Y
- AXS: Y
- Universe: Y
- Ticket Tailor: Y (basic)
- Humanitix: Y
- TicketSwap: P (for partners)
- StubHub/Viagogo: P (seller tools)
- GET Protocol: Y (for integrators)
- Moongate: Y
- YellowHeart: P
- Seatlab: P
- NFT TiX: N
- Centaurify: N
- TrueTickets: Y (shadow audience data)
- Oveit: Y
- MINGO: Y

## MARKETING TOOLS
- Ticketmaster: Y (email, presales, promotions)
- Eventbrite: Y (email, social, discount codes, ads)
- DICE: P (discovery algorithm)
- See Tickets: Y
- AXS: Y
- Universe: Y (discount codes, affiliates)
- Ticket Tailor: P (discount codes)
- Humanitix: Y (email, discount codes)
- TicketSwap: N
- StubHub/Viagogo: N
- GET Protocol: P (via integrators)
- Moongate: P (rewards engine)
- YellowHeart: P (push notifications, airdrops)
- Seatlab: P (rewards)
- NFT TiX: N
- Centaurify: N
- TrueTickets: N
- Oveit: P
- MINGO: P (basic)

## CRM / ATTENDEE DATA
- Ticketmaster: Y (comprehensive)
- Eventbrite: Y
- DICE: Y
- See Tickets: Y
- AXS: Y
- Universe: Y
- Ticket Tailor: Y (data stays with organizer)
- Humanitix: Y
- TicketSwap: P
- StubHub/Viagogo: N
- GET Protocol: Y (via integrators)
- Moongate: Y (on-chain engagement data)
- YellowHeart: P
- Seatlab: P
- NFT TiX: N
- Centaurify: N
- TrueTickets: Y (shadow audience revelation — excellent)
- Oveit: Y
- MINGO: Y

## API / INTEGRATIONS
- Ticketmaster: Y (comprehensive)
- Eventbrite: Y (good API, Zapier)
- DICE: N (closed ecosystem)
- See Tickets: Y
- AXS: Y
- Universe: Y
- Ticket Tailor: Y (Zapier, API)
- Humanitix: P
- TicketSwap: Y (ticket API)
- StubHub/Viagogo: Y (resale API)
- GET Protocol: Y (core product is an API/protocol)
- Moongate: P
- YellowHeart: P
- Seatlab: P
- NFT TiX: N
- Centaurify: N
- TrueTickets: Y (Tessitura integration)
- Oveit: P
- MINGO: ? (not documented)

## MOBILE APP
- Ticketmaster: Y (native iOS/Android)
- Eventbrite: Y (native iOS/Android)
- DICE: Y (native — app-only purchasing)
- See Tickets: N (web only)
- AXS: Y (native iOS/Android)
- Universe: N (web responsive)
- Ticket Tailor: Y (check-in app)
- Humanitix: Y (check-in app)
- TicketSwap: Y (native)
- StubHub/Viagogo: Y (native)
- GET Protocol: N (protocol — integrators build apps)
- Moongate: N (web)
- YellowHeart: Y (native app)
- Seatlab: N (web)
- NFT TiX: N (web)
- Centaurify: N (web)
- TrueTickets: N (delivery layer)
- Oveit: N (web)
- MINGO: PWA (installable, no app store download required)

## PAYMENT OPTIONS
- Ticketmaster: Credit/debit, PayPal, Apple Pay, Google Pay
- Eventbrite: Credit/debit, PayPal, Stripe
- DICE: Credit/debit, Apple Pay, Google Pay
- See Tickets: Credit/debit, PayPal
- AXS: Credit/debit, Apple Pay, Google Pay
- Universe: Stripe (credit/debit)
- Ticket Tailor: Stripe, Square, PayPal
- Humanitix: Credit/debit (built-in processing)
- TicketSwap: Credit/debit, iDEAL, Bancontact
- StubHub/Viagogo: Credit/debit, PayPal
- GET Protocol: Via integrators (fiat and crypto)
- Moongate: Fiat and crypto
- YellowHeart: Fiat and crypto
- Seatlab: Fiat and crypto
- NFT TiX: Crypto primarily
- Centaurify: Fiat on-ramp + crypto
- TrueTickets: Via existing ticketing systems
- Oveit: Credit/debit, crypto
- MINGO: Fiat (credit/debit) — crypto? (unclear)

## WHITE-LABEL
- Ticketmaster: Y
- Eventbrite: P (embeddable widgets)
- DICE: N
- See Tickets: Y
- AXS: Y
- Universe: P (embeddable)
- Ticket Tailor: Y (customers stay on your domain)
- Humanitix: N
- TicketSwap: N
- StubHub/Viagogo: N
- GET Protocol: Y (core value proposition)
- Moongate: P
- YellowHeart: N
- Seatlab: N
- NFT TiX: N
- Centaurify: N
- TrueTickets: Y (integrates with existing systems)
- Oveit: P (custom branding)
- MINGO: ? (not documented)

## RESERVED SEATING / SEAT MAPS
- Ticketmaster: Y (industry-leading)
- Eventbrite: P (limited/add-on)
- DICE: N
- See Tickets: Y
- AXS: Y
- Universe: N
- Ticket Tailor: Y
- Humanitix: P (basic)
- TicketSwap: N (resale, no seat selection)
- StubHub/Viagogo: Y (seat maps for browsing)
- GET Protocol: P (via integrators)
- Moongate: N
- YellowHeart: N
- Seatlab: N
- NFT TiX: N
- Centaurify: N
- TrueTickets: N (uses existing system's seating)
- Oveit: N
- MINGO: ? (not documented — likely limited)

## BOX OFFICE / POS
- Ticketmaster: Y
- Eventbrite: P (at-door sales)
- DICE: N
- See Tickets: Y
- AXS: Y
- Universe: N
- Ticket Tailor: P (basic)
- Humanitix: P
- TicketSwap: N
- StubHub/Viagogo: N
- GET Protocol: P (via integrators)
- Moongate: N
- YellowHeart: N
- Seatlab: N
- NFT TiX: N
- Centaurify: N
- TrueTickets: N
- Oveit: Y (NFC/cashless)
- MINGO: ? (not documented)

## STREAMING / HYBRID EVENTS
- Ticketmaster: P (limited)
- Eventbrite: Y (virtual events)
- DICE: P (some virtual)
- See Tickets: N
- AXS: P
- Universe: P
- Ticket Tailor: N
- Humanitix: Y
- TicketSwap: N
- StubHub/Viagogo: N
- GET Protocol: N
- Moongate: N
- YellowHeart: N
- Seatlab: N
- NFT TiX: P (virtual events)
- Centaurify: P (music streaming planned)
- TrueTickets: N
- Oveit: Y (livestream ticketing)
- MINGO: ? (not documented)

## NFT / DIGITAL COLLECTIBLE TICKETS
- Ticketmaster: N
- Eventbrite: N
- DICE: N
- See Tickets: N
- AXS: N
- Universe: N
- Ticket Tailor: N
- Humanitix: N
- TicketSwap: N
- StubHub/Viagogo: N
- GET Protocol: Y
- Moongate: Y
- YellowHeart: Y
- Seatlab: Y
- NFT TiX: Y
- Centaurify: Y
- TrueTickets: P (blockchain-verified but not NFT collectibles)
- Oveit: Y
- MINGO: Y

## ARTIST ROYALTIES ON RESALE
- Ticketmaster: N
- Eventbrite: N (no resale)
- DICE: N (no resale)
- See Tickets: N
- AXS: N
- Universe: N
- Ticket Tailor: N
- Humanitix: N
- TicketSwap: N
- StubHub/Viagogo: N
- GET Protocol: Y (configurable)
- Moongate: N
- YellowHeart: Y
- Seatlab: P
- NFT TiX: N
- Centaurify: P
- TrueTickets: N
- Oveit: N
- MINGO: Y

---

# WHERE MINGO WINS

## Fee Advantage (MINGO at 3.5%)
- vs Ticketmaster (24-44% total to consumer): MINGO is 7-12x cheaper
- vs Eventbrite (6-8% total): MINGO is roughly half the cost
- vs DICE (~10% included): MINGO is nearly 3x cheaper
- vs See Tickets (10-15%): MINGO is 3-4x cheaper
- vs AXS (15-25%): MINGO is 4-7x cheaper
- vs Humanitix (~5%): MINGO is ~30% cheaper
- vs TicketSwap (10% buyer fee): MINGO is nearly 3x cheaper
- vs StubHub/Viagogo (25% total): MINGO is 7x cheaper
- vs Ticket Tailor: Depends on ticket price. For tickets over ~$20, Ticket Tailor's flat $0.70 may be cheaper; for cheaper tickets, MINGO wins
- vs Universe: MINGO likely cheaper
- vs Web3 competitors: Most don't publish clear fees, but MINGO's 3.5% flat is very competitive

MINGO's 3.5% flat fee is arguably the strongest single competitive advantage in the entire ticketing industry.

## Technology Advantages
- Hedera Hashgraph: faster, cheaper, more energy-efficient than Ethereum/Polygon/Solana (used by most Web3 competitors)
- PWA approach: no app download required (beats DICE which requires app download, and native apps which need App Store approval)
- NFT tickets with blockchain verification: eliminates counterfeiting (beats all Web2 competitors)
- Anti-scalping via resale caps: built into the protocol (only DICE, TicketSwap, GET Protocol, and YellowHeart offer comparable features)
- Artist royalties on resale: only GET Protocol and YellowHeart also offer this among competitors
- "Hidden blockchain" UX: Web2 simplicity with Web3 benefits (only GET Protocol/GUTS and Seatlab attempt similar UX abstraction)

## Other Edges
- 54-country availability is broader than most Web3 competitors and comparable to mid-tier Web2 platforms
- Boxing/combat sports niche: WBC, Tyson Fury, Fight Circus, African Boxing League partnerships give MINGO a genuine vertical stronghold
- Napster AI partnership signals forward-thinking music/entertainment tech positioning
- Since 2018: longer track record than most Web3 ticketing competitors (only GET Protocol is older)
- No app store dependency: PWA avoids Apple/Google 30% cut and review process

---

# WHERE MINGO IS LACKING (HONEST ASSESSMENT)

## Missing Features vs Competitors

1. **Reserved Seating / Interactive Seat Maps**
   - Ticketmaster, AXS, See Tickets, and Ticket Tailor all offer sophisticated seat mapping
   - Critical for venues, arenas, theaters, and seated events
   - Without this, MINGO is limited to GA and simple tiered events
   - This is arguably the BIGGEST feature gap for enterprise adoption

2. **Discovery Marketplace / Consumer Audience**
   - Ticketmaster has 63% of US ticket buyers browsing their platform
   - Eventbrite has 87 million monthly active users discovering events
   - DICE has a discovery algorithm
   - MINGO has no consumer-facing discovery marketplace — organizers must drive their own traffic
   - This means MINGO provides tools but not audience

3. **Marketing and CRM Tools**
   - Ticketmaster: comprehensive email campaigns, presale systems, Verified Fan
   - Eventbrite: email marketing, social promotion, ads integration, discount codes
   - MINGO: basic tools (if any advanced marketing suite exists, it's not well documented)
   - No documented email marketing automation, retargeting, or audience segmentation

4. **White-Label / Embeddable Widgets**
   - Ticket Tailor lets organizers sell on their own domain
   - Eventbrite has embeddable widgets
   - GET Protocol's core value is white-label infrastructure
   - MINGO's white-label capabilities are not well documented

5. **API / Developer Ecosystem**
   - Ticketmaster, Eventbrite, and GET Protocol have robust APIs
   - MINGO's API availability is unclear
   - No documented developer ecosystem or third-party integrations

6. **Box Office / POS System**
   - Ticketmaster, AXS, and See Tickets offer on-site POS and box office solutions
   - Essential for venue operations
   - MINGO appears to lack this

7. **Virtual / Hybrid Event Support**
   - Eventbrite, Humanitix, and Oveit support virtual/livestream events
   - Post-COVID, hybrid capability is expected
   - Not documented for MINGO

8. **Dynamic Pricing**
   - Ticketmaster's dynamic pricing is controversial but revenue-maximizing
   - Some organizers want this capability
   - MINGO doesn't appear to offer it

## Scale and Market Presence Gaps

1. **Brand Awareness**: Almost zero consumer awareness compared to Ticketmaster (household name), Eventbrite (well-known), or even DICE
2. **Venue Relationships**: No documented exclusive venue deals. Ticketmaster and AXS lock up major venues with multi-year exclusives
3. **Ticket Volume**: Ticketmaster sells 500M+ tickets/year. Even GET Protocol has 5.5M+ on-chain. MINGO's volume is not publicly documented (likely much smaller)
4. **Geographic Depth**: Available in 54 countries but depth of penetration is unclear. Being "available" vs "established with local partnerships" are very different
5. **Enterprise Sales Team**: Major ticketing platforms have armies of sales reps. MINGO's go-to-market is unclear

## Technology Gaps

1. **Hedera Ecosystem**: While Hedera is technically superior, it has a much smaller developer ecosystem than Ethereum/Polygon. This limits third-party integrations and developer interest
2. **Native App Absence**: PWA is a strength AND weakness. Some users prefer native apps. No presence in App Store/Google Play means no organic discovery there
3. **Payment Flexibility**: Crypto payment support is unclear. In 54 countries, local payment methods matter (M-Pesa in Africa, iDEAL in Netherlands, etc.)

## Marketing / Brand Gaps

1. **Content Marketing**: Ticketmaster and Eventbrite produce massive amounts of SEO-optimized content. MINGO's online presence is thin
2. **Social Media Presence**: Compared to competitors, MINGO has minimal social following
3. **Press Coverage**: Limited mainstream press. Most coverage is in crypto/blockchain niche publications
4. **Case Studies / Social Proof**: No publicly visible case studies showing ROI for organizers
5. **The "Blockchain" Stigma**: Even though MINGO hides it well, the association with crypto/blockchain can deter traditional organizers who've seen Web3 projects fail

## Specific Feature Gaps by Competitor

What Ticketmaster has that MINGO doesn't:
- Massive consumer marketplace
- Exclusive venue contracts
- Verified Fan presale system
- Dynamic pricing
- Season ticket management
- Comprehensive box office POS
- Industry-leading seat maps

What Eventbrite has that MINGO doesn't:
- 87M monthly active users discovering events
- Robust email marketing automation
- Embeddable widgets for external sites
- Extensive API and Zapier integrations
- Virtual event support

What DICE has that MINGO doesn't:
- Discovery algorithm (recommendation engine)
- Strong indie/alternative music brand
- Social features (see what friends attend)

What GET Protocol has that MINGO doesn't:
- Open protocol approach (any ticketing company can integrate)
- Event financing / DeFi tools
- Digital twin capability (add blockchain to existing tickets)
- 20+ integrators using the protocol

---

# GEOGRAPHIC ANALYSIS

## Who Dominates Where

**North America (USA, Canada):**
- Ticketmaster: dominant (80%+ US market share)
- Eventbrite: strong #2 for mid-size events
- AXS: strong at AEG venues
- StubHub: dominant secondary market
- MINGO opportunity: Combat sports niche (WBC, boxing). Must go around Ticketmaster's venue lock-in

**UK & Ireland:**
- Ticketmaster: dominant for major events
- See Tickets: strong for festivals
- DICE: strong for indie/club scene
- AXS: The O2 and AEG venues
- MINGO opportunity: Comic-Con Ireland partnership. UK/Ireland is competitive but MINGO has a foothold. Independent venues and promoters are the entry point

**Continental Europe:**
- Ticketmaster: dominant in major markets
- See Tickets: France, Netherlands, Germany
- TicketSwap: dominant secondary in Netherlands/Benelux
- DICE: growing in France, Germany, Spain, Italy
- GET Protocol: Netherlands (via GUTS)
- MINGO opportunity: Independent promoters, combat sports. Less Ticketmaster lock-in than US

**Africa:**
- Very fragmented market
- No dominant global player
- Mobile money and local payment methods critical
- MINGO advantage: African Boxing League partnership. 54-country availability. If MINGO supports mobile money, Africa is a genuine greenfield opportunity

**Asia-Pacific:**
- Ticketmaster/Live Nation: Australia, Japan, South Korea
- AXS: Japan (B.League)
- Moongate: Asia-focused Web3 events
- MINGO opportunity: Limited current presence but low competition from blockchain ticketing

**Latin America:**
- Ticketmaster: expanding
- Eventbrite: present
- Largely fragmented
- MINGO opportunity: Growing combat sports scene. Underserved by blockchain ticketing

## MINGO's Geographic Strengths
- Combat sports niche globally (WBC is global, boxing is popular worldwide)
- Africa (African Boxing League — genuine first-mover opportunity)
- Ireland/UK (Comic-Con Ireland)
- 54-country availability gives breadth

## MINGO's Geographic Gaps
- No documented presence in the US venue/concert market (Ticketmaster fortress)
- No Asian partnerships documented
- Depth of local operations unclear (having the platform "available" vs having on-the-ground sales teams, local payment methods, and local partnerships are very different things)
- Africa opportunity requires mobile money integration to truly capitalize
- European festival circuit dominated by See Tickets and Ticketmaster
- No Latin American partnerships documented

---

# STRATEGIC SUMMARY

MINGO's position in the market is genuinely unique:

**The Bull Case:**
MINGO combines Web3 technology (NFTs, anti-fraud, anti-scalping, artist royalties) with Web2 simplicity and the lowest fees in the industry at 3.5%. No other platform achieves this exact combination. The combat sports niche gives them credible partnerships and a vertical where they can dominate. Africa represents a massive greenfield opportunity. If they can build enterprise features (seat maps, APIs, white-label) and gain scale, they have a compelling product-market fit that no competitor matches.

**The Bear Case:**
Scale, brand awareness, and missing enterprise features (seat maps, box office, comprehensive marketing/CRM tools) limit MINGO to smaller, GA-format events in a niche vertical. The ticketing industry is defined by exclusive venue contracts and distribution power, not technology. Ticketmaster's moat isn't their tech — it's their exclusive deals with 80%+ of major venues. MINGO has to either go around this (niche verticals, underserved geographies) or somehow break through it.

**The Realistic Path:**
1. Own the combat sports vertical globally (WBC, boxing, MMA)
2. Expand into underserved geographies (Africa, parts of Asia/Latin America)
3. Build enterprise features (seat maps, API, white-label)
4. Use the fee advantage to win independent promoters away from Eventbrite
5. Let the DOJ Ticketmaster antitrust case potentially open up the market
6. Keep hiding the blockchain — the "seems Web2" approach is exactly right

---

*Document compiled February 2026. Data sourced from company websites, press coverage, regulatory filings, and industry reports. Fees and features may change — verify current pricing directly with each platform.*

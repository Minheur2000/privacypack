# Ownership and original idea notice
This project was orginialy created by the [Ente](https://ente.io) team. You can see their project [here](https://github.com/ente/privacypack).

The reason of my fork is because I do not want to sign their CLA, and I'm not the only one.
I forked it and I publish it under the same licence as them ([MIT](/LICENCE)) and I take advantage of it to create a version where people can contribute **without any CLA**.

# PrivacyPack.org

Pick the mainstream apps you used before, show the privacy-respecting tools you’ve switched to, and share your privacy wins!

Create your pack at [PrivacyPack.org](https://minheur2000.github.io/privacypack).

![PrivacyPack Banner](public/og-image.png)

## Development Setup

### Prerequisites

- Node.js (v18 or higher)
- npm

### Local Development

1. Clone the repository

```bash
git clone https://github.com/ente-io/privacypack.git
cd privacypack
```

2. Install dependencies

```bash
npm install
```

3. Start the development server

```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Add a missing app

New apps can be added to the catalog by modifying `/data/apps.json` and opening a PR. Each app belongs to a category and is either a mainstream app or a privacy-focused alternative.

### App logo requirements

When adding a new app, please ensure the logo meets these specifications:

- Format: JPG
- General: 200x200px, no rounded corners, no transparent background, sufficient padding around the logo
- File size: < 50KB
- Location: Place the logo file in `/public/app-logos/{app_id}.jpg`

Please note that you are **responsible** of the content you add, and if you add a copyrighted image or brand we won't be able to be taken responsible of any problems that could create.
**If your brand, logo or anything else you built has been implemented into this project and you want it not to, please create an issue and we will sort it as quikly as possible.**

## About

PrivacyPack is created and maintained by [Ente](https://ente.io), the makers of Ente Photos and Ente Auth.
This fork is maintained by [Minheur2000](https://github.com/Minheur2000).

## License

PrivacyPack is distributed under the [MIT license](/LICENSE).

# BetterZamPen

![GitHub Repo Banner](https://ghrb.waren.build/banner?header=BetterZamPen&subheader=Building+a+better+Zamboanga+Peninsula&bg=0066CC&color=fff&support=true)
<!-- Created with GitHub Repo Banner by Waren Gonzaga: https://ghrb.waren.build -->

A community-led initiative to create a better and more accessible government information portal for the Zamboanga Peninsula (Region IX).

## Why We're Building This Project

Government information in the Zamboanga Peninsula faces similar challenges as the national portal:

- Limited online presence for many municipalities and cities
- Outdated or missing contact information for local government officials
- Scattered information across different platforms
- Difficult access to government services and transparency data
- Language barriers for citizens who primarily speak Cebuano, Bisaya, or Chavacano

These issues create barriers for residents trying to access essential local government services and information.

## Our Mission

We are a volunteer-led initiative building on the [BetterGov Philippines](https://github.com/bettergovph) movement to provide accessible government information for the Zamboanga Peninsula.

Our goals include:

- Creating a comprehensive directory of all LGUs in Region IX (Zamboanga del Norte, del Sur, Sibugay, and Basilan)
- Providing accurate, up-to-date contact information for government officials and offices
- Making transparency data (budgets, projects, procurement) easily accessible
- Ensuring accessibility for all residents, including those with disabilities
- Supporting local languages (Cebuano/Bisaya and Chavacano)
- Establishing a model for regional government digital services

## Features

- Modern, responsive design that works on all devices
- Comprehensive directory of Region IX LGUs, officials, and services
- User-friendly navigation and search
- Accessibility features for users with disabilities
- Multi-language support (English, Cebuano/Bisaya, Chavacano)
- Regular updates and maintenance

## Coverage Area

**Region IX - Zamboanga Peninsula**

We're building comprehensive coverage for all provinces in the Zamboanga Peninsula:

- **Zamboanga del Norte** (Phase 1) - 2 cities, 27 municipalities
- **Zamboanga del Sur** (Phase 2) - 2 cities, 26 municipalities  
- **Zamboanga Sibugay** (Phase 3) - 1 city, 16 municipalities
- **Basilan** (Phase 4) - 1 city, 11 municipalities

Starting with Dipolog City and expanding throughout the region.

## Documentation

For general BetterGov documentation, visit the [BetterGov Docs](https://docs.bettergov.ph/).

## Join Us as a Volunteer

We're looking for passionate individuals from the Zamboanga Peninsula to help build BetterZamPen. We need volunteers with various skills:

- Frontend and backend developers
- UX/UI designers
- Content writers and editors
- Translators (Cebuano/Bisaya and Chavacano)
- Data collectors (help verify LGU information)
- Accessibility experts
- Project managers
- QA testers

If you're interested in contributing, please open an issue in this repository or reach out through our organization discussions.

## Code of Conduct

We are committed to fostering a welcoming and respectful community.
Please read our [Code of Conduct](./CODE_OF_CONDUCT.md) before participating.

## Contributing

We welcome contributions from everyone!
Please see our [Contributing Guide](./CONTRIBUTING.md) for details on:

- Development setup
- Reporting bugs
- Opening issues and pull requests

## How to Run

```bash
# Install packages
npm install

# Start the server
npm run dev
```

**Access the application at:** `http://localhost:5173`

## GitHub Codespaces

You may use GitHub Codespaces for an instant development environment with dependencies automatically installed for you.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/bettergovph/bettergov?quickstart=1)

## Docker

This project includes Docker support for easy deployment and consistent environments.

### Building and Running

```bash
# Build the Docker image
docker build -t bettergov .

# Run the container
docker run -p 8080:80 bettergov

# Run in detached mode
docker run -d -p 8080:80 --name bettergov bettergov
```

**Access the application at:** `http://localhost:8080`

### Docker Compose

For the easiest and most consistent development experience, we recommend using Docker Compose. This method uses Docker to run the application in a controlled environment with hot-reloading enabled.

```bash
# Start the development server
docker-compose up

# Start in detached mode
docker-compose up -d

# Stop the service
docker-compose down
```
**Access the application at:** `http://localhost:5173`

## Testing

This project uses Playwright for end-to-end testing.
For setup instructions, coverage details, and examples, see our [Testing Guide](./TESTING.md).

## Contributing

Thanks to all the people who are contributing to BetterZamPen!

<a href="https://github.com/betterzampen/betterzampen/graphs/contributors">
    <img src="https://contributors-img.web.app/image?repo=betterzampen/betterzampen&max=750&columns=20" />
</a>

Built on [BetterGov.ph](https://github.com/bettergovph/bettergov) - Special thanks to the BetterGov community for creating the foundation.

## License

This project is released under the [Creative Commons CC0](https://creativecommons.org/publicdomain/zero/1.0/) dedication. This means the work is dedicated to the public domain and can be freely used by anyone for any purpose without restriction under copyright law.

---

**Made with care by the people of Zamboanga Peninsula**

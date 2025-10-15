# IPos — The #1 POS for Ethiopian Businesses

IPos is a modern, powerful point of sale system designed for Ethiopian retail, restaurants, and multi-location businesses. It offers fast checkouts, precise inventory management, integrated local payments, and robust offline capabilities.

## Features
- Advanced Inventory Management
- CRM & Loyalty Program
- Powerful Reporting & Analytics
- Employee Management
- Restaurant-Ready (table management, kitchen display, modifiers, order tracking)
- Hardware Integrations (printers, barcode scanners, customer displays)
- Offline Sync
- Integrated with Ethiopian payment gateways (Chapa, Telebirr, CBEBirr)

## Use Cases
- Cafes & Restaurants
- Retail & Boutiques
- Supermarkets
- Multi-Location Chains

## Quick Start
1. Clone this repository or download the source code.
2. Install dependencies:
   ```bash
   composer install
   ```
3. Copy the example environment file and set your configuration:
   ```bash
   cp .env.example .env
   ```
4. Generate the application key:
   ```bash
   php artisan key:generate
   ```
5. Run database migrations:
   ```bash
   php artisan migrate
   ```
6. Serve the application locally:
   ```bash
   php artisan serve
   ```

## License
Copyright © 2025 IPos Inc. Gringo2 (Eyob Bezu). All rights reserved.

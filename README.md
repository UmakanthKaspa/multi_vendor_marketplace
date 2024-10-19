### Multi Vendor Marketplace

The Multi Vendor Marketplace is an online platform that connects various vendors with customers, providing a seamless shopping experience. Vendors can easily manage their products, while customers can browse, purchase, and review a diverse range of items.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app multi_vendor_marketplace
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/multi_vendor_marketplace
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit

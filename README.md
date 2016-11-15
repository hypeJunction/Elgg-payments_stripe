# Stripe Payments for Elgg

![Elgg 2.3](https://img.shields.io/badge/Elgg-2.3-orange.svg?style=flat-square)

## Features

 * API for handling payments via Stripe

## Acknowledgements

 * Plugin has been sponsored by [Social Business World] (https://socialbusinessworld.org "Social Business World")

## Usage

To display card information input form, use:

```php

// in your form
echo elgg_view('input/stripe/card');

// in your action
$token = get_input('stripe_token');
```


# Labor Day Offer For Pet Shop

Professional Labor Day Offer email for a Pet Shop, highlighting special discounts and deals.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail, Pet Care
- **Message Type:** Marketing
- **Tags:** labordayoffer, petshopdiscount

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/labor-day-offer-for-pet-shop.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/labor-day-offer-for-pet-shop/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.labor-day-offer-for-pet-shop',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*

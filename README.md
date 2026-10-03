# Dhaba Menu - Vercel + JSON

No MySQL and no admin panel.

Routes:
- `/` or `/dinein` = Dine In
- `/parcel` = Parcel
- `/online` = Online

Edit only `data/menu.json` when adding/changing dishes.

Price fields:
- `dine_in_price`
- `pickup_price`
- `online_price`

After editing menu.json, push the change to GitHub and Vercel will redeploy.

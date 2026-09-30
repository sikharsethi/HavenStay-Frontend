# HavenStay Luxury Hotel Website

HavenStay is a static luxury hospitality website prototype for a fictional hotel brand. It explores a calm, editorial booking experience across the hotel landing page, room details, and reservation flow.

## Preview

Open the main prototype page:

- [HavenStay luxury hotel prototype](havenstay_luxury_hotel_prototype/code.html)

Other screens:

- [Luxury hotel resort page](havenstay_luxury_hotel_resort/code.html)
- [Book your stay](havenstay_book_your_stay/code.html)
- [Deluxe King room details](havenstay_deluxe_king_room_details/code.html)
- [Brand logo](havenstay_brand_logo/code.html)

## Design Direction

The interface follows a warm editorial minimalism direction inspired by quiet architectural luxury:

- Warm ivory, stone, umber, and champagne-gold color palette
- `Playfair Display` for editorial headings
- `Plus Jakarta Sans` for body copy and controls
- Spacious responsive layouts with restrained borders and shadows
- Hospitality-focused flows for discovering rooms, choosing dates, and booking a stay

The complete visual design system is documented in [DESIGN.md](havenstay_luxury_hospitality/DESIGN.md).

## Project Structure

```text
havenstay_book_your_stay/              Reservation flow
havenstay_brand_logo/                  Brand mark exploration
havenstay_deluxe_king_room_details/   Room detail page
havenstay_luxury_hospitality/         Design system documentation
havenstay_luxury_hotel_prototype/     Main hotel landing page
havenstay_luxury_hotel_resort/        Resort-focused landing page
```

Each website screen is a self-contained `code.html` file. There is no build step or framework required.

## Run Locally

Because the pages load fonts, Tailwind CSS, icons, and image assets from external CDNs, serve the project through a local web server for the most reliable preview.

From this directory, run:

```bash
py -m http.server 8000
```

Then visit:

```text
http://localhost:8000/havenstay_luxury_hotel_prototype/code.html
```

You can also open any `code.html` file directly in a browser, although some browser security settings may affect external resources or local interactions.

## Notes

- This is a front-end prototype and does not connect to a real reservation, payment, or hotel-management system.
- Content, dates, prices, and availability are illustrative.
- External fonts, icons, Tailwind CSS, and image assets require an internet connection when the pages load.

## License

This repository is a design and development prototype. Add a project-specific license before distributing it publicly.# HavenStay-Frontend

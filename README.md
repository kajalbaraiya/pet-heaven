# 🐾 Pet Haven

A responsive pet adoption website where visitors can browse adoptable pets, filter them by type and breed, view full pet profiles, and submit an adoption application. Built as a single-page front-end project with HTML, Tailwind CSS, and vanilla JavaScript.

**Live Demo:** _add your GitHub Pages link here_

---

## Features

- **Pet gallery** – card grid of adoptable pets (dogs, cats, birds, and fish)
- **Search filters** – filter by pet type and breed
- **Load more** – pets are shown in batches of 3
- **Pet profile modal** – larger photo, name, type, breed, age, and description
- **Adoption application form** – opens from the profile modal with name, email, phone, and address fields
- **Services section** – Pet Matching, Adoption Counseling, and Pet Health Checks, each with a details popup
- **Contact form** – with success message on submit
- **Responsive design** – mobile hamburger menu and layouts that adapt from phone to desktop
- **Smooth animations** – fade-in hero and slide-in cards

## Tech Stack

| Area | Technology |
| --- | --- |
| Structure | HTML5 |
| Styling | Tailwind CSS (CDN) + custom CSS animations |
| Icons | Font Awesome 6 |
| Behavior | Vanilla JavaScript (DOM manipulation, modals, filtering) |

## Project Structure

```
pet-haven/
├── index.html      # Entire site (HTML, CSS, JS in one file)
└── README.md
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. **Open the folder**
   ```bash
   cd <your-repo-name>
   ```
3. **Run it** – open `index.html` in your browser. No installation or build step is needed (an internet connection is required for the Tailwind and Font Awesome CDNs).

## How It Works

- Pet data is stored in a JavaScript array (`pets`) inside `index.html`. Each pet has an `id`, `name`, `type`, `breed`, `age`, `description`, and `image`.
- Cards are generated dynamically with `loadPets()`, and filtering is handled by `filterPets()`.
- Modals (pet profile, adoption form, service details) are shown and hidden by toggling Tailwind's `hidden` class.

## Adding a New Pet

Add an object to the `pets` array:

```js
{ id: 6, name: 'Milo', type: 'cat', breed: 'siamese', age: 'puppy',
  description: 'Playful kitten who loves to explore.',
  image: 'path/or/url/to/image.jpg' }
```

If you use a new type or breed, also add it to the matching `<select>` filter in the HTML.

## Notes

This is a front-end demo project. The contact form and adoption application only show a success message and do not send data anywhere. A backend (for example Node.js or PHP with a database) would be needed to store real submissions.

## Future Improvements

- Backend and database for pets and adoption applications
- Working Share button on pet profiles
- Favorites / wishlist
- Admin panel to add and manage pets
- More pets, filters (age, size), and pagination

## Author

**Kajal Baraiya**
Aspiring Software Developer | Web Development
Surat, Gujarat, India

If you like this project, consider giving it a ⭐ on GitHub!

## License

This project is open source and available under the [MIT License](LICENSE).

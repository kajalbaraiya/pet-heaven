🐾 Pet Haven – Find Your Furry Friend

Pet Haven is a responsive, single-page pet adoption website. Visitors can browse adoptable pets, filter them by type and breed, view detailed pet profiles, and submit an adoption application, all from one clean, modern interface.

The entire project lives in a single index.html file, built with HTML, Tailwind CSS, and vanilla JavaScript. There is no build step and no backend.

✨ Features

Hero section with a full-screen background image and a call-to-action button
Pet gallery with card-based layout showing name, type, breed, age, and a short description
Filters to search pets by type (Dog, Cat, Bird, Fish) and breed
Load More button that shows pets 3 at a time
Pet detail modal with a large photo, full profile, and "Adopt Now" and "Share" buttons
Adoption application form (name, email, phone, address) with a success message
Services section (Pet Matching, Adoption Counseling, Pet Health Checks) with "Learn More" pop-ups
Contact form with validation and a success message
Responsive navigation with a mobile hamburger menu
Smooth animations (fade-in and slide-in effects) and hover transitions

🛠️ Tech Stack

Technology	          Purpose  
HTML5	                Page structure
Tailwind CSS (CDN)	  Styling and responsive layout
JavaScript (ES6)	    Filtering, modals, form handling, dynamic pet cards
Font Awesome 6 (CDN)	Icons

📁 Project Structure

pet-haven/
├── index.html    # Markup, styles, and JavaScript in one file
└── README.md

🧩 How It Works

Pet data is stored in a JavaScript array (pets) inside index.html. Each pet has an id, name, type, breed, age, description, and image.
loadPets() builds the pet cards dynamically and handles the Load More pagination.
filterPets() applies the type and breed filters when the Search button is clicked.
Modals (pet details, adoption form, and services) are toggled with Tailwind's hidden class.

⚠️ Current Limitations

The contact and adoption forms are front-end only. Submissions show a success message but are not sent or stored anywhere.
Pet data is hard-coded sample data.
The "Share" button and the social media footer links are placeholders.
The contact details in the page (address, phone, email) are sample values.


🔮 Future Improvements
Connect the forms to a backend (Node.js/Express, PHP, or Java) with a database
Replace sample data with a real pets API or database
Add an admin panel to manage pet listings
Implement the Share button (Web Share API)
Add user authentication and a favorites/wishlist feature

🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and open a pull request.

📄 License

This project is open source and available under the MIT License.

👤 Author

Kajal Baraiya GitHub: @kajalbaraiya

Content
index.html

HTML











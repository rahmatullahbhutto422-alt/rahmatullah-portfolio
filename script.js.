
// Mobile navigation menu
const menuBtn = document.getElementById("menuBtn");
const navLinks = document.getElementById("navLinks");

menuBtn.addEventListener("click", function() {
    navLinks.classList.toggle("active");
});

// Close menu after clicking a link
document.querySelectorAll(".nav-links a").forEach(function(link) {
    link.addEventListener("click", function() {
        navLinks.classList.remove("active");
    });
});

// Automatically update copyright year
document.getElementById("year").textContent =
    new Date().getFullYear();

// Contact form demonstration
const contactForm = document.getElementById("contactForm");

contactForm.addEventListener("submit", function(event) {
    event.preventDefault();

    const name = document.getElementById("name").value;

    document.getElementById("formStatus").textContent =
        "Thank you, " + name + "! Your message was entered.";

    contactForm.reset();
});

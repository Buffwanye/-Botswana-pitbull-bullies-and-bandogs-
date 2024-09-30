document.getElementById('registrationForm').addEventListener('submit', function(e) {
    e.preventDefault();

    // Example validation for image upload
    const dogImage = document.getElementById('dogImage').files[0];
    if (dogImage) {
        alert('Registration form submitted! Thank you for registering your dog.');
        // Here you would typically send the form data to your server
    } else {
        alert('Please upload a picture of your dog.');
    }
});

document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Thank you for contacting us!');
    // Here you would typically send the contact form data to your server
});
